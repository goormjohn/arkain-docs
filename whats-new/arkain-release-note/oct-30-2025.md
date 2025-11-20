# October 30, 2025

## Highlights

<figure><img src="../../.gitbook/assets/107th_highlight.png" alt=""><figcaption></figcaption></figure>

#### 🖼️ Elevate Side Chat: Upload Images for Visual Context!&#xD;

You can now give Side Chat visual context by uploading images. Upload UI designs, mockups, or rendering issues to get more accurate AI analysis and assistance.

## New Features

* Added support for the following new LLMs.
  * claude-sonnet-4.5
  * claude-haiku-4.5
* The Credit usage page now displays the specific reason for each credit deduction.

## **Changes**

**Container management**

* Snap is now disabled when creating containers through GitHub Import and only available for empty containers.
* Inactivating containers can now be deleted.
* Improved the styling and usability of the Container Sharing popup on mobile screens.

**Workspace**

* Changed default LLM model in the Side Chat to a claude-haiku-4.5.
* Changed the Side Chat History to sort chats by last activity instead of creation time.
* Expanded the ‘Recent Chats’ view in the Side Chat to display more details.
* Added an activation animation to the Side Chat input box when users start typing.
* Improved the \[Share This Container] UI and overall usability in the Sidebar.
* Enhanced the context menu design and usability in the Project Sidebar.

## Bug Fixes

**Container management**

* Fixed the bug that allowed duplicate port settings in the domain.
* Fixed the bug where the \[Last created] filter on the All Containers page was not working.

**Credits**

* Fixed the bug where the credit usage period was incorrectly displayed when deducted due to credit overuse.
* Fixed the bug where credits continued to be deducted even after the container was inactive.
* Fixed the bug where duplicate credit deductions occurred when a container was blocked during execution.
* Fixed the bug where credit was not being properly deducted for some GPU containers.

**Template**

* Fixed the bug causing timeouts when using the AI-Generated Template Introduction in specific cases.
* Fixed the bug where the color variation was not applied to the thumbnail image when hovering over the template card.

**Workspace**

* Fixed the bug where an error was incorrectly shown after installing a Python package.

## Deprecated

* Removed the claude-sonnet-4 model from the Side Chat.
* Removed question presets from the Side Chat.
