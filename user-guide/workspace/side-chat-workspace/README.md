---
icon: comment-exclamation
---

# Side Chat (Workspace)

The **Side Chat (Workspace)** allows you to interact with powerful LLMs (Large Language Models) directly within your development environment. Whether you're debugging, optimizing, or "Vibe Coding" from scratch, Side Chat provides real-time assistance and deep project awareness.

<figure><img src="../../../.gitbook/assets/sidechat_01 (1).png" alt=""><figcaption></figcaption></figure>

***

## Getting Started

* **Access:** Open Side Chat(<img src="../../../.gitbook/assets/Sidechat_Button.png" alt="" data-size="line">) from the Sidebar in your Workspace.
* **Model Selection:** Select your preferred LLM from the dropdown menu before starting a conversation.
  * You can check the credit consumption for each model in the [**\[Supported Models\]**](../../arkain-ai/supported-models.md) guide.
* **Session Context:** Side Chat maintains context within a single session, ensuring a seamless flow of interaction.
* **Mode Selection:** Switch between Ask and Agent modes using the toggle in the input box.
  * **Ask Mode:** A read-only conversational assistant for questions, code reviews, and explanations. Code blocks are displayed for reference and can be copied, but cannot be applied directly.
  * **Agent Mode:** An autonomous AI agent that can explore your codebase, modify files, and execute terminal commands on your behalf.



## Adding Context: Precision Responses

To get the most accurate answers, provide the AI with visibility into your actual work.

#### Project Files

Click the **\[Add context]** button to reference specific code without manual copy-pasting.

* **Recent Files:** Instantly access your 5 most recently opened files.
* **Search:** Find any file by name or path within the project.

#### Visual Context (Images)

Click the **\[Upload Images]** button or **drag and drop images** directly into Side Chat to provide visual context. The LLM analyzes the content to enhance its response—perfect for UI debugging or mockup analysis.

| Feature    | Details                              |
| ---------- | ------------------------------------ |
| Capacity   | Up to 5 images per message           |
| Size Limit | Max 20MB per image (Auto-compressed) |
| Formats    | JPG, PNG, SVG, and more              |

Uploaded images are saved within your project folder, and you can freely upload images within the container's storage capacity.



## Applying Code Suggestions

When Side Chat provides a code block, you can integrate it directly into your editor:

* **Apply**: Click to apply the suggested changes directly to the target file.
* **Insert:** Paste the code at your current cursor position.
* **Copy:** Copy the code to your clipboard.
* **Preview:** Hover over the **\[Apply]** or **\[Insert]** button to see exactly where the code will be placed.

#### Reviewing Changes

Once code is applied, you can review it in the editor's diff view:

1. Compare the "Before" and "After" code.
2. Click **\[Accept]** or **\[Discard]** for individual changes.
3. Use the editor toolbar's **\[Accept All] / \[Discard All]** buttons to manage multiple changes at once.



## Managing Chat History

Never lose a valuable solution by utilizing the history features.

* **Recently Used List:** Quickly load recent conversations from the "Recently used chat" list.
* **Persistent History**: Click the \[History icon] (top left) to view all past sessions.
* **Deleting History:** Open the History list, hover over a session, and click the Trash can icon to remove it.



## Message Queue

You can continue sending messages while the AI is still generating a response. Side Chat supports a **message queue** that lets you type and send follow-up messages while the AI is still responding.

* **Queue messages**: Send up to 5 messages while the AI is responding. Messages appear in order and are sent automatically once the current response completes.
* **Model Switching:** If you change the selected model while messages are queued, the remaining messages will be sent using the newly selected model.
* **Queue Persistence:** Queued messages are saved when you close or refresh the browser tab. When you return to the same conversation, click \[Resume Sending] to continue where you left off, or \[Discard All] to clear the queue.
* **Interruptions:** If you stop a response or an error occurs, the queue pauses. You can click \[Continue Sending] to resume, \[Skip & Continue] to skip the failed message and proceed with the rest, or \[Discard All] to clear the queue.



## Tips for Efficient Use

Maximize your productivity by using the right prompts and context.

* **Be Specific:** Clear instructions yield higher-quality results.
  * _"What’s wrong with this function? \[Code snippet]"_
  * _"Can you optimize this SQL query?"_
  * _"Explain this Python error: \[Error message]"_
* **Vibe Coding:** Describe high-level requirements (e.g., _"Build a simple auth middleware"_), and let Side Chat generate the necessary logic or file structures for you.
* **Keep Context Relevant:** Use \[Add Context] to focus the AI's "attention" on specific files to avoid hallucinations.
* **Review First:** Always use the Diff View to ensure AI suggestions align with your project logic before accepting.
* **Manage History:** Use the History icon (top left) to view past sessions or delete unnecessary history.



***

{% hint style="success" %}
### **🤖 Moving to Autonomous Workflows?**

If you need the AI to independently explore your codebase and run commands, check out our \[[**Agent mode**](agent-mode.md)] guide.
{% endhint %}



With **Side Chat** in **Arkain**, you have the power of LLMs right at your fingertips. Solve problems faster, learn better, and keep track of all your conversations with ease!&#x20;
