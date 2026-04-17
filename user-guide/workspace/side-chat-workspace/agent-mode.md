---
icon: user-robot
---

# Agent Mode

<figure><img src="../../../.gitbook/assets/agent (1).png" alt=""><figcaption></figcaption></figure>

**Agent Mode** transforms Side Chat from a conversational assistant into an autonomous AI partner. Unlike Ask Mode, the Agent independently explores your codebase, creates or modifies files, and executes terminal commands—all while keeping you informed and in control.

***

### Advantages of the Agent Mode

* **Solving Container Resource Issues:** Because the agent runs without needing heavy local installations, it completely resolves the resource drain and performance bottlenecks typically caused by running resource-intensive CLI tools within the container.
* **Perfect Synergy with Arkain's Ecosystem:** The AI Agent seamlessly integrates with the existing environments and powerful features provided by Arkain. By fully leveraging these native capabilities, the agent delivers far superior and more accurate results for your projects.
* **Access to Existing Side Chat Features:** You can still utilize all the useful features provided by the existing Side Chat while using the Agent Mode, making your workflow even more convenient and fluid.

### How the Agent Works

Once you provide a requirement, the Agent follows a transparent, step-by-step workflow:

1. **Code Exploration:** The Agent searches your files using pattern matching and content search to understand the project structure.
2. **Action Plan:** The Agent generates a plan displayed as a checklist above the input area, allowing you to track its progress in real-time.
3. **Thinking Process:** Between actions, the Agent's reasoning is displayed in real time, so you can follow its approach and decision-making.
4. **File Changes & Diff View:** When the Agent modifies or creates files, the changes appear instantly in the Diff Viewer. You can inspect every addition or removal before they are finalized.
5. **Terminal Execution:** If a terminal command is required, the Agent presents the command for your review before execution.

### Control & Safety: Reviewing Actions

The Agent requests your approval before executing terminal commands:

* **Accept / Reject:** Each command suggestion shows **\[Accept]** and **\[Reject]** buttons. Click **\[Accept]** to allow execution, or **\[Reject]** to decline.
* **Command Results:** Once a command is executed, the terminal output is displayed directly within the conversation for your review.
* **Stopping the Agent:** Click the **\[Stop]** button at any time to immediately halt the Agent's current operation.

{% hint style="info" %}
For file modifications, the Agent applies changes automatically, but you can review every change through the diff viewer that shows exactly what was added, removed, or modified.
{% endhint %}

{% hint style="warning" %}
The conditions under which the approval dialog appears can be customized through Agent Permissions below.
{% endhint %}

***

### Agent Permissions

You can configure fine-grained permissions for the Agent through the "Agent Permissions" section in Preferences. All permission rules can be managed via the GUI. Your permission settings are saved and persist across conversations.

#### Approve All

When Approve All is enabled, all actions are performed without asking. Deny rules always take precedence — even with Approve All enabled, denied commands are always blocked.

#### Command Permissions&#x20;

Command permissions use a `cmd:args` pattern format (e.g., `git:`_,_ `rm:`, `npm:install`) and follow a strict priority order:

1. Deny patterns: Commands matching a Deny pattern are immediately rejected
2. Allow patterns: Commands matching an Allow pattern are immediately executed without an approval dialog.
3. Unmatched commands: If a command does not match any pattern, an approval dialog will appear.  Click **\[Accept]** to allow execution, or **\[Reject]** to decline.

#### File Access Restrictions

You can define file path Deny patterns using glob syntax (e.g., `/.env`, `/secrets/**`).

* When the Agent attempts to access a file that matches a Deny pattern, the operation is blocked and the Agent receives an error, prompting it to find an alternative approach.&#x20;
* This protects sensitive files such as environment variables, credentials, and secret configurations from unintended access.

#### Tool Permissions

Control the Agent's access to file, search, and execution tools. Each tool can be set to Allow (default) or Deny. When a tool is set to Deny, the Agent is blocked from invoking it — any attempt to call the tool will be intercepted and rejected before execution.

* **Explore:** Keyword search, file pattern matching, and directory listing
* **Read:** File reading and code analysis
* **Write File:** File creation
* **Edit File:** File editing
* **Command:** Terminal commands (including destructive operations)

***

### Custom Instructions via `ARKAIN.md`

You can provide specific context and tailored instructions to your agent simply by adding an `ARKAIN.md` file to your project. Guide your agent to perform tasks exactly the way your project requires!

To edit `ARKAIN.md` directly in the editor, go to **Preferences → Custom Instructions** and click the **\[Open ARKAIN.md]** button.

#### 💡 `ARKAIN.md` Example&#x20;

Create an ARKAIN.md file in your project's root directory. The Agent will read it automatically and follow the instructions when generating code.

```markdown
## Brief Project Description
This is a Todo management web application running on the Arkain platform.

## Tech Stack
- Frontend: React, TypeScript
- Backend: Node.js, Express
- Database: MongoDB

## Development Rules
- Use camelCase for all variables and function names.
- Always leave a comment explaining the reason for any code modifications.

## Precautions
- Never hardcode sensitive information like database passwords; always use environment variables.
```

***
