---
icon: brackets-curly
---

# URL / Port

### Domain <a href="#domain" id="domain"></a>

Arkain provides a default subdomain (e.g., `https://mydomain.arkain.site`) for every container. This means you don't need to purchase your own domain to get started.

### Running your application <a href="#running-your-application" id="running-your-application"></a>

Run your application by clicking the **\[Run]** button or through the terminal. Verify if the application is running successfully through the terminal panel, and note the port number where the application is running.

The application's port number is necessary for registering a domain.

### Registering a subdomain <a href="#registering-a-domain" id="registering-a-domain"></a>

Click on the **\[Preview]** → **\[Running URL and Port]** button in the menu bar of the Workspace to open the sub domain settings popup. Here, you can register a new subdomain and view the list of registered sub domains.

To register a new subdomain, enter the URL and port number you want in the input field, and click the **\[Register]** button. Note that for some base templates, subdomains for default ports may already be registered.

You cannot register multiple domains with the same port number.

### Registering a Custom domain <a href="#registering-a-custom-domain" id="registering-a-custom-domain"></a>

You can register your own domain instead of the subdomains provided by Arkain such as `mydomain.run.arkain.site`. You can configure a custom domain from the Arkain Dashboard page. Go to **\[Container Settings]]\(**<img src="../../.gitbook/assets/setting.png" alt="" data-size="line">**)**  → **URL/Port section**, click the **\[+ Add]** button, and select **\[Custom Domain].**

And enter the domain to register starting from `www`, and upload the `crt` and `key` files. If the certificate has a password, include the password in a file and upload it.

### **Setting up DNS Domain**

On your domain registrar's website, you must create a CNAME record that points to the Arkain server for your container's region.

* **Seoul**: `${your_domain}.ap-northeast-2.arkain.site`
* **Oregon**: `${your_domain}.us-west-2.arkain.site`
* **Frankfurt**: `${your_domain}.eu-central-1.arkain.site`
* **Mumbai**: `${your_domain}.ap-south-1.arkain.site`

### Accessing the Domain through browser <a href="#accessing-the-domain-through-browser" id="accessing-the-domain-through-browser"></a>

Open your web browser and enter the registered domain to access it. You should see your application displayed. If **Hot Module Replacement** (HMR) is applied in your code, your code changes will be reflected in the browser in real-time without browser refresh.

* If you encounter a **404 error** page, double-check that you entered the domain correctly in the browser.
* If you encounter a **Connection Refused** page, check that the application is running correctly and ensure that the port number you entered during domain registration is correct.

{% hint style="info" %}
If your server's hosting setting is localhost or 127.0.0.1, try changing it to **0.0.0.0 .**

It allows external access.
{% endhint %}
