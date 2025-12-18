---
hidden: true
noIndex: true
icon: play
---

# How to use Arkain Snap(아케이드 제거 버전)

There are two ways to use Arkain Snap, depending on how you want to start your project.

### Option 1: Start from the Dashboard

_<mark style="color:$info;">Recommended if you simply want to try Arkain Snap</mark>_

Go to the [Arkain Dashboard](https://arkain.io/my/dashboard) to start using Arkain Snap.

For a detailed step-by-step guide, follow the instructions on [this page](../dashboard/container/container-management/creating-container/using-arkain-snap.md).

{% hint style="warning" %}
**Note**

By default, Arkain Snap from the Dashboard creates a container based on **Node.js**. Automatic base template selection is **only** available when you use a **Quick Prompt**.

To **manually** choose a base template from the beginning, please use [**Option 2**](how-to-use-arkain-snap.md#option-2-start-in-container-with-a-specific-base-template) instead.
{% endhint %}

### Option 2: Start in Container with a Specific Base Template

_<mark style="color:$info;">Recommended if you want to work with a specific programming language or framework</mark>_

<figure><img src="../../.gitbook/assets/스크린샷 2025-09-11 오전 10.28.53.png" alt=""><figcaption><p>snap intro 화면. 프롬프트가 입력돼서 버튼이 활성화된 상태여도 됨.</p></figcaption></figure>

{% stepper %}
{% step %}
### Create a Container

Go to the [Arkain Dashboard](https://arkain.io/my/dashboard), click the **\[New container]** button and create a container by following the instuctions on [this page](../dashboard/container/container-management/creating-container/).

{% hint style="info" %}
Arkain Snap is available with **Python, Node.js, Java, React, and Go** Containers.
{% endhint %}
{% endstep %}

{% step %}
### Run the Container and Enter Your Prompt

After the container is created, click the **\[Run Container]** button. On the first run, Arkain Snap will appear inside your container.

Describe your idea in natural language in the input box, then click **\[Generate with Arkain Snap]** button.
{% endstep %}

{% step %}
### Build the Project

Arkain Snap will automatically:

* Configure the environment for the selected base template and your project
* Generate the project structure and code
* Install dependencies and start the application

{% hint style="warning" %}
**Note**

* If a command fails to run, click the **\[Run]** button in the top-right corner of the command code block to re-execute it.
* The success or failure of the command will be shown at the bottom of the code block as **"Success"** or **"Failed building the project"**.
{% endhint %}
{% endstep %}

{% step %}
### Preview the Result

Once Arkain Snap finishes building the project, the **Preview** will automatically open in your workspace so you can test the app right away.
{% endstep %}
{% endstepper %}

<figure><img src="../../.gitbook/assets/스크린샷 2025-09-11 오후 12.53.39.png" alt=""><figcaption><p>snap 워크플로우 이미지. 워크플로우와 Preview 화면 강조</p></figcaption></figure>

{% hint style="success" %}
Want to take it even further? Use [Side Chat](/broken/pages/zF4s8B1CyX42hZ7SLKtL) to vibe coding and keep improving your app in real time.
{% endhint %}
