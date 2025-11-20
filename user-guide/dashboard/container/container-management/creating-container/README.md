---
description: >-
  Creating a new container in Arkain is simple and efficient! Follow these steps
  to set up your container and start working on your project seamlessly.
icon: container-storage
---

# Creating Container

Go to the [Arkain Dashboard](https://arkain.io/my/dashboard) page, Click the **\[New container]** button.

<figure><img src="../../../../../.gitbook/assets/Creating Container (2).png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
**Set Up a Container Base template**

Currently, the supported base templates are **Blank, NVIDIA Tesla T4, Python, Node.js, Java, React and Go**.
{% endstep %}

{% step %}
**Configure OS**&#x20;

The available OS versions are **Ubuntu 22.04 LTS** and **Ubuntu 20.04 LTS**.
{% endstep %}

{% step %}
**Set a Container Name**

Enter a name for your container.

{% hint style="warning" %}
**Note**

* Container names must only contain **alphabets, numbers, underscores (\_), or hyphens (-).**
* The container name must be **unique** among your containers.
{% endhint %}
{% endstep %}

{% step %}
**Configure Container Performance**

You can check the available container performance on [this page](https://docs.arkain.io/user-guide/dashboard/container/container-specifications).
{% endstep %}

{% step %}
**Enable the advanced features (optional)**

You can enable the advanced features such as [**AI Supporter**](../../../../arkain-ai/ai-supporter.md) **and** [**Code Supporter**](../../../../workspace/editor/code-supporter.md).

{% hint style="warning" %}
The cost for using the advanced features such as **AI Supporter and Code Supporter** is added to your container cost. However, when using a GPU container, there is no additional charge for these features; instead, your allocated **GPU compute and memory resources** will be reduced.
{% endhint %}
{% endstep %}

{% step %}
**Configure Additional Storage**

* **Default:** 5GB / **Up to:** 80GB
* **Free Plan**: 5GB for free
* **Membership Plan**: 15GB for free

{% hint style="info" %}
GPU containers are created with **30GB of storage by default**.
{% endhint %}

{% hint style="warning" %}
**Note**

* Once upgraded, storage **cannot be downgraded.**
* If you **exceed your free storage**, **additional charges** will apply based on your usage.
* You can also **upgrade storage after the container has been created**.
{% endhint %}
{% endstep %}

{% step %}
**Activate Additional Modules/Packages (optional)**

Install additional modules and packages during container creation to save time.
{% endstep %}
{% endstepper %}

***

With these easy steps, you’re all set to create and customize your container in Arkain! \
Start building smarter and faster today.&#x20;
