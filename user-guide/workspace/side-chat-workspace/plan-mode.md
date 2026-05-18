---
icon: clipboard-list
---

# Plan Mode

**Plan Mode** transforms Side Chat into a collaborative planning partner. Instead of making changes directly, the AI analyzes your codebase and works with you through interactive questions to build a clear action plan — before any code is touched.

***

### **When to Use Plan Mode**

Plan Mode is ideal for complex tasks where architectural decisions or multiple implementation paths exist. Use it when:

* **Designing New Features:** Mapping out file structures and logic flows from scratch.
* **Complex Refactoring:** Identifying dependencies and risks across multiple files.
* **Strategic Alignment:** Ensuring the AI's intended approach matches your project's standards before execution.



### **How Plan Mode Works**

Once you describe what you want to accomplish, the AI follows a collaborative workflow:

{% stepper %}
{% step %}
#### Code Exploration

The AI searches and reads your project files to understand the current architecture and relevant logic, similar to the initial stage of Agent Mode.
{% endstep %}

{% step %}
#### Interactive Discovery (Question Cards)

When requirements are ambiguous or multiple paths are possible, the AI will not guess. Instead, it presents **Interactive Question Cards**:

* **Choice Buttons:** Select from predefined options to quickly guide the AI.
* **Free Input:** Provide custom text instructions to refine the requirement.
* **Dynamic Updates:** Once you respond, the card updates to show your answer, and the AI proceeds with the new context.
{% endstep %}

{% step %}
#### Action Plan Generation (.md)

The AI generates a structured **Action Plan** in Markdown format that opens directly in your editor. This plan is **fully editable**, allowing you to manually refine steps or implementation details. Your edits serve as the final source of truth for the execution phase.
{% endstep %}

{% step %}
#### Execution: Approve & Run

Plan Mode itself is **read-only**. To bring the plan to life:

1. **Review & Edit:** Finalize the Markdown plan in your editor.
2. **Approve:** Click the **\[Approve & Run]** button in the Side Chat.
3. **Transition:** The session automatically transitions to [**Agent Mode**](agent-mode.md), where the AI uses the finalized plan as its instruction set to perform the actual implementation.
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
**Plan Mode** is read-only — the AI cannot modify files, create files, or execute terminal commands.
{% endhint %}

***
