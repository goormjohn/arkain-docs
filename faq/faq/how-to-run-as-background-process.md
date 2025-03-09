---
icon: comment-question
---

# How to run as background process

If you turn off the **Auto-off** feature, the container will remain running even if you close the workspace, but processes running in the terminal will be terminated. To prevent this, you need to run the process as a **background process**.

There are 2 options to set-up;

* Run in the background setting (recommended!)
* Use `nohup` command

## **Run in the background setting** <a href="#id-1-run-in-the-background-setting" id="id-1-run-in-the-background-setting"></a>

Enter the execution command in the script, then tap the **Run in the background** checkbox to run the command.

command tap → Run → click right on wanted run command → setting → **check Run in the background** → Save and run.

## **Use nohup** command <a href="#id-2-use-nohup-command" id="id-2-use-nohup-command"></a>

### **How to run**

{% stepper %}
{% step %}
If the file to be run in the background process is `a.out`, you can run it as a background process by entering the following command in the terminal.

```bash
# nohup <absolute path>/ filename &
```
{% endstep %}

{% step %}
You can check for execution with the command below.

```bash
 # ps -aux | grep a.out
```
{% endstep %}
{% endstepper %}

### **How to end**

After finding the PID value with the ps command, end the process with the kill command.

```bash
# ps -ef | grep a.out
# kill -TERM PID number
```

{% hint style="info" %}
**Note**\
nohup command automatically creates a file called nohup.out.
{% endhint %}

This file records the output of the commands you run with `nohup`.

If you don't want to create this file, you can have it output to /dev/null.

```bash
# nohup echo hello > /dev/null
```

## **If you are using node app** <a href="#if-you-are-using-node-app" id="if-you-are-using-node-app"></a>

You can simply run it as a background process using the _**forever**_ command in the npm package.

{% stepper %}
{% step %}
Install `forever`

```bash
$ npm install -g forever
```
{% endstep %}

{% step %}
Run the app with the command below

```bash
$ forever start app.js
```
{% endstep %}

{% step %}
You can verify whether it's running or not with the command below.

```bash
$ forever list
```
{% endstep %}
{% endstepper %}

{% hint style="info" %}
For detailed usage, please refer to **forever usage**.
{% endhint %}
