---
title: Step-by-Step Tutorial on Installing and Configuring Your License Server
date: 2024-10-02T18:24:06.777Z
updated: 2024-10-05T18:25:58.499Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094421/7443" target="_top" id="2094421">
  <img src="//a.impactradius-go.com/display-ad/7443-2094421" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094421/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Install the license server

The license server is part of Advanced Installer. You must [download](https://tools.techidaily.com/advancedinstaller/products/) and install the entire application on your server machine. Just copying the license server files over is not enough.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Launch the configuration wizard

Launch advinstlicenseserver.exe from the /bin/x86 subfolder of the Advanced Installer install directory.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The license server configuration process requires Administrator privileges.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959764/19272" target="_top" id="1959764">
  <img src="//a.impactradius-go.com/display-ad/19272-1959764" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959764/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Set a port number

The first setting is the license server port number. It will be used by client Advanced Installer instances to connect to the server.

Set an unused port number in the appropriate field and press \[Next \] button.

![License Server Configuration Wizard](https://cdn.advancedinstaller.com/img/dialog/license-server-config.png "License Server Configuration Wizard")  

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

### 5.2 The syntax for restarting the License Server is:

          advinstlicenseservercli.exe   /RestartLicenseServer  [-stoppreviousservice]
          

Copy

Parameters:

* **\-stoppreviousservice** \- Use this parameter if you have a License Server of an older version of Advanced Installer running on your machine. This will stop the service associated with the old version of the License Server and will start the new version.

### 5.3 The Syntax for uninstalling the License Server is:

          advinstlicenseservercli.exe  /UninstallLicenseServer
          

Copy

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943648/22993" target="_top" id="1943648">
  <img src="//a.impactradius-go.com/display-ad/22993-1943648" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Configure the license server page

Access the license server page by going tohttp://\[servername\]:\[port\]/admin in your web browser.

 Check the available registered licenses, add the computers that use them, and set the priority level of each computer. 

Check "Log license incidents" to enable logging the license server. The log is created in %ALLUSERSPROFILE%\\Caphyon\\License Server\\licenseincidents.json on your license server computer. 

![Register License Page](https://cdn.advancedinstaller.com/img/tutorial/license-server-ai/server-page.png "Register License Page")  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049369/7443" target="_top" id="2049369">
  <img src="//a.impactradius-go.com/display-ad/7443-2049369" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049369/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)FQDN (fully qualified domain name) is supported in Allow and Deny list. To obtain the FQDN of a computer use _ping -a <ip>_ command line.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130885/7443" target="_top" id="2130885">
  <img src="//a.impactradius-go.com/display-ad/7443-2130885" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130885/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)Using FQDN can delay license acquiring from the server even when the access list is not used. The FQDN resolve can be disabled from Admin panel (http://\[servername\]:\[port\]/admin) by uncheking _Resolve IP to fully qualified domain name (FQDN)_ option.

<!-- affiliate ads begin -->
<span id="1424533">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424533.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424533">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424533.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424533%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424533/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Register using the license server

With a running license server, you can now [register](https://tools.techidaily.com/advancedinstaller/products/) any Advanced Installer instance. Start Advanced Installer, access the “Help > Register” menu inside the application and select the “by using a license server” option.

![Register Advanced Installer](https://cdn.advancedinstaller.com/img/dialog/register-with-server.png "Register Advanced Installer")  

After specifying the license server host name and port number, you can click\[Next \] to finish the registration. Your current Advanced Installer instance will use one of the available license slots.

![License Server Address](https://cdn.advancedinstaller.com/img/dialog/license-server-access.png "License Server Address")  

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)Once an Advanced Installer copy is registered with a license server, it stays permanently registered. You don't need to re-register every time you edit a project.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049363/7443" target="_top" id="2049363">
  <img src="//a.impactradius-go.com/display-ad/7443-2049363" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049363/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-lab.techidaily.com/n-2024-fixing-the-no-thumbnail-issue-in-youtubes-shorts-videos/"><u>[New] In 2024, Fixing the No-Thumbnail Issue in YouTubes Shorts Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-overview-fb-video-dimension-categories/"><u>[Updated] 2024 Approved Overview FB Video Dimension Categories</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-leap-into-efficiency-with-quick-srt-to-txt-2023-guide/"><u>[Updated] Leap Into Efficiency with Quick SRT to TXT 2023 Guide</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/adopting-a-simple-yet-powerful-approach-to-advertising-content-for-2024/"><u>Adopting a Simple Yet Powerful Approach to Advertising Content for 2024</u></a></li>
<li><a href="https://fox-within.techidaily.com/comprehensive-service-offerings-overview/"><u>Comprehensive Service Offerings Overview</u></a></li>
<li><a href="https://fox-within.techidaily.com/detect-and-eradicate-cryptomining-malware-a-guide-to-protect-your-system/"><u>Detect & Eradicate Cryptomining Malware: A Guide to Protect Your System</u></a></li>
<li><a href="https://fox-within.techidaily.com/enhance-search-efficiency-with-advanced-prerequisite-configuration-options/"><u>Enhance Search Efficiency with Advanced Prerequisite Configuration Options</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-asus-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Asus Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://discover-dash.techidaily.com/jpeg-jpeg-movavi/"><u>JPEG 이미지를 제공하는 핸드널 비용 없음 JPEG 전환 - Movavi</u></a></li>
<li><a href="https://fox-within.techidaily.com/predesignated-storage-bin-layouts/"><u>Predesignated Storage Bin Layouts</u></a></li>
<li><a href="https://fox-within.techidaily.com/step-by-step-guide-accessing-documents-on-your-ios-device/"><u>Step-by-Step Guide: Accessing Documents on Your iOS Device</u></a></li>
</ul></div>

