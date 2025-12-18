---
description: >-
  A guide to valid questions you can ask in the Side Chat within the Dashboard
  page.
icon: question
---

# What You Can Ask Side Chat

{% hint style="warning" %}
**Responses provided by Side Chat may not always be accurate and should be used as reference information only.**
{% endhint %}

### **1.** Arkain Feature Guidance

* **What it does**
  * Answers questions about Arkain’s features and services by using an LLM trained on and referencing the official documentation at [docs.arkain.io](http://docs.arkain.io/), helping you understand how each capability works and when to use it.
* **Example requests**
  * What is Arkain Snap?
  * What is Auto Stop?
  * What is Arkain template?
  * What is AI Supporter?
  * What is Code Supporter?
* **Constraints**
  * <mark style="background-color:$danger;">AI responses may be approximate or outdated; please refer to the official documentation for accurate details.</mark>

***

### **2.** Credit Support

{% hint style="danger" %}
Side Chat enforces strict access control and only supports searching data owned by the **authenticated user.**
{% endhint %}

#### 2.1. Credit calculation

* **What it does**
  * Calculates credit usage based on container specifications and usage duration, allowing you to estimate hourly and monthly credit consumption.
* **Example requests**
  * Calculate how many credits the active container is using per hour.
  * Calculate the monthly usage credits for the medium container.
  * Calculate the monthly credit usage for the GPU container.
  * Calculate the hourly usage for a 10GB container with micro specs.

#### 2.2. Check credits

* **What it does**
  * Shows your current credit balance, monthly credit usage, and real-time credit consumption for the active container.
* **Example requests**
  * Check credits.
  * How many credits do I have left?
  * Show credit status.
* **Constraints**
  * <mark style="background-color:$danger;">Credit information can only be viewed for the currently</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**authenticated user**</mark><mark style="background-color:$danger;">.</mark>&#x20;
  * <mark style="background-color:$danger;">There may be a slight delay before updates are reflected.</mark>

***

### **3.** Container Management

{% hint style="danger" %}
* For actions that require a specific container, the Side Chat will ask for the container name if you don’t provide it.
* The Side Chat enforces strict access control and only supports searching data owned by the **authenticated user.**
* Checking or updating **shared containers** via Side Chat is **currently unavailable**.
{% endhint %}

#### 3.1. Check Container

#### 3.1.1. Get Container List

* **What it does**
  * Shows up to five of your most recently used containers, including their current status and the last updated time.
* **Example requests**
  * View containers.
  * Which containers were updated recently?

#### 3.1.2. Get Container Detail

* **What it does**
  * Returns full details for a specific container: basic info, spec, storage, advanced setting info, URL/port, init script, SSH info, and more.
* **Example requests**
  * Show details for my "my-project" container.
  * What are the spec and storage for "project-alpha"?
  * Show the URL/port settings for "web-service".
  * Show only SSH info for “my-app” container.
* **Constraints**
  * <mark style="background-color:$danger;">Getting container details is not allowed when the container is inactive.</mark>

#### 3.2 Update Container Settings

{% hint style="info" %}
**Note**

* All changes **require explicit user approval** before execution. The Side Chat will propose the update, you confirm, then the operation runs.
* Note that updating container specs, storage, or advanced settings may **change the number of credits deducted.**
{% endhint %}

{% hint style="danger" %}
**Common Constraints**

Updates to container information and status are not allowed when a container is **inactive**.
{% endhint %}

#### 3.2.1. Update Basic Info

* **What it does**
  * Changes the container’s name or description.
* **Example requests**
  * Rename my "api-server" container to "project-alpha".
  * Update the description of "data-pipeline" container to "Daily ETL jobs".
  * Set empty description from the “algorithm-practice” container.
* **Constraints**
  * <mark style="background-color:$danger;">You can’t rename a container to a name that is already in use.</mark>
  * <mark style="background-color:$danger;">Only one field can be updated per request.</mark>

#### 3.2.2. Update Spec

* **What it does**
  * Updates the container’s resource specification to one of: micro, small, medium, or large.
* **Example requests**
  * Set my container spec to medium.
  * Upgrade the “qna-dashboard” container to large.
  * I want to change spec to small for “nextjs-app” container.
* **Constraints**
  * <mark style="background-color:$danger;">Specs can only be changed when the container is</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**stopped**</mark><mark style="background-color:$danger;">.</mark>
  * <mark style="background-color:$danger;">Changing a general container to a</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**GPU is not permitted**</mark><mark style="background-color:$danger;">.</mark>

#### 3.2.3. Update Storage

* **What it does**
  * Increases the container’s storage capacity in gigabytes (GB).
* **Example requests**
  * Increase the storage for the “portfolio-web” container to 20 GB.
  * Expand "data-lab" storage to 25 GB.
  * Update "etl-runner" container’s storage to 30 GB.
  * I want to change storage size to 15 GB for “python-app” container.
* **Constraints**
  * <mark style="background-color:$danger;">Storage can only be changed when the container is</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**stopped**</mark><mark style="background-color:$danger;">.</mark>
  * <mark style="background-color:$danger;">You can upgrade again</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**6 hours**</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">after the previous upgrade.</mark>
  * <mark style="background-color:$danger;">Once a container's storage capacity is increased, it</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**cannot be reduced.**</mark>
  * <mark style="background-color:$danger;">You can upgrade the storage</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**up to 80GB.**</mark>

#### 3.2.4. Update URL / Port

* **What it does**
  * Manages exposed running URL and port mappings for the container. You can add a URL, change its port, or delete it.
* **Example requests**
  * Add the “tetris-api” URL and port 8080 to the “tetris” container.
  * Change the "web" URL port to 3001.
  * Remove the “front-app” URL from the “portfolio” container.
* **Constraints**
  * <mark style="background-color:$danger;">URL/Port can only be changed when the</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**container is stopped**</mark><mark style="background-color:$danger;">.</mark>
  * <mark style="background-color:$danger;">You can’t add a url name that is</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**already in use.**</mark>
  * <mark style="background-color:$danger;">When updating the URL, you must enter the</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**subdomain name of the URL**</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">you wish to use.</mark>
    * For example, if you want to add a URL like `https://my-api-server.ap-northeast-2.arkain.site`, you should only enter “my-api-server”.
  * <mark style="background-color:$danger;">**Custom Domains cannot be added via Side Chat**</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">and must be configured directly on the Container settings page.</mark>

#### 3.2.5. Update Init Script

* **What it does**
  * Modifies the init script that runs when the container runs.
* **Example requests**
  * Update the init script to run "mkdir project & cd project".
  * Set the init script to "bash [init.sh](http://init.sh)" for “blank-project” container.
  * Change the init script to empty.
* **Constraints**
  * <mark style="background-color:$danger;">Init Script can only be changed when the container is</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**stopped**</mark><mark style="background-color:$danger;">.</mark>

#### 3.2.6. Update Advanced Settings

* **What it does**
  * Enables or disables advanced features such as [**Auto-stop**](https://docs.arkain.io/user-guide/dashboard/container/auto-stop), [**AI Supporter**](https://docs.arkain.io/user-guide/arkain-ai/ai-supporter), and [**Code Supporter**](https://docs.arkain.io/user-guide/workspace/editor/code-supporter).
* **Example requests**
  * Turn on auto-stop for "project-alpha" container.
  * Disable AI supporter on "my-project".
  * Enable code supporter for "web-service".
  * Turn off auto-stop for "etl-runner".
* **Constraints**
  * <mark style="background-color:$danger;">Advanced Settings can only be changed when the container is</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**stopped**</mark><mark style="background-color:$danger;">.</mark>
  * <mark style="background-color:$danger;">**Only one setting**</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">can be changed per request.</mark>

***

### **4. Template Recommendations**

* **What it does**
  * Recommends Arkain templates based on your project goals and use cases.
* **Example requests**
  * Find template for game.
  * Find template for boilerplate.
  * Find template for React.
  * Find template for AI-powered app.
* **Constraints**
  * <mark style="background-color:$danger;">Template recommendations are prioritized based on usage frequency, with</mark> <mark style="background-color:$danger;"></mark><mark style="background-color:$danger;">**the most commonly used templates shown first**</mark><mark style="background-color:$danger;">.</mark>



