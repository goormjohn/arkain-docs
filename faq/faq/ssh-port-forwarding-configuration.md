---
icon: comment-question
---

# SSH Configuration

You can access containers in Arkain from the outside using the SSH / Port Forwarding feature.

## **SSH Configuration** <a href="#ssh-configuration" id="ssh-configuration"></a>

{% hint style="info" %}
**The SSH feature can be used after membership subscription.**
{% endhint %}

You can SSH to the Arkain container from the outside.

{% stepper %}
{% step %}
Click **\[Container]** → **\[SSH Configuration]** on the top menu to open the **\[SSH Configuration]** pop-up window.

<figure><img src="../../.gitbook/assets/SSH Configuration_01.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Click the copy icon to the right of the command and paste it from your local environment or other external instances shell.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Then enter your password.

If this is your first connection, click the **\[Generate]** button to generate a password. Click the copy icon on the right to copy it and paste it in the shell you want to SSH into.\
The password that is issued is not stored anywhere. Once you've been issued a password, you can use it for subsequent accesses.

<figure><img src="../../.gitbook/assets/SSH Configuration_02.png" alt=""><figcaption></figcaption></figure>

If you don't remember it, you can **\[Regenerate]**.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
The SSH connection IP and port change every time the Arkain container is turned off and on.\
SSH connections are only available while the Arkain container is on.
{% endhint %}
