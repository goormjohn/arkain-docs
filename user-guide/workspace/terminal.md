---
icon: square-terminal
---

# Terminal

**Arkain** provides a built-in terminal, so developers who are comfortable with commands can use it to perform advanced tasks.

By default, the terminal is available as the Terminal tab in the bottom layout of the goormIDE interface. To open it in a new window, go to **\[Window] > \[New Terminal Window]** or press the default shortcut **`Alt + Shift + T (Mac: ⌥⇧T)`**.

A new terminal window will appear in your workspace. The terminal window does not persist when you refresh goormIDE.

You can open the Terminal in a new window by right-clicking on a folder in the Project Explorer and clicking the **\[Open Terminal with this location]** menu, which will automatically take you to the folder.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-legacy-files%2Fo%2Fassets%252F-Lq-Q9LciN1X9EABxGkt%252F-LvyeWwXWpV1I5yFc4yF%252F-Lvykpz-psuBQia28h8J%252Fimage.png%3Falt%3Dmedia%26token%3Dbbc1e7b2-3716-40ea-b67b-4f4296bf3b13&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=739a5583&#x26;sv=2" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
As a docker container-based service, goormIDE does not support system privileges for containers due to security policy. Therefore, commands that access system resources such as **`ufw, systemctl, docker`**(docker in docker) cannot be used.
{% endhint %}

