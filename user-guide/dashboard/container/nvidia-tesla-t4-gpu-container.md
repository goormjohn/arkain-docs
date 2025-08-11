---
icon: microchip
---

# NVIDIA Tesla T4 GPU Container

**NVIDIA Tesla T4** GPU resources can be paired with **Arkain** to create containers that can perform tasks that require high-performance computing, such as deep learning.

### GPU Container Specification

<table><thead><tr><th width="243">Type</th><th align="center">Specification</th></tr></thead><tbody><tr><td>vCPU</td><td align="center">3.5</td></tr><tr><td>Memory</td><td align="center">13GB</td></tr><tr><td>Container creation</td><td align="center">unlimited</td></tr><tr><td>Weekly usage hours</td><td align="center">unlimited</td></tr></tbody></table>



<figure><img src="../../../.gitbook/assets/GPU_container.png" alt=""><figcaption></figcaption></figure>

### **GPU Storage Billing Policy**

* GPU containers are created with **30GB of storage by default.** If you want more storage, you can upgrade and use it.
* **Free Plan: Credits are charged** based on the usage of 30GB.
* **Membership Plan:** Up to 30GB **can be used for free.**

{% hint style="info" %}
For more information about pricing and container Specifications, see [Container Specifications.](container-specifications.md)
{% endhint %}

### Create a GPU Container

To create a GPU container, select \[**NVIDIA Tesla T4]** as the software stack when creating the container. The creation time for GPU containers can be longer than for regular containers.

{% hint style="warning" %}
GPU resources in Arkain are configured in the cloud environment. As so, the creation and execution of GPU containers may be limited by the available GPU resources in the cloud.\
Therefore, if creation fails, **please try again after a short while.**
{% endhint %}
