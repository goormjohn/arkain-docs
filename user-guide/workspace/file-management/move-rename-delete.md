---
icon: cabinet-filing
---

# Move / Rename / Delete

## Move File

The Move feature allows you to move files or folders from their current location to a desired location. In Arkain's **Project Sidebar**, select the file/folder you want, right-click, and choose **\[Move]** to relocate it.

{% stepper %}
{% step %}
Select the file or folder you want to move in the **Project Sidebar**.
{% endstep %}

{% step %}
Right-click and select **\[Move]** from the menu.
{% endstep %}

{% step %}
In the newly opened **Move file popup**, select the desired location in the file tree and click the **\[OK]** button.
{% endstep %}

{% step %}
The file or folder will be moved to the specified location.
{% endstep %}
{% endstepper %}

Alternatively, you can drag and drop the file or folder within the Project Sidebar. Simply click and hold the item, drag it to the desired folder, and release to move it.

{% hint style="danger" %}
Please be careful. If there is a file or folder with the same name in the destination, it will be overwritten.
{% endhint %}

## Rename File

The Rename feature allows you to change the name of files or folders in the **Project Sidebar**.

To rename an item, right-click the file or folder and select **\[Rename]**. An input field will appear in place of the existing name. Enter the new name and press Enter to confirm.

Alternatively, you can select the file or folder and press <kbd>**F2**</kbd>. This will immediately activate the Rename input field, allowing you to type a new name.

{% hint style="info" %}
If the new name already exists, the input field turns red and the change is blocked. The same applies if you use characters other than English letters and approved special characters.
{% endhint %}

### Rename Container

You can also rename the container **by renaming the main project**.

To rename the container, open the **More Actions**(<img src="../../../.gitbook/assets/스크린샷 2025-10-27 오후 4.39.30.png" alt="" data-size="line">) menu in the **Project header** and select the **\[Rename Container]**.\
Alternatively, you can rename the container by selecting the main project and pressing <kbd>**F2**</kbd> (the same method used for renaming files).

Renaming the container updates the container name in both the **Project Sidebar** and the **Dashboard page**, ensuring the new name is applied across the Workspace and visible to collaborators.

{% hint style="warning" %}
* Only the container **owner** can rename the container.
* Containers can be renamed while running, but the editor will refresh right after, which may clear unsaved edits.
{% endhint %}

## Delete File

The Delete feature allows you to remove files or folders from the **Project Sidebar**.

To delete an item, right-click the file or folder and select **\[Delete]**. A confirmation popup will appear, asking if you really want to delete the item. Click the **\[Delete File]** button in the popup to confirm and remove the file.

Alternatively, you can select the file or folder and press **`Ctrl` + `⌫`** Backspace (macOS `⌘` + **`⌫`**). This will also open the deletion confirmation popup.

{% hint style="danger" %}
* You can recover the deletion by pressing <kbd>**Ctrl**</kbd>**&#x20;+&#x20;**<kbd>**z**</kbd>, only when you delete the files or folders by using the **\[Delete]** button or <kbd>**Ctrl**</kbd>**&#x20;+&#x20;**<kbd>**⌫**</kbd> Backspace key.
* Please note that once the file or folder is deleted by command or is larger than 10 MB, it cannot be restored.
{% endhint %}
