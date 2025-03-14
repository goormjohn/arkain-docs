---
icon: share-nodes
---

# Container Sharing

You can share your container with others to collaborate or showcase your projects. Even if someone doesn't have a Arkain account, they can still access the shared container.

Click the **\[Setting]** button (<img src="../../../../../.gitbook/assets/setting (1).png" alt="" data-size="line">) of the container you want to share on the Arkain's Dashboard. In the Container Settings page, click the **\[Share]** button (<img src="../../../../../.gitbook/assets/share (1).png" alt="" data-size="line">) at the top-right corner.

<figure><img src="../../../../../.gitbook/assets/share.png" alt=""><figcaption></figcaption></figure>

There are two ways to share containers:

### **Share with Members**

{% stepper %}
{% step %}
Enter the email address of the user you want to invite to the container. The user's email must be the email registered with Arkain.

<figure><img src="../../../../../.gitbook/assets/share_01.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Select permissions to access the container.

<table><thead><tr><th width="241">Permission</th><th>Possible actions</th></tr></thead><tbody><tr><td>Read</td><td><ul><li>Source code view</li></ul></td></tr><tr><td>Read/Write</td><td><ul><li>Source code view, <strong>edit</strong></li></ul></td></tr><tr><td>Root</td><td><ul><li>Source code view, edit</li><li><strong>Version control (Git)</strong></li><li><strong>Configuring init script</strong></li><li><strong>URL/Port</strong></li><li><strong>Environment Variable</strong></li></ul></td></tr><tr><td>Sharable (Root)</td><td><ul><li>Source code view, edit</li><li>Version control (Git)</li><li>Configuring init script</li><li>URL/Port</li><li>Environment Variable</li><li><strong>Sharing Container</strong></li><li><strong>Changing member permissions</strong></li></ul></td></tr></tbody></table>
{% endstep %}

{% step %}
Click the **\[Invite]** button to share the container with the selected user.
{% endstep %}
{% endstepper %}

### **Share with Link**

{% stepper %}
{% step %}
Set the sharing scope and permissions above the Members list for the link.

If you set the sharing scope to **\[Invited user]**, only members who have been invited to the container will be able to access the container using the link. On the other hand, if you select \[Anyone with a link], any user can access the container using the link , even if they are not a member of the container.
{% endstep %}

{% step %}
Share the link with the users who you want to invite.
{% endstep %}

{% step %}
Users who access the container through the shared link will receive access to the container based on the sharing link settings.
{% endstep %}
{% endstepper %}

Also, you can share a Container from the Workspace settings

{% content-ref url="../../../../workspace/collaboration/contaienr-sharing.md" %}
[contaienr-sharing.md](../../../../workspace/collaboration/contaienr-sharing.md)
{% endcontent-ref %}

