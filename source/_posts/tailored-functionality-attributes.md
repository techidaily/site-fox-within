---
title: Tailored Functionality Attributes
date: 2024-09-24T02:30:13.651Z
updated: 2024-09-29T20:26:17.504Z
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

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014857/22899" target="_top" id="2014857">
  <img src="//a.impactradius-go.com/display-ad/22899-2014857" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014857/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Execution Time

* _Immediately_ \- the action will be executed immediately when it is found in the action sequence.
* _When the system is being modified (deferred)_ \- the action will be executed in order as part of the script built out of all the non-immediate actions. Custom Actions before InstallInitialize (Preparing action group) and after InstallFinalize (Finish Execution action group) can not be deferred and they must be Immediate. Note that deferred custom actions do not have access to installer's public properties.
* _During installation rollback_ \- execute the action only if something failed after this action and the installation is being rolled back.
* _After the system has been successfully modified (commit)_ \- the action will be executed in the Commit phase, after everything got installed successfully.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)On Windows Vista or above the custom actions which affect the system or require Administrator privileges should run without impersonation. For this you can simply check the **Run under the LocalSystem account with full privileges (no impersonation)** option.

### Execution Options

* _Run under the LocalSystem account with full privileges (no impersonation)_ \- the custom action will be executed under the LocalSystem account with full privileges. This option is not available for custom actions which are executed Immediately.
* _Wait for custom action to finish before proceeding_ \- determines if the main installation thread waits for the custom action to complete. Windows Installer always waits for custom actions executed during rollback.
* _Fail installation if custom action returns an error_ \- determines if the custom action return code is checked by Windows Installer. For more information about custom action return codes, please see the [Custom Actions Page](https://tools.techidaily.com/advancedinstaller/products/).
* _Wait for return code at the end of the sequence_ \- determines if the current stage (Wizard Dialogs Stage or Install Execution Stage) will wait for the custom action return code after all actions have been executed. The actual return code is ignored by the installation.
* _Action Text..._ \- specify a text that will be displayed in the progress dialog box or written in the log file, when the custom action is being run. Use the button. The [Edit Action Properties Dialog](https://tools.techidaily.com/advancedinstaller/products/) will be displayed and will allow you to specify the text. Note that only deferred custom actions can set an Action Text.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)Custom actions that are _executable_ files must return a value of 0 for success. The installer interprets any other return value as failure.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186802/12108" target="_top" id="1186802">
  <img src="//a.impactradius-go.com/display-ad/12108-1186802" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186802/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139116/17108" target="_top" id="2139116">
  <img src="//a.impactradius-go.com/display-ad/17108-2139116" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139116/17108" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130889/7443" target="_top" id="2130889">
  <img src="//a.impactradius-go.com/display-ad/7443-2130889" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-data.techidaily.com/024-approved-audiovisual-authority-the-finest-computers-for-professional-edits/"><u>[New] 2024 Approved Audiovisual Authority The Finest Computers for Professional Edits</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unveiling-the-art-of-sideways-iphone-photography/"><u>[New] Unveiling the Art of Sideways iPhone Photography</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-6-affordable-high-definition-projectors/"><u>Best 6 Affordable High-Definition Projectors</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-test-drive-of-the-newly-released-samsung-chromebook-galaxy-gen2/"><u>Comprehensive Test Drive of the Newly Released Samsung Chromebook (Galaxy Gen2)</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/discover-unlimited-stories-free-extensions-and-mobile-marvels-for-2024/"><u>Discover Unlimited Stories – FREE Extensions & Mobile Marvels for 2024</u></a></li>
<li><a href="https://fox-within.techidaily.com/extract-high-definition-audio-and-video-from-youtube-watch-history-for-pcs-and-macs-in-mp4-or-mp3-format/"><u>Extract High Definition Audio and Video From YouTube Watch History for PCs and Macs in MP4 or MP3 Format</u></a></li>
<li><a href="https://fox-within.techidaily.com/get-premium-quality-youporn-content-for-offline-viewing-convert-and-download-as-mp4-avi-wmv-files-easily/"><u>Get Premium Quality YouPorn Content for Offline Viewing – Convert and Download as MP4, AVI, WMV Files Easily!</u></a></li>
<li><a href="https://fox-within.techidaily.com/get-premium-raaga-tunes-in-mp3-wav-or-aac-format-with-easy-downloading-options/"><u>Get Premium Raaga Tunes in MP3, WAV or AAC Format with Easy Downloading Options</u></a></li>
<li><a href="https://fox-within.techidaily.com/get-your-favorite-mls-soccer-media-with-one-click-download-clips-songs-and-more/"><u>Get Your Favorite MLS Soccer Media with One-Click Download: Clips, Songs, and More!</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-error-1015-while-restoring-iphone-6-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to fix error 1015 while restoring iPhone 6 | Stellar</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-vivo-y27s-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Vivo Y27s to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://fox-within.techidaily.com/playfm-music-conversion-guide-download-mp3-aac-wav-files-now/"><u>Play.FM Music Conversion Guide - Download MP3, AAC, WAV Files Now</u></a></li>
<li><a href="https://fox-within.techidaily.com/step-by-step-guide-converting-rooster-teeth-shows-into-mp4-and-avi-formats/"><u>Step-by-Step Guide: Converting Rooster Teeth Shows Into MP4 & AVI Formats</u></a></li>
<li><a href="https://fox-within.techidaily.com/step-by-step-guide-converting-vidlii-downloads-into-multiple-video-formats-like-mp4-avi-and-mov/"><u>Step-by-Step Guide: Converting VidLii Downloads Into Multiple Video Formats Like MP4, AVI & MOV</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722969477841-step-by-step-guide-updating-graphics-and-chipset-drivers-on-your-dell-xps-15/"><u>Step-by-Step Guide: Updating Graphics and Chipset Drivers on Your Dell XPS 15</u></a></li>
<li><a href="https://fox-within.techidaily.com/step-by-step-tutorial-downloading-and-saving-vrt-nu-live-shows-as-high-quality-video-files-on-windows-or-macos/"><u>Step-by-Step Tutorial: Downloading and Saving VRT NU Live Shows as High-Quality Video Files on Windows or macOS</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-fixes-for-nonfunctioning-chromecast-sound-issues/"><u>The Ultimate Fixes for Nonfunctioning Chromecast Sound Issues</u></a></li>
</ul></div>

