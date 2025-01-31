---
icon: microchip
---

# Introduction to GPU

`NVIDIA Tesla T4` GPU resources can be paired with **Arkain** to create containers that can perform tasks that require high-performance computing, such as deep learning.

### GPU Container Specification

<table><thead><tr><th width="243">Type</th><th align="center">Specification</th></tr></thead><tbody><tr><td>vCPU</td><td align="center">3.5</td></tr><tr><td>Memory</td><td align="center">13GB</td></tr><tr><td>Container creation</td><td align="center">unlimited</td></tr><tr><td>Weekly usage hours</td><td align="center">unlimited</td></tr></tbody></table>

{% hint style="warning" %}
_Please remind that you can use max. 12 hours a day depending on the GPU resources in the cloud._
{% endhint %}

### **GPU Storage Billing Policy**

* **Free Plan:** You can use up to **5GB of storage for free**. If you exceed 5GB, credits will automatically be deducted and you can expand your storage to up to 30GB.
* **Membership Plan:** You can use up to **30GB of storage space for free**, and you can use up to 80GB of storage space with credits.

{% hint style="info" %}
For more information about pricing and container Specifications, see [Container Specifications.](container-specifications.md)
{% endhint %}

### Create a GPU Container

To create a GPU container, select `NVIDIA Tesla T4` as the software stack when creating the container. \
The creation time for GPU containers can be longer than for regular containers (up to 5 minutes).

{% hint style="warning" %}
GPU resources in Arkain are configured in the cloud environment. As so, the creation and execution of GPU containers may be limited by the available GPU resources in the cloud.\
Therefore, if creation fails, **please try again after a short while.**
{% endhint %}
