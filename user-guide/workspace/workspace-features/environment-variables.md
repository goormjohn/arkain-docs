# Environment Variables

Sensitive data like passwords and API keys can be stored in Environment Variables to be used when running Commands. Environment variables are divided into global environment variables and local environment variables.

### Global Environment Variables <a href="#global-environment-variables" id="global-environment-variables"></a>

Global environment variables are variables that can be used in all terminals and Commands. You can set global environment variables on the Container setting page. You can view the list of `Key-Value` pairs in the table of environment variables on the Container setting page.

### Local Environment Variables <a href="#local-environment-variables" id="local-environment-variables"></a>

Local environment variables are variables that can be used only in specific commands. You can set local environment variables on the Command settings tab within the workspace. You can view the list of `Key-Value` pairs in the table of environment variables on the Command settings tab.

### Using Environment Variables <a href="#using-environment-variables" id="using-environment-variables"></a>

#### ➡️ in Container Configuration

<figure><img src="../../../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

#### ➡️ in Workspace

You can use environment variables in terminals and Commands using the following format: `${Key_Of_The_Environment_Variable}`

### Command Variables <a href="#command-variables" id="command-variables"></a>

Command variables are default environment variables provided by the Arkain, consisting of values that might be challenging for users to manage easily. You can check the list of command variables on the command settings tab. The usage of command variables is the same as using environment variables.
