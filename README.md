THE OLD MONKEES
===============
<i>"The old Monkees"</i> is a project work written and developed in partial fulfilment for the requirements of
the User Centric Frontend development by the Code Institute, Ireland.
The focus of this project work is to provide a forum for interaction between "The Monkees", 
which is a 1960s' Rock Band and their existing and prospective fan base with a view to improving their competitive advantage in the
 modern music and entertainement industry.

USER EXPERIENCE:
----------------
This project work is designed to provide the following functionalities:
1. Provide a site for fans and members to see and hear clips from their back catalog, and any new material as it becomes available.
2. Provide a facility to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.
3. Provide a medium through which their social media presence will be accessed for instance access to their Facebook, Twitter and YouTube pages.

In order to achieve these objectives, "The Old Monkees" utilized current technologies of HTML5 
and has created a potent media presence on the internet to showcase the activities of "The Monkees", and keep them in vogue with modern communication and also
to express the nature and nuture of their perforamances.
As a means to effectively engage with clients, <b><i>The Old Monkees</b></i> created backgrounds with visual effects to arouse the attention of people that will visit the site 
Also, the landing page(HOME), provides hypertext links to various pages among which are the <b><i>'SHOWCASE'</i>,</b> and <b><i>'CONTACT' webpages</i></b>. The <b><i>SHOWCASE</i></b>
as the term implies is the media home of the website. It provides the technological resource that carries all the pictures, audios and video for the enjoyment of the fans, members and customers
while the <b><i>CONTACT</I></b> provides client with the facilities to actively interact with the band using of the following features that are constructed
into the page:
1. Button for registration and log in
2. Button for booking performance for chrismas events
3. Button for booking perforamance for birthday and marriage
4. Feedback button

These buttons are hyperlink in nature as a result, they open into a new .html extension that will provide the user with booking forms that are meets the specific requirements of their needs.
Other mediums for active interaction like <b>phone links</b>, clickable <b>join now links</b>, <b>search</b> and <b>navigation menus</b> are provided throughout the
the various pages of the project.
The bottom of the page provides icons for navigation to the various social medias, duplicate navigation menus
and additional navigation list for blog, news, gallery and media.

This project was initially conceived with the name "rock60" which was used as mockup for development. During the development, rock60 was cloned as
rock60-a and rock60-b for testing, documentation and correction. These mockups are hosted in cloud9 and their links are:
1. https://ide.c9.io/ufedo/rock60
2. https://ide.c9.io/ufedo/rock60-cloned-a
3. https://ide.c9.io/ufedo/rock60-cloned-b



FEATURES:
---------
<b><i>"The OLD MONKEES"</i></b> a five webpage project that contains the following .html pages
1. index.html
2. showcase.html
3. service.html
4. about.html and
5. contact.html

and the following form pages for active interaction with members
1. contact-birthday.html
2. contact-christmas.html
3. contact-feedback.html
4. contact-logister.html

index.html is the landing page of the project. It provides a captivating visual effect to project a sentimental undertone of the 
music type provided by the Rock Band and to positively arouse the emotions and interest of the users. The primary focus of this page is to sell the band to the users through visual 
and emotional attraction. And to consolidate on this approach, the users are provided with
a web page which is fully functional and written on a user friendly
fonts (font-family:"Arial", Serif). It also employs the use of fontawesome to show the social icons.
The project in itself is designed using a mobile first approach however this landing page is conceived and executed without the use
of bootstrap hence it relies heavily on media queries to achieve the surprise.
Although there are a number of elements on the page which are responsive, I shall dwell only briefly on the relationship of the
"navbar" and the "side menu"(reference lines 42 to 56 and 57 to 76 of index.html) and on the "booking" and "btn-booking" button(reference line 75 and 79 of index.html)
At a viewport width of 860px and over, the navbar menu is available to use on desktop and every other device that has larger screen but when the width of the screen reduces
below 860px, the navbar menu will disappear from view on the screen and the white svg navigation icon will popup at the top left of the screen indicating the presence of the side menu to alternate function with the navbar menu. 
In a related manner, the booking and btn-booking are two different buttons but the perform the same function on different viewport. While the booking button is available for larger screen, btn-booking 
pops up on the screen with lower resolution but redirect to the same contact.html page.
The purpose of this functionality is to give users the facility to be able to register and log-in from both mobile and desktop devices. Although only one button could be used to provide this service for both resolution,
however,  at a lower resolution, the booking button usually occupies a position that disables some functionalities from the side nav as a result of which it becomes imperative to experiment with a 
a cloned copy of the button from a different location on the html page. And with media queries, it worked. The homepage also consist of other elements that are responsive when the size of the viewport changes in relation to 
their size and position.
Worthy of note also is the footer. It provides social icons that are used to navigate to facebook, twitter, google plus, youtube, instagram and linked pages of the 
rock band. The presence of these social icon was achieved by the use of fontawesome reference
line 8, and 107 to 113 of index.html. The navigation menu is further duplicated at the footer and additional menus were added to link with blog, news, gallery and media.
This architectural design is the primary structure on which the rest of pages are built on but with changes to suit their specific purposes.

