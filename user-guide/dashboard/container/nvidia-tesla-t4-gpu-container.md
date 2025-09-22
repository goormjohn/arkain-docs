---
icon: microchip
---

# NVIDIA Tesla T4 GPU Container

**NVIDIA Tesla T4** GPU resources can be paired with **Arkain** to create containers that can perform tasks that require high-performance computing, such as deep learning.

### GPU Container Specification

<table><thead><tr><th width="243">Type</th><th align="center">Specification</th></tr></thead><tbody><tr><td>vCPU</td><td align="center">3.5</td></tr><tr><td>Memory</td><td align="center">13GB</td></tr></tbody></table>

{% hint style="warning" %}
Using advanced features like **AI Supporter and Code Supporter** on a GPU container will reduce your allocated GPU compute and memory resources. This does not incur an additional credit charge.
{% endhint %}

<figure><img src="../../../.gitbook/assets/NVIDIA Tesla T4 GPU Container.png" alt=""><figcaption></figcaption></figure>



### **GPU Storage Billing Policy**

* GPU containers are created with **30GB of storage by default.** If you want more storage, you can upgrade and use it.
* **Free Plan: Up to 5GB can be used for free.**
* **Membership Plan:** **Up to 15GB** **can be used for free.**
* Additional storage will be charged in credits based on usage.

{% hint style="info" %}
For more information about pricing and container performance, refer to the [Container Performance](container-performance.md) document.
{% endhint %}

### Create a GPU Container

To create a GPU container, select \[**NVIDIA Tesla T4]** as the base template when creating the container. The creation time for GPU containers can be longer than for regular containers.

{% hint style="warning" %}
GPU resources in Arkain are configured in the cloud environment. As such, the creation and execution of GPU containers may be limited by the available GPU resources in the cloud.\
Therefore, if creation fails, **please try again after a short while.**\
You can receive a notification 1 minute before your GPU container is terminated due to insufficient cloud resources.
{% endhint %}
