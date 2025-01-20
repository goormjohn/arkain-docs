# Event tab

In the **"Events"** tab, you can see _what you've been working on using goormIDE's Git GUI._

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FuMGwPfQ5ig7YbI5MOM0J%252Fimage.png%3Falt%3Dmedia%26token%3D82c8b755-d8b3-45a8-9cfd-928c085dbbc0&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=b1e50181&#x26;sv=2" alt=""><figcaption></figcaption></figure>

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
