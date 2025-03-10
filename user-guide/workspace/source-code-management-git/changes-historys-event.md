---
icon: code-branch
---

# Changes / Historys / Event tabs

Check the revision status of the current project files/folders in the Changes, Historys, Event tab of the Git Sidebar. You can use key Git commands such as **Add, Commit, Push, Pull,** and **Ignore** here.

<figure><img src="../../../.gitbook/assets/git_03 (1).png" alt=""><figcaption></figcaption></figure>

In the **Changes tab**, you can easily see whether a file is staged or unstaged at a glance. In the **Historys tab**, you can view commit history, and in **Event tab**, you can see what you've been working on using Arkain's Git GUI.

<figure><img src="../../../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

We've also added a walkthrough feature that tells you in more detail what caused the failure and offers solutions to the problem, making it easier for beginners who aren't familiar with Git.

## Examples of Errors <a href="#examples-of-errors" id="examples-of-errors"></a>

### **Commit**

* **Reason**: You haven't entered a commit message&#x20;
* **Solution**: After pressing the Commit button, fill in the commit message and commit again.

### **Checkout**

* **Reason**: The following error occurs when you make a branch change without saving your changes.
* **Solution**: There are 3 possible workarounds

{% stepper %}
{% step %}
Commit the changes directly to the current branch and then change the branch.
{% endstep %}

{% step %}
Force checkout to delete unsaved changes and then change branches.
{% endstep %}

{% step %}
Pressing Smart Checkout will merge your current changes into the branch you are moving to.
{% endstep %}
{% endstepper %}

### **Push**

* **Reason**: If you don't have permissions on the Git origin repository, the following error occurs.&#x20;
* **Solution**: After pressing the **\[Register Permissions]** button, enter ID, PW(Password), and push again.

### **Pull**

* **Reason**: Occurs when an automatic merge fails after receiving a Git pull.&#x20;
* **Solution**: Click View Conflicting Files to open a list of conflicting files. Resolve the conflicts in the open files before committing.
