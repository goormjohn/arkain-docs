# Diff

Diff lets you see what changes have been made in your goormIDE before committing to your linked Git account.

## How to use Diff <a href="#how-to-use-diff" id="how-to-use-diff"></a>

In the **\[Git] > \[Changes]** tab, clicking a file opens the Diff Tool, which lets you see the changes to the source code in the editor.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FDxn8Zkm5oPRJVUyHKZ29%252Fimage.png%3Falt%3Dmedia%26token%3D3ee9ed8f-69c3-4754-bf94-db90350c5cd6&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=5658a022&#x26;sv=2" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
**\[Note]** If you open the **\[Git]** tab and there is only a **\[Register repository]** button, you need to connect the repository first. See how to connect on [Import Github Repos](https://help.goorm.io/en/goormide/workspace/import-github-repos) page.
{% endhint %}

There are 2 areas in the Diff Tool;

1. **The editor area** is where you can see the changes you've made to the source code.
2. **The button area** is where provides convenience features available in the Diff Tool.



### **The editor area**

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FqtuOUHf7utskU9rl6jCm%252Fimage.png%3Falt%3Dmedia%26token%3Dfea2fa74-1ec2-4fcf-9e68-c81c9b6dd342&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=8d5b2a4a&#x26;sv=2" alt=""><figcaption><p><em>before the change (left), after the change (right)</em></p></figcaption></figure>

You can compare the source code **before the change (left)** and the source code **after the change (right)**.

In the pre-change source code, **lines of code that were deleted are&#x20;**<mark style="color:red;">**highlighted in red**</mark> and marked with a - next to the line number.&#x20;

In the after-change source code shows the **lines of code that were added with a&#x20;**<mark style="color:green;">**green highlight**</mark> and a + next to the line number. Also, the code that was actually changed is highlighted darker.

{% hint style="info" %}
**Tip: The status of the file determines which source code is compared.**

If you open the Diff Tool from a file that is ‘**off-stage’**, the source code before the change is the source code as of the last commit, and the source code after the change is the source code you are currently working on.

If you open the Diff Tool from a ‘staged file’, the pre-change source code is the source code at the last commit and the post-change source code is the source code at the time it was added to the stage, and modifying the source file does not modify the source code in the Diff Tool.

You can tell which status of the Diff Tool was opened in by looking at the Editor tab. Diff tool opened from `Files Removed from Stage` are named with the original filename followed by _(Working Tree)_, Diff tool opened from `Files Added to Stage` will have the original filename followed by _(Index)_.
{% endhint %}



<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FyeLK293zcpxH3OvYKsF5%252Fimage.png%3Falt%3Dmedia%26token%3D5096a73a-afd1-4f6e-92d3-f95639714894&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=9169877b&#x26;sv=2" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FeGllmObta1iDIOlx8xDR%252Fimage.png%3Falt%3Dmedia%26token%3D4ba7ec27-843e-4aa5-a4a4-7581b941f5b5&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=30b20abb&#x26;sv=2" alt="" width="375"><figcaption></figcaption></figure>





### **The button area**

The buttons area in the top right corner of the screen provides 4 functions.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252Fw3tnK8B5llY3UEG7f7yz%252Fimage.png%3Falt%3Dmedia%26token%3D26f3d9a6-a2d0-4521-a767-6db6d8bba6ad&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=7e84d68a&#x26;sv=2" alt="" width="375"><figcaption></figcaption></figure>

1. **Open file:** Opens the Diff Tool's source file editor for the file you are currently viewing.
2. **Previous change, Next change**: Moves the cursor to the previous, next change of the current cursor in the source code area after a change.
3. **Toggle collapse unchanged regions**: Unchanged source code areas are hidden. If the unchanged source code area is small, it may not be hidden. Click the button one more time to see the full source code again.
4. **Change the way the editor area is viewed**: You can change the placement of the source code before changes and the source code after changes. Click the `Split` button to change to a left-to-right orientation, or the `Inline` button to change to a top-to-bottom orientation.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FM0Dl5kPtyviNAKWlEToI%252Fimage.png%3Falt%3Dmedia%26token%3D9e1740eb-e4f6-4c2e-b8d8-08602beec2b1&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=69f52a14&#x26;sv=2" alt=""><figcaption></figcaption></figure>

* **Button area reference image**

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FPVVZcrEeRd2AAg7wu8q3%252Fimage.png%3Falt%3Dmedia%26token%3D927a7894-b12c-42fe-8733-43b97d5d27b6&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=8ec19dfa&#x26;sv=2" alt=""><figcaption><p>Image of after clicking '<strong>Toggle collapse unchanged regions</strong>' button</p></figcaption></figure>

[\
](https://help.goorm.io/en/goormide/workspace/source-code-management-git/event-tab)

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FKCWesj30uHrs92Q0tNaR%252Fimage.png%3Falt%3Dmedia%26token%3D2f20d0bd-8e3c-4352-a9d1-881451391c21&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=10a8db8a&#x26;sv=2" alt=""><figcaption><p>Image of after clickling <strong>'Inline'</strong> button</p></figcaption></figure>
