---
title: Tailored Functionality Attributes
date: 2024-10-09T23:31:54.838Z
updated: 2024-10-11T03:24:53.875Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Tailored Functionality Attributes
thumbnail: https://thmb.techidaily.com/b2faccf55ba2f62eeda01fb2856eae6cf952310d841c8d8317d40b9a309e6901.jpg
---

## Tailored Functionality Attributes

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
         * [User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
         * [System Changes](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Search](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Properties Page](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Custom Actions](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Custom Action Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                                             * [Edit Action Properties Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                                             * [Edit Condition Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                                             * [Advanced Execution Scenarios Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Custom Actions List](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Table Editor](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patch Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Merge Module Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Updates Configuration Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Store App Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Modification Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Optional Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Mobile CAB Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio Extension Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Software Installer Wizards - Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Alternative to AdminStudio/Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Replace Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Migrating from Visual Studio Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Keyboard Shortcuts](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Shell Integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer PowerShell Automation Interfaces](https://tools.techidaily.com/advancedinstaller/products/)
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

## Custom Action Properties

See [Custom Actions List](https://tools.techidaily.com/advancedinstaller/products/) for a detailed description of each predefined custom action in Advanced Installer.

### Execution Time

* _Immediately_ \- the action will be executed immediately when it is found in the action sequence.
* _When the system is being modified (deferred)_ \- the action will be executed in order as part of the script built out of all the non-immediate actions. Custom Actions before InstallInitialize (Preparing action group) and after InstallFinalize (Finish Execution action group) can not be deferred and they must be Immediate. Note that deferred custom actions do not have access to installer's public properties.
* _During installation rollback_ \- execute the action only if something failed after this action and the installation is being rolled back.
* _After the system has been successfully modified (commit)_ \- the action will be executed in the Commit phase, after everything got installed successfully.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)On Windows Vista or above the custom actions which affect the system or require Administrator privileges should run without impersonation. For this you can simply check the **Run under the LocalSystem account with full privileges (no impersonation)** option.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Execution Options

* _Run under the LocalSystem account with full privileges (no impersonation)_ \- the custom action will be executed under the LocalSystem account with full privileges. This option is not available for custom actions which are executed Immediately.
* _Wait for custom action to finish before proceeding_ \- determines if the main installation thread waits for the custom action to complete. Windows Installer always waits for custom actions executed during rollback.
* _Fail installation if custom action returns an error_ \- determines if the custom action return code is checked by Windows Installer. For more information about custom action return codes, please see the [Custom Actions Page](https://tools.techidaily.com/advancedinstaller/products/).
* _Wait for return code at the end of the sequence_ \- determines if the current stage (Wizard Dialogs Stage or Install Execution Stage) will wait for the custom action return code after all actions have been executed. The actual return code is ignored by the installation.
* _Action Text..._ \- specify a text that will be displayed in the progress dialog box or written in the log file, when the custom action is being run. Use the button. The [Edit Action Properties Dialog](https://tools.techidaily.com/advancedinstaller/products/) will be displayed and will allow you to specify the text. Note that only deferred custom actions can set an Action Text.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)Custom actions that are _executable_ files must return a value of 0 for success. The installer interprets any other return value as failure.

### Execution Condition

* _Install_ \- Enable this option if you want your custom action to execute during installation of the package.  
   * _First Time Install_ \- The custom action will execute during installation of the package if no older version was found on the target computer.  
   * _Upgrade_ \- The custom action will execute during installation of the package only if an older version was found on the target computer.
* _Uninstall_ \- Enable this option if you want your custom action to execute during removal of the package.  
   * _Regular uninstall_ \- The custom action will execute during a complete uninstall of the application, not during an upgrade. This option is available only during "Install Execution Stage".  
   * _Replaced by a new version_ \- The custom action will execute during removal of the application trigerred by the installation of a new version. This option is available only during "Install Execution Stage".
* _Maintenance_ \- Enable this option if you want your custom action to execute during a repair or customization of the package.
* _Condition_ \- a boolean expression which must be true for the Custom Action to be executed. Edit this field using [Smart Condition Edit Control](https://tools.techidaily.com/advancedinstaller/products/).

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The _First Time Install_, _Upgrade_,_Regular uninstall_ and _Replaced by a new version_ options may not displayed by default, you should use the _Show upgrade options_ link to display them.

<!-- affiliate ads begin -->
<span id="1975648">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975648%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

* _Advanced execution scenarios_ \- this link displays the [Advanced Execution Scenarios Dialog](https://tools.techidaily.com/advancedinstaller/products/).

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2145009/26400" target="_top" id="2145009">
  <img src="//a.impactradius-go.com/display-ad/26400-2145009" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2145009/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### UI Triggering Events

A list with all the [events](https://tools.techidaily.com/advancedinstaller/products/) that trigger the custom action at install time. Each entry shows the name of the dialog on the first column, and on the second column, the name of the control from the dialog that triggers the event when the user interacts with it.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)This list is shown only for custom actions without sequence. If the list is empty then the custom action will never execute.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484">
  <img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Select an event and click **Go to selected event dialog** link button to configure it in the [Dialog Editor Page](https://tools.techidaily.com/advancedinstaller/products/).

## Topics

* [Edit Action Properties Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Specify a text which is displayed when a custom action runs.
* [Edit Condition Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
This dialog allows you to specify a conditional statement.
* [Advanced Execution Scenarios Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Use corner case execution options for your custom action.

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
<li><a href="https://remote-screen-capture.techidaily.com/updated-screenscape-innovations-an-unbiased-look-at-apeaksoft-2023-edition/"><u>[Updated] Screenscape Innovations An Unbiased Look at Apeaksoft, 2023 Edition</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-unlocked-mac-capture-tool-no-cost/"><u>[Updated] Unlocked Mac Capture Tool - No Cost</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-step-by-step-process-of-setting-up-your-logitech-webcam-for-video/"><u>2024 Approved Step-by-Step Process of Setting Up Your Logitech Webcam for Video</u></a></li>
<li><a href="https://fox-within.techidaily.com/3-proven-techniques-for-efficiently-recovering-deleted-images/"><u>3 Proven Techniques for Efficiently Recovering Deleted Images</u></a></li>
<li><a href="https://fox-within.techidaily.com/automatic-app-closure-feature-update/"><u>Automatic App Closure Feature Update</u></a></li>
<li><a href="https://fox-within.techidaily.com/convert-mov-videos-to-wmv-quickly-enjoy-a-hassle-free-free-file-conversion-tool/"><u>Convert MOV Videos to WMV Quickly - Enjoy a Hassle-Free, FREE File Conversion Tool!</u></a></li>
<li><a href="https://fox-within.techidaily.com/custom-actions-component-enhance-your-app-with-tailored-functionality/"><u>Custom Actions Component: Enhance Your App with Tailored Functionality</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1726027285947-dvd/"><u>DVDの新品再生に困る方のため、安全かつ簡単な解決法</u></a></li>
<li><a href="https://fox-within.techidaily.com/effective-strategies-to-eliminate-the-windows-security-alert-phishing-scheme/"><u>Effective Strategies to Eliminate the Windows Security Alert Phishing Scheme</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-mov-movies-on-galaxy-m34-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>Failed to play MOV movies on Galaxy M34 5G</u></a></li>
<li><a href="https://app-tips.techidaily.com/forgetting-passwords-fuels-growing-demand-for-biometric-security-solutions/"><u>Forgetting Passwords Fuels Growing Demand for Biometric Security Solutions</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-get-ready-to-be-amazed-the-best-4k-video-clips/"><u>In 2024, Get Ready to Be Amazed The Best 4K Video Clips</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Poco M6 5G | Dr.fone</u></a></li>
<li><a href="https://fox-within.techidaily.com/leading-no-cost-video-editor-apps-seamless-file-conversions-anytime-anywhere/"><u>Leading No-Cost Video Editor Apps: Seamless File Conversions Anytime, Anywhere</u></a></li>
<li><a href="https://fox-within.techidaily.com/navigating-system-modification-insights-into-the-page-group-category/"><u>Navigating System Modification: Insights Into the Page Group Category</u></a></li>
<li><a href="https://fox-within.techidaily.com/quick-and-effective-techniques-for-modifying-pdf-text-content-with-adobes-tools/"><u>Quick and Effective Techniques for Modifying PDF Text Content with Adobe's Tools</u></a></li>
<li><a href="https://fox-that.techidaily.com/speed-hacks-quickly-enhance-safari-performance-on-iphone-heres-how/"><u>Speed Hacks: Quickly Enhance Safari Performance on iPhone Here's How</u></a></li>
<li><a href="https://fox-within.techidaily.com/step-by-step-tutorial-on-installing-and-configuring-your-license-server/"><u>Step-by-Step Tutorial on Installing and Configuring Your License Server</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unlocking-ultra-hd-viewing-with-tcls-budget-friendly-50s425-50-inch-roku-tv-a-thorough-review/"><u>Unlocking Ultra HD Viewing with TCL's Budget-Friendly 50S425 50-Inch Roku TV - A Thorough Review!</u></a></li>
</ul></div>

