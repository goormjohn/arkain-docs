---
icon: rectangle-vertical-history
---

# Multi Project

Multi-project is the feature to work on multiple projects in a single container.

### Creation <a href="#creation" id="creation"></a>

In the Project Sidebar on the right, press the **\[+]** icon and click the **\[New Sub project]** button.

Enter the project name you want to use and click the **Create New Sub project** button to create a new project with the same environment as your existing project.

<figure><img src="../../.gitbook/assets/Multi Project_01.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Multi Project_02.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Sub projects can only have the same stack and the same templates as the main project.
{% endhint %}

### Setting <a href="#setting" id="setting"></a>

To set build options, click **\[Function]** button (![](<../../.gitbook/assets/menubar_function button.png>)) → **\[Properties].**

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FjXl96fdMoC41uvvm40ag%252Fimage.png%3Falt%3Dmedia%26token%3Dacc3bafd-47f8-493b-a388-483c9584a457&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=8ce88cf3&#x26;sv=2" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Please refer to [Build setting for each stack](https://help.goorm.io/en/goormide/getting-started/build#build-settings-for-each-stack)
{% endhint %}

### Git integration <a href="#git-integration" id="git-integration"></a>

Click the **\[Register repository]** button on the Git sidebar, or click the **\[Directory settings]** icon (<img src="../../.gitbook/assets/image (35).png" alt="" data-size="line">) on the top right to display the Git sidebar. In the Git settings window, you can enter the **\[Directory Settings]** tab and select a folder to integrate Git. From here, you can select the desired subproject and connect the repository to use Git in the subproject.

<figure><img src="../../.gitbook/assets/git_17.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Before setting the directory, you need to run `git init` or run **Git clone** on the **\[Repository Registration]** tab to get the Change button when you select the folder.
{% endhint %}
