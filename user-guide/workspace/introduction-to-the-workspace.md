---
icon: square-check
---

# Introduction to the Workspace

This page provides an overview of the terms we use to describe each of the pieces of the user interface (UI) available to you in Arkain projects.

<figure><img src="../../.gitbook/assets/Group 46 (1).png" alt=""><figcaption><p>Arkain Workspace User Interface</p></figcaption></figure>

***

## Menubar <a href="#menu-bar" id="menu-bar"></a>

<figure><img src="../../.gitbook/assets/image (18).png" alt=""><figcaption><p>Arkain Workspace Menu Bar</p></figcaption></figure>

The Menu Bar is where you perform general operations on your Arkain Workspace. It includes, from left to right

* The function buttons on the left side of the menu bar are dedicated to file-related operations. They allow users to create, copy, delete, rename, and save files, providing a streamlined file management experience.

<figure><img src="../../.gitbook/assets/image (19).png" alt="" width="260"><figcaption></figcaption></figure>

If you'd like to explore additional file-related features, please check the link below:

{% content-ref url="file-management/" %}
[file-management](file-management/)
{% endcontent-ref %}

* The central section of the menu bar handles URL and port management, allowing users to manage running URLs, ports, SSH settings, SBOM management, and project configurations.

<figure><img src="../../.gitbook/assets/image (20).png" alt="" width="375"><figcaption></figcaption></figure>

* The **Preview** tab allows users to preview their project within the workspace or in a new tab. It also provides options for configuring the execution URL and port settings.

<div align="center"><figure><img src="../../.gitbook/assets/image (21).png" alt="" width="283"><figcaption></figcaption></figure></div>

* The **Run** menu allows users to manage and execute custom run commands they have written.

<figure><img src="../../.gitbook/assets/image (22).png" alt="" width="262"><figcaption></figcaption></figure>

* It also includes a **file-saving** feature and an **"Exit Container"** button, which allows users to switch from the workspace to the console.

***

## Activitybar <a href="#sidebar" id="sidebar"></a>

The Activity Bar allows you to select a view to display in the sidebar from the available:

#### ➡️ Side Chat : opens Side Chat

We’re thrilled to unveil **AI Code Assistant : Arkain**, an intelligent feature in our webIDE that lets you interact with your code like never before!&#x20;

{% content-ref url="../ai-code-assistant-arkain/side-chat.md" %}
[side-chat.md](../ai-code-assistant-arkain/side-chat.md)
{% endcontent-ref %}

#### ➡️ [Project : opens the Project sidebar](introduction-to-the-workspace.md#project-sidebar)

#### ➡️ [Command : opens the Command sidebar](introduction-to-the-workspace.md#command-sidebar)

#### ➡️ [Git : opens the Git sidebar](introduction-to-the-workspace.md#git-opens-the-git-sidebar)

#### ➡️ [Debug : opens the Debug sidebar](introduction-to-the-workspace.md#debug-sidebar)

#### ➡️[ Source Code : opens the Source Code sidebar](introduction-to-the-workspace.md#source-code-opens-the-source-code-sidebar)

#### ➡️ [Share This Container : opens the Share This Container sidebar](introduction-to-the-workspace.md#share-this-container-opens-the-share-this-container-sidebar)

#### ➡️ Help&#x20;

#### You can access various **help documents** for assistance.

<div align="center"><figure><img src="../../.gitbook/assets/image (1) (1) (1).png" alt="" width="310"><figcaption></figcaption></figure></div>

* Find Menu : You can invoke the **Quick Execute** feature.

<figure><img src="../../.gitbook/assets/image (24).png" alt="" width="375"><figcaption></figcaption></figure>

* &#x20;**Arkain service center** : You can open the messenger for contacting **Customer Support**.
* **View All Shortcut** : You can view the **shortcut keys for the entire IDE**.

{% content-ref url="keyboard-shortcut.md" %}
[keyboard-shortcut.md](keyboard-shortcut.md)
{% endcontent-ref %}

* Language documentation : You can navigate to the official online documentation for the created **container stack**.

#### ➡️ Preference

You can open the **project settings modal**.

<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

#### ➡️ Profile and Container Info

You can navigate to the page where you can manage your **member profile** and **container information**.

<div align="center"><figure><img src="../../.gitbook/assets/image (1) (1) (1) (1).png" alt="" width="269"><figcaption></figcaption></figure></div>

* **Profile** : You can navigate to the **Profile Settings** page to edit your profile information.
* **Container Info** : You can navigate to the **Container Settings** page to configure detailed container settings.
* **Go to Release Notes**
* **Edit Preference File** : You can configure the **IDE settings** based on files.
* Go to Container Dashboard
* **Sign out** : You can **log out** and return to the **main page**.

***

## Sidebar <a href="#sidebar" id="sidebar"></a>

When you open a Arkain project, the Sidebar defaults to the _Project_ icon's expanded view. You can open a different view by clicking on the icons in the Activity Bar.

#### ➡️ Project Sidebar

The **Project Sidebar View** includes the project description (if provided by the author) and allows you to **browse project files**.

You can also **create, edit, and delete files** related to the project directly from the sidebar. 🚀

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

#### ➕ **Create Files & Folders**

#### Click the **“+” button** to create new **files and folders** within your project.

#### 📂 **Folder Management**

* Use the **“-” icon** to collapse or expand all folders.
* Click the **refresh button** to update the file tree and keep it in sync.

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

#### 🖱 **Right-Click for File Actions**

Right-click on a file to access all available **file-related features**, including **renaming, deleting, moving, and more**! 🚀

### ➡️ Command Sidebar

### ➡️ Git Sidebar

### ➡️ Debug Sidebar

### ➡️ Source Code Sidebar

### ➡️ Share This Container Sidebar

***

## Editor <a href="#editor" id="editor"></a>

The Editor section of the IDE displays the content of the currently selected file. You can perform several actions in the Editor's top-right side such as format code with [Prettier](https://prettier.io/) or manage the file tabs if you have several open.

<figure><img src="../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

***

## Terminal <a href="#terminal" id="terminal"></a>

**Arkain** provides a built-in terminal, so developers who are comfortable with commands can use it to perform advanced tasks.

By default, the terminal is available as the Terminal tab in the bottom layout of the goormIDE interface. To open it in a new window, go to **\[Window] > \[New Terminal Window]** or press the default shortcut **`Alt + Shift + T (Mac: ⌥⇧T)`**.

A new terminal window will appear in your workspace. The terminal window does not persist when you refresh goormIDE.

You can open the Terminal in a new window by right-clicking on a folder in the Project Explorer and clicking the **\[Open Terminal with this location]** menu, which will automatically take you to the folder.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-legacy-files%2Fo%2Fassets%252F-Lq-Q9LciN1X9EABxGkt%252F-LvyeWwXWpV1I5yFc4yF%252F-Lvykpz-psuBQia28h8J%252Fimage.png%3Falt%3Dmedia%26token%3Dbbc1e7b2-3716-40ea-b67b-4f4296bf3b13&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=739a5583&#x26;sv=2" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
As a docker container-based service, goormIDE does not support system privileges for containers due to security policy. Therefore, commands that access system resources such as **`ufw, systemctl, docker`**(docker in docker) cannot be used.
{% endhint %}

***

## Bottombar <a href="#terminal" id="terminal"></a>

*

***

## Side Chat <a href="#terminal" id="terminal"></a>

*
