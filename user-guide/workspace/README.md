---
icon: square-check
---

# Workspace

Arkain's **Workspace** is an IDE environment designed to help you efficiently develop software. It provides features such as editing, building, testing, and deploying software. The key area terms of the Workspace are as follows.

<figure><img src="../../.gitbook/assets/Workspace_01 (2).png" alt=""><figcaption><p>Studio layout</p></figcaption></figure>

***

## 1. Menu bar <a href="#menu-bar" id="menu-bar"></a>

<figure><img src="../../.gitbook/assets/Workspace_02 (1).png" alt=""><figcaption><p>Menu bar</p></figcaption></figure>

The Menu bar is where you perform general operations on your Arkain Workspace. It includes, from left to right

* The **\[Menu]** button(<img src="../../.gitbook/assets/[core] Button.png" alt="" data-size="line">) of the menu bar allowing users to Process list, SSH Configuration, Manage SBOM, and project properties, New Terminal Window.

<figure><img src="../../.gitbook/assets/Workspace_03 (2).png" alt=""><figcaption></figcaption></figure>

* The **\[Save]** button(<img src="../../.gitbook/assets/save (1).png" alt="" data-size="line">) allows you to save the open file, save as a new name, or save all files.
* The **\[Preview]** button(![](../../.gitbook/assets/preview.png)) allows users to preview their project within the workspace or in a new tab or workspace. It also provides options for configuring the execution URL and port settings.

<div align="center"><figure><img src="../../.gitbook/assets/Workspace_04 (1) (1).png" alt=""><figcaption></figcaption></figure></div>

* The **\[Run]** button (<img src="../../.gitbook/assets/run.png" alt="" data-size="line">) allows users to manage and execute custom run commands they have written.

<figure><img src="../../.gitbook/assets/Workspace_05 (2).png" alt=""><figcaption></figcaption></figure>

