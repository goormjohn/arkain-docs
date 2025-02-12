---
icon: code-branch
---

# Ignore

Are there files in your project that you don't want to version control? If so, use the Ignore command. You can make them no longer appear when the Status command is run.

Click the **'Settings'** button in the top right corner of Git Sidebar → **Source Code Management** (![](<../../../.gitbook/assets/스크린샷 2025-02-10 오후 3.03.06 (1).png>)) and select the **\[ignore list]** tab.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252Fc9UPVGqUSpNEPc59bKzW%252Fimage.png%3Falt%3Dmedia%26token%3D8871feaf-62ed-4823-9da4-d1feb57e3adb&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=51ae067f&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Specify the files you don't want Git to track here.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FjL0tDdoCOHgUccDFaIOB%252Fimage.png%3Falt%3Dmedia%26token%3D370df8dd-9292-49ac-8411-da4f8b8b6779&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=2cb75eb2&#x26;sv=2" alt=""><figcaption></figcaption></figure>

The Ignore command is good for things like error logs or automatically generated files. However, **if a file is already versioned by Git** (if it has been added to the repository)**, it will not be ignored.** Git already knows about it, so it can't ignore it.
