---
icon: brackets-curly
---

# URL/Port

### Domain <a href="#domain" id="domain"></a>

A domain is an address that identifies a website or application on the internet, and Arkain provides default sub domains like `https://mydomain.arkain.io/` for each container.

Therefore, there is no need to purchase a domain.

### Running your application <a href="#running-your-application" id="running-your-application"></a>

Run your application by the **\[Run]** button or thorugh the terminal. Verify if the application is running successfully through the terminal panel, and note the port number where the application is running.

The application's port number is necessary for registering a domain.

### Registering a sub domain <a href="#registering-a-domain" id="registering-a-domain"></a>

Click on the **\[Preview]** → **\[Running URL and Port]** button in the menu bar of the workspace to open the sub domain settings modal. Here, you can register a new sub domain and view the list of registered sub domains.

To register a new sub domain, enter the URL and port number you want in the input field, and click the **\[Register]** button. Note that for some software stacks, sub domains for default ports may already be registered.

You cannot register multiple domains with the same port number.

### Registering a Custom domain <a href="#registering-a-custom-domain" id="registering-a-custom-domain"></a>

You can register your own domain instead of the sub domains provided by Arkain such as `mydomain.run.arkain.app`. A custom domain can be set in Arkain's Dashboard by going to **\[Container Settings]**(![](<../../.gitbook/assets/new_setting (1).png>)) → **URL/Port section**, then clicking the **\[+ Add]** button and selecting **\[Custom domain].**

And enter the domain to register starting from `www`, and upload the `crt` and `key` files. If the certificate has a password, include the password in a file and upload it.

<figure><img src="../../.gitbook/assets/port_01.png" alt=""><figcaption></figcaption></figure>

### **Setting up DNS Domain**

Set the DNS CNAME of Arkain on the domain management service page. You need to configure a different CNAME depending on the container's region.

* **Seoul**: domain.run-ko-seoul1.arkain.site
* **Oregon**: domain.run-us-west2.arkain.io
* **Frankfrut**: domain.run-eu-central1.arkain.io
* **Mumbai**: domain.run-ap-south1.arkain.io

### Accessing the Domain through browser <a href="#accessing-the-domain-through-browser" id="accessing-the-domain-through-browser"></a>

Open your web browser and enter the registered domain to access it. You should see the results of the application you've developed displayed. If **Hot Module Replacement** (HMR) is applied in your code, your code changes will be reflected in the browser in real-time without broswer refresh.

* If you encounter a **404 error** page, double-check that you entered the domain correctly in the browser.
* If you encounter a **Connection Refused** page, check that the application is running correctly and ensure that the port number you entered during domain registration is correct.

[\
](https://help.goorm.io/en/goormide/workspace/features/commands)
