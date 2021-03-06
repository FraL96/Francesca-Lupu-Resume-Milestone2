# ReadMe - My resume
----------------------

![My Resume](./readme/responsive.png)

This website has been created to display my resume.
Its scope is to provide to possible employers a better experience than the traditional method of a Curriculum Vitae
printed on a sheet of paper.

You can visit my resume by clicking [here](https://fral96.github.io/Francesca-Lupu-Resume-Milestone2/).

--------------------------------------------------------------------------------------------------------------------------------------
## 1. UX

### 1.1 Project goals

This resume website has been designed to help both potential employers and myself.

The idea is that an employer with a vacant position in his company could view my website
and get an idea about me and about my coding skills.

This will certainly also be helpful personally as it could be a useful tool in securing future employment in this field.

In fact, in my opinion while looking for a position in such creative work field, there is a need for more than a simple paper resume.

----------------------------------------------------------------------------------------------------------------------------------------------

### 1.2 User stories

#### General

* As a moderator I want visitors and potential employers to view my resume, so they can understand more about me and possibly offer me a job.
* As a visitor I want to understand more about the moderator so I can appreciate if she can be the right person for my vacant place.
* As a moderator, I want my website to be easily accessible, that's why I will make it responsive for a large range of devices.
* As a visitor, I want to be able to view the moderator's website/resume even if I am on the go, that's why I want it to be possible to access from my smartphone or tablet, besides my pc.
* As a moderator I want the visitor to feel like he/she knows a bit about me so I will provide access to my personal social media.
* As a visitor I want to browse through the moderator’s website so I can get an idea about both her skills and her personality.

#### Homepage

* As a moderator I want my webpage to be eye catching but still be simple and clean so it will impress and attract the visitor. 
* As a visitor I want to be attracted by the design first so I will be more persuaded to look into the website.
* As a moderator I want my website to be easy to consult so I will provide the visitor with an intuitive navigation menu to allow him/her to access the various areas.
* As a visitor I want to easily browse between the website sections that’s why I want the menu to be simple and functional.

#### About me

* As a moderator I want the visitors to understand who I am that is why I will provide this section with a picture of me and an introduction.
* As a visitor it is nice to put a face to a name that is why I would like to see a picture and read a few lines about her in order to know who I am reading about.
* As a moderator I want the visitor to know, besides professional information about me, also something more personal, that is why I want to add my hobbies.
* As a visitor I want to have a little but global knowledge about the person I am considering for my vacant position, for this motivation I would also like to know what her passions and her interests are.

#### Education

* As a moderator I want the visitors to easily see on a map the places where I studied so that they can understand more about my background.
* As a visitor I want to easily see where the moderator got her education and built her skills so I can have more details about her and her studies.
* As a moderator I want the visitor to be able to get all the necessary information about where I recieved my eduaction; for this reason I will provide phone number and address for each of the places.
* As a visitor I want to have access to some details on the places where the moderator studied in case I would need to contact them for references.

#### Work Experience

* As a moderator I want to display all my working experiences on a map so that the visitor will see at a glance all the places I worked before.
* As a visitor and possible future employer, I want to see where the moderator worked before as I can get an idea of her background and experiences.
* As a moderator, I want the visitors to be able to get information about the places I worked, that's why I will provide every place with some extra details.
* As a visitor, if I read about a place that I am not familiar with I would like to be able to research it ; that's why I would like to have some extra information about the moderators previous work places.

#### Skills

* As a moderator I want the visitors and possible future employer to know my strength points that is why I want to introduce and explain my top 6 skills.
* As a visitor and possible future employer I am looking for a person with a specific range of skills and this section will help me understand if they match the ones of the moderator.

#### Contact me

* As a moderator I want to give the possibility to all visitors to easily contact me in case they want to work with me or if they have questions about my resume; that is why in this section I want to add a contact form.
* As a visitor, if I enjoyed the moderator resume, I want to be able to easily contact her to schedule a meeting for example; for this reason I would need a contact feature.

-------------------------------------------------------------------------------------------------------------------------------------------------------

### 1.2 Wireframes

The wireframes for this project were designed on Balsamiq.
Click on the following link to view them.

* [Desktop](./wireframes/desktop-wireframe.pdf)
* [Tablet](./wireframes/tablet-wireframe.pdf)
* [Mobile](./wireframes/mobile-wireframe.pdf)

------------------------------------------

## 2.Features

### 2.1 Present Features

* Navigation menu: In the homepage the links to the pages are in some colored balls.
The first one, with a picture of mine in it contains the link to the home,
the other ones contain the name and link to the other pages and are of the color of the page they represent.
When hovering on them the text "bounces in" and gets white.
The navigation menu changes in the other pages and it becomes a line on top of the screen with the names (and links) to the other pages.
When you are for example in the "About me" page, the name of the page in the navigation menu will become white.
For the home link I am using a logo with my name.
This menu transforms in a collapsable hamburger menu on mobile devices.

* Homepage background: The background of the homepage is been created with Javascript and is black with some colored balls jumping around.
When hovering on one of these balls, they grow.
This background is been chosen to match the navigation menu of the homepage. The background jumping balls have a 50% opacity in order to don't distract from the menu ones.

* Footer: The footer is located on the bottom of every page. It is semi-transparent and it includes the links to my [Facebook](https://www.facebook.com/), [Instagram](https://www.instagram.com/) and [Twitter](https://www.twitter.com/) pages.
The icons of the social networks are located into small grey circles that become black when hovering on them.

* About me: In this page is displayed a picture of me on the left that scrolls down when the page is being scrolled.
On the right instead there is an introduction text about myself. At its bottom there are some pictures of my favorite hobbies displayed into ovals.
Underneath every picture there is a card with a little text about each of them.

* My Education: In this page, on the top is displayed a map from [Google Maps](https://www.google.com/maps) with some markers representing the last 3 places where I studied.
When clicking on a marker, an infowindow will open and will display the name, type, address and phone number of each place.
The markers contain some letters (A, B and C) and those are to connect them to the text located underneath the map.
There is a little text for each location with the name, location, date I studied there and the qualification I got after completing the studies.

* My Work Experience: This page is very similar to the previous. The only differences are that this time on the map are represented my previous employment places.
These markers also contain letters to connect them to the texts under the map. In these texts this time there are also little lists with the tasks I had when working in that specific place.

* My Skills: In the skills page I listed my top 6 skills. In order to identify them better and improve the design, on top of each skill there is an icon that represents it.

* Contact me: In this page the visitors of the website can contact me. There is a form and filling up name, email address and message (and pressing "Send") I will receive the message on my email.
The form has some validation requirements: the name has to be filled in and do not contain digits, the email address will be valid just if all the jQuery requirements are met and the message has to be long at least 10 characters and do not be composed by only white spaces.
After all the requirements are met and the "Send" button is been pressed an alert will inform the visitor if the message is been sent or not.
If the message is been sent correctly the form will be cleared after pressing "OK" on the alert. 


---------------------------------------------------------------------------------------------------------------------------

### 2.2 Future Features

* In the future I would like to switch the introduction of the "About Me" page with a video introduction.
* I would like to add a page with my portfolio where to display (or to link to) my best and most recent projects.
* Finally I would like to add a JS animation when sending a message in the "Contact me" page.

------------------------------------------------------------------------------------

## 3. Technologies used

* [HTML5](https://en.wikipedia.org/wiki/HTML5) - used to write the code for the website.
* [CSS3](https://en.wikipedia.org/wiki/CSS) - used to style the website.
* [JavaScript](https://en.wikipedia.org/wiki/JavaScript) - used to add interactive elements to the website.
* [JQuery](https://jquery.com/) - used to add interactive features.
* [Balsamiq](https://balsamiq.com/) - used to design the wireframes.
* [Gitpod](https://www.gitpod.io/) - used to design and host the project.
* [GitHub](https://github.com/) - used to hold the repository and deploy the project (GitHub Pages).
* [Bootstrap](https://getbootstrap.com/) - used to create the structure of the website.
* [Google fonts](https://fonts.google.com/) - used for the website's fonts.
* [Google Cloud Platform](https://en.wikipedia.org/wiki/Google_Cloud_Platform) - used to add the maps.
* [AmIResponsive](http://ami.responsivedesign.is/#) - used for the READ ME picture.
* [Fontawesome](https://fontawesome.com/v4.7.0/) - used for the icons.
* [Email JS](https://www.emailjs.com/) - used to connect the form to my email.

-----------------------------------------------------------

### 4.Testing

#### Code Validators

##### HTML files with [W3C](https://validator.w3.org/) :

![passed test html](./readme/passed.png)

* All the HTML files passed the validator test.

##### CSS files with [W3C](https://jigsaw.w3.org/css-validator/#validate_by_input) :

![passed test css](./readme/css.png)

* Both the CSS files passed the validator test.

#### JS files with [JSHint](https://jshint.com/) :

* The form.js file passed the validator without errors.

* The home.js file passed the validator without errors.

* The map-edu.js and map-we.js files passed the validator without errors. They only had one warning. I decided to don't modify anything about it.

![map-edu.js](./readme/js.png)
-------------------------------------------------------------

#### Responsiveness

To test the responsiveness of the website I used [DevTools](https://developers.google.com/web/tools/chrome-devtools).
To check the devices where it was better supported instead, I used [Responsive Design Checker](https://www.responsivedesignchecker.com/).
The website is been also tested on my personal devices.

Below in the table you can find some examples of the devices where the website looks good and all features work well.

Mobile | Tablet | Desktop
-------|--------|--------
Iphone 3 to X | Ipad 8th Gen. | 19" to 24" desktop
Samsung Galaxy S5-S6-S7 | Ipad Pro | 10" to 15" notebook
Google Pixel| Ipad Mini |
Huawei P Smart | Amazon Kindle Fire

-----------------------------------------------------------------------------------------

The website was also tested in the following browsers:

* [Chrome](https://www.google.com/intl/en_ie/chrome/)
* [Safary](https://www.apple.com/safari/)
* [Opera](https://www.opera.com/)
* [Firefox](https://www.mozilla.org/en-US/firefox/new/)
* [Internet Explorer](https://www.microsoft.com/en-ie/download/details.aspx?id=41628)
* [Edge](https://www.microsoft.com/en-us/edge)

The website display perfectly and all the features work great on all browsers.

------------------------------------------------------------------------

#### Testing User stories

#### General

* As a moderator I want visitors and potential employers to view my resume, so they can understand more about me and possibly offer me a job.
* As a visitor I want to understand more about the moderator so I can appreciate if she can be the right person for my vacant place.

The visitor and navigate through the pages of the website and learn different aspects about me.

* As a moderator, I want my website to be easily accessible, that's why I will make it responsive for a large range of devices.
* As a visitor, I want to be able to view the moderator's website/resume even if I am on the go, that's why I want it to be possible to access from my smartphone or tablet, besides my pc.

The website is fully responsive and it works and displays great on many devices, from the mobile to the big desktop screen.

* As a moderator I want the visitor to feel like he/she knows a bit about me so I will provide access to my personal social media.

At the bottom of every page is displayed the footer containing my social media. By clicking on the selected logo the visitors can view my Facebook, Instagram and Twitter page.

* As a visitor I want to browse through the moderator’s website so I can get an idea about both her skills and her personality.

The resume is designed to show both my hard and soft skills to give a global idea about me to the visitor.

#### Homepage

* As a moderator I want my webpage to be eye catching but still be simple and clean so it will impress and attract the visitor. 
* As a visitor I want to be attracted by the design first so I will be more persuaded to look into the website.

The homepage background is been designed to be eyecatching and coherent with the rest of the page but to not distract from the main menu.
The background with the bouncing balls was used to seem original and to persuade to explore more into the website.

* As a moderator I want my website to be easy to consult so I will provide the visitor with an intuitive navigation menu to allow him/her to access the various areas.
* As a visitor I want to easily browse between the website sections that’s why I want the menu to be simple and functional.

The navigation menu is intuitive and located in the center of the page. By clicking on the name of the selected page he/she will immediately accede it.

#### About me

* As a moderator I want the visitors to understand who I am that is why I will provide this section with a picture of me and an introduction.
* As a visitor it is nice to put a face to a name that is why I would like to see a picture and read a few lines about her in order to know who I am reading about.

On this page I displayed a picture of myself so that the visitors can put a face on the name. I also wrote a little introduction about me and explaining the working position I am looking for.

* As a moderator I want the visitor to know, besides professional information about me, also something more personal, that is why I want to add my hobbies.
* As a visitor I want to have a little but global knowledge about the person I am considering for my vacant position, for this motivation I would also like to know what her passions and her interests are.

Underneath this intro, the visitor can find also a little section with my main 4 hobbies, so he/she can have an idea about my interests.

#### Education

* As a moderator I want the visitors to easily see on a map the places where I studied so that they can understand more about my background.
* As a visitor I want to easily see where the moderator got her education and built her skills so I can have more details about her and her studies.

In this page the visitor can view on a map the last 3 places I studies.Underneath the map the visitor will find information about what I did in those locations (what I studied there and the qualifications I got).

* As a moderator I want the visitor to be able to get all the necessary information about where I recieved my eduaction; for this reason I will provide phone number and address for each of the places.
* As a visitor I want to have access to some details on the places where the moderator studied in case I would need to contact them for references.

By clicking on the marker it will be displayed some contact information for each place. The visitor will have access to phone number and address of every location.

#### Work Experience

* As a moderator I want to display all my working experiences on a map so that the visitor will see at a glance all the places I worked before.
* As a visitor and possible future employer, I want to see where the moderator worked before as I can get an idea of her background and experiences.

In this page, as the previous one, some locations will be shown on a map. The visitor this time will be able to see the last 3 places where I worked.
Moreover under the map the visitor will find some details about the tasks that I had when I was working in those places.

* As a moderator, I want the visitors to be able to get information about the places I worked, that's why I will provide every place with some extra details.
* As a visitor, if I read about a place that I am not familiar with I would like to be able to research it ; that's why I would like to have some extra information about the moderators previous work places.

By clicking on the marker the visitor will be able to get address and phone number of the places.

#### Skills

* As a moderator I want the visitors and possible future employer to know my strength points that is why I want to introduce and explain my top 6 skills.
* As a visitor and possible future employer I am looking for a person with a specific range of skills and this section will help me understand if they match the ones of the moderator.

When entering this page, the visitor will find one or two paragraphs about my top 6 skills so he/she can appreciate if they meet the ones they are looking for.

#### Contact me

* As a moderator I want to give the possibility to all visitors to easily contact me in case they want to work with me or if they have questions about my resume; that is why in this section I want to add a contact form.
* As a visitor, if I enjoyed the moderator resume, I want to be able to easily contact her to schedule a meeting for example; for this reason I would need a contact feature.

In this section the visitor will have the possibility to contact me. If he/she wants to contact me it will be enough to fill up their name and email in the dedicated areas and write their message in the bigger section and click "Send".
I will immediately receive that message in my personal email.

--------------------------------------------------------------------------

#### Bugs

* At the beginning I had a problem in making work well the hamburger menu on the mobiles.
I could see the icon but nothing happened when I pressed.
By searching on [Bootstrap](https://getbootstrap.com/) I found out that I had to add the JS Bootstrap CDN to my code to make it work.

* I also had some issue in positioning the text "Work Experience" in the ball in the "Homepage".
I tried to use "line-height" to position the text of all the page names at the center of their ball.
However being "Work Experience" written on two lines, by applying that styling the space was applyed also between the 2 lines of this text, placing the word "Work" in the center of the ball,
while the word "Experience" in the bottom, out of the ball. I solved this by using "margin-top" instead.

* I also had a little issue with the background of the Homepage. At first I set it on white with bright colored balls.
Then, also with the help of my mentor, I noticed that it made it a bit difficult and a bit distracting to distinguish the background balls from the menu ones.
To solve this issue I set the background on black and applyed a 50% opacity to the background balls.
This will maintain the coherence of the page by reducing the distraction.

* When I was about to submit my project I realised that after sending an email from the contact form, an error showed up
in the console saying that the sendMail function was not defined. After trying more times to modify my js code, I also tried to remove the "onSubmit"
attribute from the form. This solution seemed to solve my problem; the error message disappeared and the contact form continued to work perfectly fine.

##### Bugs during the validation phase

* The about-me.html file had 2 errors at first: I forgot to add the alt attribute to the images and I set their width to "100%" instead of to "100"(these errors were repeted for each image).
Once I corrected that, the file passed the validator test.
![about-me.html](./readme/aboutme.png)

* The work-experience.html file had 1 error at first: the W3C said that a closing paragraph tag was found but not an opening one (this error was repeted 3 times).
The opening paragraph tag was actually there but I think the error was created by the fact that I placed an unordered list inside the paragraph.
Once I moved the unordered list out of the paragraph the error disappeared.
![work-experience.html](./readme/workexperience.png)

* The contact.html file had 1 warning: In the snippet from EmailJS that connects the form to my email, inside the script tag there was also a type attribute (this error was found 2 times).
I removed it and luckily the error disappeared and the form was still working correctly.
![contact.html](./readme/contactme.png)

---------------------------------------------------------------------------


### 5.Deployment

#### To deploy the project

I deployed this website on Github pages. 
The procedure was the following:

1. Google search "Github" and click the first result.
2. Log in with my username and password.
3. Select the repository "Francesca-Lupu-Resume-Milestone2".

![Select Repository](./readme/clone-and-deploy-1.png)

4. Click on settings (on top of the green button).

![Click Settings](./readme/deploy-2.png)

5. Scroll down to "Github Pages".
6. Select Branch as Master and save.
7. Refresh the page.
8. Scroll down to the same section.
9. A message will appear saying "Your site is published at: https://fral96.github.io/Francesca-Lupu-Resume-Milestone2/".

![Published website](./readme/deploy-3.png)

10. Click on that URL and you will be redirected to the website.

![Website](./readme/deploy-4.png)

--------------------------------------------------------------------

#### To clone the project

1. Google search "Github" and click the first result.
2. Log in with my username and password.
3. Select the repository "Francesca-Lupu-Resume-Milestone2".

![Select Repository](./readme/clone-and-deploy-1.png)

4. Click on the "Code" button on the right.

![Click Green Button](./readme/clone-2.png)

5. Copy the HTTPS link.
6. Open Git Bash from your computer.
7. Type "git clone" and paste the copied link.

![Git Clone](./readme/clone-3.png)

8. Press enter and the file will be downloaded on your computer.

![Downloaded file](./readme/clone-4.png)

--------------------------------------------------------------------------

### 6.Credits

#### 6.1 Content 

This website is been created by me. The general structure is been inspired by the [Rosie Resume](https://github.com/FraL96/Rosie_resume) from [Code Institute](https://courses.codeinstitute.net/program/FullstackWebDeveloper) and from the [Milestone 1](https://github.com/FraL96/Milestone_1_StreamingPal_Website) created by me.

The homepage background is been created by [Roger van Hout](https://codepen.io/b4rb4tron/pen/wjyXNJ) and then modified by me to adapt it to my project.

To realize the maps in the "My Education" and "My Work Experience" pages I got the [Google](https://developers.google.com/maps/documentation/javascript/examples/marker-simple) snippet on how to create a map with a marker,
then I combined it with a snippet from [ASP Snippets](https://www.aspsnippets.com/Articles/Google-Maps-API-V3-Add-multiple-markers-with-InfoWindow-to-Google-Map.aspx) to add the infowindows.
The maps have then been customized by me.

The contact form is been implemented with [EmailJS](https://www.emailjs.com/) to connect it to my personal email. Moreover I followed the tutorial to add the [JQuery Validator](https://jqueryvalidation.org/).
[W3School](https://www.w3schools.com/) and [Stack Overflow](https://stackoverflow.com/) helped me when I got stuck or I needed an advice.

-------------------------------------------------------------------

#### 6.1 Media

The [uno.jpg](./assets/pics/uno.jpg) and [netflix.jpg](./assets/pics/netflix.jpg) pictures have been taken from [Unsplash](https://unsplash.com/) while the other pictures that have been used belong to me.

To design the logo I used [Canva](https://www.canva.com/).

The icons used in the "My Skills" area are from [Fontawesome](https://fontawesome.com/v4.7.0/).

#### 6.2 Acknowledgments

I have to thank [Precious Ijege](https://www.linkedin.com/in/precious-ijege-908a00168/) that gave me great advices for this milestone.

Thank you to my partner [Cathal Moore](https://www.linkedin.com/in/cathal-moore-674949197/) for always helping me and sustaining me in every possible way.

To my parents [Monica and Gabriel](https://www.facebook.com/lupu.emonica), for never stopping to believe in me.

To [Declan Moore](https://www.linkedin.com/in/declan-moore-83728b80/) for introducing me to Code Institute.
