---
description: >-
  Multi-project is the feature to work on multiple projects in a single
  container.
icon: rectangle-vertical-history
---

# Multi Project

{% stepper %}
{% step %}
In the **Project Sidebar**, press the **\[+]** icon and select the **\[New Sub project]** button.
{% endstep %}

{% step %}
Enter the project name you want to use and click the **\[Create new sub project]** button to create a new project with the same environment as your existing project.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
Sub projects can only have the same base template as the main project.
{% endhint %}

### Git integration <a href="#git-integration" id="git-integration"></a>

{% stepper %}
{% step %}
Click the **\[Register repository]** button on the Git Sidebar, or click the **\[Settings]** icon (<img src="../../.gitbook/assets/ActivityBar-item-10 (1).png" alt="" data-size="line">) on the top right to display the Git Sidebar.&#x20;
{% endstep %}

{% step %}
In the Git settings popup, you can enter the **\[Directory Setting]** tab and select a folder to integrate Git. From here, you can select the desired subproject and connect the repository to use Git in the subproject.
{% endstep %}
{% endstepper %}

<figure><img src="../../.gitbook/assets/git_18.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Before setting the directory, you need to run `git init` or run **Git clone** on the **\[Preference]** tab to get the Change button when you select the folder.
{% endhint %}
