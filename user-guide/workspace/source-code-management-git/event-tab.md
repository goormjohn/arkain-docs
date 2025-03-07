---
icon: code-branch
---

# Event tab

In the **"Events"** tab, you can see _what you've been working on using Arkain's Git GUI._

<figure><img src="../../../.gitbook/assets/git_10.png" alt=""><figcaption></figcaption></figure>

We've also added a walkthrough feature that tells you in more detail what caused the failure and offers solutions to the problem, making it easier for beginners who aren't familiar with Git.

## Examples of Errors <a href="#examples-of-errors" id="examples-of-errors"></a>

### **Commit**

Reason: You haven't entered a commit message Solution: After pressing the Commit button, fill in the commit message and commit again.

### **Checkout**

Reason: The following error occurs when you make a branch change without saving your changes. Solution: There are 3 possible workarounds

1. Commit the changes directly to the current branch and then change the branch.
2. Force checkout to delete unsaved changes and then change branches.
3. Pressing Smart Checkout will merge your current changes into the branch you are moving to.

### **Push**

Reason : If you don't have permissions on the Git origin repository, the following error occurs. Solution : After pressing the Register Permissions button, enter ID, PW, and push again.

### **Pull**

Reason: Occurs when an automatic merge fails after receiving a Git pull. Solution : Click View Conflicting Files to open a list of conflicting files. Resolve the conflicts in the open files before committing.

[\
](https://help.goorm.io/en/goormide/workspace/source-code-management-git/log)
