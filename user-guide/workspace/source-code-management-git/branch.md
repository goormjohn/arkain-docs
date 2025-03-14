---
icon: code-branch
---

# Branch

You can easily manage branches using the **\[Branch]** tab(![](<../../../.gitbook/assets/스크린샷 2025-03-08 오후 2.29.24.png>)) in the Git Sidebar. It shows the list of currently created branches and indicates the branch you are working on.

You can change the branch you want to work on by selecting a branch from the branch list.

<figure><img src="../../../.gitbook/assets/git_07.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Git provides different working directories for different branches, so if you move a branch, your working directory will also change.
{% endhint %}

The Branch tab offers 3 commands you can select a single branch to execute a command.

* **Create a new Branch**\
  Creates a new branch. Click the button and a pop-up window will appear where you can enter a name for the branch. Enter the branch name and click the **\[OK]** button to complete the branch creation.

<figure><img src="../../../.gitbook/assets/git_08.png" alt=""><figcaption></figcaption></figure>

* **Merge into selected branch**\
  Merges the selected branch into the desired branch.\
  ![](<../../../.gitbook/assets/스크린샷 2025-03-08 오후 2.35.37.png>)
* **Checkout new branch**\
  Moves the working directory to the selected branch. After clicking the button, the **\[Branch]** tab and Project Sidebar will update and you will see that your current location has been moved to the selected branch.

When you create a branch, you can select a starting point for the branch.

You can select the parent commit of the current working copy, a specific commit, a specific branch, a specific tag, or you can select a commit directly from the list of the last 15 commits.
