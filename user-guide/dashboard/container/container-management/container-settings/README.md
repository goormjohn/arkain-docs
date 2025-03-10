---
icon: container-storage
---

# Container Settings

Click![](<../../../../../.gitbook/assets/스크린샷 2025-02-24 오후 1.32.16.png>) button in the Container Card. You can go to the container **settings page.**

<figure><img src="../../../../../.gitbook/assets/Setting.png" alt=""><figcaption></figcaption></figure>

***

### **Container Basics**

Add a description to provide context for what the container is used for. This is especially helpful for collaboration.

### **Container info**

You can check various container information, such as the container's hardware specs including CPU, memory, and storage, as well as the container region, stack and OS.

{% content-ref url="../../container-specifications.md" %}
[container-specifications.md](../../container-specifications.md)
{% endcontent-ref %}

You can also add storage capacity or change the container specs (CPU and memory).

* Add Storage
  * **Default:** 5GB / **Up to:** 200GB
  * **Free Plan**: 5GB for free
  * **Membership Plan**: 30GB for free

{% hint style="info" %}
You can change settings after stopping the container.
{% endhint %}

{% hint style="warning" %}
**Check before Adding Storage**

* Once upgraded, storage **cannot be downgraded.**
* You can upgrade again **6 hours after** the previous upgrade.
* If you **exceed your free storage**, **additional charges** will apply based on your usage.
{% endhint %}

### Share container

You can invite other users to your container with 4 permissions (Readonly, Editable(non-root/root), Editable & sharable(root)). You can also share the container's shared link with other users.

{% content-ref url="container-sharing.md" %}
[container-sharing.md](container-sharing.md)
{% endcontent-ref %}

### **Container status**

Save resources by activating the **Auto-off** feature. The container will automatically stop after a period of inactivity, reducing unnecessary costs and improving efficiency.

{% content-ref url="../../auto-off.md" %}
[auto-off.md](../../auto-off.md)
{% endcontent-ref %}

### **Init Script**

If you have a script that needs to be executed repeatedly when running a container, try the Init script! The Init script runs from the root directory `(/)` of the container and is executed when the container starts.

{% content-ref url="init-script.md" %}
[init-script.md](init-script.md)
{% endcontent-ref %}

### **URL/Port**

View and manage the unique URL and Port for accessing your running application directly from the browser. Port is crucial for ensuring your application or services can be accessed externally.

{% content-ref url="../../../../workspace/url-port.md" %}
[url-port.md](../../../../workspace/url-port.md)
{% endcontent-ref %}

### **7. Environment Variables**

Environment variables are defined as key-value pairs and can be used to store database credentials, API keys, and other sensitive information for applications.&#x20;

By using environment variables, programs can be executed according to the environment without changing the source code, and sensitive security keys do not need to be stored directly in configuration files, enhancing security.

{% content-ref url="environment-variable.md" %}
[environment-variable.md](environment-variable.md)
{% endcontent-ref %}

### **8. Delete this container**

You can delete the container by clicking the **\[Delete]** button on the container settings page.

