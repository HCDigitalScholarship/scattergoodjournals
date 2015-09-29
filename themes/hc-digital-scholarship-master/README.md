Haverford College Digital Scholarship Theme
===========================================
_An Omeka theme created for the Haverford College community_

- - -

## Credits

#### created/modified by
Caleb Eckert ’17  
as part of the  
[Haverford College Libraries Digital Scholarship Program](http://library.haverford.edu/services/digital-scholarship/)
 
#### compatible with
Omeka 2.0-2.1

#### based on
the Omeka [Thanks, Roy](http://omeka.org/add-ons/themes/thanks-roy/) theme

### Contact
Should you have any questions, issues, or suggestions about this theme, please contact me via [GitHub](https://github.com/calebeckert/hc-digital-scholarship), [email](ceckert@haverford.edu), or [Twitter](https://twitter.com/eckertcaleb)

- - - 

### Updates
_(Check [CHANGELOG](https://github.com/calebeckert/hc-digital-scholarship/blob/master/CHANGELOG.md) for details)_

2013 Dec 10: uploaded to GitHub  
2013 Dec 08: upgraded to Omeka 2.1.3  

- - - 

#### Document Standards (for this readme):

“filename.extension”  
“/path/to/folder” or "/foldername/”  
“/foldername/file.php”: the initial / begins at the theme folder's path “/themes/hc-digital-scholarship/... (i.e. “/index.php” is really "sitename/themes/hc-digital-scholarship/common/index.php")


IMPLEMENTATION
--------------

1. Make sure you install and configure Omeka correctly (visit the [Omeka Installation Guide](http://omeka.org/codex/Installation) for help)
2. Download the theme's entire repository/folder into a .zip file
3. In the root folder of your new install, navigate to "/themes/", upload, and extract the .zip file
4. Return to your admin panel and change the theme to this one

UPGRADING
---------

Please read [Upgrading Omeka](http://omeka.org/codex/Upgrading) for details

Basic Reminders:
* Make sure to copy “db.ini” from the root Omeka folder and copy it back it after updating

THEME DOCUMENTATION
-------------------

**In all edited files, I have commented "DOC:" where files have been changed.  
Command/Control + F and search "DOC" without quotes to find them.**

#### Edited Files:

**CSS**  
“/css/style.css”
 - I eliminated the old mobile styling (as well as code in "global.js") and edited others in order to fix mobile site
 
**Index**  
“/index.php”: added another “tertiary” class section
 
**Header**  
“/common/header.php”: shifted around some ordering, changed navigation

**Footer**  
“/common/footer.php”: added credit to Haverford DS

**Items**  
“/items/show.php“: edited the items view

**Exhibits**  
“/exhibit-builder/exhibits/browse.php”: removed the “total” count

**Javascripts**  
“/javascripts/global.js“: commented out a few of the lines for mobile modifications

- - - 

Enjoy the theme, and send me comments/questions/bugs/suggestions/etc.  

See what Haverford Digital Scholarship is up to:  
[Website](http://library.haverford.edu/services/digital-scholarship/) | [Twitter](https://twitter.com/search?q=%23haverfordds&src=hash&f=realtime)
