## Link
Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing. You will commonly come across the following types of links:
●● Links from one website to another
●● Links from one page to another on the same website
●● Links from one part of a web page to another part of the same page
●● Links that open in a new browser window
●● Links that start up your email program and address a new email to someone

### Writing Links
Links are created using the <a> element. Users can click on anything between the opening <a> tag and the closing </a> tag. You specify which page you want to link to using the href attribute.

<a href="http://www.imdb.com">IMDB</a>

The text between the opening <a> tag and closing </a> tag is known as link text.

### Linking to Other Sites
<a>
Links are created using the <a> element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link.

### Linking to Other Pages on the Sa me Site
When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a
relative URL. If all the pages of the site are in the same folder, then the value of the href attribute is just the name of the file. If you have different pages of a site in different folders, then you can use a slightly more complex syntax to indicate where the page is in relation to the current page.

#### Rela tive URLs
When linking to other pages within the same site, you can use relative URLs. These are like a shorthand version of absolute URLs because you do not need to specify the domain name.

## Directory Structure
On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a website are sometimes referred to as directories

#### Structure
The diagram on the right shows the directory structure for a fictional entertainment listings website called ExampleArts.

#### Rela tionships
The relationship between files and folders on a website is described using the same terminology as a family tree.

#### Home pages
The main homepage of a site written in HTML (and the homepages of each section in a child folder) is called index.html. 

## Rela tive UR Ls
Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.

When you are linking to a page on your own website, you do not need to specify the domain name. You can use relative URLs which are a shorthand way to tell the browser where a page is in relation to the current page.

## Rela tive Link Type
Same Folder
To link to a file in the same folder, just use the file name. (Nothing else is needed.) 
To link to music reviews from the music homepage:
<a href="reviews.html">Reviews</a>

Child Folder
For a child folder, use the name of the child folder, followed by a forward slash, then the file name.
To link to music listings from the homepage:
<a href="music/listings.html">Listings</a>

Grandchild Folder
Use the name of the child folder, followed by a forward slash, then the name of the grandchild folder, followed by another forward slash, then the file name.
To link to DVD reviews from the homepage:
<a href="movies/dvd/reviews.html"> Reviews</a>

Parent Folder
Use ../ to indicate the folder above the current one, then follow it with the file name.
To link to the homepage from the music reviews:
<a href="../index.html">Home</a>

GrandParent Fold er
Repeat the ../ to indicate that you want to go up two folders (rather than one), then follow it with the file name.
To link to the homepage from the DVD reviews: <a href="../../index.html">Home</a>

## Email Links
mailto: 
email-links.html HTML To create a link that starts up the user's email program and addresses an email to a specified email address, you use the <a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.

## Opening Links in a New Window
target
If you want a link to open in a new window, you can use the target attribute on the opening <a> tag. The value of this attribute should be _blank.

## Linking to a Sp ecific Part of the Sa me Page
At the top of a long page you might want to add a list of contents that links to the corresponding sections lower down. Or you might want to add a link from part way down the page back to the top of it to save users from having to scroll back to the top. Before you can link to a specific part of a page, you need to identify the points in the page that the link will go to. You do this using the id attribute (which can be used on every HTML element). You can see that the <h1> and <h2> elements in this example have been given id attributes that identify those sections of the page.

### Linking to a Sp ecific Part of Another Page
If you want to link to a specific part of a different page (whether on your own site or a different website) you can use a similar technique. As long as the page you are linking to has id attributes that identify specific parts of the page, you can simply add the same syntax to the end of the link for that page.

# Layout
we are going to look at how to control where each element sits on a page and how to create attractive page layouts.
This involves learning about how designing for a screen can be different to designing for other mediums (such as print).

### Key Concepts in Positioning El ements
Building Blocks
CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors.


Containing Elements
If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element. It is common to group a number of elements together inside a <div> (or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The <div> element that contains this group of elements is then referred to as the containing element.

### Controll ing the Position of El ements
CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property. 

Normal flow
Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).

Relative Positioning
This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.
 
Absolute positioning
This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position
of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.

To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed. (You will meet these when we introduce the positioning schemes on the following pages.)

Fixed Positioning
This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element. Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page

## Normal Flow
position:static
In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be:
position: static; 
I have not specified a width property for the heading element, so you can see how it stretches the width of the entire browser window by default

## Relative Positioning
position:relative
Relative positioning moves an element in relation to where it would have been in normal flow. For example, you can move it 10 pixels lower than it would have been in normal flow or 20% to the right. You can indicate that an element should be relatively positioned using the position property with a value of relative.

## Absolute Positioning
position:absolute
When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.) The box offset properties (top or bottom and left or right) specify where the element should appear in relation to its containing element.

## Fixed Positioning
position:fixed
Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed. It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. It is a good idea to try this example in your browser to see the effect. To control where the fixed position box appears in relation to the browser window, the box offset properties are used.

## Overlapping Elements
z-index
When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front. For example, an element with a z-index of 10 will appear over the top of one with a z-index of 5.

## Floating Elements
float
The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. Anything else that sits inside the containing element will flow around the element that is floated. When you use the float property, you should also use the width property to indicate how wide the floated element should be. If you do not, results can be inconsistent but the box is likely to take up the full width of the containing element (just like it would in normal flow)

### Using Float to Place Elements Side-by-Side
A lot of layouts place boxes next to each other. The float property is commonly used to achieve this. When elements are floated, the height of the boxes can affect where the following elements sit. In this example, you can see six paragraphs, each of which has a width and a float property set. The fourth paragraph does not go across to the left hand edge of the page as one might expect. Rather it sits right under the third paragraph.

### Clearing Fl oats
clear
The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. It can take the following values:

left
The left-hand side of the box
should not touch any other
elements appearing in the same
containing element.

right
The right-hand side of the
box will not touch elements
appearing in the same containing
element.

both
Neither the left nor right-hand
sides of the box will touch
elements appearing in the same
containing element.

none
Elements can touch either side

### Parents of Floated Elements: Problem
If a containing element only contains floated elements, some browsers will treat it as if it is zero pixels tall. As you can see in this example, the one pixel border assigned to the containing element has collapsed, so the box looks like a two pixel line.

### Parents of Fl oated Elements: Solution
Traditionally, developers got around this problem by adding an extra element after the last floated box (inside the containing element). A CSS rule would be applied to this additional element setting the clear property to have a value of both. But this meant that an extra element was added to the HTML just to fix the height of the containing element.









