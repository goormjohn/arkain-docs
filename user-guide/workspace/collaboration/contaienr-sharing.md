---
description: >-
  You can share your container with others to collaborate or showcase your
  projects. Even if someone doesn't have a Arkain account, they can still access
  the shared container.
---

# Container Sharing

### Sharing a Container from the Workspace <a href="#sharing-a-container-from-the-workspace" id="sharing-a-container-from-the-workspace"></a>

You can also share containers from Arkain's Workspace. In the Workspace of the container you want to share, click **\[Share This Container]**(![](<../../../.gitbook/assets/스크린샷 2025-03-08 오후 3.55.49.png>)) in the Activity bar to open the Sidebar.

#### **Share as an email**

{% stepper %}
{% step %}
Click the **\[Share as an email]** accordion button, enter the email address of the user you want to share the container with.
{% endstep %}

{% step %}
Set the sharing permissions.

<table><thead><tr><th width="241">Permission</th><th>Possible actions</th></tr></thead><tbody><tr><td>Read</td><td><ul><li>Source code view</li></ul></td></tr><tr><td>Read/Write</td><td><ul><li>Source code view, <strong>edit</strong></li></ul></td></tr><tr><td>Root</td><td><ul><li>Source code view, edit</li><li><strong>Version control (Git)</strong></li><li><strong>Configuring init script</strong></li><li><strong>URL/Port</strong></li><li><strong>Environment Variable</strong></li></ul></td></tr><tr><td>Sharable (Root)</td><td><ul><li>Source code view, edit</li><li>Version control (Git)</li><li>Configuring init script</li><li>URL/Port</li><li>Environment Variable</li><li><strong>Sharing Container</strong></li><li><strong>Changing member permissions</strong></li></ul></td></tr></tbody></table>
{% endstep %}

{% step %}
Click the **\[Share]** button to share the container with the selected user.

{% hint style="warning" %}
The email must be the one of a member who has registered on Arkain. You cannot share a container with the email of a member who is not registered on Arkain.
{% endhint %}
{% endstep %}
{% endstepper %}

#### **Share by link**

{% stepper %}
{% step %}
Set the shared scope and permission on invitation for the link. **\[Anyone]** allows access without logging in, while **\[Container member]** requires logging into Arkain.
{% endstep %}

{% step %}
Share the link with the users who you want to invite.
{% endstep %}

{% step %}
Users who access the container through the shared link will receive access to the container based on the shared link settings.
{% endstep %}
{% endstepper %}

### Sharing a Container from the Dashboard <a href="#sharing-a-container-from-the-workspace" id="sharing-a-container-from-the-workspace"></a>

You can also share containers in [Arkain Dashboard](https://arkain.io/my/dashboard).

{% content-ref url="../../dashboard/container/container-management/container-settings/container-sharing.md" %}
[container-sharing.md](../../dashboard/container/container-management/container-settings/container-sharing.md)
{% endcontent-ref %}
