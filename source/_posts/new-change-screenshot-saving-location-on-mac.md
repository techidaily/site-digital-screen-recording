---
title: "[New] Change Screenshot Saving Location on Mac"
date: 2024-07-24T03:32:07.843Z
updated: 2024-07-25T03:32:07.843Z
tags: 
  - screen-recording
  - ai video
  - ai audio
categories: 
  - ai
  - screen
description: "This Article Describes [New] Change Screenshot Saving Location on Mac"
excerpt: "This Article Describes [New] Change Screenshot Saving Location on Mac"
keywords: "\"Save Screen Shot Locally (Mac),Change Screenshot Path (Mac),Mac Screenshots Localize,Set Default Screenshot Save (Mac),Alter Screenshot Folder (Mac),Mac: Modify Image Location,Redirect Mac Screenshots (Change Loc.)\""
thumbnail: https://thmb.techidaily.com/ef69c6cfc05813b51fd415fbeca882846dc473b99199e876bd020898984fe0d1.png
---

## Change Screenshot Saving Location on Mac

# How to Change the Destination Where Screenshots are Saved on your Mac

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![author avatar](https://images.wondershare.com/filmora/article-images/max-wales-author.jpg)

##### Max Wales

 Mar 27, 2024• Proven solutions

Whenever you take a screenshot on a Mac computer, a file is saved to the desktop by default. Most Mac users never have the need to change this setting, because they can always move the file to a folder where they want to store it. On the other hand, creating a lot of screenshots every day can make a chaos on your desktop. Luckily changing the destination where your screenshots are saved is a simple process that lets you decide where your images will be stored.

Here's how you can change the location where the screenshots you take using the keyboard shortcuts will be saved.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Filmora logo](https://images.wondershare.com/filmora/logo_icon/wondershare-filmora-logo-horizontal.png) ![filmora product interface](https://images.wondershare.com/filmora/images/common/filmora-product-banner.png)

### The All-in-One Screen Recorder & Video Editor

* Record desktop screen, voiceover, and webcam simultaneously
* Edit recorded clips quickly with a wide range of professional tools
* Built-in plentiful templates and effects
* Export to MP4, MOV, MKV, GIF and multiple formats

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For Win 7 or later (64-bit)

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For macOS 10.12 or later

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![secure download](https://static.wondershare.com/images-filmora/images/common/securety.svg)Secure Download

## Part 1: How to Save Screenshots to a Specific Folder on Mac

Changing the folder where you store your screenshots is not an irreversible process, which means that you can reset the destination where the files are saved to Desktop at any point. Do not delete the new folder, because your Mac may not be able to take screenshots, afterward. The process described below is the only way you can delete a folder or add a new destination for your screenshots, and failing to comply with it may cause your Mac to malfunction.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
![ Mac Screenshots](https://images.wondershare.com/filmora/article-images/mac-screenshot-terminal.jpg)

Create a new folder on the desired location on your hard drive, and then launch Terminal, by typing Terminal in the Search Box and clicking on its icon. Once the app is open, you should insert the following command into the Terminal window:

**defaults write com.apple.screencapture location**

Then enter a space at the end after 'location'.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
![ Mac Screenshots](https://images.wondershare.com/filmora/article-images/mac-screenshot-terminal-settings.jpg)

The next step is to add the new location at which screenshots will be saved and you can do this by simply dragging the folder you created into Terminal and adding it at the end of the command you just entered. A path is created and the command line should now contain the folder's unique location and it should look like this:

**defaults write com.apple.screencapture location /Users/username/Screenshots**

To execute the command you have to press Enter. After Terminal finishes running the command, its window will appear on the screen again. You should proceed to confirm the changes you've just made by resetting the User Interface on your computer. In order to do so, you'll have to insert this command below the one you previously entered：

**killall SystemUIServer**

Hit Enter once more to confirm the changes and run the new command. Close Terminal app by clicking on the Terminal menu and selecting the Quick Terminal option. The default location where the screenshots are saved on your Mac is now changed and every time you take a screenshot using the Command + Shift + 3 shortcut the file will be saved at the new location. If for whatever reason you want to make the Desktop once again the destination where the screenshots on your computer will be saved here's how you can do it.

## Part 2: How to Change the Screenshot Save Location Back to Desktop

The process of changing the default screenshot save location back to Desktop is nearly identical to the process we just described. You just have to open the Terminal app and insert the following command into the prompt.

**defaults write com.apple.screen capture location /Users/Username/Desktop/**

Make sure that your username is properly written, and then press Enter to run the command. Now you only have to reset the UI so it can recognize the changes you've made, and you can do it by inserting the **killall SystemUIServer** command into the Terminal window and pressing Enter to execute it.

Don't forget that deleting the folder you use as a default location for storing screenshots should only be done using the process we just described in the Terminal application, since all other methods may cause unnecessary trouble.

![author avatar](https://images.wondershare.com/filmora/article-images/max-wales-author.jpg)

Max Wales

Max Wales is a writer and a lover of all things video.

Follow @Max Wales

##### Max Wales

 Mar 27, 2024• Proven solutions

Whenever you take a screenshot on a Mac computer, a file is saved to the desktop by default. Most Mac users never have the need to change this setting, because they can always move the file to a folder where they want to store it. On the other hand, creating a lot of screenshots every day can make a chaos on your desktop. Luckily changing the destination where your screenshots are saved is a simple process that lets you decide where your images will be stored.

Here's how you can change the location where the screenshots you take using the keyboard shortcuts will be saved.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
![Filmora logo](https://images.wondershare.com/filmora/logo_icon/wondershare-filmora-logo-horizontal.png) ![filmora product interface](https://images.wondershare.com/filmora/images/common/filmora-product-banner.png)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### The All-in-One Screen Recorder & Video Editor

* Record desktop screen, voiceover, and webcam simultaneously
* Edit recorded clips quickly with a wide range of professional tools
* Built-in plentiful templates and effects
* Export to MP4, MOV, MKV, GIF and multiple formats

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For Win 7 or later (64-bit)

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For macOS 10.12 or later

![secure download](https://static.wondershare.com/images-filmora/images/common/securety.svg)Secure Download

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Part 1: How to Save Screenshots to a Specific Folder on Mac

Changing the folder where you store your screenshots is not an irreversible process, which means that you can reset the destination where the files are saved to Desktop at any point. Do not delete the new folder, because your Mac may not be able to take screenshots, afterward. The process described below is the only way you can delete a folder or add a new destination for your screenshots, and failing to comply with it may cause your Mac to malfunction.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![ Mac Screenshots](https://images.wondershare.com/filmora/article-images/mac-screenshot-terminal.jpg)

Create a new folder on the desired location on your hard drive, and then launch Terminal, by typing Terminal in the Search Box and clicking on its icon. Once the app is open, you should insert the following command into the Terminal window:

**defaults write com.apple.screencapture location**

Then enter a space at the end after 'location'.

![ Mac Screenshots](https://images.wondershare.com/filmora/article-images/mac-screenshot-terminal-settings.jpg)

The next step is to add the new location at which screenshots will be saved and you can do this by simply dragging the folder you created into Terminal and adding it at the end of the command you just entered. A path is created and the command line should now contain the folder's unique location and it should look like this:

**defaults write com.apple.screencapture location /Users/username/Screenshots**

To execute the command you have to press Enter. After Terminal finishes running the command, its window will appear on the screen again. You should proceed to confirm the changes you've just made by resetting the User Interface on your computer. In order to do so, you'll have to insert this command below the one you previously entered：

**killall SystemUIServer**

Hit Enter once more to confirm the changes and run the new command. Close Terminal app by clicking on the Terminal menu and selecting the Quick Terminal option. The default location where the screenshots are saved on your Mac is now changed and every time you take a screenshot using the Command + Shift + 3 shortcut the file will be saved at the new location. If for whatever reason you want to make the Desktop once again the destination where the screenshots on your computer will be saved here's how you can do it.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Part 2: How to Change the Screenshot Save Location Back to Desktop

The process of changing the default screenshot save location back to Desktop is nearly identical to the process we just described. You just have to open the Terminal app and insert the following command into the prompt.

**defaults write com.apple.screen capture location /Users/Username/Desktop/**

Make sure that your username is properly written, and then press Enter to run the command. Now you only have to reset the UI so it can recognize the changes you've made, and you can do it by inserting the **killall SystemUIServer** command into the Terminal window and pressing Enter to execute it.

Don't forget that deleting the folder you use as a default location for storing screenshots should only be done using the process we just described in the Terminal application, since all other methods may cause unnecessary trouble.

![author avatar](https://images.wondershare.com/filmora/article-images/max-wales-author.jpg)

Max Wales

Max Wales is a writer and a lover of all things video.

Follow @Max Wales

##### Max Wales

 Mar 27, 2024• Proven solutions

Whenever you take a screenshot on a Mac computer, a file is saved to the desktop by default. Most Mac users never have the need to change this setting, because they can always move the file to a folder where they want to store it. On the other hand, creating a lot of screenshots every day can make a chaos on your desktop. Luckily changing the destination where your screenshots are saved is a simple process that lets you decide where your images will be stored.

Here's how you can change the location where the screenshots you take using the keyboard shortcuts will be saved.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Filmora logo](https://images.wondershare.com/filmora/logo_icon/wondershare-filmora-logo-horizontal.png) ![filmora product interface](https://images.wondershare.com/filmora/images/common/filmora-product-banner.png)

### The All-in-One Screen Recorder & Video Editor

* Record desktop screen, voiceover, and webcam simultaneously
* Edit recorded clips quickly with a wide range of professional tools
* Built-in plentiful templates and effects
* Export to MP4, MOV, MKV, GIF and multiple formats

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For Win 7 or later (64-bit)

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For macOS 10.12 or later

![secure download](https://static.wondershare.com/images-filmora/images/common/securety.svg)Secure Download

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Part 1: How to Save Screenshots to a Specific Folder on Mac

Changing the folder where you store your screenshots is not an irreversible process, which means that you can reset the destination where the files are saved to Desktop at any point. Do not delete the new folder, because your Mac may not be able to take screenshots, afterward. The process described below is the only way you can delete a folder or add a new destination for your screenshots, and failing to comply with it may cause your Mac to malfunction.

![ Mac Screenshots](https://images.wondershare.com/filmora/article-images/mac-screenshot-terminal.jpg)

Create a new folder on the desired location on your hard drive, and then launch Terminal, by typing Terminal in the Search Box and clicking on its icon. Once the app is open, you should insert the following command into the Terminal window:

**defaults write com.apple.screencapture location**

Then enter a space at the end after 'location'.

![ Mac Screenshots](https://images.wondershare.com/filmora/article-images/mac-screenshot-terminal-settings.jpg)

The next step is to add the new location at which screenshots will be saved and you can do this by simply dragging the folder you created into Terminal and adding it at the end of the command you just entered. A path is created and the command line should now contain the folder's unique location and it should look like this:

**defaults write com.apple.screencapture location /Users/username/Screenshots**

To execute the command you have to press Enter. After Terminal finishes running the command, its window will appear on the screen again. You should proceed to confirm the changes you've just made by resetting the User Interface on your computer. In order to do so, you'll have to insert this command below the one you previously entered：

**killall SystemUIServer**

Hit Enter once more to confirm the changes and run the new command. Close Terminal app by clicking on the Terminal menu and selecting the Quick Terminal option. The default location where the screenshots are saved on your Mac is now changed and every time you take a screenshot using the Command + Shift + 3 shortcut the file will be saved at the new location. If for whatever reason you want to make the Desktop once again the destination where the screenshots on your computer will be saved here's how you can do it.

## Part 2: How to Change the Screenshot Save Location Back to Desktop

The process of changing the default screenshot save location back to Desktop is nearly identical to the process we just described. You just have to open the Terminal app and insert the following command into the prompt.

**defaults write com.apple.screen capture location /Users/Username/Desktop/**

Make sure that your username is properly written, and then press Enter to run the command. Now you only have to reset the UI so it can recognize the changes you've made, and you can do it by inserting the **killall SystemUIServer** command into the Terminal window and pressing Enter to execute it.

Don't forget that deleting the folder you use as a default location for storing screenshots should only be done using the process we just described in the Terminal application, since all other methods may cause unnecessary trouble.

![author avatar](https://images.wondershare.com/filmora/article-images/max-wales-author.jpg)

Max Wales

Max Wales is a writer and a lover of all things video.

Follow @Max Wales

##### Max Wales

 Mar 27, 2024• Proven solutions

Whenever you take a screenshot on a Mac computer, a file is saved to the desktop by default. Most Mac users never have the need to change this setting, because they can always move the file to a folder where they want to store it. On the other hand, creating a lot of screenshots every day can make a chaos on your desktop. Luckily changing the destination where your screenshots are saved is a simple process that lets you decide where your images will be stored.

Here's how you can change the location where the screenshots you take using the keyboard shortcuts will be saved.

![Filmora logo](https://images.wondershare.com/filmora/logo_icon/wondershare-filmora-logo-horizontal.png) ![filmora product interface](https://images.wondershare.com/filmora/images/common/filmora-product-banner.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The All-in-One Screen Recorder & Video Editor

* Record desktop screen, voiceover, and webcam simultaneously
* Edit recorded clips quickly with a wide range of professional tools
* Built-in plentiful templates and effects
* Export to MP4, MOV, MKV, GIF and multiple formats

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For Win 7 or later (64-bit)

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For macOS 10.12 or later

![secure download](https://static.wondershare.com/images-filmora/images/common/securety.svg)Secure Download

## Part 1: How to Save Screenshots to a Specific Folder on Mac

Changing the folder where you store your screenshots is not an irreversible process, which means that you can reset the destination where the files are saved to Desktop at any point. Do not delete the new folder, because your Mac may not be able to take screenshots, afterward. The process described below is the only way you can delete a folder or add a new destination for your screenshots, and failing to comply with it may cause your Mac to malfunction.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
![ Mac Screenshots](https://images.wondershare.com/filmora/article-images/mac-screenshot-terminal.jpg)

Create a new folder on the desired location on your hard drive, and then launch Terminal, by typing Terminal in the Search Box and clicking on its icon. Once the app is open, you should insert the following command into the Terminal window:

**defaults write com.apple.screencapture location**

Then enter a space at the end after 'location'.

![ Mac Screenshots](https://images.wondershare.com/filmora/article-images/mac-screenshot-terminal-settings.jpg)

The next step is to add the new location at which screenshots will be saved and you can do this by simply dragging the folder you created into Terminal and adding it at the end of the command you just entered. A path is created and the command line should now contain the folder's unique location and it should look like this:

**defaults write com.apple.screencapture location /Users/username/Screenshots**

To execute the command you have to press Enter. After Terminal finishes running the command, its window will appear on the screen again. You should proceed to confirm the changes you've just made by resetting the User Interface on your computer. In order to do so, you'll have to insert this command below the one you previously entered：

**killall SystemUIServer**

Hit Enter once more to confirm the changes and run the new command. Close Terminal app by clicking on the Terminal menu and selecting the Quick Terminal option. The default location where the screenshots are saved on your Mac is now changed and every time you take a screenshot using the Command + Shift + 3 shortcut the file will be saved at the new location. If for whatever reason you want to make the Desktop once again the destination where the screenshots on your computer will be saved here's how you can do it.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Part 2: How to Change the Screenshot Save Location Back to Desktop

The process of changing the default screenshot save location back to Desktop is nearly identical to the process we just described. You just have to open the Terminal app and insert the following command into the prompt.

**defaults write com.apple.screen capture location /Users/Username/Desktop/**

Make sure that your username is properly written, and then press Enter to run the command. Now you only have to reset the UI so it can recognize the changes you've made, and you can do it by inserting the **killall SystemUIServer** command into the Terminal window and pressing Enter to execute it.

Don't forget that deleting the folder you use as a default location for storing screenshots should only be done using the process we just described in the Terminal application, since all other methods may cause unnecessary trouble.

![author avatar](https://images.wondershare.com/filmora/article-images/max-wales-author.jpg)

Max Wales

Max Wales is a writer and a lover of all things video.

Follow @Max Wales

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

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







