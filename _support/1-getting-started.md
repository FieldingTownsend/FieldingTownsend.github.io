---
title: FT-SM Appliance Issues
icon: cog
toc: true
---

### Are you having issues with a Fielding Townsend Systems Manager appliance?

If you are having issues with your FT-SM appliance we recommend that you restart it.
At the >ok prompt you can type:

```bash
system reset -soft
```

When the appliance restarts simply run:
```bash
system selfcheck -deep
```

You can find more on the [FT-SM Troubleshooting](https://fieldingtownsend.freshdesk.com/support/solutions) page on the Fielding Townsend Support website.

### Updating the firmware

Download the latest version of the FT-SM firmware by running the following:

```bash
system update -all -reset -clearNVR
```
