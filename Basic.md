# Basic knowledge
 * The \<meta\> tag provides metadata about the HTML document. Metadata will not be displayed on the page, but will be machine parsable. Meta elements are typically used to specify page description, keywords, author of the document, last modified, and other metadata.
 
 * \<meta name="viewport" content="width=device-width, initial-scale=1"\>
  - The width=device-width part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).
  - The initial-scale=1 part sets the initial zoom level when the page is first loaded by the browser.
  
 * Bootstrap also requires a containing element to wrap site contents. There are two container classes to choose from:
  - The .container class provides a responsive fixed width container
  - The .container-fluid class provides a full width container, spanning the entire width of the viewport
  
  __Note: Containers are not nestable (you cannot put a container inside another container).__
  
 * \<meta charset="[UTF-8](http://www.w3schools.com/html/html_charset.asp)"\>
  - Because ANSI and ISO-8859-1 were so limited, the default character encoding was changed to UTF-8 in HTML5. UTF-8 (Unicode) covers almost all of the characters and symbols in the world.

# Bootstrap Grids
 * Bootstrap's grid system allows up to 12 columns across the page. If you do not want to use all 12 columns individually, you can group the columns together to create wider columns:
 
 * The Bootstrap grid system has four classes:
  - xs (for phones)
  - sm (for tablets)
  - md (for desktops)
  - lg (for larger desktops)
  
 * The following is a basic structure of a Bootstrap grid:
  - First; create a row (\<div class="row">). Then, add the desired number of columns (tags with appropriate .col-\*-\* classes). Note that numbers in .col-\*-\* should always add up to 12 for each row.
  - For example:<br/>
   \<div class="row"><br/>
   &nbsp;&nbsp;&nbsp;\<div class="col-*-*"></div><br/>
   \</div><br/>
   \<div class="row"><br/>
   &nbsp;&nbsp;&nbsp;\<div class="col-\*-\*">\</div><br/>
   &nbsp;&nbsp;&nbsp;\<div class="col-\*-\*">\</div><br/>
   &nbsp;&nbsp;&nbsp;\<div class="col-\*-\*">\</div><br/>
   \</div><br/>
   \<div class="row"><br/>
   &nbsp;&nbsp;&nbsp;...<br/>
   \</div><br/>
   
   
