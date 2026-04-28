---
icon: ban
---

# Auto-stop

**Auto-stop** automatically shuts down containers after 30 minutes of inactivity to prevent unnecessary credit consumption. The system checks the activity of both the owner and all invited members to ensure the container only stops when no one is using it.

## Feature Guide <a href="#feature-guide" id="feature-guide"></a>

1. When **Auto-stop** is **On**

* **Participant-based Tracking:** The 30-minute countdown begins only after all participants (owner and members) close their Workspace browsers and stop all editor activities.
* **Activity Detection:** Auto-stop tracks not just browser closure, but also active editing. If anyone is still typing or running tasks, the container stays active.
* **Credit Efficiency:** Once the 30-minute window of total inactivity passes, the container stops automatically, and no further credits are deducted.



2. When **Auto-stop** is **Off**

* **Always-on (Background Run):** The container will continue to run even if everyone leaves the Workspace. Use this mode if you have background processes that need to stay active.
* **Manual Stop Required:** You must manually click the \[Stop] button on the Dashboard page or the Workspace.
* **Continuous Credit Use:** Credits will be deducted as long as the container is running. Be sure to stop it manually to avoid unexpected charges.



3. Setting Permissions

* **Owner Only:** Only the container owner has the authority to Enable or Disable the Auto-stop feature. Members can view the status but cannot change it.

## Set **Auto-stop** <a href="#set-automatic-stop" id="set-automatic-stop"></a>

You can set **Auto-stop** from the Dashboard page and the Workspace.

### From Dashboard <a href="#from-dashboard" id="from-dashboard"></a>

* Click the **\[Settings]**(<img src="../../../../../.gitbook/assets/setting (2).png" alt="" data-size="line">) button of the container → Active **\[Auto-stop]** in Container Status section.

<figure><img src="../../../../../.gitbook/assets/automaticstop (1).png" alt=""><figcaption></figcaption></figure>

### From Workspace <a href="#from-ide" id="from-ide"></a>

* Click the **\[Auto-stop]** button(<img src="../../../../../.gitbook/assets/stop.png" alt="Auto-off" data-size="line">) in the bottom bar, and then click the **\[Enable]** button in the popup to enable the container's Auto-stop feature.
* To turn off the feature, click the **\[Auto-stop]** button(<img src="../../../../../.gitbook/assets/stop (1).png" alt="Auto-off" data-size="line">) again.

<figure><img src="../../../../../.gitbook/assets/Terminal2 (1).png" alt=""><figcaption></figcaption></figure>
