Simple footer module for webtrees
=================================

[![Latest Release](https://img.shields.io/github/release/JustCarmen/webtrees-simple-footer.svg)][1]
[![webtrees major version](https://img.shields.io/badge/webtrees-v2.1.x-green)][2]
[![Downloads](https://img.shields.io/github/downloads/JustCarmen/webtrees-simple-footer/total.svg)]()

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=XPBC2W85M38AS&item_name=webtrees%20modules%20by%20JustCarmen&currency_code=EUR)

Description
------------
Would you like to have an easy solution to add an extra footer item to your webtrees installation?
Here it is!

With this module you can set a new footer item, with or without link to an additional page. You can use it to add your credits or copyright to the footer or to add a link to your own custom page with your privacy policy or additional conditions.

It is a simple module, without fancy extras. It is developed to quickly add a new footer item and optionally page to webtrees, that is it. It does not provide the ability to add different pages per language for example.

Installation & upgrading
------------------------
[Download][1] and unpack the zip file and place the folder jc-simple-footer-1 in the modules_v4 folder of webtrees. Upload the newly added folder to your server. It is activated by default. Go to the control panel, click in the module section on 'Footers' where you can find the newly added footer item. You can move it up or down to change the order. Click on the tools icon next to the title of the newly added footer item. This will open the settings page where you can set a footer text and if desired, add a page title and text.

Extra footer items and pages
---------------------
If you want to have multiple footer items and associated pages, just make a copy of this module in your modules_v4 folder. Change the serial number at the end from 1 to 2 and so on. You can use this module indefinitely, as long as you give each module a unique name. Keep in mind that you must repeat this step after each upgrade. You will not lose your settings after an upgrade as long as you give the new version of the module the same folder name as before.

Translation
-----------
This module contains a few translatable textstrings. Copy the file nl.php into the resources/lang folder and replace the Dutch text with the translation into your own language. Use the official two-letter language code as file name. Look in the webtrees folder resources/lang to find the correct code.

Bugs and feature requests
-------------------------
This is a simple module and provided as is. However, if you experience any bugs you can [create a new issue on GitHub][3]. Since this is a simple module, I will be reluctant to accept feature requests.

 [1]: https://github.com/JustCarmen/webtrees-simple-footer/releases/latest
 [2]: https://webtrees.github.io/download/
 [3]: https://github.com/JustCarmen/webtrees-simple-footer/issues?state=open
