---
icon: comment-question
---

# Can't use AI-Generated Template Introduction

If you cannot use the **AI-Generated Template Introduction** feature, please check whether the currently accessed region matches the region where your container was created.

## 1. Why This Happens

The AI-Generated Template Introduction feature only works when:

* The currently accessed region is the same as the container's region.

If the regions are different, the feature will not be available.

## 2. How to Check the Region

You can check both regions in the following ways:

* **Currently accessed region:** Check the URL of the Dashboard page you are using.

| Region    | URL                        |
| --------- | -------------------------- |
| Seoul     | `ap-northeast-2.arkain.io` |
| Oregon    | `us-west-2.arkain.io`      |
| Frankfurt | `eu-central-1.arkain.io`   |
| Mumbai    | `ap-south-1.arkain.io`     |

* **Container’s region:** Go to the **Container Settings** page, then click the **\[More]** button to find the container's region details.

{% hint style="info" %}
When creating a container, the region closest to your current location is automatically selected.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (63) (1).png" alt=""><figcaption></figcaption></figure>

## 3. What to Do if Regions Don’t Match

If the **currently accessed region** and the **container’s region** are different, you need to migrate your container to the **currently accessed region**.

### <mark style="color:$primary;">**Option 1: Using Export / Import feature**</mark>

You can **export the container** and then **import it into a new container in the currently accessed region.**

**Steps:**

1. Go to your container's **Workspace**.
2. Right-click on your project folder in the **Project Sidebar** and select **\[Export Folder]**.
3. Choose your preferred compression format: ZIP, TAR, or TAR.GZ.
4. In your currently accessed region, create a new container and run it.
5. Right-click on an empty area in the **Project Sidebar** and select **\[Upload Folder].**
6. In the Import Folder popup, upload the exported folder, select the desired location, and click the **\[Import]** button to upload it.

{% content-ref url="../../user-guide/workspace/file-management/import-export.md" %}
[import-export.md](../../user-guide/workspace/file-management/import-export.md)
{% endcontent-ref %}

### <mark style="color:$primary;">**Option 2: Creating a Template**</mark>

Alternatively, you can create a **template** from your existing container and then create a new container from that template in the **currently accessed region**.

**Steps:**

1. Go to the container you want to migrate.
2. [create-a-template.md](../../user-guide/templates/create-a-template.md "mention") from it.
3. In your currently accessed region, create a new container using that template.



After migration, you will be able to use the AI-Generated Template Introduction feature as usual.
