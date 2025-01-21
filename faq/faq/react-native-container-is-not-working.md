---
icon: comment-question
---

# React native container is not working

Enter the following into your terminal in the order below

### Node version up <a href="#node-version-up" id="node-version-up"></a>

```bash
rm -rf /usr/lib/node_modules
rm -rf /usr/bin/node
rm -rf /usr/include/node
rm -rf /usr/local/bin/node
rm -rf /usr/local/include/node
rm -rf /usr/share/man/man1/node*
rm -rf /usr/local/lib/node_modules/
rm -rf /usr/local/bin/npm
rm -rf ~/.npm
rm -rf ~/.node-gyp
apt remove nodejs -y

curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs
```

### **Refresh Terminal** <a href="#refresh-terminal" id="refresh-terminal"></a>

<figure><img src="https://mkdocs-mxedr.run.goorm.site/assets/images/React-native-container-is-not-working.en_60.png" alt=""><figcaption></figcaption></figure>

Refresh the terminal by pressing the `Refresh` button next to the terminal.

### **Edit package.json file** <a href="#edit-packagejson-file" id="edit-packagejson-file"></a>

**\{{insert PORT number here\}}** with **the value of the external port corresponding to the internal port 19000** in the top menu **\[Container] > \[Port Forwarding Configuration]**.

```json
{
  "main": "node_modules/expo/AppEntry.js",
  "scripts": {
    "start": "expo start --port {{Insert PORT number here}}",
    "android": "expo start --android",
    "ios": "expo start --ios",
    "web": "expo start --web"
  },
  "dependencies": {
    "expo": "~48.0.10",
    "expo-status-bar": "~1.4.4",
    "react": "18.2.0",
    "react-native": "0.71.6",
    "react-native-web": "~0.18.10",
    "react-dom": "18.2.0",
    "@expo/webpack-config": "^18.0.1"
  },
  "devDependencies": {
    "@babel/core": "^7.20.0"
  },
  "private": true
}

```

### Install node\_modules <a href="#install-node_modules" id="install-node_modules"></a>

{% code overflow="wrap" %}
```bash
npm i

npx expo install react-native-web@~0.18.10 react-dom@18.2.0 @expo/webpack-config@^18.0.1
```
{% endcode %}

### **Run with React Native command** <a href="#run-with-react-native-command" id="run-with-react-native-command"></a>

<figure><img src="https://mkdocs-mxedr.run.goorm.site/assets/images/React-native-container-is-not-working.en_61.png" alt=""><figcaption></figcaption></figure>

Press the `Run(project)` button in the top right corner.
