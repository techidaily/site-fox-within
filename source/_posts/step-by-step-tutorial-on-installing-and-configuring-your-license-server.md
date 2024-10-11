---
title: Step-by-Step Tutorial on Installing and Configuring Your License Server
date: 2024-10-09T23:53:06.375Z
updated: 2024-10-10T21:54:57.038Z
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Install the license server

The license server is part of Advanced Installer. You must [download](https://tools.techidaily.com/advancedinstaller/products/) and install the entire application on your server machine. Just copying the license server files over is not enough.

## 2\. Launch the configuration wizard

Launch advinstlicenseserver.exe from the /bin/x86 subfolder of the Advanced Installer install directory.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The license server configuration process requires Administrator privileges.

<!-- affiliate ads begin -->
<span id="1531879">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531879.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531879">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531879.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531879%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531879/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Set a port number

The first setting is the license server port number. It will be used by client Advanced Installer instances to connect to the server.

Set an unused port number in the appropriate field and press \[Next \] button.

![License Server Configuration Wizard](https://cdn.advancedinstaller.com/img/dialog/license-server-config.png "License Server Configuration Wizard")  

The License Server Wizard will automatically check if the specified port is open. It will also configure the Windows Firewall to allow access to this port. If the port is blocked by an external firewall, an error message will be shown.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105869/7443" target="_top" id="2105869">
  <img src="//a.impactradius-go.com/display-ad/7443-2105869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Specify your license key

If your server machine has an active Internet connection, you can enter your_License Key_ and press \[Next \]. The wizard will automatically download the license file and finish the configuration.

If no Internet connection is available, you can use the “I would like to register by email” option. We will require your _Computer ID_ along with the License Key to generate and return you a license file.

![Register License Server](https://cdn.advancedinstaller.com/img/dialog/license-server-key.png "Register License Server")  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135375/19272" target="_top" id="2135375">
  <img src="//a.impactradius-go.com/display-ad/19272-2135375" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135375/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Configuring the License Server from Command Line

The License Server could be also configured using Command Line, by calling our tool**advinstlicenseservercli.exe** from the /bin/x86 subfolder of the Advanced Installer install directory.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)**advinstlicenseservercli.exe** requires Administrator privileges so it must be run from an Administrator Command Prompt

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880940/19272" target="_top" id="1880940">
  <img src="//a.impactradius-go.com/display-ad/19272-1880940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880940/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

## 6\. Configure the license server page

Access the license server page by going tohttp://\[servername\]:\[port\]/admin in your web browser.

 Check the available registered licenses, add the computers that use them, and set the priority level of each computer. 

Check "Log license incidents" to enable logging the license server. The log is created in %ALLUSERSPROFILE%\\Caphyon\\License Server\\licenseincidents.json on your license server computer. 

![Register License Page](https://cdn.advancedinstaller.com/img/tutorial/license-server-ai/server-page.png "Register License Page")  

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)If one of your computers is a Build Server, or you just want to give priority to a certain computer in case of a simultaneous request to use the license. you could set its**Priority Level** to _Build Server_.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)Using FQDN can delay license acquiring from the server even when the access list is not used. The FQDN resolve can be disabled from Admin panel (http://\[servername\]:\[port\]/admin) by uncheking _Resolve IP to fully qualified domain name (FQDN)_ option.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136614/26400" target="_top" id="2136614">
  <img src="//a.impactradius-go.com/display-ad/26400-2136614" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136614/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Register using the license server

With a running license server, you can now [register](https://tools.techidaily.com/advancedinstaller/products/) any Advanced Installer instance. Start Advanced Installer, access the “Help > Register” menu inside the application and select the “by using a license server” option.

![Register Advanced Installer](https://cdn.advancedinstaller.com/img/dialog/register-with-server.png "Register Advanced Installer")  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

After specifying the license server host name and port number, you can click\[Next \] to finish the registration. Your current Advanced Installer instance will use one of the available license slots.

![License Server Address](https://cdn.advancedinstaller.com/img/dialog/license-server-access.png "License Server Address")  

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)Once an Advanced Installer copy is registered with a license server, it stays permanently registered. You don't need to re-register every time you edit a project.

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
<li><a href="https://screen-video-capture.techidaily.com/updated-perfect-pc-video-grabbers-a-comprehensible-selection/"><u>[Updated] Perfect PC Video Grabbers A Comprehensible Selection</u></a></li>
<li><a href="https://fox-within.techidaily.com/3-proven-techniques-for-efficiently-recovering-deleted-images/"><u>3 Proven Techniques for Efficiently Recovering Deleted Images</u></a></li>
<li><a href="https://fox-within.techidaily.com/automatic-app-closure-feature-update/"><u>Automatic App Closure Feature Update</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-practices-for-a-robust-spotify-ad-campaign/"><u>Best Practices for a Robust Spotify Ad Campaign</u></a></li>
<li><a href="https://extra-tips.techidaily.com/boost-video-velocity-top-android-helpers/"><u>Boost Video Velocity - Top Android Helpers</u></a></li>
<li><a href="https://fox-within.techidaily.com/convert-mov-videos-to-wmv-quickly-enjoy-a-hassle-free-free-file-conversion-tool/"><u>Convert MOV Videos to WMV Quickly - Enjoy a Hassle-Free, FREE File Conversion Tool!</u></a></li>
<li><a href="https://fox-within.techidaily.com/custom-actions-component-enhance-your-app-with-tailored-functionality/"><u>Custom Actions Component: Enhance Your App with Tailored Functionality</u></a></li>
<li><a href="https://fox-within.techidaily.com/effective-strategies-to-eliminate-the-windows-security-alert-phishing-scheme/"><u>Effective Strategies to Eliminate the Windows Security Alert Phishing Scheme</u></a></li>
<li><a href="https://extra-information.techidaily.com/essential-techniques-for-erasing-background-elements-in-figma/"><u>Essential Techniques for Erasing Background Elements in Figma</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-honor-x7b-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Honor X7b? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Samsung Galaxy F04? | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/rating-moving-images-into-non-paid-content-for-2024/"><u>Integrating Moving Images Into Non-Paid Content for 2024</u></a></li>
<li><a href="https://fox-within.techidaily.com/leading-no-cost-video-editor-apps-seamless-file-conversions-anytime-anywhere/"><u>Leading No-Cost Video Editor Apps: Seamless File Conversions Anytime, Anywhere</u></a></li>
<li><a href="https://fox-within.techidaily.com/navigating-system-modification-insights-into-the-page-group-category/"><u>Navigating System Modification: Insights Into the Page Group Category</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/prophotomaster-the-ai-enhanced-editing-edge-for-2024/"><u>ProPhotoMaster The AI-Enhanced Editing Edge for 2024</u></a></li>
<li><a href="https://fox-within.techidaily.com/quick-and-effective-techniques-for-modifying-pdf-text-content-with-adobes-tools/"><u>Quick and Effective Techniques for Modifying PDF Text Content with Adobe's Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/shrouded-screen-images-techniques-for-redacting-info/"><u>Shrouded Screen Images Techniques for Redacting Info</u></a></li>
<li><a href="https://win11.techidaily.com/the-developers-playbook-mastering-dev-drive-in-windows-11/"><u>The Developer's Playbook: Mastering Dev Drive in Windows 11</u></a></li>
<li><a href="https://fox-within.techidaily.com/understanding-user-share-settings-the-essential-guide/"><u>Understanding User Share Settings: The Essential Guide</u></a></li>
</ul></div>

