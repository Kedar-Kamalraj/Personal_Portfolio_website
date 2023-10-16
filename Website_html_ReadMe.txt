website_index is the html file and website_style is the css file

HEAD
---------------
Lang attribute is given inside the html tag to specify the language of the document.

Meta tag provides metadata and it helps browers and others users to handle the webpage

This is the encoding line of the html code.It defines how the characters are represented in the document.UTF-8 supports multiple languages
Specifies how internet explorer should render a page

The "X-UA Compatible" lets you specify the mode of internet explorer you are using
The"IE=edge" instructs the internet explorer to use the highest available document mode
The content attribute specifies the value or content associated with a particular meta tag

The name attribute denotes the type or name of metadata given
Here in this case it is viewport,thus the meta tag indicates the viewport settings of the web page
viewport is the visible area of the webpage
The content attribite contains a comma separated list of settings for viewport
"width=device-width"-This makes sure that the width of the webpage fits the device perfectely 
This is to ensure good web responsive design
"initial-scale=1.0"-This indicates the initial zooming of the webpage.
The value 1.0 indicates that the webpage is in its's actual size when opened without any unnecessary zooming

The title tag specifies the title 

The link tag is used to link the css file
The rel attribute specifies the relationship between the html fime and the linked file
Here the value is given "stylesheet" hence the linked file is identified as a css file
The href attritube is used to specify the url of the css file
---------------

BODY
---------------

div with id=#header is created
the div tag is used to divide the code into sections so that styling is accuarte
id has a unique value each time it is used i.e, no two id can have same name
It's value starts with a #

div with a class container is created
Two classes can have the same name

The "nav" tag is used for navigating the website
Section inside the nav tag represents the navigation of the website
The image tag "img" is used to add a logo to the website and a class called"logo" is assigned to it
An unordered list is created that contain all the navigation elements
Links are created to the elements(Home,Abouit,Services,Portfolio,Contact)
The " href='#' " denotes a placeholder link i.e, it does not have a specific destination

created another div tag with the class "header-text" and using paragragh tag a text "PROGRAMMER" is given
With h1 tag "Hi I am Kedar Kamalraj From Nettayam" is written
A span is given to "Kedar Kamalraj" and a line break is provided after it
All the div tags are closed

A comment to indicate the start of the about section is given
A div tag with id as"about" is created
Another div tag inside the id='about' is created with a class name 'container'
The same name 'container' has been given to the starting division of the home page, thus the css is same for both since they have same class name
Another div with class name 'row' is created and inside it another div with class name 'about-col-1' is created
These container elements are created so as to apply the appropriate css design

In the given html code there are two div tags with class name 'about-col-1' and 'about-col-2' that are given inside the class 'row'
In one section, the left one contains the image and the link of the image is given through the image tag
The link given in image section is local
To work in a web environment, a relative url should be given
The other section contains the main contents

The 'h1' heading tag displays the heading 'About Me' in the second section
A class called 'tab-title' is assigned to the tag
The 'p' tag gives the text in the about me section 

Another div tag with class 'tab-title' is created
A paragraph tag is opened with class names 'tab-links' and 'active-link'
In the same paragraph tag and onclick attribute that directs to the opentab function in javascript provided in the script tag
The value 'skills' is passed to the opentab function
Inside the 'p' tag the content given is 'Skills'
This is the code to showcase the skills in the website under the about me.
When clicked on 'Skills' it shows the skills

Similarily the same set is done for experience and education
For experience a 'p' tag is created and the class name 'tab-links' is given
The class 'active link' is given only for skills and not given for education and experience
That class shows the active status of the tab
The class 'tab-links' is given to every tab along with the onclick attribute
The onclick attribute directs the control flow to opentab function with it's parameters
The parameter is 'education' for education tab and  'experience' for experience tab

Another division is created 
The class for this division is 'tab-contents' and 'active-tab' and an id='skills' is given
The active-tab section shows which tab is currently active
The id is sent as parameter to the opentab function
With the use of li,span and br tags the contents of the tab are created

Another tag with similar settings and attribute are created for experience and education with id='experience' and id='education' respectively
These id's are passed as parameter to the opentab function

Another div tag with id as services for the services section
Inside that a class named "container" is created so as to access the css