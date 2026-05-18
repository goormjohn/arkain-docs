---
icon: book-bookmark
---

# Skills

<figure><img src="../../../.gitbook/assets/skills (1).png" alt=""><figcaption></figcaption></figure>

**Skills** allow teams to capture repeatable workflows—such as code review checklists, commit conventions, or migration playbooks—as reusable instructions that the Side Chat agent follows on demand. Once defined, these skills can be invoked manually via slash commands or automatically by the AI when the context is relevant.

***

### Getting Started: Creating a Skill

Skills are managed through through the **Preferences** menu.

1. Navigate to **Preferences > Skills**.
2. Click the **\[New Skill]** button located on the right side of the page.
3. Fill in the required fields in the **Create New Skill** popup:

<table><thead><tr><th width="191" align="center">Field</th><th width="107" align="center">Required</th><th>Notes</th></tr></thead><tbody><tr><td align="center"><strong>Name</strong></td><td align="center">✅</td><td>Identifier using lowercase letters, numbers, and hyphens only (max 64 chars).</td></tr><tr><td align="center"><strong>Description</strong></td><td align="center">✅</td><td>Explain when the agent should call this skill. The LLM uses this to decide when to invoke the skill automatically. (Max 1,024 chars).</td></tr><tr><td align="center"><p><strong>Instruction</strong></p><p>(SKILL.md body)</p></td><td align="center">✅</td><td>The actual guidance the agent should follow. Including specific rules and examples leads to better results.</td></tr><tr><td align="center"><strong>License</strong><br>(Advanced)</td><td align="center">⬜</td><td>Optional license tag for the skill itself.</td></tr><tr><td align="center"><strong>Compatibility</strong> (Advanced)</td><td align="center">⬜</td><td>Optional environment notes. (Max 500 chars)</td></tr></tbody></table>

### Managing Skills

* **Editing & Renaming:** Clicking a skill in the list opens the edit dialog. Renaming a skill renames its physical folder on disk and migrates its current status (enabled/disabled) to the new name.
* **Enabling/Disabling:** Each row has a toggle on the right.
  * **Enabled:** The skill can be called via slash commands and is available as an auto-invokable tool.
  * **Disabled:** The skill remains on disk but is not loaded into the conversation.
* **Active Limit (Max 10):** Up to 10 skills can be enabled simultaneously. Once the limit is reached, toggles for disabled skills are greyed out with a tooltip: _"You have reached the maximum number of active skills. Disable another skill first."_
* **Parsing Errors:** If a `SKILL.md` has invalid formatting or missing required fields, it appears in a "Parsing errors" section. Use the **\[Open file]** link to fix the syntax in the editor.

{% hint style="info" %}
If you try to rename a skill to one that already exists, the dialog blocks the save with a clear **"A skill with the same name already exists"** error instead of a generic failure toast.
{% endhint %}

***

### Project Structure

When you save a skill, Arkain automatically creates a dedicated folder within your project at `.arkain/skills/`.

```
<project>/
└── .arkain/
    └── skills/
        ├── code-review/
        │   └── SKILL.md
        └── commit-message/
            ├── SKILL.md
            └── examples.md
```

**The SKILL.md Format**

The `SKILL.md` file uses Markdown with a **metadata block** at the top for configuration, followed by the instructions.

**Example (code-review/SKILL.md):**

{% code title="code-review/SKILL.md" %}
```markdown
---
description: "Review the changed files and report bugs, performance issues, and readability concerns in three separate sections."
license: "MIT"
compatibility: "claude-3-5-sonnet"
---
# [Skill Title]
## Guidelines

When this skill is invoked, follow these steps:
1. Read every changed file to understand the surrounding context.
2. Report potential bugs, performance issues, and readability concerns in
   separate sections.
3. Suggest concrete edits, not just observations.
```
{% endcode %}

***

### Using Skills in Side Chat

#### 1. Explicit Slash Invocation

Trigger a specific skill by typing `/` followed by the skill name anywhere in your message.

> `/code-review take a look at the latest commit`

* **Chaining:** Multiple skills can be invoked in one message: `/code-review /commit-message`.
* **Visual Feedback:** Recognized slash tokens render as monospace chips in the input box and chat bubbles.

#### 2. Automatic Invocation

Enabled skills are exposed to the AI as the `invoke_skill` tool. If the AI determines a skill is relevant based on its **description**, it invokes the skill automatically. A visual marker (e.g., `/code-review used`) appears in the conversation history to indicate its use.

***

### Tips for Writing Good Skills

* **Make `description` count.** It is the line the LLM reads to decide whether to invoke the skill on its own. Be specific about _when_ the skill should fire and _what_ it produces.
* **Write the instruction like a checklist.** Numbered steps and explicit output formats lead to far more consistent results than free-form prose.
* **Keep the body focused.** Instructions over \~3,000 characters trigger a length warning in the editor; move large reference material into a sibling file (`examples.md`, `style-guide.md`) and reference it from the instruction.
* **Name with intent.** The skill name _is_ the slash command. `/code-review` reads better in chat than `/cr-helper-v2`.

### Common Scenarios

| You want to...                                                 | Use this                                                                                 |
| -------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Apply the same commit-message convention every time            | `/commit-message` (explicit invocation)                                                  |
| Run a fixed PR review checklist                                | `/code-review` (explicit invocation)                                                     |
| Have the agent automatically apply a domain rule when relevant | Encode the trigger condition in `description`, leave the skill enabled (auto-invocation) |
| Park a skill you're still drafting                             | Keep it disabled until it's ready                                                        |

***

With **Skills**, your team's hard-won conventions live next to the code they apply to, and Side Chat can apply them with a single slash — or pick them up on its own when the moment is right. For more on how Side Chat orchestrates these calls, see [**Agent mode**](agent-mode.md).

