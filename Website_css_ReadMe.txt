website_index is the html file and website_style is the css file

---------------
* is a universal selector it states that the style given in brackets are applicable to all the elements in the css file
It contains the default settings of the webpage

margin and padding are initialy set to 0 to avoid any default spacing

Poppins is given as the font to ensure same font throught the webpage.
If Poppins is not available in the device, sans-serif is used as the font
This is to ensure the uniformity of font throught the webpage

box-sizing is the property which determines how the height and width are calculated
default is content-box which measures the height and width  based on the contents available
box-boreder includes the paddings and margin during calculation


body
---------------
background color of the webpage is set to black(#080808)

text color is set to white


#header
---------------
"width:100%" - sets the width of the selected element to 100% if it's containing element
In this case the header element spans the entire area of parent container

"height:100vh" - sets the height of the browser window to 100% of the viewport height
Viewport height is a unit of measurement relative to height of browser window
Here the header occupies the entire height of the browser window

"background-image" is set by giving the url of the image

"background-size" is used to size the background image to the containing element
Since it is set to "cover" it scales the image up and down to fit the area without laeving empty spaces
The aspect ratio is maintained
It fits the image in the space even it means cropping or clipping some part of the image 

"background-position" is used align the image both horizontally and vertically
"center" is used to centre the image


.container
---------------
padding of 10px from the left and 10% from the top is given


nav
--------------
"display;flex" - This is used to enable the Flexbox layout mode
This makes the container a flex container and its elements flex items

The flex items within the flex container has two axis - the horizontal main axis and vertical cross axis
"align-items:center" - This is used to sdjust the vertical alignment of the flex items along the cross axis
"center" is used to align the flex elements to the centre of the flex container along the cross axis

"justify-content:space between" - Align the flex items horizontally within the flex container along the main axis
When set to "space between" , it evenly distributes the elements along the main axis 
It places the first element at the start and the last at the end of the axis with equal space in between

"flex-warp:warp" - It adjusts the flex item when they do not fit in the width of the container
"warp" enables the content to warp to new lines if they do not fit in the container

nav ul li 
---------------
"display: inline-block" - All the flex items are aligned horizontally in a single line

"list-style:none" removes the bullet points.
It is used to give bullets nad numbering to the elements

"margin:10px 20px" sets a margin 10px from top and bottom and 20px from left and right of the assigned container

nav ul li a 
---------------
color of the fontis given as white

"text-decoration" is set to none to remove the underline.
This attribute removes any decorations provided to the text

font size is set to 18px

position is set to relative that is the position of child element can be cahanged by the parent element

nav ul li a::after
---------------
width is set to 0 so that later it appears only on hovering

height is set to 3 px

background color is set to black

"position:absolute" is made absolute thus the postion of the line is determined relative to the nearest placed ancestor
"left:0" means the line starts from the left end
"bottom:-6px" means it is placed 6px up it's containing block

Content is not given and the code will work even without that attribute

"transition:0.2s" of 0.2s sets the black line to appesar in 0.2s when hovered over it

nav ul li a:hover::after
---------------
In this case the width becomes 100% as soon as we hover over the content
A transition of 0.2s is given
The transition attribute can be placed here instead of in "nav ul li a::after"

#about
---------------
text color is gold
A padding of about 80 px from top and bottom and 0 from left and right is given

.row
---------------
A flexbox is created and the items become flexitems
A flexbox is a layout mode which allows to manage space and alignment of elements 

Aligns the item horizontally and the last element is put at the end and the first at the beginning

The wrap adjusts the text to the width of the flexbox and if it overflows then it is warped to a new lines

.about-col-1
---------------
"flex-basis:35%" this states that the width of the column is 35%

.about-col-1 img
---------------
width is set to 100%
A border radius of 15px is applied

.about-col-2
---------------
60% of the flexbox is alloted to this element by "flex-basis: 60%"

.tab-title
---------------
"margin: 20px 0 40px" reprsents the margin at top right bottom and left respectively
Since no value is given for left it is taken as zero

A flexbox is created and the items become flexitems
A flexbox is a layout mode which allows to manage space and alignment of elements

font colour is blue , font size is 45px and font weight is 600