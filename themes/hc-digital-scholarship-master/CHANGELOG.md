## v1.0 ~ December 2013

#### Changes:

 - Changed the layout of individual items' and exhibits' pages

#### Fixes:

 - Added Neatline back into the public navigation by updating a small chunk of their code ([resource here](https://github.com/scholarslab/Neatline/commit/5b88ff9e9ffb9ebabd4ba7f6e3d612e5762d9cc1))
 - Fixed the navigation to change dynamically with browser width

**Misc/more:**  
Prob: Omeka would error upon attempting to import into Neatline exhibit  
Fix: in "/application/config/config.ini" changed background.php.path from "" to "/usr/local/bin/php" 

Prob: Dublin Core text over item metadata  
Fix: Copied “record-metadata.php” to “/common” ([forum resource](http://omeka.org/forums/topic/changing-dublin-core-titlessubtitles))  

Prob: Index page column responsiveness  
Fix: Divided the two divs that constituted the columns into three sections  

Prob: Index page mobile column space: large amount of space on right side of columns  
Fix: Fixed conflicting CSS styles between “primary” and “secondary” div styling