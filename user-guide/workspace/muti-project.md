---
icon: rectangle-vertical-history
---

# Muti Project

Multi-project is the feature to work on multiple projects in a single container.

### Creation <a href="#creation" id="creation"></a>

In the Project Explorer on the right, press the `+` icon and click the **New Sub project** button.

Enter the project name you want to use and click the **Create New Sub project** button to create a new project with the same environment as your existing project.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FU1ODFoxL4V1RAS6d4712%252Fimage.png%3Falt%3Dmedia%26token%3D539d86bd-a78a-44a0-8228-f2c9cbfa2cb7&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=5f2e12b7&#x26;sv=2" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Sub projects can only have the same stack and the same templates as the main project - we don't yet support creating different templates!
{% endhint %}

### Setting <a href="#setting" id="setting"></a>

To set build options, click **\[Project] > \[Properties].**

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FjXl96fdMoC41uvvm40ag%252Fimage.png%3Falt%3Dmedia%26token%3Dacc3bafd-47f8-493b-a388-483c9584a457&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=8ce88cf3&#x26;sv=2" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Please refer to [Build setting for each stack](https://help.goorm.io/en/goormide/getting-started/build#build-settings-for-each-stack)
{% endhint %}

### Git integration <a href="#git-integration" id="git-integration"></a>

Click the **Register repository** button on the Git tab, or click the folder settings icon on the top right to display the Git settings window. In the Git settings window, you can enter the **\[Folder settings]** tab and select a folder to integrate Git. From here, you can select the desired subproject and connect the repository to use Git in the subproject.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252Fa5Rr3flS7quNt3Lkhezy%252F%25EB%25A9%2580%25ED%258B%25B0%2520%25ED%2594%2584%25EB%25A1%259C%25EC%25A0%259D%25ED%258A%25B8%252003_KR.png%3Falt%3Dmedia%26token%3Dace5449b-8c5c-4279-99d3-a5e48e1da806&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=d67a3972&#x26;sv=2" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Before setting the folder, you need to run `git init` or run **Git clone** on the **\[Repository Registration]** tab to get the Change button when you select the folder.
{% endhint %}
