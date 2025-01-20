# Arkain Chat

### Chat

Chat lets you talk with an AI that sees your codebase. The chat can always see your current file and cursor, so you can ask it things like: "Is there a bug here?". You can add particular blocks of code to the context with ⌘+Shift+L or "@." You can chat with your entire codebase with ⌘+Enter.

### Instant Apply

Apply the code suggestions from chat back into your codebase by clicking the play button on top of any chat codeblock.

### Codebase Answers

Use @Codebase or ⌘ Enter to ask questions about your codebase. Cursor will search your codebase to find relevant code to your query.

### Reference your Code

Reference code with @ symbols to be used as context for the AI. Just type @ to see a list of all the files and code symbols in your folder.



***



Chat

## Overview

Learn about Cursor Chat, your AI coding assistant that lives in your editor

Cursor Chat lets you ask questions or solve problems in your codebase with the most capable language models, all in your editor.

\
For language models to give good answers, they need to know specific things that are relevant to your codebase — context.

Cursor has several built in features to provide context in chat, such as automatically including context across your entire codebase, searching the web, indexing documentation, and user-specified references to code blocks. They are built to eliminate the tedious copy-pasting otherwise necessary for working with language models on code.

By default, Cursor Chat is in the AI pane, which is on the opposite side of your primary sidebar. You can toggle the AI pane by pressing `Ctrl/⌘ + L`, which focuses onto the chat when opened. To submit your query, press `Enter`.

#### [​](https://docs.cursor.com/chat/overview#user-and-ai-messages)User and AI Messages <a href="#user-and-ai-messages" id="user-and-ai-messages"></a>

User messages contain the text you type, along with the context you’ve referenced. You can go back to any previous user messages to edit and rerun your queries. This will overwrite any messages after that and regenerate new ones.

AI messages are the responses generated from the AI model you’ve picked. They are paired with the user message before them. AI messages may contain parsed code blocks which can be added to your codebase with [instant apply](https://docs.cursor.com/chat/apply).

All user/AI messages together in the same thread are called a chat thread, and each chat thread is saved in your chat history.

#### [​](https://docs.cursor.com/chat/overview#chat-history)Chat History <a href="#chat-history" id="chat-history"></a>

By pressing on the “Previous Chats” button on the top right of the AI pane, or by pressing `Ctrl/⌘ + Alt/Option + L`, you can see the chat history. You can click on any chat thread to go back and see the messages that make up that thread, and you can also modify the title of the thread by clicking the pen icon, or delete the thread by clicking the garbage can icon upon hovering over the thread in the history.

The title of a Cursor thread is just the first few words of the first user message.

#### [​](https://docs.cursor.com/chat/overview#default-context)Default Context <a href="#default-context" id="default-context"></a>

By default, Cursor Chat includes the current file as context. You can submit a query without including any context by removing the current file pill from the message. As you type, you can see what will be included in context in the pills above the input box.

#### [​](https://docs.cursor.com/chat/overview#adding-context)Adding Context <a href="#adding-context" id="adding-context"></a>

By default, user messages will contain the text you type, along with the context you’ve referenced. You can add more custom context to each bubble with @ symbols, and by default, the current viewing file will be used as context as well in the user message.

See the [@ symbols](https://docs.cursor.com/context/@-symbols/@-files) pages for more information.

#### [​](https://docs.cursor.com/chat/overview#ai-fix-in-chat)AI Fix in Chat <a href="#ai-fix-in-chat" id="ai-fix-in-chat"></a>

A convenient feature to fix linter errors in your codebase is to use the AI fix in chat. To do this, hover over the error in the editor, and click the blue AI fix button that shows up.

The keyboard shortcut for this would be to do `Ctrl/⌘ + Shift + E`.

