---
icon: rectangle-vertical-history
description: >-
  Multi-project is the feature to work on multiple projects in a single
  container.
---

# Multi Project

{% stepper %}
{% step %}
In the Project Sidebar on the right, press the **\[+]** icon and click the **\[New Sub project]** button.
{% endstep %}

{% step %}
Enter the project name you want to use and click the **\[New Sub project]** button to create a new project with the same environment as your existing project.
{% endstep %}
{% endstepper %}

<figure><img src="../../.gitbook/assets/Multi Project_01.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Multi Project_02.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Sub projects can only have the same stack and the same templates as the main project.
{% endhint %}

### Git integration <a href="#git-integration" id="git-integration"></a>

{% stepper %}
{% step %}
Click the **\[Register repository]** button on the Git Sidebar, or click the **\[Directory settings]** icon (<img src="../../.gitbook/assets/image (35).png" alt="" data-size="line">) on the top right to display the Git Sidebar.&#x20;
{% endstep %}

{% step %}
In the Git settings window, you can enter the **\[Directory Settings]** tab and select a folder to integrate Git. From here, you can select the desired subproject and connect the repository to use Git in the subproject.
{% endstep %}
{% endstepper %}

<figure><img src="../../.gitbook/assets/git_17.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Before setting the directory, you need to run `git init` or run **Git clone** on the **\[Repository Registration]** tab to get the Change button when you select the folder.
{% endhint %}
