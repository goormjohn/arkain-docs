---
icon: coin-vertical
description: >-
  Credits are the currency required for using containers. When you use
  containers, credits are deducted. The price of 1 credit is $0.02.
---

# Credits

### **Conditions for Credit Deductions**

Credits are deducted under the following conditions:

* **Container Usage**\
  Credit deductions occur while the container is running, based on the container specifications.
* **Storage Usage**\
  If the storage usage of each container exceeds the default capacity, **0.018 credits** will be deducted per **1GB** of storage per hour. Storage is charged r**egardless of whether the container is running or stopped.**&#x20;
  * The amount of **free storage** available **varies by plan.**
* **Traffic Usage**\
  If your container's monthly cumulative traffic exceeds 10GB, you will be charged 10 credits for each additional 1GB of traffic per minute.&#x20;
* **Free Credits**\
  You get 45 free credits per month, which expire on the last day of the month. (Award and expiration times are based on Coordinated Universal Time - UTC.) If you have a Membership plan, you can get an additional 90 credits.

You can monitor network traffic and storage usage for each container in the **\[Resources Monitor]** panel at the bottom of the workspace. You can monitor your real-time credit usage on the Home or Dashboard page.

{% hint style="info" %}
**Hint**\
You can monitor network traffic and storage usage for each container in the **Resources monitor** panel at the bottom of the workspace.

<img src="../.gitbook/assets/스크린샷 2025-02-24 오후 1.07.38.png" alt="" data-size="original">
{% endhint %}

***

## **Calculate Your Credit Usage**

Arkain allows you to estimate credit consumption based on performance and usage purpose. Plan your credits wisely and optimize your service usage efficiently.&#x20;

You can check the Credit Calculator on the Pricing Page or Payment Page to get a detailed estimate and ensure you're only using what you need!&#x20;

* The credit calculator can be accessed from the 'How much credit do I need?' section on the page opened by clicking **\[Pricing]** in the top menu of the Arkain website.
* You can use the credit calculator by clicking **\[Profile]** → **\[Pricing]** at the bottom left of the Arkain dashboard, or by clicking **\[Billing]** → **\[Buy credit]** → **\[Calculate credits]**.

***

## Purchasing Credits

You can purchase credits as needed on the **Payment page**. \
Follow these steps to charge credits:

{% stepper %}
{% step %}
### **Navigate to the Payment Page**

* You can access it through the **\[To buy credit]** button on the **Home or Dashboard page**.
* You can access it through the **\[Buy now]** button on the **Pricing page**.
* You can access it through the **\[Buy credit]** button on the **Billing page**.
* You can access it through the **\[Buy additional credits]** button on the **Workspace.**
{% endstep %}

{% step %}
### **Enter the Number of Credits**

Specify how many credits you want to purchase. You can use bulk buttons for convenience.&#x20;
{% endstep %}

{% step %}
### **Calculate Credits**

Click the **\[Calculate credits]** button to estimate the amount based on your usage.&#x20;
{% endstep %}

{% step %}
### **Confirm Purchase**

Review the amount of credits and the total payment amount.&#x20;
{% endstep %}

{% step %}
### **Enter the Payment details**

Enter the required information, and click the **\[Charge credits]** button.&#x20;
{% endstep %}
{% endstepper %}

{% hint style="info" %}
**Minimum Purchase**: You can purchase credits starting from a minimum of **100 credits**.&#x20;
{% endhint %}

## Managing Credits

* **Check Purchased Credits**\
  You can view the amount of credits you've purchased on the **Billing page**.&#x20;
* **Monthly Usage Report**\
  Access the **Credit Usage page** to review your monthly credit usage report. This helps you manage your credit payments efficiently.&#x20;
  * **The Credit Usage page** can be accessed by clicking **\[Profile]** → **\[Billing]** → **\[View usage]** in the dashboard.

***

## How Credits Are Calculated

This is a forecasting tool that provides an approximate cost based on your specified project or usage. However, the forecasted cost may differ from the actual cost due to various factors:

* **Duration**\
  Assumes **720 hours** per month and does not account for leap years.&#x20;
* **Promotional Credits**\
  Does not include promotional credits or discounts.
* **Additional Charges**\
  Does not account for additional usage not included in the forecast (e.g., if you use more than **5GB** of storage on the Free plan, you pay **0.018 credits** per GB per hour).&#x20;
* **Currency**\
  Forecasts are based on a fixed exchange rate.

### Credit amount by resource <a href="#credit-amount-by-resource" id="credit-amount-by-resource"></a>

**General Containers**

<table><thead><tr><th>Container Type</th><th width="115">vCPU</th><th>Memory</th><th>Cost per Hour (Credits)</th></tr></thead><tbody><tr><td>Micro</td><td>0.5</td><td>1 GB</td><td>2.25 credits</td></tr><tr><td>Small</td><td>2</td><td>2 GB</td><td>5.25 credits</td></tr><tr><td>Medium</td><td>4</td><td>4 GB</td><td>9.75 credits</td></tr><tr><td>Large</td><td>8</td><td>8 GB</td><td>18.75 credits</td></tr></tbody></table>

**GPU Containers**

<table><thead><tr><th>Container Type</th><th width="115">vCPU</th><th>Memory</th><th>Cost per Hour (Credits)</th></tr></thead><tbody><tr><td>Basic</td><td>3.5</td><td>13 GB</td><td>13.2 credits</td></tr></tbody></table>

**Additional Charges**

| Type             | Cost (Credits)                                   |
| ---------------- | ------------------------------------------------ |
| Traffic Addition | 10 credits/1GB/minute (exceeding 10GB per month) |
| Storage Addition | \~0.018 credits/1GB/hour (exceeding free)        |

***

<details>

<summary>Credit terms</summary>



* This policy constitutes part of the[ Arkain](https://accounts.goorm.io/terms) Terms of Service, and any matters not specified in this policy shall be governed by the terms and conditions of the Arkain Terms of Service.

- By paying for Arkain credits, you are deemed to have agreed to the paid service agreement.

* Members may withdraw their subscription within 7 days from the date of subscription. However, if the contents of the contract are different from the contents displayed or advertised by the company or if the contents of the contract are different from the contents of the contract, the subscription may be withdrawn within 1 month from the date of subscription or within 14 days from the date on which the fact was known or could have been known.

- Arkain may provide credits to members based on promotions or members’ activity history, and the conditions and details of credit provision will be announced separately through Arkain.

* If a member’s service is restricted or the member withdraws due to the member’s fault, the remaining credits will be forfeited and the member cannot claim repayment or compensation for the forfeited credits. However, if the member’s service restriction is lifted, the credits will not be forfeited.

- Arkain may change the price of credits at any time and will not compensate members for any loss caused by the changed price.

</details>
