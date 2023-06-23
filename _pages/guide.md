---
title: "Quick Start Guide and Demo"
permalink: /guide/
layout: single
excerpt: "WCT Quick Start Guide and Demo"
last_modified_at: 2020-12-07T03:02:20+00:00
---

Great that you would like to start using the WCT. So, let’s get started!

You can either start with a fresh installation or try the demo version of WCT, available as Virtual Box disk image. If you want the latter, please go to the section “Try the Demo!” below.

For a full installation of the WCT, please go to the documentation section first to learn about the installation requirements and the installation process of WCT. Go to:<br>
[https://webcuratortool.readthedocs.io/en/latest/guides/quick-start-guide.html](https://webcuratortool.readthedocs.io/en/latest/guides/quick-start-guide.html)

This will guide you through the whole process. If you need any help, please see the [Support](/support/) page for more information.


### Try the Demo!
The WCT is also available in a demonstration setup. This might be useful for you to just test WCT out of the box and see what it is and what it can do for you before fully installing and configuring it.

#### What’s in this demo version?
It contains the full WCT application version 3, including the Heritrix crawl engine. It is configured in such a way that you can start a crawl and check the results. It runs in localhost on your own machine. Harvest results are only stored on your machine. None of the data is uploaded to an online server.

#### How to start using the demo?
Please follow the next steps to get the WCT demo version running:

#### What you need:
- freely available disk space of at least 6 GB (necessary when the VM is running)
- disk image containing the setup WCT
- Virtual Box application installed. Virtual box is available for free at [https://www.virtualbox.org/](https://www.virtualbox.org/)
- Web browser (any kind will work) to access and use WCT

**Step 1:** download the [disk image](https://drive.google.com/file/d/1tOfD9Hyq12Vacpxj48B1QEvhwVE5DhUG/view?usp=sharing) (about 4 GB) with WCT configured first.<br>
**Step 2:** open Virtual Box and import the disk image by clicking “menu File -> Import Appliance”. Use the default options.<br>
**Step 3:** start the newly created VM in Virtual Box.<br>

*Note:* in some cases Virtual Box produces an error message about 'VT-x’. This is because Virtual Box requires hardware virtualisation to operate smoothly. You can enable this in the BIOS of your computer. In the BIOS search for "hardware virtualization" or "virtual technology" or "vt" to be allowed / enabled.

**Step 4:** open your regular web browser and navigate to http://localhost:3080/wct<br>
**Step 5:** you now should see the start page from WCT. Login to the administration interface using the following credentials:

user: demo<br>
password: Demo2020

Congratulations! You are now ready to use the WCT.

The user manual can be found at the Documentation section, please see here:<br>
[https://webcuratortool.readthedocs.io/en/latest/guides/overview-history.html](https://webcuratortool.readthedocs.io/en/latest/guides/overview-history.html)

If you need support or have a question about this demo version, please contact us via the [Support](/support/) page.




