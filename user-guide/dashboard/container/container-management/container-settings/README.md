---
icon: container-storage
---

# Container Settings

Click the **\[Settings]** button(<img src="../../../../../.gitbook/assets/setting (1) (1) (1).png" alt="" data-size="line">) in the Container Card. You can go to the **Container Settings page.**

<figure><img src="../../../../../.gitbook/assets/Container Settings (3).png" alt=""><figcaption></figcaption></figure>

***

### **Container Basics**

Add a description to provide context for what the container is used for. This is especially helpful for collaboration.

### **Container info**

You can check various container information, such as the container's hardware specs including CPU, memory, and storage, as well as the container region, base template and OS.

{% content-ref url="../../container-performance.md" %}
[container-performance.md](../../container-performance.md)
{% endcontent-ref %}

You can also add storage capacity or change the container specs (CPU and memory).

* Add Storage
  * **Default:** 5GB / **Up to:** 80GB
  * **Free Plan**: 5GB for free
  * **Membership Plan**: 15GB for free

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

You can invite other users to your container with 4 permissions (Readonly, Editable(non-root/root), Editable & sharable(root)). You can also share the container's sharing link with other users.

{% content-ref url="container-sharing.md" %}
[container-sharing.md](container-sharing.md)
{% endcontent-ref %}

### **Container status**

* **Auto-stop**

Save resources by activating the **Auto-stop** feature. The container will automatically stop after a period of inactivity, reducing unnecessary costs and improving efficiency.

{% content-ref url="../../auto-stop.md" %}
[auto-stop.md](../../auto-stop.md)
{% endcontent-ref %}

* **AI Supporter**

Boost Side Chat's effectiveness with the **AI Supporter** feature. By learning your project's context—including codebase, configurations, and structure—it enables more precise, relevant, and context-aware assistance.

{% content-ref url="../../../../arkain-ai/ai-supporter.md" %}
[ai-supporter.md](../../../../arkain-ai/ai-supporter.md)
{% endcontent-ref %}

* **Code Supporter**

Write and fix code more easily and accurately with the **Code Supporter** feature. It provides real-time assistance through features like Go to Definition, Autocomplete Suggestions, and Live Diagnostics.

{% content-ref url="../../../../workspace/editor/code-supporter.md" %}
[code-supporter.md](../../../../workspace/editor/code-supporter.md)
{% endcontent-ref %}

### **Init Script**

If you have a script that needs to be executed repeatedly when running a container, you can use the Init script. The Init script runs from the root directory `(/)` of the container and is executed when the container starts.

{% content-ref url="init-script.md" %}
[init-script.md](init-script.md)
{% endcontent-ref %}

### **URL/Port**

View and manage the unique URL and Port for accessing your running application directly from the browser. Port is crucial for ensuring your application or services can be accessed externally.

{% content-ref url="../../../../workspace/url-port.md" %}
[url-port.md](../../../../workspace/url-port.md)
{% endcontent-ref %}

### **SSH**

View and manage the SSH command and password for accessing containers in Arkain from the outside. SSH connections are only available while the container is running.

{% hint style="info" %}
The SSH feature is available only to **membership** plan users.
{% endhint %}

{% content-ref url="ssh-configuration.md" %}
[ssh-configuration.md](ssh-configuration.md)
{% endcontent-ref %}

### **Environment Variables**

Environment variables are defined as key-value pairs and can be used to store database credentials, API keys, and other sensitive information for applications.&#x20;

By using environment variables, programs can be executed according to the environment without changing the source code, and sensitive security keys do not need to be stored directly in configuration files, enhancing security.

{% content-ref url="environment-variable.md" %}
[environment-variable.md](environment-variable.md)
{% endcontent-ref %}

### **Delete this container**

You can delete the container by clicking the **\[Delete]** button on the Container Settings page.