showcase.html as the term implies is the online resource that is used to hold and display the pictures, videos, images, songs and audios for the consumption of 
the clients. The architecture contains the paraphernalia of the primary structure of the home page but without the side nav which was not deem neccessary to be activated here seeing that the footer is available to provide the 
functionality for navigation at a lower resolution. 
It introduces the use of Bootstrap and jQuerry to the project which is used to provide a carousel slideshow to cycle through the pictures and images of the rockband 
reference(lines 11 to 14 and 165 to 246). In addition, the html5 video and audio elements are used to display the video and audio respectively.

From line 97 to 102, the contact.html introduced a new functionality that is used to utilize the .html forms mentioned above. Here, html buttons enclosed 
within the section element are wrapped in anchor tags to provide links to the four .html form pages mentioned above so that clicking on each of the button will automatically
open up the reference form that provides the desired service.
In a related manner, the service.html was designed with same structure and ideology but the difference is that service.html page was styled with bootstrap while contact.html is styled with css.

about.html is a simple text base html page that is styled using the css3 column count property. The contents are culled from wikipedia.
from wikipedia.
The four .html forms included are designed using the html5 Form and Table elements. The Table elements is used to provide columns and rows for necessary dat collection.
But the contact-logister.html Form uses additional feature from jQuerry to spice up its functions. It calls the 'animate' property to provide option for registration and login-in into the resource(reference line 399 to 404 of contac-logister.html)

FEATURES LEFT TO IMPLEMENT IN THE FUTURE:
-----------------------------------------
1. Reference lines 97 to 102 of contact.html, the button elements are wrapped in anchor tags to provide hyperlinks to the pages which they are pointing to. The use of this technique for manipulation is present with most of
the anchor button element used in this project. Although the desired result is achieved, the w3c validator disagrees with the use of button as a child element of an acnhor tag. This observation has been noted to implement
in future development.
2. The current state of the Form pages requires further development and styling to make the website more competitive interms of interaction. These also has been noted for future development 

TESTING
-------
1. BROWSERS: This app is tested on chrome 71.0.3578.98, microsoft edge, and fireforx 64.0.2 and the desired result was achieved.
2. w3c validator: The html and css file are validated by direct input at https://validator.w3.org/#validate_by_input and the necessary corrections were made while logics that
 are not corrected are noted for future development (reference FEATURES LEFT TO IMPLEMENT IN THE FUTURE ABAOVE)

TECHNOLOGIES USED
-----------------
The tehnologies used for the design of this app are:
1. html5: 
    +   This is the markup language used to provide the core content and the structure of this application.
        +   https://www.w3.org/html/

2. css3:
    +   https://www.w3.org/Style/CSS/
        +Cascading style sheet 3 is used to style and describe the presentation of the html5 markup in this project
    
3. javascript: Is used with html5 svg element to draw the hamburger menu used for the side nav. It is also used to style the margin and width of the 'title' and 'slide-menu' when the side nav is clicked on.
4. jQuerry: 
    +   https://jquery.com/
        +   simplify DOM manipulation
        +   used with bootstrap to implement the pictorial slideshow on the showcase.html page
    
5. bootstrap
    +   https://getbootstrap.com/
        +   it is used to apply the rule of third to the styling of row and column on the service.html page
        +   used in conjuction with jQuerry to provide the slideshow on showcase.html page
   
6. fontawesome:
    +   https://fontawesome.com/
        +   used to provide styling for the social icon
   

DEPLOYMENT
----------
A streamlined version of this app is has been deployed to github at the following url:
https://github.com/AchileAchile/user-centric.git


CREDIT:
------
+ css gold gradient
    +https://codepen.io/chilliconcode/pen/OWxqYR
    + background radial gradient obtained from css gold gradient
    
+   The code institute tutorial team
    +   https://codeinstitute.net/

+   https://www.pexels.com/
    +additional pictures are obtained from pexels.com

+ wikipedia
 + https://en.wikipedia.org/wiki/The_Monkees
 + information about the Monkees is obtained from the wikipedia

ACKNOLEDGEMENT
--------------
This project work is modelled according the code institute training instruction.





