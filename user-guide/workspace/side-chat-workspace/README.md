---
icon: comment-exclamation
---

# Side Chat (Workspace)

**Side Chat** is a powerful LLM-driven assistant integrated directly into your Workspace. It moves beyond simple Q\&A by understanding your entire project context, suggesting code, and even executing tasks autonomously.

<figure><img src="../../../.gitbook/assets/sidechat_01 (1).png" alt=""><figcaption></figcaption></figure>

***

## Getting Started

* **Access:** Open Side Chat(<img src="../../../.gitbook/assets/Sidechat_Button.png" alt="" data-size="line">) from the Sidebar in your Workspace.
* **Model Selection:** Select your preferred LLM from the dropdown menu before starting a conversation. You can check the credit consumption for each model in the [**\[Supported Models\]**](../../arkain-ai/supported-models.md) guide.
* **Session Context:** Side Chat maintains context within a single session, ensuring a seamless flow of interaction as you build your project.



## The Three Modes of Side Chat

Choose the mode that best fits your current objective. You can switch between them using the dropdown menu in the input box.

#### 1. [Agent Mode](agent-mode.md) (Autonomous Execution)

* **Best for:** Automating repetitive tasks, creating new files, and running terminal commands.
* **How it works:** An autonomous agent that can independently explore your codebase, modify files, and use terminal tools to complete tasks on your behalf.

#### 2. [Plan Mode](plan-mode.md) (Collaborative Strategy)

* **Best for:** Designing new features or complex refactorings that require a roadmap.
* **How it works:** The AI interacts with you through interactive questions to clarify your intent. It then generates a structured Action Plan (.md) in your editor. You can view and edit this plan manually.
* **Execution:** Once you are satisfied, click the **\[Approve & Run]** button to transition to Agent Mode and implement the plan.

#### 3. Ask Mode (Read-Only)

* **Best for:** Explaining code, debugging advice, and general questions.
* **How it works:** A conversational assistant that can read your files but cannot modify them. It provides code snippets you can manually copy or apply.



## [Skills](skills.md) & Capabilities

**Skills** are specialized tools the AI uses to interact with your environment. Powered by the MCP (Model Context Protocol) framework, they allow the AI to perform actions beyond just generating text.

* **Code Search:** Finding specific logic across your entire project.
* **Terminal Execution:** Running builds, tests, or installations.
* **Web Fetch:** Retrieves and references live web content, such as documentation or API specifications, during task execution. Domain permissions and restrictions are managed through the **Preferences** panel.



## Key Features for Precision

#### Adding Context

To get the most accurate results, give the AI visibility into your work:

* **Files:** Click the **\[Add context]** button to reference specific files. You can quickly pick from your 5 most recently opened files or find any file by name or path within the project.
* **Images:** Click the **\[Upload Images]** button or drag and drop images directly into Side Chat. The LLM analyzes the content to enhance its response—perfect for UI debugging or mockup analysis.
  * **Note:** Uploaded images are saved within your project folder. You can freely upload images within your container's storage capacity.

| Feature    | Details                              |
| ---------- | ------------------------------------ |
| Capacity   | Up to 5 images per message           |
| Size Limit | Max 20MB per image (Auto-compressed) |
| Formats    | JPG, PNG, SVG, and more              |

#### Applying Code Suggestions (Ask & Plan Modes)

In **Ask** and **Plan** modes, you can manually integrate suggested code into your editor:

* **Apply/Insert:** Integrate code directly into your editor or at your cursor position with one click.
* **Diff View:** Review changes in a "Before/After" view. Use **\[Accept]** or **\[Discard]** to finalize the edits.



#### Managing Chat History

Never lose a valuable solution by utilizing the built-in history features:

* **Recently Used List:** Quickly load recent conversations from the "Recently used chat" list.
* **Persistent History:** Click the **History icon** (top left) to view all past sessions across your Workspace.
* **Deleting History:** Open the History list, hover over a session, and click the **Trash can icon** to remove it.



#### Message Queue

Side Chat supports a message queue, allowing you to type and send follow-up messages while the AI is still generating a response.

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
* **Master the Workflow:** For large tasks, start in **Plan Mode** to align on the strategy. Once the plan is solid, use Approve & Run to let the Agent handle the implementation.



***

With Side Chat in Arkain, you have the power of LLMs right at your fingertips to solve problems faster, learn better, and keep track of all your conversations with ease!
