---
icon: scroll
---

# Init Script

If you have a script that needs to be executed repeatedly when running a container, you can use the Init script. The **Init script** runs from the root directory `(/)` of the container and is executed when the container starts.

It is commonly used to write scripts that execute your application.

<figure><img src="../../../../../.gitbook/assets/Init Script.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
#### Shell environment limitations

The **Init Script** is executed using **`/bin/sh`**, which has the following limitations:

* Only POSIX-compliant `sh` commands are supported.
* Bash-specific syntax (e.g., `[[ ]]`, `source`, arrays, or `bash` shebangs) cannot be used.
* Existing scripts written for `bash` must be adapted to be compatible with `/bin/sh`.

**Useful Resources:**

* [POSIX Shell Standard](https://www.google.com/search?q=%5Bhttps://pubs.opengroup.org/onlinepubs/9699919799.2018edition/utilities/V3_chap02.html%5D\(https://pubs.opengroup.org/onlinepubs/9699919799.2018edition/utilities/V3_chap02.html\)): Official documentation for the standard `/bin/sh` command language.
{% endhint %}

### How to use the Init Script?

{% stepper %}
{% step %}
You can navigate to the **Dashboard** page and enter the **Container Settings** page.
{% endstep %}

{% step %}
In the **Container Settings** page, under the **Init Script** section, you can write the execution commands. Once you're done writing, it will be saved automatically, and these commands will automatically run when the container starts.&#x20;
{% endstep %}
{% endstepper %}
