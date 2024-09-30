---
title: Step-by-Step Tutorial on Installing and Configuring Your License Server
date: 2024-09-26T05:04:33.731Z
updated: 2024-09-30T11:15:51.536Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Step-by-Step Tutorial on Installing and Configuring Your License Server
thumbnail: https://thmb.techidaily.com/08c04182a5370a9894bbb7d5aedb620a94eb3a5d17a6c123fae986b1d0cc282e.jpg
---

## Step-by-Step Tutorial on Installing and Configuring Your License Server

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Per-User Subscription](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Team Subscription](https://tools.techidaily.com/advancedinstaller/products/)  
   * [License Server](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)
* [Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Samples](https://tools.techidaily.com/advancedinstaller/products/)
* [How-tos](https://tools.techidaily.com/advancedinstaller/products/)
* [FAQs](https://tools.techidaily.com/advancedinstaller/products/)
* [Windows Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Deployment Technologies](https://tools.techidaily.com/advancedinstaller/products/)
* [IT Pro](https://tools.techidaily.com/advancedinstaller/products/)
* [MSIX](https://tools.techidaily.com/advancedinstaller/products/)
* [Video Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Advanced Installer Blog](https://tools.techidaily.com/advancedinstaller/products/)
* [Table of Contents](https://tools.techidaily.com/advancedinstaller/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Configuring the License Server

To use an Advanced Installer **floating license** you first need to install and configure the License Server. A running License Server is required when registering your copy of Advanced Installer.

* 1\. [Install the license server](https://tools.techidaily.com/advancedinstaller/products/)
* 2\. [Launch the configuration wizard](https://tools.techidaily.com/advancedinstaller/products/)
* 3\. [Set a port number](https://tools.techidaily.com/advancedinstaller/products/)
* 4\. [Specify your license key](https://tools.techidaily.com/advancedinstaller/products/)
* 5\. [Configuring the License Server from Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * 5.1 [The syntax for configuring the License Server is:](https://tools.techidaily.com/advancedinstaller/products/)  
   * 5.2 [The syntax for restarting the License Server is:](https://tools.techidaily.com/advancedinstaller/products/)  
   * 5.3 [The Syntax for uninstalling the License Server is:](https://tools.techidaily.com/advancedinstaller/products/)
* 6\. [Configure the license server page](https://tools.techidaily.com/advancedinstaller/products/)
* 7\. [Limit access to the license server page](https://tools.techidaily.com/advancedinstaller/products/)
* 8\. [Register using the license server](https://tools.techidaily.com/advancedinstaller/products/)

## 1\. Install the license server

The license server is part of Advanced Installer. You must [download](https://tools.techidaily.com/advancedinstaller/products/) and install the entire application on your server machine. Just copying the license server files over is not enough.

## 2\. Launch the configuration wizard

Launch advinstlicenseserver.exe from the /bin/x86 subfolder of the Advanced Installer install directory.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The license server configuration process requires Administrator privileges.

## 3\. Set a port number

The first setting is the license server port number. It will be used by client Advanced Installer instances to connect to the server.

Set an unused port number in the appropriate field and press \[Next \] button.

![License Server Configuration Wizard](https://cdn.advancedinstaller.com/img/dialog/license-server-config.png "License Server Configuration Wizard")  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

The License Server Wizard will automatically check if the specified port is open. It will also configure the Windows Firewall to allow access to this port. If the port is blocked by an external firewall, an error message will be shown.

## 4\. Specify your license key

If your server machine has an active Internet connection, you can enter your_License Key_ and press \[Next \]. The wizard will automatically download the license file and finish the configuration.

If no Internet connection is available, you can use the “I would like to register by email” option. We will require your _Computer ID_ along with the License Key to generate and return you a license file.

![Register License Server](https://cdn.advancedinstaller.com/img/dialog/license-server-key.png "Register License Server")  

## 5\. Configuring the License Server from Command Line

The License Server could be also configured using Command Line, by calling our tool**advinstlicenseservercli.exe** from the /bin/x86 subfolder of the Advanced Installer install directory.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)**advinstlicenseservercli.exe** requires Administrator privileges so it must be run from an Administrator Command Prompt

### 5.1 The syntax for configuring the License Server is:

          advinstlicenseservercli.exe   /ConfigureLicenseServer   <floating_license_id>  <license_server_tcp_port>
          

Copy

Parameters:

* **<floating\_license\_id>** \- The License key
* **<license\_server\_tcp\_port>** \- The License Server port number

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/999558/11832" target="_top" id="999558">
  <img src="//a.impactradius-go.com/display-ad/11832-999558" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/999558/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 5.2 The syntax for restarting the License Server is:

          advinstlicenseservercli.exe   /RestartLicenseServer  [-stoppreviousservice]
          

Copy

Parameters:

* **\-stoppreviousservice** \- Use this parameter if you have a License Server of an older version of Advanced Installer running on your machine. This will stop the service associated with the old version of the License Server and will start the new version.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062450/7443" target="_top" id="1062450">
  <img src="//a.impactradius-go.com/display-ad/7443-1062450" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062450/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 5.3 The Syntax for uninstalling the License Server is:

          advinstlicenseservercli.exe  /UninstallLicenseServer
          

Copy

## 6\. Configure the license server page

Access the license server page by going tohttp://\[servername\]:\[port\]/admin in your web browser.

 Check the available registered licenses, add the computers that use them, and set the priority level of each computer. 

Check "Log license incidents" to enable logging the license server. The log is created in %ALLUSERSPROFILE%\\Caphyon\\License Server\\licenseincidents.json on your license server computer. 

![Register License Page](https://cdn.advancedinstaller.com/img/tutorial/license-server-ai/server-page.png "Register License Page")  

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)If one of your computers is a Build Server, or you just want to give priority to a certain computer in case of a simultaneous request to use the license. you could set its**Priority Level** to _Build Server_.

## 7\. Limit access to the license server page

Limiting access to the license server page can be done by following these steps: 

1\. Create an empty JSON file in C:\\ProgramData\\Caphyon\\License Server and name it accesslist.json.

2\. Copy and paste the code below into the new JSON.

 "FormatVersion": 1,
 "AccessList": [

     "Path": ["/admin", "/admin.html", "/getlicense"],
     "Deny": [],
     "Allow":[]

]

Copy

3\. Add the IPs of the computers that are allowed access to the license server page; if left empty anyone from your network can access the page.

  "Allow":["11.0.0.1" , "11.0.0.2"]

Copy

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)To deny access to a few specific computers, add their IPs to Deny and leave Allow empty.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139113/17108" target="_top" id="2139113">
  <img src="//a.impactradius-go.com/display-ad/17108-2139113" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139113/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)FQDN (fully qualified domain name) is supported in Allow and Deny list. To obtain the FQDN of a computer use _ping -a <ip>_ command line.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)Using FQDN can delay license acquiring from the server even when the access list is not used. The FQDN resolve can be disabled from Admin panel (http://\[servername\]:\[port\]/admin) by uncheking _Resolve IP to fully qualified domain name (FQDN)_ option.

## 8\. Register using the license server

With a running license server, you can now [register](https://tools.techidaily.com/advancedinstaller/products/) any Advanced Installer instance. Start Advanced Installer, access the “Help > Register” menu inside the application and select the “by using a license server” option.

![Register Advanced Installer](https://cdn.advancedinstaller.com/img/dialog/register-with-server.png "Register Advanced Installer")  

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

After specifying the license server host name and port number, you can click\[Next \] to finish the registration. Your current Advanced Installer instance will use one of the available license slots.

![License Server Address](https://cdn.advancedinstaller.com/img/dialog/license-server-access.png "License Server Address")  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885943/19272" target="_top" id="1885943">
  <img src="//a.impactradius-go.com/display-ad/19272-1885943" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885943/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)Once an Advanced Installer copy is registered with a license server, it stays permanently registered. You don't need to re-register every time you edit a project.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135316/14409" target="_top" id="2135316">
  <img src="//a.impactradius-go.com/display-ad/14409-2135316" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135316/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

#### Did you find this page useful?

Please give it a rating:

 Thanks!

#### Report a problem on this page

Information is incorrect or missing

Information is unclear or confusing

Something else

#### Can you tell us what’s wrong?

Send message

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-a-step-by-step-guide-to-crafting-captivating-podcast-scripts-plus-free-examples/"><u>[New] 2024 Approved A Step-By Step Guide to Crafting Captivating Podcast Scripts (Plus Free Examples)</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-ultimate-guide-to-hexacopter-wonders/"><u>[New] 2024 Approved Ultimate Guide to HexaCopter Wonders</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-aspiring-youtubers-guide-to-affiliate-allies-for-2024/"><u>[New] Aspiring YouTubers' Guide to Affiliate Allies for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-decoding-steps-to-access-your-channels-eyeballs-for-2024/"><u>[New] Decoding Steps to Access Your Channel's Eyeballs for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-the-ultimate-method-to-integrate-flv-content-on-youtube/"><u>[New] In 2024, The Ultimate Method to Integrate FLV Content on YouTube</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-eight-outstanding-choices-for-private-video-communication/"><u>[Updated] Eight Outstanding Choices for Private Video Communication</u></a></li>
<li><a href="https://fox-within.techidaily.com/creative-tims-top-picks-over-40-elegant-vite-template-collections-for-rapid-web-development/"><u>Creative Tim's Top Picks: Over 40 Elegant Vite Template Collections for Rapid Web Development</u></a></li>
<li><a href="https://fox-within.techidaily.com/django-boosted-with-bootstrap-4-the-ultimate-black-admin-by-creative-tim/"><u>Django Boosted with Bootstrap 4 - The Ultimate Black Admin by Creative Tim</u></a></li>
<li><a href="https://fox-within.techidaily.com/figma-pro-mastery-unlocking-efficiency-with-horizon-ai-boilerplate-plus-design-excellence-by-creative-tim/"><u>Figma Pro Mastery: Unlocking Efficiency with Horizon AI Boilerplate PLUS | Design Excellence by Creative Tim</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-revolutionize-your-video-presence-with-personalized-shorts-thumbnails/"><u>In 2024, Revolutionize Your Video Presence with Personalized Shorts Thumbnails</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-motorola-moto-g84-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What are Location Permissions Life360 On Motorola Moto G84 5G? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/maximize-your-productivity-for-free-optimal-gpt-4-usage-with-copilot-support/"><u>Maximize Your Productivity for Free - Optimal GPT-4 Usage with Copilot Support</u></a></li>
<li><a href="https://fox-within.techidaily.com/react-paper-dashboard-with-bootstrap-4-professional-admin-layout-by-creative-tim/"><u>React Paper Dashboard with Bootstrap 4 - Professional Admin Layout by Creative Tim</u></a></li>
<li><a href="https://fox-within.techidaily.com/superior-project-manager-dashboard-2-professional-edition-with-laravels-livewire-features-by-creative-tim-and-updivision-for-ultimate-uiux-experience/"><u>Superior Project Manager Dashboard 2 Professional Edition with Laravel's Livewire Features by Creative Tim & UPDIVISION for Ultimate UI/UX Experience</u></a></li>
</ul></div>