* The **\[Publish]** (<img src="../../.gitbook/assets/publish.png" alt="" data-size="line">) button deploys the currently active container as a template. Deployed templates are made public on the [Templates page](https://arkain.io/template).
* Clicking the **\[Exit Container]** button (<img src="../../.gitbook/assets/exit.png" alt="" data-size="line">) will exit the workspace. The container execution will stop upon exit.

{% hint style="warning" %}
**Warnning**\
Even if you close the web browser, the container will remain running. **While the container is running, credits will be consumed.** It is recommended to click the **\[EXIT]** button to exit Arkain.
{% endhint %}

***

## 2. Activity bar <a href="#sidebar" id="sidebar"></a>

The sidebar is an area that helps you easily access key features needed for development. You can open a different Sidebar by clicking on the icons in the Activity bar.

#### &#x20;![](../../.gitbook/assets/aichat.png) [\[Side Chat\]](../arkain-ai/)

Clicking on **\[Side Chat]** will open a Side Chat on the left side of the workspace, where you can converse with the **AI code assistant**.

<figure><img src="../../.gitbook/assets/Workspace_06 (2).png" alt=""><figcaption></figcaption></figure>

{% content-ref url="../arkain-ai/how-to-use-side-chat.md" %}
[how-to-use-side-chat.md](../arkain-ai/how-to-use-side-chat.md)
{% endcontent-ref %}

#### <img src="../../.gitbook/assets/ActivityBar-item-2.png" alt="" data-size="line"> [Project](./#project-sidebar) Sidebar

The **\[Project button]** is opens the Project Sidebar area. The project sidebar is a type of file explorer that allows you to create, edit, and delete project files and folders.

You can click to open documents like the Readme, which contains project descriptions, or source code.

<figure><img src="../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

#### ➕ **Create Files & Folders**

Click the \[**+] button** to create new **files, folders** and sub projects within your project.

#### **Folder Management**

* Use the ![](<../../.gitbook/assets/스크린샷 2025-02-25 오후 8.16.35.png>) **icon** to collapse or expand all folders.
* Click the ![](<../../.gitbook/assets/스크린샷 2025-02-25 오후 8.17.40.png>) **refresh button** to update the file tree and keep it in sync.



:mouse: **Right-Click for File Actions**

Right-click on a file to access all available file-related features, including renaming, deleting, moving, and more!&#x20;

<div><figure><img src="../../.gitbook/assets/스크린샷 2025-02-25 오후 8.18.52.png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/스크린샷 2025-02-25 오후 8.19.08.png" alt=""><figcaption></figcaption></figure></div>



#### <img src="../../.gitbook/assets/ActivityBar-item.png" alt="" data-size="line"> [\[Git\]](source-code-management-git/git.md) Sidebar

It opens Git, a distributed version control system, in the sidebar to track and synchronize changes to files. **Arkain** provides most of the Git commands.

<figure><img src="../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

{% content-ref url="source-code-management-git/git.md" %}
[git.md](source-code-management-git/git.md)
{% endcontent-ref %}

<img src="../../.gitbook/assets/ActivityBar-item-3.png" alt="" data-size="line"> [\[Source Code\]](./#source-code-sidebar) Sidebar

It opens a sidebar where you can view the source code's hierarchy, bookmarks, and change history.

<figure><img src="../../.gitbook/assets/2025-02-012.48.21-ezgif.com-video-to-gif-converter.gif" alt=""><figcaption></figcaption></figure>

* **Automatic Save History** \
  Your work sessions are stored as a list, allowing you to restore previous versions easily.
* **Quick Navigation with Bookmarks** \
  Set bookmarks to jump directly to specific points in your code.
* **Replay Your Code Changes**\
  Watch your code edits play back in chronological order, making it easy to review your progress and understand changes over time.

Effortlessly track, revert, and replay your coding journey!&#x20;

#### <img src="../../.gitbook/assets/ActivityBar-item-4.png" alt="" data-size="line"> [\[Share This Container\]](./#share-this-container-sidebar)

You can share your container with others to collaborate or showcase your projects. Even if someone doesn't have a Arkain account, they can still access the shared container.

<figure><img src="../../.gitbook/assets/2025-02-012.55.22-ezgif.com-video-to-gif-converter.gif" alt=""><figcaption></figcaption></figure>

{% content-ref url="collaboration/contaienr-sharing.md" %}
[contaienr-sharing.md](collaboration/contaienr-sharing.md)
{% endcontent-ref %}



#### <img src="../../.gitbook/assets/ActivityBar-item-5.png" alt="" data-size="line"> \[Help]

Here, you can find Arkain's features, view [shortcuts](keyboard-shortcut.md), and access help.

<div align="center"><figure><img src="../../.gitbook/assets/Workspace_07 (1).png" alt=""><figcaption></figcaption></figure></div>

#### ![](../../.gitbook/assets/arkain_activitybar_icon_preference.png) \[Preference]&#x20;

You can open the project settings modal. You can change the editor, terminal, and theme styles, as well as configure key Arkain features such as AI auto-completion.

<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

#### ![](../../.gitbook/assets/credit.png) [\[Credit\]](../../credit-and-membership/credit.md)

You can check the available credits along with Container usage time, Estimated uptime, and Used credit.

#### ![](../../.gitbook/assets/arkain_activitybar_icon_profile.png) \[Account]

You can navigate to the page where you can manage your member profile and container information.

<div align="center"><figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt="" width="269"><figcaption></figcaption></figure></div>

* **Profile** : You can navigate to the Profile Settings page to edit your profile information.
* **Container Info** : You can navigate to the Container Settings page to configure detailed container settings.
* **Go to Release Notes** : You can check the version-specific changes, added features, improved functionalities, and bugs of the Arkain service in the release notes.
* **Edit Preference File** : You can configure the IDE settings based on files.
* **Go to Dashboard :** You exit the workspace and move to the dashboard.
* **Sign out** : You can log out.

***



## 3. Editor <a href="#editor" id="editor"></a>

The Editor section of the Workspace displays the content of the currently selected file. You can perform several actions in the Editor's top-right side such as format code with [Prettier](https://prettier.io/) or manage the file tabs if you have several open.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

***

## 4. Toggle Panel <a href="#terminal" id="terminal"></a>

In Arkain's toggle panel, you can use features such as the terminal, search, and resource monitor.

### Terminal Panel

**Arkain** provides a built-in terminal, so developers who are comfortable with commands can use it to perform advanced tasks.

By default, the terminal is available as the Terminal tab in the toggle Panel of the Arkain interface. To open it in a new terminal window, go to **\[Menu]**(<img src="https://docs.arkain.io/~gitbook/image?url=https%3A%2F%2F2536619093-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fvv0eKmOn3DY36Ox1EqCE%252Fuploads%252Fum5iOjy95Gfbbha1uOG8%252F%255Bcore%255D%2520Button.png%3Falt%3Dmedia%26token%3Db2c7c88e-3bdc-411e-bf19-d19c064e8c55&#x26;width=102&#x26;dpr=4&#x26;quality=100&#x26;sign=df8f1d77&#x26;sv=2" alt="" data-size="line">) → **\[New Terminal Window]** or press the default shortcut <kbd>Alt</kbd> + <kbd>Shift</kbd> + `T` (macOS <kbd>⌥</kbd> <kbd>⇧</kbd> <kbd>T</kbd>).&#x20;

You can open the Terminal in a new window by right-clicking on a folder or file in the Project Sidebar and clicking the **\[Open Terminal with this location]** menu, which will automatically take you to the folder.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-legacy-files%2Fo%2Fassets%252F-Lq-Q9LciN1X9EABxGkt%252F-LvyeWwXWpV1I5yFc4yF%252F-Lvykpz-psuBQia28h8J%252Fimage.png%3Falt%3Dmedia%26token%3Dbbc1e7b2-3716-40ea-b67b-4f4296bf3b13&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=739a5583&#x26;sv=2" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
As a docker container-based service, Arkain does not support system privileges for containers due to security policy. Therefore, commands that access system resources such as `ufw`, `systemctl`, `docker`(docker in docker) cannot be used.
{% endhint %}



### Search Panel

The Search Panel displays search results for all documents within the project. When you change the search scope to 'Search All' in search or replace, the Search Panel will show keyword search results for each file.

<figure><img src="../../.gitbook/assets/스크린샷 2025-02-26 오전 11.25.03.png" alt=""><figcaption></figcaption></figure>

### Resource monitor Panel

The resource monitor panel displays the usage of container resources such as CPU, memory, disk, and network in a graphical format.

<figure><img src="../../.gitbook/assets/스크린샷 2025-02-26 오후 12.50.20.png" alt=""><figcaption></figcaption></figure>



***

## 5. Bottom bar <a href="#terminal" id="terminal"></a>

The bottom bar is an area that provides various tools and information to enhance convenience when using Arkain. It includes the editor's code Lint and Editor information, along with the Toggle Panel, Auto-completion, and Auto-off toggle buttons.

#### Status Area

The Status Area displays linting check results and editor line information. Linting is a tool that identifies and notifies errors related to syntax and code style in the source code.&#x20;

The **Status Area** shows, from left to right, the **lint errors**, **lint warnings**, and the total number of lines in the editor along with the current cursor position in the format of 'number:number'.

<figure><img src="../../.gitbook/assets/스크린샷 2025-02-26 오후 1.30.34.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
The lint information is only available in the Python container.
{% endhint %}



#### **Toggle Button**

* **Toggle Panel**: You can open and close the Toggle Panel. Closing the Toggle Panel allows you to focus more on your code.
* **Auto-Completion**: Get smart coding suggestions in real-time.
* **Auto-off**: You can toggle the feature to automatically stop container usage when the browser is closed.
* **1:1 Support Chat** – Click to open a chat window for direct support.

<figure><img src="../../.gitbook/assets/2025-02-013.07.18-ezgif.com-video-to-gif-converter.gif" alt=""><figcaption></figcaption></figure>
