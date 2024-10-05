---
title: Tailored Functionality Attributes
date: 2024-10-04T18:42:06.862Z
updated: 2024-10-05T19:31:16.146Z
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
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Execution Options

* _Run under the LocalSystem account with full privileges (no impersonation)_ \- the custom action will be executed under the LocalSystem account with full privileges. This option is not available for custom actions which are executed Immediately.
* _Wait for custom action to finish before proceeding_ \- determines if the main installation thread waits for the custom action to complete. Windows Installer always waits for custom actions executed during rollback.
* _Fail installation if custom action returns an error_ \- determines if the custom action return code is checked by Windows Installer. For more information about custom action return codes, please see the [Custom Actions Page](https://tools.techidaily.com/advancedinstaller/products/).
* _Wait for return code at the end of the sequence_ \- determines if the current stage (Wizard Dialogs Stage or Install Execution Stage) will wait for the custom action return code after all actions have been executed. The actual return code is ignored by the installation.
* _Action Text..._ \- specify a text that will be displayed in the progress dialog box or written in the log file, when the custom action is being run. Use the button. The [Edit Action Properties Dialog](https://tools.techidaily.com/advancedinstaller/products/) will be displayed and will allow you to specify the text. Note that only deferred custom actions can set an Action Text.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)Custom actions that are _executable_ files must return a value of 0 for success. The installer interprets any other return value as failure.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052059/7443" target="_top" id="2052059">
  <img src="//a.impactradius-go.com/display-ad/7443-2052059" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052059/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

* _Advanced execution scenarios_ \- this link displays the [Advanced Execution Scenarios Dialog](https://tools.techidaily.com/advancedinstaller/products/).

### UI Triggering Events

A list with all the [events](https://tools.techidaily.com/advancedinstaller/products/) that trigger the custom action at install time. Each entry shows the name of the dialog on the first column, and on the second column, the name of the control from the dialog that triggers the event when the user interacts with it.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)This list is shown only for custom actions without sequence. If the list is empty then the custom action will never execute.

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
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-pair-phonetablet-and-computer-calendars-for-seamless-zoom-scheduling/"><u>[Updated] In 2024, Pair Phone/Tablet & Computer Calendars for Seamless Zoom Scheduling</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-untouched-live-visual-recorders-for-2024/"><u>[Updated] Untouched Live Visual Recorders for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-hook-creation-tool-for-online-titles/"><u>2024 Approved Ultimate Hook-Creation Tool for Online Titles</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/combining-security-effortlessly-an-insightful-overview-of-the-arlo-video-doorbell-with-built-in-alarm-features/"><u>Combining Security Effortlessly: An Insightful Overview of the Arlo Video Doorbell with Built-In Alarm Features</u></a></li>
<li><a href="https://youtube-web.techidaily.com/led-insights-into-youtubes-perfected-aspect-ratios/"><u>Detailed Insights Into YouTube's Perfected Aspect Ratios</u></a></li>
<li><a href="https://fox-within.techidaily.com/discovering-the-hidden-places-of-chrome-browser-plugins-and-extensions/"><u>Discovering the Hidden Places of Chrome Browser Plugins and Extensions</u></a></li>
<li><a href="https://fox-within.techidaily.com/easy-methods-to-duplicate-content-from-your-xiaomi-11-onto-your-pc/"><u>Easy Methods to Duplicate Content From Your Xiaomi 지패11 Onto Your PC</u></a></li>
<li><a href="https://extra-resources.techidaily.com/eliminating-barriers-accessing-fcp-at-no-charge/"><u>Eliminating Barriers Accessing FCP at No Charge</u></a></li>
<li><a href="https://fox-within.techidaily.com/engage-and-configure-user-friendly-interface-for-quick-setup-processes/"><u>Engage & Configure: User-Friendly Interface for Quick Setup Processes</u></a></li>
<li><a href="https://fox-within.techidaily.com/expert-tips-on-speedy-production-of-quicktime-audio-captures/"><u>Expert Tips on Speedy Production of QuickTime Audio Captures</u></a></li>
<li><a href="https://win-able.techidaily.com/fixing-ghost-recon-breakpoint-resolving-game-crashes-fast-and-simple/"><u>Fixing Ghost Recon Breakpoint: Resolving Game Crashes Fast and Simple</u></a></li>
<li><a href="https://fox-within.techidaily.com/innovative-dialogue-formatting-strategies-in-writing/"><u>Innovative Dialogue Formatting Strategies in Writing</u></a></li>
<li><a href="https://fox-within.techidaily.com/malwarefox-unveiled-a-comprehensive-guide-on-spyware-and-malware-distinctions-for-optimal-protection/"><u>MalwareFox Unveiled: A Comprehensive Guide on Spyware and Malware Distinctions for Optimal Protection</u></a></li>
<li><a href="https://fox-within.techidaily.com/real-time-notification-updates-never-miss-out-on-important-information/"><u>Real-Time Notification Updates - Never Miss Out on Important Information!</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/the-essential-list-of-macs-top-snipping-apps/"><u>The Essential List of Mac's Top Snipping Apps</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-beginners-guide-to-the-5-highest-ranking-vlogging-cameras-on-the-market-today/"><u>The Ultimate Beginners' Guide to the 5 Highest-Ranking Vlogging Cameras on the Market Today</u></a></li>
<li><a href="https://fox-within.techidaily.com/ultimate-file-deletion-tool-effortless-cleanup-with-iremovefiles/"><u>Ultimate File Deletion Tool: Effortless Cleanup with IRemoveFiles</u></a></li>
<li><a href="https://fox-within.techidaily.com/ultimate-guide-to-setting-up-alarms-on-android-phones-and-tablets/"><u>Ultimate Guide to Setting Up Alarms on Android Phones and Tablets</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/unmatched-recording-alternatives-for-modern-gaming-enthusiasts-for-2024/"><u>Unmatched Recording Alternatives for Modern Gaming Enthusiasts for 2024</u></a></li>
</ul></div>

