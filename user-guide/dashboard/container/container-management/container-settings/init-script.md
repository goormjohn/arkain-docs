---
icon: scroll
---

# Init Script

If you have a script that needs to be executed repeatedly when running a container, you can use the Init script. The **Init script** runs from the root directory `(/)` of the container and is executed when the container starts.

It is commonly used to write scripts that execute your application.

<figure><img src="../../../../../.gitbook/assets/Init Script.png" alt=""><figcaption></figcaption></figure>

### How to use the Init Script?

{% stepper %}
{% step %}
You can navigate to the **Dashboard** page and enter the **Container Settings** page.
{% endstep %}

{% step %}
In the **Container Settings** page, under the **Init Script** section, you can write the execution commands. Once you're done writing, it will be saved automatically, and these commands will automatically run when the container starts.&#x20;
{% endstep %}
{% endstepper %}
