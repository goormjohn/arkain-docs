---
icon: comment-exclamation
---

# Side Chat (Workspace)

The **Side Chat** feature in **Arkain** allows you to interact with powerful LLMs (Large Language Models) directly within your development environment. Whether you're debugging, optimizing, or "Vibe Coding" from scratch, Side Chat provides real-time assistance and deep project awareness.

<figure><img src="../../../.gitbook/assets/image (127).png" alt=""><figcaption></figcaption></figure>

***

## Getting Started

* **Access:** Open Side Chat from the Sidebar in your Workspace.
* **Model Selection:** Select your preferred LLM from the dropdown menu before starting a conversation.
* **Session Context:** Side Chat maintains context within a single session, ensuring the AI remembers previous interactions for a seamless conversation.



## Asking Questions & Vibe Coding

Simply type your requirements or questions in the input box.

* **Prompting Examples:**
  * "What’s wrong with this function? `[Code snippet]`"
  * "Can you optimize this SQL query?"
  * "Explain this Python error: `[Error message]`"
* **Vibe Coding:** Describe a high-level requirement, and let Side Chat generate the necessary logic or file structures for you.



## Adding Context: Sharpen AI Responses

To get the most accurate answers, provide the AI with visibility into your actual work.

#### Adding Project Files

Click the **\[Add context]** button to include relevant files without manual copy-pasting.

* **Recent Files:** Instantly access your 5 most recently opened files.
* **Project Search:** Search any file by name or path.
* [**AI Supporter**](../../arkain-ai/ai-supporter.md)**:** Enable this feature to allow the AI to automatically reference the most relevant files across your entire project.

#### Adding Images

Click the **\[Upload Images]** button or drag and drop images directly into Side Chat to provide visual context. The LLM will automatically analyze and understand the image content to enhance its responses.

Image Upload Details:

* Supports common image formats: JPG, PNG, SVG, and more
* Add up to 5 images per message (separate from file attachments)
* Maximum file size: 20MB per image
* Large images are automatically compressed during upload.
* Uploaded images are saved within your project folder, and you can freely upload images within the container's storage capacity.

This feature is particularly useful for analyzing UI designs or mockups, or  for debugging visual rendering issues.



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



## **Managing Chat History**

Never lose a valuable solution by utilizing the history features.

* **Recently Used List:** Quickly load recent conversations from the "Recently used chat" list.
* **Persistent History**: Click the \[History icon] (top left) to view all past sessions.
* **Deleting History:** Open the History list, hover over a session, and click the Trash can icon to remove it.



## Tips for Efficient Use

* **Be Specific:** Provide clear instructions to get the most accurate code suggestions.
* **Keep Context Relevant:** Use \[Add Context] to focus the AI's "attention" on specific files to avoid hallucinations.
* **Review Before Accepting:** Always use the Diff view to ensure the AI's suggestion aligns with your project's logic before clicking \[Accept All].



***

With **Side Chat** in **Arkain**, you have the power of LLMs right at your fingertips. Solve problems faster, learn better, and keep track of all your conversations with ease!&#x20;
