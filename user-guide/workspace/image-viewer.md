---
icon: image-landscape
---

# Image Viewer

The **Image Viewer** supports convenient image inspection with features like zooming, background color selection, scaling options, and keyboard shortcuts.

### Opening Images

Clicking on an image file in **Project Sidebar** automatically opens the image in the viewer.\
Depending on the image dimensions, it will be scaled as follows:

* If the image is smaller than the viewer, it displays at **100% (actual size).**
* If the image is larger, it is scaled down to fit the screen while preserving its aspect ratio.

{% hint style="warning" %}
**Note:** The image viewer does not support previewing images **larger than 4MB**.
{% endhint %}

### Image Control with Toolbar

In the bottom-right corner of the Image Viewer, you'll find a toolbar that lets you control how the image appears — you can zoom in or out, change the background color, switch scaling modes, or access advanced settings.

<figure><img src="../../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

#### Zooming In and Out

To zoom in or out:

* Click the **\[+] or \[-]** buttons in the toolbar.
* Use keyboard shortcuts:
  * **Zoom in:** <kbd>Ctrl + =</kbd> (macOS: <kbd>⌘=</kbd>)
  * **Zoom out:** <kbd>Ctrl + -</kbd> (macOS: <kbd>⌘-</kbd>)

Each action adjusts the zoom level by **10%**.\
If the current scale is a decimal (e.g., 23.2%), it will be **rounded to the nearest 10%** (e.g. zoom in → 30%, zoom out → 20%).

{% hint style="info" %}
The zoom range is limited between **10% and 300%**. Once the limit is reached, the corresponding button will be disabled.
{% endhint %}

#### Restoring Default Scaling

To return to the default scaling:

* Click the **\[View with default scaling]\(**<img src="../../.gitbook/assets/image (6).png" alt="" data-size="line">**)** button in the toolbar.
* Or press the shortcut <kbd>Ctrl + 0</kbd>(macOS: <kbd>⌘0</kbd>).

This resets the image to the scaling option defined in your settings (e.g., Actual Size or Fit Width and Height).

#### Adjusting Scaling Options

You can change how the image is displayed by clicking the **\[Change scaling option]\(**<img src="../../.gitbook/assets/image (3) (3).png" alt="" data-size="line">**)** button in the toolbar to open the dropdown menu.

From there, you can choose between:

* **Actual Size**: Displays the image at 100% of its original dimensions
* **Fit Width and Height** (default): Scales the image to fit the viewer while keeping its aspect ratio

#### Changing Background Color

You can change the image viewer’s background color for better visibility:

* Click the **\[Change background color]\(**<img src="../../.gitbook/assets/image (1) (3).png" alt="" data-size="line">**)** button in the toolbar.
* Select a color from the **color picker** in the toolbar.
* Click the **\[Reset]\(**<img src="../../.gitbook/assets/image (2) (3).png" alt="" data-size="line">**)** button to restore the default background color.
* Click the **displayed HEX code** to copy it to your clipboard.

{% hint style="info" %}
Scaling option and Background color changes apply **only to the current viewer** and do not affect other image viewers.
{% endhint %}

#### Advanced Settings

You can access **Image Viewer settings tab** in three ways:

* From the **background color picker**, click the **\[settings icon]\(**<img src="../../.gitbook/assets/image (4) (3).png" alt="" data-size="line">**)** in the top-right corner.
* From the **scaling options dropdown**, click the **Advanced Settings** at the bottom of the list.
* From the **Preference tab**, click the **Image Viewer** of the list.

In the settings tab, you can adjust:

* **Default background color**
* **Default scaling option** (e.g., Actual Size or Fit Width and Height)

{% hint style="info" %}
Changes in settings do **not affect currently open viewers**.
{% endhint %}
