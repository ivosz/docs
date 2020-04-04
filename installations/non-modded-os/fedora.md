---
description: This tutorial will guide you through the installation of Fedora.
---

# Fedora

![](../../.gitbook/assets/fedora_banner.png)

## Essential Information

Fedora provided by Andronix is open source including all the scripts needed for installing it. You can take a look at it [here](https://github.com/AndronixApp/AndronixOrigin).

**Download size** - 45 MB

{% hint style="warning" %}
The size mentioned above is not the size after installing Fedora but it's just the tar size that Andronix downloads. **This doesn't include a desktop environment for the GUI**.
{% endhint %}

## How to Install?

* Open the[ Andronix App](https://andronix.app/) and click on the Fedora card.
* Click the **Install** button.

![](../../.gitbook/assets/fedora.png)

* Tap "**Copy**" button and then tap "**Termux**" to go the Termux app.

![](../../.gitbook/assets/fedora_inst.png)

* Use the command below to update your termux packages so that you're running the updated versions of the required packages.

```text
pkg update
```

![](../../.gitbook/assets/termux-1.png)

* Tap & hold anywhere on the screen and press **Paste**.
* Press **Enter** and wait till the installation completes. 
* Type the following command to start the distro ****and press enter.

```text
./start-fedora.sh
```

* Now if you see `root@localhost` in Termux then you have successfully started Fedora.

{% hint style="danger" %}
This only includes the bare-bone Fedora system that can be used through a CLI \(Command Line Interface\). To install a **desktop environment** follow the guide here.
{% endhint %}
