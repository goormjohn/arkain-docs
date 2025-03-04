---
icon: ban
---

# Automatic Stop

**Automatic stop** shuts down containers after 30-40 minutes when the container's owner closes all **Workspace** browsers.

This feature prevents unnecessary credit use and allows you to use the service more efficiently.

## Feature Guide <a href="#feature-guide" id="feature-guide"></a>

When **Automatic Stop** is **On**;

* **Automatic Stop**: The container will automatically shut down 30-40 minutes after all browsers are closed. No credits are deducted after that.
* **Owner-based**: The container owner must close all browsers for **Automatic Stop** to occur. If you are only using it as a guest, owner should turn off **Automatic Stop**.
* **Background run**: If you want to keep container running in the background (always-on), you must turn off **Automatic Stop**.

When **Automatic Stop** is **Off**;

* **Manual Exit(stop)**: The container will continue to run even if you close only browsers. Please manually stop the container by clicking the **\[Container Exit]** button located in the workspace or the **\[Stop]** button located in the dashboard.
* **Credit use**: If you do not manually stop the container, it will continue to deduct credits. To avoid unnecessary credit use, be sure to exit and stop the container.

{% hint style="danger" %}
**NOTE**\
The **Automatic Stop** feature works based on all browsers of the container owner being closed. Be sure to turn off **Automatic Stop** when using guest accounts or background run.
{% endhint %}

## Set Automatic Stop <a href="#set-automatic-stop" id="set-automatic-stop"></a>

You can set **Automatic Stop** from the Dashboard and Workspace.

### From Dashboard <a href="#from-dashboard" id="from-dashboard"></a>

* Click Container setting button![](https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FAnr0KhV0ED5q8oUqo0zY%252Fimage.png%3Falt%3Dmedia%26token%3D8268a1f0-d890-4277-ac95-5dd60224a352\&width=300\&dpr=4\&quality=100\&sign=1527ba46\&sv=2) → Active **\[Automatic container stop]** in Container Status

<figure><img src="../../../.gitbook/assets/automaticstop_01.png" alt=""><figcaption></figcaption></figure>

## From Workspace <a href="#from-ide" id="from-ide"></a>

* Click the **\[Auto stop]** (<img src="../../../.gitbook/assets/[core] Button.png" alt="" data-size="line">) button in the bottom bar, and then click **\[Using feature]** in the popup window to enable the container's automatic stop feature.
* To turn off the feature, click the **\[Auto stop]** (<img src="../../../.gitbook/assets/[core] Button.png" alt="" data-size="line">) button again and then click **\[Turn off the feature]** in the popup.

<figure><img src="../../../.gitbook/assets/automaticstop_01-1.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/automaticstop_03 (1).png" alt=""><figcaption></figcaption></figure>
