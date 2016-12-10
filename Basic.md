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
  
 * \<small>
  - In Bootstrap the HTML \<small> element is used to create a lighter, secondary text in any heading. <br/>
    \<h1>h1 heading \<small>secondary text\</small>\</h1>
  
 * \<mark>
  - Bootstrap will style the HTML \<mark> element in the following way: <br/>
    \<p>Use the mark element to \<mark>highlight\</mark> text.\</p>
    
 * \<abbr>
  - Bootstrap will style the HTML \<abbr> element in the following way: <br/>
    \<p>The \<abbr title="World Health Organization">WHO\</abbr> was founded in 1948.\</p><br/>
 
 * \<blockquote>
  - Bootstrap will style the HTML \<blockquote> element in the following way:<br/>
    \<blockquote><br/>
    &nbsp;&nbsp;&nbsp;\<p>For 50 years, WWF has been protecting the future of nature.\</p><br/>
    &nbsp;&nbsp;&nbsp;\<footer>From WWF's website\</footer><br/>
    \</blockquote><br/>
   - To show the quote on the right, use the .blockquote-reverse class:<br/>
    \<blockquote class="blockquote-reverse">
    
 * \<dl>
  - The dl element indicates a description list: <br/>
    \<dl><br/>
    &nbsp;&nbsp;&nbsp;\<dt>Coffee\</dt><br/>
    &nbsp;&nbsp;&nbsp;\<dd>- black hot drink\</dd><br/>
    &nbsp;&nbsp;&nbsp;\<dt>Milk\</dt><br/>
    &nbsp;&nbsp;&nbsp;\<dd>- white cold drink\</dd><br/>
    \</dl><br/>     
  
 * [\<code>](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_txt_code&stacked=h)
 
 * [\<kbd>](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_txt_kbd&stacked=h)
 
 * [\<pre>](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_txt_pre&stacked=h)
 
 * Contextual Colors and Backgrounds<br/>
  - Bootstrap also has some contextual classes that can be used to provide "meaning through colors".<br/>
  - The classes for text colors are:.text-muted, .text-primary, .text-success, .text-info, .text-warning, and .text-danger.[Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_txt_colors&stacked=h)<br/>
  - The classes for background colors are:.bg-primary, .bg-success, bg-info, bg-warning, and .bg-danger.[Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_txt_bgcolors&stacked=h)<br/>
  
  * The Bootstrap classes below can be added to style HTML elements further:
  
| Class | Description | Example |
| :---: | :---: | ----- |
| .lead | Makes a paragraph stand out | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_txt_lead&stacked=h) |
| .small | Indicates smaller text (set to 85% of the size of the parent) | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_txt_small&stacked=h) |
| .text-left | Indicates left-aligned text | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_text-left&stacked=h) |
| .text-center | Indicates center-aligned text | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_text-left&stacked=h) |
| .text-right | Indicates right-aligned text | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_text-left&stacked=h) |
| .text-justify | Indicates justified text | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_text-left&stacked=h) |
| .text-nowrap | Indicates no wrap text | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_text-left&stacked=h) |
| .text-lowercase | Indicates lowercased text | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_text-lowercase&stacked=h) |
| .text-uppercase | Indicates uppercased text | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_text-lowercase&stacked=h) |
| .text-capitalize | Indicates capitalized text | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_text-lowercase&stacked=h) |
| .initialism | Displays the text inside an \<abbr> element in a slightly smaller font size | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_txt_abbr2&stacked=h) |
| .list-unstyled | Removes the default list-style and left margin on list items<br/> (works on both \<ul> and \<ol>). This class only applies to <br/> immediate children list items (to remove the default list-<br/>style from any nested lists, apply this class to any nested <br>lists as well) | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_txt_list-unstyled&stacked=h) |
| .list-inline | Places all list items on a single line | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_txt_list-inline&stacked=h) |
| .dl-horizontal | Lines up the terms (\<dt>) and descriptions (\<dd>) in <br/>\<dl> elements side-by-side. Starts off like default \<dl>s, <br/>but when the browser window expands, it will line up side-by-side | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_txt_dl-horizontal&stacked=h) |
| .pre-scrollable | Makes a \<pre> element scrollable | [Example](http://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_ref_txt_pre&stacked=h) |


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
   
   
