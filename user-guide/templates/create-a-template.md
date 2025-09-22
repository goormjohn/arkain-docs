---
icon: sidebar
---

# Create a Template

Creating a template allows you to share your project setup with others and make development faster and easier. Here’s how to create and share your own template:



{% stepper %}
{% step %}
### **Access the** [**Templates**](https://arkain.io/template) **page**&#x20;

There are three ways to create a template:

* Click the **\[Create template]** button on the [Templates](https://arkain.io/template) page.
* Click the **\[More]**(<img src="../../.gitbook/assets/스크린샷 2025-02-24 오후 8.41.53.png" alt="" data-size="line">) → **\[Publish to community]** button on the Container card within the **Dashboard page**.
* Click the **\[Publish]** button located at the top of the Workspace.
{% endstep %}

{% step %}
### **Fill in Template Details**

<figure><img src="../../.gitbook/assets/template_01.png" alt=""><figcaption></figcaption></figure>

#### Select Your Container

Select the container to publish as a template.

#### **Enter Your Template Name**

Write a name that will make your template stand out. We recommend that the name clearly reflect the purpose or technology being used.\
&#xNAN;_&#x65;.g., "React Starter Template" or "Python Flask API"_

#### **Description**

Provide a detailed description of your template.

* Specific use cases.\
  &#xNAN;_&#x65;.g., "A simple example using OpenWeatherMap API and The Solar System OpenData API."_
* Description can be up to 280 characters long.

{% hint style="info" %}
**Tip:** The description will be shown on the template card. Write a short and clear explanation to help users quickly grasp what your template offers.
{% endhint %}

{% hint style="warning" %}
Please note that template name and description fields only support English.
{% endhint %}

#### **Stack**

Please enter the technology stack used in the container. You can add up to 10 items.

#### **Recommended** Performance

Please select the Recommended Performance.\
Your container's performance is preselected as the Recommended Performance. This setting will then be the default choice for all users who create a new container using your template. [container-performance.md](../dashboard/container/container-performance.md "mention")

* Micro (0.5vCPU, 1GB Memory)
* Small (2vCPU, 2GB Memory)
* Medium (4vCPU, 4GB Memory)
* Large (8vCPU, 8GB Memory)



Click the **\[Temporary save]** button to save temporarily, or click the **\[Next]** button to proceed to the next step.

{% hint style="warning" %}
Please note that **only one Temporary save is possible.**
{% endhint %}
{% endstep %}

{% step %}
### Enter your template introduction

A text file that contains basic information and usage instructions for software. It typically explains the purpose of the project, installation steps, and how to use it, serving as an important first impression that introduces the project.

<figure><img src="../../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>

Please provide introduction of your template. We recommend including the following:

* **Overview**\
  Describe the main function or purpose of the template. Also add the intended audience, expected benefits, and examples of its use.
* **Preview**\
  Add preview images of the result screen, code structure, or key features after the template is run.
* **Features**\
  List the Key Features.
* **Requirements**\
  Lists the environment and tools required to run this template.

If it’s difficult to write, you can use the [AI-Generated Template Introduction](create-a-template/ai-generated-template-introduction.md) feature!

{% hint style="success" %}
_**New**_ 🎉\
With the AI-Generated Template Introduction feature, you can now let AI automatically create an introduction for your template. The AI reads the code in your container and generates a clear, helpful overview—saving you time and effort.

[ai-generated-template-introduction.md](create-a-template/ai-generated-template-introduction.md "mention")
{% endhint %}
{% endstep %}

{% step %}
### Create a Template

<figure><img src="../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

Please review the content you've written, and if everything is correct, click the **\[Create]** button. Before template creation begins, make sure the following is met:

* Don't you have a file like a password?
* Is it possible to run the template right away?
* Is there any file that would violate the security?

{% hint style="info" %}
Note

* How do I add a **thumbnail image?**
  * When creating a template, if you upload at least one image in your Template Introduction, the first image will automatically be set as the template thumbnail. If no image is provided,  a default thumbnail will be generated using the **Default Stack** background and your template name.\
    If a first image exists, a thumbnail toggle UI will appear, allowing you to choose between the default thumbnail and the first uploaded image.
* **When a template is created, any containers running will be terminated.**
* After a template is created, it undergoes a security review.
* If the container has **a large file size** or the security review process takes a long time, template creation **may take a long time.**
{% endhint %}

{% hint style="warning" %}
Note

If your template **fails to create**:

1. **Click your failed template.**
2. **Check fail reasons**&#x20;
   1. If a file contained in the container is causing the issue, click the  ![](../../.gitbook/assets/run_container.png) button to run the container and resolve the issue.
   2. If the template fails to create even though your container has no issues, please contact us for assistance.
3. If you have resolved the cause, Click the **\[Re-create]** button.
{% endhint %}
{% endstep %}
{% endstepper %}

***

### **Best Practices for Template Creation**

* **Keep it Clean and Simple**\
  Avoid unnecessary files or configurations to keep the template lightweight.
* **Provide Clear Documentation**\
  Include a README.md file to guide users on how to use the template effectively.
* **Test Before Publishing**\
  Ensure your template is fully functional and error-free.

By creating a template, you contribute to a collaborative and efficient development community. Start building your template today and share your expertise with the world.
