---
icon: circle-4
---

# SSH / Port Forwarding Configuration

You can access containers in Arkain from the outside using the SSH / Port Forwarding feature.

#### **SSH Configuration**[¶](https://mkdocs-mxedr.run.goorm.site/06.-FAQ/SSH_Port-Forwarding-Configuration/#ssh-configuration) <a href="#ssh-configuration" id="ssh-configuration"></a>

**The SSH feature can be used after membership subscription.**

You can SSH to the Arkain container from the outside.

Click\*\* \[Container] > \[SSH Configuration]\*\* on the top menu to open the \[SSH Configuration] pop-up window.

![image alt text](https://mkdocs-mxedr.run.goorm.site/assets/images/SSH/Port-Forwarding-Configuration.en_54.png)

Click the copy icon to the right of the command and paste it from your local environment or other external instances shell.

![image alt text](https://mkdocs-mxedr.run.goorm.site/assets/images/SSH/Port-Forwarding-Configuration.en_55.png)

Then enter your password.

If this is your first connection, click the _**Generate**_ button to generate a password. Click the copy icon on the right to copy it and paste it in the shell you want to SSH into.

The password that is issued is not stored anywhere.

![image alt text](https://mkdocs-mxedr.run.goorm.site/assets/images/SSH/Port-Forwarding-Configuration.en_56.png)

Once you've been issued a password, you can use it for subsequent accesses.

If you don't remember it, you can _**Regenerate**_.

**The SSH connection IP and port change every time the Arkain container is turned off and on.**

**SSH connections are only available while the Arkain container is on.**

#### **Port Forwarding Configuration (Port Forwarding)**[¶](https://mkdocs-mxedr.run.goorm.site/06.-FAQ/SSH_Port-Forwarding-Configuration/#port-forwarding-configuration-port-forwarding) <a href="#port-forwarding-configuration-port-forwarding" id="port-forwarding-configuration-port-forwarding"></a>

You can open a specific port of the Arkain container to make it accessible from the outside.

Click **\[Container] > \[Port Forwarding Configuration] \*\*in the top menu to open the** \*\*\[Port Forwarding Configuration] pop-up window.

![image alt text](https://mkdocs-mxedr.run.goorm.site/assets/images/SSH/Port-Forwarding-Configuration.en_57.png)

You can register the port you want to open by entering it directly in 'Internal ports', or you can register the default port of the selected service by selecting it in 'Type'.

The registered ports will be available in the table below.

![image alt text](https://mkdocs-mxedr.run.goorm.site/assets/images/SSH/Port-Forwarding-Configuration.en_58.png)

You can access it from the outside using the 'IP' and 'External Port'.

The 'IP' and 'External port' change every time the corresponding Arkain container is turned off and on.

You can register up to 2 port forwarding settings per container.

**External access is only possible while the Arkain container is on.**
