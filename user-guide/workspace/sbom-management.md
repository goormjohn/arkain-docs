---
icon: file-waveform
---

# SBOM Management

A **Software Bill of Material** (SBOM) is a statement of all software information that is utilized by a developer to build a software or service.&#x20;

As the use of open source has expanded, the problem of security vulnerabilities has grown. In fact, a security vulnerability scan of 2,700 of software found security vulnerabilities in more than 95% of applications.

{% hint style="info" %}
Source: BLACKDUCK's AppSec Decoded: Takeaways from the 2022 “[Software Vulnerability Snapshot](https://www.blackduck.com/blog/appsec-decoded-2022-software-vulnerability-snapshot-report-takeaways.html)” report
{% endhint %}

In response to this, Arkain provides tools to generate and manage SBOM information for safer software development.

{% stepper %}
{% step %}
Quickly track and respond to known and new vulnerabilities.&#x20;
{% endstep %}

{% step %}
Check the latest component status.&#x20;
{% endstep %}

{% step %}
Check license compliance.&#x20;
{% endstep %}

{% step %}
Get visibility into your software.
{% endstep %}
{% endstepper %}

## How to Generate SBOM and Automatic Generation Methods

#### Step-by-Step Process

{% stepper %}
{% step %}
#### Click the **\[Menu]** button and select the **\[Manage SBOM]**.


{% endstep %}

{% step %}
#### Click the **\[SBOM Settings]** button. (Optional)

Enable **\[Automatic report generation during GIT PUSH]** feature to configure automatic SBOM generation. To use this feature, you must first link your project with Git.
{% endstep %}

{% step %}
Click the **\[Generate SBOM]** button.

* Set the SBOM report format. You can choose between **SPDX** and **CycloneDX**.
* Personalize your document by entering a **Name** for easy identification.
{% endstep %}

{% step %}
#### Click the **\[Create]** button to start the report generation process.

The generated report file will be automatically downloaded and saved locally. You can also view previously generated reports in the report history section.
{% endstep %}

{% step %}
#### Click the **\[Confirmation]** button to finish the process.


{% endstep %}
{% endstepper %}

{% hint style="info" %}
The SBOM report can be uploaded to an external SBOM analysis platform for more detailed analysis.
{% endhint %}

### Automatic Generation Setup

When you enable automatic report generation during Git push, SBOM reports will be created automatically each time you push changes to your repository. This ensures your SBOM stays up-to-date with your latest code changes.

### Report Formats

* **SPDX (Software Package Data Exchange)**: An open standard for communicating software bill of materials information, including components, licenses, copyrights, and security references.
* **CycloneDX**: A lightweight software bill of materials standard designed for use in application security contexts and supply chain component analysis.

