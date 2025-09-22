# Credits Deduction

## Credits Deduction Situation

### Container stop

When the container is stop, you will be billed based on the time, storage, and traffic used by the container up to that point.

### Container run

When a container is run, you are charged for the storage used while the container is in a stopped state.

{% hint style="info" %}
Using the Advanced feature will consume additional credits per hour.&#x20;

* [code-supporter.md](../../user-guide/workspace/editor/code-supporter.md "mention")&#x20;
* [ai-supporter.md](../../user-guide/arkain-ai/ai-supporter.md "mention")
{% endhint %}

### Monthly deduction

On the 1st of each month, we perform billing for all containers currently using resource.

### Overused

If the credits due to be deducted exceed the available credits, all running containers will be stopped.

{% hint style="warning" %}
For containers that use **credits for storage,** once credits are exhausted, the container is **automatically inactivation.** [inactive-container.md](../../user-guide/dashboard/container-managing/inactive-container.md "mention")
{% endhint %}

### AI features

*   ### [Arkain Snap](../../user-guide/arkain-ai/what-is-arkain-snap.md)

    When you create a container through Snap, credits will be consumed based on AI usage.
*   ### [Side Chat](../../user-guide/arkain-ai/side-chat/)

    When you ask a question in the workspace side chat, credits will be used based on the model and token usage.
*   ### [AI Supporter](../../user-guide/arkain-ai/ai-supporter.md)

    Using AI Supporter incurs credits charges for AI to understand your code.

### Change plan

If the plan changes, all credits currently being charged will be deducted.

{% hint style="warning" %}
### Order of deduction by credits type

The order of credits usage is free credits first, then purchased credits. Free credits are used in order of shortest expiration date.
{% endhint %}

## Low Credits Mail

When the remaining credits allows for less than 1 hour of usage, you will receive an email notification that your credits balance is low.

{% hint style="warning" %}
The same email will not be sent again until you purchase credits. \
Additionally, if you have opted out of receiving credits emails, the email will not be sent.
{% endhint %}
