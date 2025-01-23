---
icon: comment-question
---

# SSH / Port Forwarding Configuration

You can access containers in Arkain from the outside using the SSH / Port Forwarding feature.

## **SSH Configuration** <a href="#ssh-configuration" id="ssh-configuration"></a>

{% hint style="info" %}
**The SSH feature can be used after membership subscription.**
{% endhint %}

You can SSH to the Arkain container from the outside.\
Click **\[Container] > \[SSH Configuration]** on the top menu to open the **\[SSH Configuration]** pop-up window.

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

Click the copy icon to the right of the command and paste it from your local environment or other external instances shell.

<figure><img src="../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

Then enter your password.\
If this is your first connection, click the _**Generate**_ button to generate a password. Click the copy icon on the right to copy it and paste it in the shell you want to SSH into.\
The password that is issued is not stored anywhere.

<figure><img src="../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

Once you've been issued a password, you can use it for subsequent accesses.

If you don't remember it, you can _**Regenerate**_.\
**The SSH connection IP and port change every time the Arkain container is turned off and on.**\
**SSH connections are only available while the Arkain container is on.**

***

## **Port Forwarding Configuration (Port Forwarding)** <a href="#port-forwarding-configuration-port-forwarding" id="port-forwarding-configuration-port-forwarding"></a>

You can open a specific port of the Arkain container to make it accessible from the outside.\
Click **\[Container] > \[Port Forwarding Configuration]** in the top menu to open the **\[Port Forwarding Configuration]** pop-up window.

<figure><img src="../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

You can register the port you want to open by entering it directly in 'Internal ports', or you can register the default port of the selected service by selecting it in 'Type'.

The registered ports will be available in the table below.

<figure><img src="../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

You can access it from the outside using the 'IP' and 'External Port'.\
The 'IP' and 'External port' change every time the corresponding Arkain container is turned off and on.\
You can register up to 2 port forwarding settings per container.

{% hint style="info" %}
**External access is only possible while the Arkain container is on.**
{% endhint %}
