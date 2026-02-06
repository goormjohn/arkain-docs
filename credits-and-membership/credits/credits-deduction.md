---
description: >-
  This page outlines the specific conditions, situations, and notification
  policies regarding credit deductions.
icon: coin-vertical
---

# Credits Deduction

## 1. **Conditions for Credit Deductions**

Credits are deducted under the following conditions:

* **Container Usage:** Deductions occur while a container is running, based on the container's performance tier.
* **Storage Usage:** If a container's storage exceeds your plan's free limit, 0.018 credits are deducted per 1GB per hour.
  * **Free Plan:** Up to 5GB free
  * **Membership Plan:** Up to 15GB free
  * **Note:** Storage is billed regardless of **whether the container is running or stopped**.
* **Traffic Usage:** If monthly cumulative traffic exceeds 10GB, 8 credits are deducted for each additional 1GB.

***

## 2. Deduction Situations

Credits are deducted during the following specific scenarios:

#### **1. Container Stop**

When you stop a container, the following are calculated and deducted at once:

* **Time-based usage:** Credits for the container performance tier.
* **Advanced Features:** Additional hourly credits for using [code-supporter.md](../../user-guide/workspace/editor/code-supporter.md "mention") or [ai-supporter.md](../../user-guide/arkain-ai/ai-supporter.md "mention").
* **Active usage:** Storage and traffic credits used during the session.

#### **2. Container Run**

When a container is started, you are deducted for the storage used while the container was in a stopped state.

#### **3. Monthly Deduction**

On the 1st of each month (UTC), billing is performed for all containers currently using resources.

#### **4. AI Features**

* **Arkain Snap:** Deductions occur based on AI usage during container creation.
* **Side Chat(Workspace):** Deductions occur based on the model and token usage per question.

#### **5. Change Plan**

If you change your plan, all currently accrued usage credits will be deducted immediately.

#### 6. Overused

If the required deduction exceeds your available credits, a final settlement is performed, and all running containers are stopped immediately.

{% hint style="warning" %}
For containers that use **credits for storage,** once credits are exhausted, the container is **automatically inactivation.** [inactive-container.md](../../user-guide/dashboard/container-managing/inactive-container.md "mention")
{% endhint %}

***

## 3. Credit Deduction Order

Credits are deducted in the following priority:

1. **Free Credits:** Deducted first (those with the shortest expiration date are deducted first).
2. **Purchased Credits:** Deducted only after all free credits are exhausted.

***

## 4. Low Credit Mail Notifications

To prevent service interruption, Arkain sends an automated alert when your balance is nearly exhausted.

* **Trigger:** Sent when your remaining credits allow for less than **1 hour** of usage.
* **Frequency:** This notification is sent only once per purchase cycle. You will not receive another alert until you top up your credits.
* **Settings:** You can enable or disable these alerts via the **\[Credit mail]** toggle on the **Billing page**.

***
