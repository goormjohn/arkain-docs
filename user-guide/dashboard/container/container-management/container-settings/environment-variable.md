---
icon: square-check
---

# Environment Variable

Sensitive data like passwords and API keys can be stored in Environment Variables for use in running Commands. Environment variables are divided into global environment variables and local environment variables.

* **Global Environment Variables**\
  Global environment variables can be used in all terminals and Commands. You can set global environment variables on the Container setting page. You can view the list of `Key-Value` pairs in the table of environment variables on the Container setting page.
* **Local Environment Variables**\
  Local environment variables can be used only in specific commands. You can set local environment variables on the Command settings tab within the Workspace. You can view the list of `Key-Value` pairs in the table of environment variables on the Command settings tab.

### Using Environment Variables <a href="#using-environment-variables" id="using-environment-variables"></a>

* **In the Container Settings page**

<figure><img src="../../../../../.gitbook/assets/Environment variable.png" alt=""><figcaption></figcaption></figure>

* **In the Workspace**\
  You can use environment variables in terminals with the following command:

<pre class="language-sh"><code class="lang-sh"><strong>$ export ${key}=${value}
</strong></code></pre>

### Command Variables <a href="#command-variables" id="command-variables"></a>

Command variables are default environment variables provided by Arkain, consisting of values that might be challenging for users to manage easily. You can check the list of command variables on the command settings tab. The usage of command variables is the same as using environment variables.
