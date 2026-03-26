---
icon: user-robot
---

# Agent mode

**Agent Mode** transforms Side Chat from a conversational assistant into an autonomous AI partner. Unlike Chat Mode, the Agent independently explores your codebase, creates or modifies files, and executes terminal commands—all while keeping you informed and in control.

***

### Advantages of the Agent Mode

* **Solving Container Resource Issues:** Because the agent runs without needing heavy local installations, it completely resolves the resource drain and performance bottlenecks typically caused by running resource-intensive CLI tools within the container.
* **Perfect Synergy with Arkain's Ecosystem:** The AI Agent seamlessly integrates with the existing environments and powerful features provided by Arkain. By fully leveraging these native capabilities, the agent delivers far superior and more accurate results for your projects.
* **Access to Existing Side Chat Features:** You can still utilize all the useful features provided by the existing Side Chat while using the Agent Mode, making your workflow even more convenient and fluid.

### How the Agent Works

Once you provide a requirement, the Agent follows a transparent, step-by-step workflow:

1. **Code Exploration:** The Agent searches through your files using pattern matching and content search to understand the project structure.
2. **Action Plan:** The Agent generates a plan displayed as a checklist above the input area, allowing you to track its progress in real-time.
3. **Thinking Process:** Between actions, you can see the Agent’s reasoning as it navigates through your project, helping you understand its approach and decision-making.
4. **File Changes & Diff View:** When the Agent modifies or creates files, the changes appear instantly in the Diff Viewer. You can inspect every addition or removal before they are finalized.
5. **Terminal Execution:** If a terminal command is required, the Agent presents the command for your review before execution.

### Control & Safety: Reviewing Actions

The Agent asks for your approval before executing terminal commands to ensure you maintain full control:

* **Accept / Reject:** Each command suggestion shows **\[Accept]** and **\[Reject]** buttons. Click **\[Accept]** to allow execution, or **\[Reject]** to decline.
* **Auto-Approve Settings:** Use the approval dropdown to switch between:
  * **Ask every time (Default):** Requires manual approval for every command.
  * **Always accept:** Automatically approves all command executions during the current session.
* **Command Results:** Once a command is executed, the terminal output is displayed directly within the conversation for your review.
* **Stopping the Agent:** Click the \[Stop] button at any time to immediately halt the Agent's current operation.

{% hint style="info" %}
For file modifications, the Agent applies changes automatically, but you can review every change through the diff viewer that shows exactly what was added, removed, or modified.
{% endhint %}

### Custom Instructions via `ARKAIN.md`

You can provide specific context and tailored instructions to your agent simply by adding an `ARKAIN.md` file to your project. Guide your agent to perform tasks exactly the way your project requires!

#### 💡 `ARKAIN.md` Example&#x20;

By creating a simple file like the one below in your project's root directory, the agent will read it and write code according to your project's rules.

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

