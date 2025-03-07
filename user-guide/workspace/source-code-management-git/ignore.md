---
icon: code-branch
---

# Ignore

Are there files in your project that you don't want to version control? If so, use the Ignore command. You can make them no longer appear when the Status command is run.

Click the **'Settings'** button in the top right corner of Git Sidebar → **Source Code Management** (<img src="../../../.gitbook/assets/image (33).png" alt="" data-size="line">) and select the **\[ignore list]** tab.

<figure><img src="../../../.gitbook/assets/git_05.png" alt=""><figcaption></figcaption></figure>

Specify the files you don't want Git to track here.

<figure><img src="../../../.gitbook/assets/git_06.png" alt=""><figcaption></figcaption></figure>

The Ignore command is good for things like error logs or automatically generated files. However, **if a file is already versioned by Git** (if it has been added to the repository)**, it will not be ignored.** Git already knows about it, so it can't ignore it.
