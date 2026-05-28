---
icon: github
---

# Import GitHub Repos

You can import existing projects directly from **GitHub** to continue working on them inside Arkain. Arkain supports both public repository URLs (no login required) and personal repositories via GitHub authentication.

{% stepper %}
{% step %}
### Open the Creation Popup <a href="#step-1-go-to-the-dashboard-and-click-new-container" id="step-1-go-to-the-dashboard-and-click-new-container"></a>

Go to the [Dashboard](https://arkain.io/my/dashboard) page and click the \[+ New container] button to open the Create container popup.
{% endstep %}

{% step %}
### Choose Your Import Method

**Option A: Import via Public URL (No Login Required)**

Ideal for quickly spinning up any public open-source project without syncing your account.

1. Select the URL tab at the top of the popup.
2. Paste the full GitHub repository address (e.g., `https://github.com/owner/repo`) into the Repository URL field.

**Option B: Import via Authenticated Account (Personal & Private Repos)**

Ideal for accessing your own repositories, including private ones.

1. Select the Repo tab at the top of the popup.
2. Click the authorization button to securely link your GitHub account.
3. Once authenticated, select the desired repository from your personal list. Private repositories will be clearly marked with a badge.
{% endstep %}

{% step %}
### Configure Environment & Build

* **Template & Name:** Arkain automatically detects and fills in the appropriate base template and project name based on the repository contents. You can freely modify these as needed.
* **Customization:** Configure your OS, Performance tier, and additional storage, or toggle Modules / Packages if you need extra dependencies pre-installed.
* **Launch:** Click the \[Import project] button at the bottom to create and launch your container environment.
{% endstep %}
{% endstepper %}
