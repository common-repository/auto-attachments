﻿=== Auto Attachments ===
Contributors: kaisercrazy,berkaygeldec
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=HFYQEQFUBJ2RE&lc=TR&item_name=Auto%20Attachments%20Donation&currency_code=TRY&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted
Tags: attachments, attachment, zip, rar, tar, tar.gz, mp3, player, flv, mp4, mpg, odf, ods, plugin, documents, excel, files, pdf, spreadsheet, text, word
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Requires at least: 3.0
Tested up to: 4.9.2
Stable tag: trunk

This plugin makes your attachments more effective. Supported attachment types: Word, Excel, Pdf, PowerPoint, odf, ods, zip, rar, tar, mp3...

== Description ==
PLUGIN SUPPORT ENDS TODAY! [Please read this](http://wordpress.org/support/topic/auto-attachments-support-ends-today)
Auto Attachments make your attachmens more effective. When you upload an attachment to your article, this plugin detect attachment's type and create a file list and a download area after <code>the_content</code>. And if you add some audio and video files the plugin add a jw player for this file. Plugin works with mp3, ogg, FLV, MP4 and other video & audio types (What supports by JW Player and WordPress)

IF YOU WANT TO SHOW FILES INSTEAD OF AUDIO OR VIDEO, [A MINI PLUGIN IS HERE](http://wordpress.org/plugins/auto-files)

**Shortcode Panel Adeed**

**NOTICE**: Please Set your thumbnail and big image sizes and rebuild your images once. Read [FAQ](faq/) please

With new admin area (1.0 - [look screenshots](screenshots/)) options were groupped with clean, Bootstrap based design. You can control all of plugin's options. You can decide downloadble files design, list or grid. Also you can add header titles for video and audio files. You can find a .pot file in languages folder.

= Languages Included =
* Turkish (tr_TR)	(Default)
* English (en_US)	(Default)
* Romanian (ro_RO)	[Web Hosting Geeks](http://webhostinggeeks.com/)
* Russian (ru_RU)	[Artiom Pulatov](http://papiko.ru/)
* Italian (it_IT)   Andrea Primiani
* Slovak (sk_SK)	[Branco, Web Hosting Geeks](http://webhostinggeeks.com/blog/)
* Hebrew (he_IL)    [oriadam](http://wordpress.org/support/profile/oriadam)
* Thai (th_TH)		[N Admission.in.th](http://www.admission.in.th/)
* Serbian (sR_RS)	[Borisa Djuraskovic](http://www.webhostinghub.com/)

More Changes? [Look At Changelog](changelog/)
Some FAQ Added [FAQ](faq/)

Plugin is multilingual. If you translate [please contact me](mailto:info@wpadami.com) and send files. Türkçe (Turkish) bilgi için : [WpAdami](http://www.wpadami.com)


== Installation ==

1. Upload `auto-attachments` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= How i upload files to my blog or posts? =
Use WordPress media uploader when you create new page or post **(Insert / Upload button)** and upload your files. No special things required. Plugin uses wordpress attachments.

= My Thumbnail is too big. How can i change size? =
Go to Auto Attachments => Gallery Settings from accordion and set Thumnbail & Big size dimensions what px you want. And please use Rebuild Thumbnail page.

= How i change file list type to multi-column (or reverse) =
Go to Auto Attachments => Misc. Settings and if you want to use multi-column list set yes "List view of Files" (default No).

= How i create shortcodes = 
Go to Posts (or Pages) -> Create New (or Edit). You will see a new button with a paperclip. Press this button and follow the instruction.


== Screenshots ==

1. Files Section & Audio Player
2. Audio & video Player
3. Admin Area
4. Shortcode Panel

== Changelog ==

= Version 1.8.5 =
* Media Elements removed for security issue

= Version 1.8.4 =
* Plugin Support Ends ([Please read this](http://wordpress.org/support/topic/auto-attachments-support-ends-today))
* DO NOT USE WITH WORDPRESS 3.9

= Version 1.8.2 =
* Audio & Video Shortcode updated with recent changes.
* Tested for 3.8.1 again. Working. 
* Some base code changes. Shortcodes will not broke plugin settings

= Version 1.8.1 =
* Screenshots changed
* video and Audio javascript files splitted and configured.
* If you hide a section (video/audio) script will no effect hidden section. You can use your own player instead of media elements.
* Rebuild page paperclip icon added
* Donate Button added to Settings Page. 

= Version 1.8 = 
* Illegal string issue fixed [See This Request](http://wordpress.org/support/topic/disable-if-no-attachment-on-postpage?replies=11#post-5154915)
* You can hide Audio, Video, Files section from plugin settings page for all site content. [See This Request](http://wordpress.org/support/topic/remove-video-showing)
* Admin panel and page/post metaboxes updated.
* Some code improvments about plugin.

= Version 1.7 =
* Banner image of plugin changed
* Paperclip icon (image) changed to modern svg font.
* Some readme.txt fixes and cleanup
* New function (show/hide video,audio,file,gallery area) test. Working!
* I make TO DO list for some changes. I will open a Support Topic About This. [Look at here](http://wordpress.org/support/plugin/auto-attachments)

= Version 1.6 =
* Metaboxes extended
* You can control all sections of plugin from New/Edit Post area

= Version 1.5 =
* Tested With 3.8. Working!
* Settings page button group problem solved.
* Checked for modal area. I think no problem.
* One TODO: Auto Detect if content have any image & add to exclude list.

= Version 1.4 =
* Serbian Language Added. Thanks Borisa!

= Version 1.3 =

* Audio & Video player shortcode fixed

= Version 1.2 =

* Password Protected post/page function corrected [Password protected page not showing password input field](http://wordpress.org/support/topic/password-protected-page-not-showing-password-input-field)

= Version 1.1 =

* Media Elements fix for video and audio players
* Video & Audio Player placement fix. No more li tags.
* JW Player Totally removed from plugin

= Version 1.0 =
* Admin area jQuery UI removed
* Shortcode Panel jQuery UI still working. Only Modal.
* Admin area bootstrapped. 
* Admin area options page responsive.
* Video and audio player changed to Media Elements. Experimental but still working good. Please Respond issues
* Plugin control function name changed to fix this issue [Plugin Activate Error](http://wordpress.org/support/topic/plugin-activate-error)
* Password Protected Posts issue fixed [Password protected posts show attachments](http://wordpress.org/support/topic/password-protected-posts-show-attachments)
* Tested for 3.7.1 No Problem :)

= Version 0.7.7 = 
* Weird CSS problem fixed on post pages shortcode's modal.
* jQuery UI CSS minimized. Saved 12kb :)
* Tested for 3.6.1. No Problem :)

= Version 0.7.6 =
* Slimbox2 Upgraded to 2.05
* There was a problem with slimbox2 css. Fixed with this version. Thanks Paul!
* Slimbox2 light scheme images stored into a folder.

= Version 0.7.5.5 =
* Compability Check for Wordpress 3.6
* Plugişn will not shown if post hasn't any attachments.

= Version 0.7.5.4 =
* I've found a minor bug in my code. Fixed.
* insertintoPage() function merged into insertintoContent() (core) function. 
* Single & Page check controllers changed to post type controllers.
* Post Types Exclude function corrected & changed. You can't disable core post and page post types (builtin post types) from option panel now.

= Version 0.7.5.3 = 
* Post Types Exclude Option Added in Misc. Settings Panel
* Turkish & English Lang files updated.
* New File Type Support Added (Macro Enabled Workbook). Thanks for suggestion [bobheinen](http://wordpress.org/support/topic/xlsm-files-not-shown)
* Mime image added for new file type

= Version 0.7.5.2 =
* Thai Language Added. Thanks N!
* POT file updated.

= Version 0.7.5.1 =
* Fix about attachment position.
* jQuery Fix

= Version 0.7.5 =
* Users can select where to show Auto Attachments on posts. Thanks for suggestion [kerms](http://wordpress.org/support/topic/show-attachment-list-at-top-of-the-page)
* Metabox added for this functionality.

= Version 0.7.4.2 =
* Minor bug fixed. Fix based on ed523's [support thread](http://wordpress.org/support/topic/illegal-string-offset-2). Thanks ed523!

= Version 0.7.4.1 =
* Minor bug fixed in shortcodes. File shortcode give a wrong link. Thanks [lownotes](http://wordpress.org/support/topic/icon-and-button-urls-are-different)
* Minor clean for empty lines.

= Version 0.7.4 =
* ODT text and PPSX file support added
* ODT text and PPSX file type icons added
* Minor CSS Bugs fixed
* Minor JS bugs fixed
* Custom jQuery UI problem fixed (it will load only plugin page & post-new,post page)
* Custom CSS editor added to admin area. You can change plugin's css code.

= Version 0.7.2 = 
* Shortcode Modal Box Fix, box will load footer of post and post-new
* Gallery Listing Width Fix Width now 100%
* Video Player Skin Fix

= Version 0.7.1 = 
* jQuery Fix for admin area  page/post edit area

= Version 0.7 =
* Tested with WordPress 3.5.1. Working!
* Admin area jQuery UI upgraded
* Admin area jQuery Uı theme changed
* Shortcode Panel Added
* Shortcodes added for Images, Files, Audio files and Videos
* Image size rebuilder code cleaned and changed some litte code
* Some jQuery code changed
* Tested with 3.5.1 & new shortcode panel. Working

= Version 0.6.7.1 = 
* Bugfix for Open file in new window area (Thanks Matt!)

= Version 0.6.7 =
* Category pages `is_category()` support added
* Show on Categories Option added to Admin Area

= Version 0.6.6 =
* Hebrew Language Added. Thanks oriadam!
* Start working on shortcodes & other new stuff.

= Version 0.6.5 =
* jQuery implement was break dashboard left menu. Corrected. Thanks [Chris](http://wordpress.org/support/topic/seems-to-break-javascript-in-backend)
* Tested for WordPress 3.5. Working!
* Admin area code cleaned after jquery fix.

= Version 0.6.4 =
* Pot file updated
* New language added (Slovak). Thanks Branco!
* One FAQ added about upload files

= Version 0.6.3 =
* Prevent from Featured Image in Gallery

= Version 0.6.2 =
* Added a new icon for rar files

= Version 0.6.1 =
* Works with WordPress 3.4.2

= Version 0.6 =
* Rar Upload Option Deleted.
* Admin Area Code Cleaned.
* Options Serialized.
* Added meta box for "Show on Pages".
* Colorbox Replaced with Slimbox2 with light and dark style option.
* Gallery Thumbnail Style Added light and dark.
* Auto Attachments has a new menu area on the left.
* Thumbnail and Big image sizes are configurable now.
* Timthumb deleted from plugin. Plugin uses WordPress image crop.
* Thumbnail Rebuilder added. Please Use this first when you set image sizes.

= Version 0.5.6 =
* We have a little "Title" problem after 0.5.5. Solved! Thanks for reported Kris.

= Version 0.5.5 =
* Compatibility check for 3.4. Working!
* Added Option to Show title before attachments. (Thanks Kris :) )
* Php code format changes. More readable/ediatable code.

= Version 0.5.4 = 
* Multicolumn Listview
* Cache Folder Check
* Downloadable files' icon size select
* Downloadable files' link target attribute

= Version 0.5.3.1 = 
* Admin area CSS changes/fixes
* TimThumb Update to latest version
* Compatibility check for 3.3.2 Working!.

= Version 0.5.3 =
* Settings Page Changed. It will be more beautiful with jQueru UI
* Added 7 themes for JW Player. You can select what theme you want (With Preview)
* Added option to change grid to list for downloadable files
* Some codes and folders/paths changed in base of plugin
* Colorbox Upgraded to latest version
* Timthumb problem solved for multisite. Timthumb can create thumbnails for subdirectory sites.

= Version 0.5.2 =
* Homepage And Page Function corrected

= Version 0.5.1 =
* Multisite Support Added.
* Timhumb upgraded to latest version.
* Security Update for file protect
* Compatibility check for 3.3.1 Working!.
* You can show on homepage if you want. Thanks to [venttom](http://wordpress.org/support/topic/plugin-auto-attachments-does-not-show-attachments-for-posts-on-the-home-page?replies=2#post-2627965)
* Checkboxes are radio buttons now. Option added "Yes" and "No".

= Version 0.4.3 =
* Timhumb upgraded to latest version.
* Some mimetypes added.
* Compatibility check for 3.3. Working!.
* Multisite links fixed thanks [lopo](http://wordpress.org/support/topic/plugin-auto-attachments-does-not-work-if-wp-folder-is-different-than-home-with-fix?replies=2)
* Some code changes for multisite. Test it on your own multisites. Send me bug report if i have.

= Version 0.4.2 =
* Support added for pages.
* You can decide to show attachments on pages.
* Minor Admin area changes.

= Version 0.4.1 =
* After this update 4 more supported extensions.XLSX, PPTX, DOCX, TXT.
* More functional and fast code.
* Second security fix with folders and other things.

= Version 0.4 =
* Long File names not lay on images if you use galelry option.
* Security fix for Timthumb.

= Version 0.3 =
* A CSS Error Fixed. Thanks [Ramazan Benek](http://www.ramazanbenek.com/)

= Version 0.2.9 =
* Tested for WordPress 3.2.1
* Changed admin area view. Preview area changed.
* Clean a messy code which breaks `#content` area in posts.

= Version 0.2.8 =
* Tested for WordPress 3.2
* Gallery Thumbs are Resizeable now.

= Version 0.2.7 =
* Gallery support added. Gallery use colorbox. You can enable or disable.
* Language files are updated.
* Some mess code cleaned.
* New screenshot added.

= Version 0.2.6 =
* Admin Area Upgraded. Now you can decide rar upload, header text display.
* Plugin Now multilingual. en_US and tr_TR for now. If you translate plugin please contact me.
* Facebook Like and Share buttons added for WordPress plugin page.
* Admin area screenshot replaced

= Version 0.2.5 =
* Some mess code cleaned.
* Improved Admin Area. If you dont fill Header text you'll get error.
* Improved Default Texts. Default array rewritten.
* Added admin area error screenshot.

= Version 0.2.4 =
* Added user friendly admin setting page.
* Improve code when install. You will see a notice when you activate plugin.
* Added Default Texts for information bar.
* Added admin area screenshot.

= Version 0.2.3 =
* Added some information bar for videos and audio files.
* Updated some old code.
* Added a new screenshot
* Tested for WP version 3.1.3 

= Version 0.2.2 =
* Code Cleanup and version update. 

= Version 0.2.1 =
* Security and Version Update. 
* ODF, ODS support added.
* RAR files can upload.

= Version 0.2 =
* Video Support added. The plugin support for FLV, MP4 and other video types with JW player. Screenshot added.

= Version 0.1b =
* Plugin Released

== Upgrade Notice ==
No need any changes
