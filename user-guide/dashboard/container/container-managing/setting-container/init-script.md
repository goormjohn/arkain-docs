---
icon: scroll
---

# Init Script

If you have a script that needs to be executed repeatedly when running a container, try the Init script! The Init script runs from the root directory `(/)` of the container and is executed when the container starts.

It is commonly used to write scripts that execute your application.

<figure><img src="../../../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

### How to use init script?

You can navigate to the **Dashboard** and enter the **Container Settings** page.

In the **Container Settings** page, under the **Init Script** section, you can write the execution commands. Once you're done writing, it will be saved automatically. And these commands will automatically run when the container starts.

{% hint style="warning" %}
**Script will run in the root path(/).**
{% endhint %}







