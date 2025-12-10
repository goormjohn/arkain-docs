---
icon: comment-question
---

# How to run as background process

If you turn off the **Auto-stop** feature, the container will remain running even if you close the Workspace, but processes running in the terminal will be terminated. To prevent this, you need to run the process as a **background process** using the `nohup` command.

## **Use nohup** command <a href="#id-2-use-nohup-command" id="id-2-use-nohup-command"></a>

### **How to run**

{% stepper %}
{% step %}
For example, to run `npm run start` command in the background, you can use the `setsid nohup` command together as shown below.

```bash
$ setsid nohup npm run start > app.log 2>&1 &
```
{% endstep %}

{% step %}
You can check for execution with the command below.

```bash
 $ ps -aux | grep "npm run start"
```
{% endstep %}

{% step %}
The output and error logs will be saved to `app.log`. You can check the log with the command below.

```bash
$ cat app.log
```
{% endstep %}
{% endstepper %}

### **How to end**

After finding the PID value with the `ps` command, end the process with the `kill` command.

```bash
$ ps -ef | grep "npm run start"
[1] [Your PID]
$ kill -TERM [Your PID]
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



## An app that uses npm start <a href="#if-you-are-using-node-app" id="if-you-are-using-node-app"></a>

You can run the command set in `scripts.start` of `package.json` using `npm start`, but with PM2, you can run it more easily as a background application.

{% stepper %}
{% step %}
Install `pm2`

```bash
$ npm install -g pm2
```
{% endstep %}

{% step %}
Run the app with the command below

```bash
$ pm2 start npm -- start
```
{% endstep %}

{% step %}
You can verify whether it's running or not with the command below.

```bash
$ pm2 status
```
{% endstep %}
{% endstepper %}

