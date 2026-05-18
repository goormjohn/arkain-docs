---
description: You can create a custom container with the Arkain AI by typing prompts.
icon: wand-magic-sparkles
---

# Using Arkain Snap

**Arkain Snap** is an AI agent that turns ideas into reality. You can create services or apps just with natural language prompts, without needing to learn programming languages anymore.\
There are two ways to use Arkain Snap:

{% hint style="success" %}
🎁 **Free Trial:** The **Arkain Snap** feature is available free of charge for up to 3 uses! Additional usage may consume credits.
{% endhint %}

## Start from the Dashboard

[**Arkain Snap**](../../arkain-ai/what-is-arkain-snap.md)  is available on the Dashboard page for easy access.

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/이미지 첨부 (1) (1).png" alt=""><figcaption></figcaption></figure></div>

{% stepper %}
{% step %}
#### Define Your Goal & Add Context

Enter your requirements in the central prompt box. To ensure the highest quality results, you can provide additional context directly from the Dashboard:

* **Natural Language:** Describe features, logic, and goals. Use **Quick Prompts** for inspiration. By default, a container is generated in a Node.js base template, but using a Quick Prompt will select the template most appropriate for that prompt.
* **Visual Context (Images):** Click the \[Upload Images] icon(<i class="fa-image">:image:</i>) or drag and drop UI mockups, sketches, or screenshots, allowing the AI to guide the visual design based on your provided images.
* [**External Tools (MCP)**](connect-external-tools.md)**:** Click the Connector icon to link services like Notion. The AI can search your docs automatically or use a specific page URL to build your app based on your existing PRDs or specs.
{% endstep %}

{% step %}
#### Requirement Analysis & Refinement

Once you submit your request, Side Chat(Dashboard) analyzes your intent before the build begins.

* **Prompt Generation:** The Side Chat (Dashboard) will display a **"Creating Snap prompt..."** indicator while the AI prepares a refined technical summary of your project.
* **Review & Edit:** Review the AI-generated summary. If you want to change the direction or add more detail, click the **Edit** button to manually adjust the prompt to match your exact intent.
{% endstep %}

{% step %}
#### Autonomous Building

After you confirm the prompt by clicking the \[Generate with Arkain Snap] button, the automated build process starts:

* **Container Creation:** A development environment is created based on your prompt (e.g., Node.js or a specialized template).
* **Agent Execution:** The Snap Agent plans the structure and writes the code autonomously. You can watch the live progress as the AI builds your service in real-time.
{% endstep %}

{% step %}
#### Final Refinements in Workspace

Once the build is complete, your project opens in the Workspace.

* Use the **Side Chat (Workspace)** to make further adjustments, fix UI details, or add new features.
* _Note: External tool context (like Notion) is used for the initial creation stage on the Dashboard only and is not carried over into the Workspace session._
{% endstep %}
{% endstepper %}

## Start with a Specific Base Template

If you prefer to set up your environment first, you can launch Arkain Snap from within a pre-configured container.

<figure><img src="../../../.gitbook/assets/Arkain AI (2).png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
### Create a Container

Go to the [Arkain Dashboard](https://arkain.io/my/dashboard), click the **\[New container]** button and create a container by following the instuctions on [this page](../container/container-management/creating-container.md).

{% hint style="info" %}
Arkain Snap is available with **Python, Node.js, Java, React, and Go** Containers.
{% endhint %}
{% endstep %}

{% step %}
### Run the Container and Enter Your Prompt

After the container is created, click the **\[Run Container]** button. On the first run, Arkain Snap will appear inside your container.

Describe your idea in natural language in the input box, then click the **\[Generate with Arkain Snap]** button.
{% endstep %}

{% step %}
### Build the Project

Arkain Snap will automatically:

* Configure the environment for the selected base template and your project.
* Generate the project structure and code.
* Install dependencies and start the application.
* Self-heal on errors — If any issue arises during setup or startup, the agent automatically\
  detects and fixes it.
{% endstep %}
{% endstepper %}

## Preview the Result

<figure><img src="../../../.gitbook/assets/PREVIEW_01 (1).png" alt=""><figcaption></figcaption></figure>

Once Arkain Snap finishes building the project, the **Preview** will automatically open in your Workspace so you can test the app right away. Check the service created based on your prompt and use the **Side Chat** to make changes to your service.

