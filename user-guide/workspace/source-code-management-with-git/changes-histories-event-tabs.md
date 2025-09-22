---
icon: code-branch
---

# Changes / Histories / Event tabs

Check the revision status of the current project files / folders in the Changes, Histories, and Event tabs of the Git Sidebar. You can use key Git commands such as **Add, Commit, Push, Pull,** and **Ignore** here.

In the **Changes tab**, you can easily see whether a file is staged or unstaged at a glance. In the **Histories tab**, you can view commit history, and in **Event tab**, you can see what you've been working on using Arkain's Git GUI.

We've also added a walkthrough feature that tells you in more detail what caused the failure and offers solutions to the problem, making it easier for beginners who aren't familiar with Git.

## Examples of Errors <a href="#examples-of-errors" id="examples-of-errors"></a>

### **Commit**

* **Reason**: You haven't entered a commit message&#x20;
* **Solution**: After pressing the Commit button, fill in the commit message and commit again.

### **Checkout**

* **Reason**: This error occurs when you try to switch branches without saving your changes.
* **Solution**: There are 3 possible workarounds

{% stepper %}
{% step %}
Commit the changes directly to the current branch and then change the branch.
{% endstep %}

{% step %}
Force checkout to delete unsaved changes and then change branches.
{% endstep %}

{% step %}
Press Smart Checkout to merge your current changes into the branch you are switching to.
{% endstep %}
{% endstepper %}

### **Push**

* **Reason**: If you don't have permissions on the Git origin repository, the following error occurs.&#x20;
* **Solution**: After pressing the **\[Register Permissions]** button, enter ID, PW(Password), and push again.

### **Pull**

* **Reason**: Occurs when an automatic merge fails after receiving a Git pull.&#x20;
* **Solution**: Click View Conflicting Files to open a list of conflicting files. Resolve the conflicts in the open files before committing.
