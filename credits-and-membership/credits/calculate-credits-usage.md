# Calculate Credits Usage

Arkain allows you to estimate credits consumption based on performance and usage purpose. Plan your credits wisely and optimize your service usage efficiently.&#x20;

***

## Credits amount by resource <a href="#credit-amount-by-resource" id="credit-amount-by-resource"></a>

<table><thead><tr><th width="162">Performance</th><th width="279">Specification</th><th width="154">Credits per hour</th><th>Price</th></tr></thead><tbody><tr><td>Micro</td><td>0.5 vCPU, 1GB Memory</td><td>1.96</td><td>$0.0392</td></tr><tr><td>Small</td><td>2 vCPU, 2GB Memory</td><td>6.80</td><td>$0.1360</td></tr><tr><td>Medium</td><td>4 vCPU, 4GB Memory</td><td>13.60</td><td>$0.2720</td></tr><tr><td>Large</td><td>8 vCPU, 8GB Memory</td><td>27.20</td><td>$0.5440</td></tr><tr><td><a href="../../user-guide/dashboard/container/nvidia-tesla-t4-gpu-container.md">GPU Basic </a>(NVIDIA Tesla T4)</td><td>3.5 vCPU, 13GB Memory</td><td>51.76</td><td>$1.0352</td></tr><tr><td><a href="../../user-guide/arkain-ai/ai-supporter.md">AI Supporter </a>(Advanced)</td><td>0.5 vCPU 2 GB memory</td><td>2.94</td><td>$0.0588</td></tr><tr><td><a href="../../user-guide/workspace/editor/code-supporter.md">Code Supporter</a> (Advanced)</td><td>0.5 vCPU, 1GB Memory</td><td>1.96</td><td>$0.0392</td></tr></tbody></table>

{% hint style="warning" %}
The cost for using the optional **AI Supporter and Code Supporter** features is added to your container cost. However, when using a GPU container, there is no additional charge for these features; instead, your allocated **GPU compute and memory resources** will be reduced.
{% endhint %}

**Additional Charges**

<table><thead><tr><th width="169.59375">Type</th><th>Cost (Credits)</th></tr></thead><tbody><tr><td>Traffic Addition</td><td>8 credits/1GB (exceeding 10GB per month)</td></tr><tr><td>Storage Addition</td><td>~0.018 credits/1GB/hour (exceeding the free storage available for your plan)</td></tr></tbody></table>

***

## Credits amount by LLMs <a href="#credit-amount-by-resource" id="credit-amount-by-resource"></a>

<table><thead><tr><th width="169">Model</th><th>1 token Output (Credit)</th><th>1 token Input (Credit)</th></tr></thead><tbody><tr><td>claude-sonnet-4.5</td><td>0.001200</td><td>0.00024</td></tr><tr><td>gemini-2.5-pro</td><td>0.000800</td><td>0.0001</td></tr><tr><td>gpt-5.1</td><td>0.000800</td><td>0.0001</td></tr><tr><td>gpt-5</td><td>0.000800</td><td>0.0001</td></tr><tr><td>gpt-4.1</td><td>0.000640</td><td>0.00016</td></tr><tr><td>gpt-o3 (reasoning)</td><td>0.000640</td><td>0.00016</td></tr><tr><td>claude-haiku-4.5<br>(default)</td><td>0.000400</td><td>0.00008</td></tr><tr><td>gpt-o4-mini-high</td><td>0.000352</td><td>0.000088</td></tr><tr><td>gpt-o4-mini</td><td>0.000352</td><td>0.000088</td></tr><tr><td>gpt-5-mini</td><td>0.000160</td><td>0.00002</td></tr><tr><td>gpt-4.1-mini</td><td>0.000128</td><td>0.000032</td></tr><tr><td>gpt-5-nano</td><td>0.000032</td><td>0.000004</td></tr></tbody></table>
