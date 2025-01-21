---
icon: circle-2
---

# How to run as background process

Exiting the workspace does not terminate the container, but it does terminate the process running in the terminal. To avoid this, you should run it as a **background process**.

There are 2 options to set-up;

1. Run in the background setting (recommended!)
2. Use `nohup` command

## **1. Run in the background setting** <a href="#id-1-run-in-the-background-setting" id="id-1-run-in-the-background-setting"></a>

Enter the execution command in the script, then tap the **Run in the background** checkbox to run the command.

command tap > Run > click right on wanted run command > setting > **check Run in the background** > Save and run

![image alt text](https://mkdocs-mxedr.run.goorm.site/assets/images/How-to-run-as-background-process.en_62.png)

## **2. Use nohup** command <a href="#id-2-use-nohup-command" id="id-2-use-nohup-command"></a>

### **1. How to run**[**¶**](https://mkdocs-mxedr.run.goorm.site/06.-FAQ/How-to-run-as-background-process/#1-how-to-run)

* Prepare a file(ex. a.out) that you want to run in a background process.
* Type the command

```bash
# nohup <absolute path>/a.out &
```

* You can check for execution with the command below.

```bash
 # ps -aux | grep a.out
```

### **2. How to end**[**¶**](https://mkdocs-mxedr.run.goorm.site/06.-FAQ/How-to-run-as-background-process/#2-how-to-end)

* After finding the PID value with the ps command, end the process with the kill command.

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

## **If you are using node app**[¶](https://mkdocs-mxedr.run.goorm.site/06.-FAQ/How-to-run-as-background-process/#if-you-are-using-node-app) <a href="#if-you-are-using-node-app" id="if-you-are-using-node-app"></a>

You can simply run it as a background process using the _**forever**_ command in the npm package.

#### **1. How to run**[**¶**](https://mkdocs-mxedr.run.goorm.site/06.-FAQ/How-to-run-as-background-process/#1-how-to-run_1)

* Install `forever`

```bash
$ npm install -g forever
```

* Run the app with the command below

```bash
$ forever start app.js
```

* You can verify whether it's running or not with the command below.

```bash
$ forever list
```

{% hint style="info" %}
For detailed usage, please refer to **forever usage**.
{% endhint %}
