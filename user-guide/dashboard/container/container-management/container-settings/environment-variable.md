---
icon: square-check
---

# Environment Variable

Sensitive data like passwords and API keys can be stored in Environment Variables for use in running Commands.

* Environment variables are applied globally within the container and can be used across terminals and commands, while their values are only accessible to users with root privileges.
* You can configure environment variables from the Container Settings page or the Workspace, and view the list of configured `Key-Value` pairs in the Environment Variables table.

### Using Environment Variables <a href="#using-environment-variables" id="using-environment-variables"></a>

* **In the Container Settings page**

<figure><img src="../../../../../.gitbook/assets/Environment variable (1).png" alt=""><figcaption></figcaption></figure>

* **In the Workspace**\
  You can configure environment variables from the Command Settings tab, and they will be applied when running commands in the Workspace.

After modifying environment variables, refresh the terminal to apply the changes.

### Command Variables <a href="#command-variables" id="command-variables"></a>

Command variables are default environment variables provided by Arkain, consisting of values that might be challenging for users to manage easily. You can check the list of command variables on the command settings tab. The usage of command variables is the same as using environment variables.
