# Ironwork Fitness README.md Document

## 5 Planes of UX Design:

#  Aims of my website:

* Website: Ironworks Fitness

* User Goals: To gain knowledge about the gym and what it has to offer. They may wish to look into classes to attend, or contact 
the gym if they have any questions. They may potentially want to know what measures are in place to reduce the spread of coronavirus.

*Site Owner Goals: The site owner will want the people that visit the website to want to sign up for a membership, by informing them about all the 
things the gym has to offer. 

## Strategy Plane:

### Focus:
1. Gallery
2. Contact Information
3. Map/ location of the gym
4. Information about the classes the gym offers
5. Sign Up Modal
6. Social Media links 
7. Social Distancing measures

The focuses listed above are essential for the website to contain as this is the information that a user will be looking for to decide wheather 
they want to become a member at the gym or not.

The target audience of the site will be 16+ as this is the age where gyms will allow you to lift actual weights at the gym. Content should be simplistic so that 
the older generation of visitors can navigate their way around the site relatively easy to find the information they need.

### Definition:
I am creating a website to inform the existing members about classes that the gym has to offer them, in case they want to change up their usual standard
gym workouts with something like indoor cycling with a group or yoga.

The site is also for potential members and aims to get them to sign up for a membership to recieve exclusive members benefits.

A clean and simple colour scheme will help to attract people to the aesthetic of the site.

### Value:
The value of this site to potential members is that they will understand the measures in place for covid-19, and find out what the gyms contact information is.
Information on the classes can also be found easily on the classes page, along with reviews. 

The gallery page will produce some photos to the users of the site to show them what the atmoshphere and comminity is like at the gym.

## Scope Plane:

### features to include:
* Covid-19 measures 
* gallery
* contact info
* Map
* Class Information
* Social Media links
* Clear Navigation
* Sign Up
* Class reviews

Features to include if I have time?
* Events
* Hiring personal trainers
* FAQ

### User Stories - 

Scenario One:                             
Customer Views site and wants to become a member

requirement: 
Option to sign up and become a member. Reminders to the user 
throughout the site and on each page to keep the thought fresh in
their mind

Scenario Two:
User wishes to contact gym regarding a question they have 

Requirement:
Contact information and clear links to social media if they wish to 
reach out that way.

Scenario Three: 
User would like to find out about available classes and times 
for them.

Requirement:
Information about classes, followed by reviews from members that have/ do
participate in the classes regularly

Scenario Four: 
Someone would like to know about the measures in place to reduce the
spread of covid-19 whilst at the gym

Requirement:
Container on the home page with the different ways the gym is working
to reduce transmission of covid-19

## Structure Plane:

The seeable homepage upon landing on the site will have more information creeping into site at the bottom of the it when the page first loads up.
A 'sign up' button will be the central focus of the homepage as this is the end goal after the user has decided whether they wish to become a member or not.

I have opted for a color scheme of light blue, grey and a subtle off-white color. These colors will make espects such as images and buttons pop out, whilst also
keeping all the information clear and readable.

Navigation will be done through a navigation bar at the top, social media icons and buttons throughout the pages of the site. For user friendliness, these will be light blue or white in the nav/ footer
so the user can find them easily.

The presentation of the site will be relatively spread out and easy for the user of the website to digest, and make the UX as clean and clear as possible.

## Skeleton Plane:

The landing page will have a master image of somebody performing an exercise, along with a 'Sign Up' button and a motivational quote.

Further down the page, brief information about the offering of classes to members will be shown, along with a link to the gallery page if the
user wishes to view the images taken at the gym.

Reviews will be shown next to stock photos of people on the classes page, to entice the user into following in their words, and starting a class, whether through a membership or not.

The gallery page will consist of images of people having fun and working out at the gym. This may potentially motivate members to sign up. 

Top priority content will be at the top of each page, as this is the information that is most important for the user to see.

## Surface Plane:

Information will be contextual to each page, starting with the most important information at the top of each page of the site. 

Colors of the site will be dark grey, off white and light blue. This should provide a good amount of color without overwhelming the site with color and making for 
a bad user experience. 

I plan to use the fonts 'Bebas Neue' and 'Noto Sans SC' for the website. I feel the Bebas Neue provides a nice heading, and the Noto Sans SC is a simplistic text for paragraphs etc.

# Problems I encountered whilst building the IronWork Fitness website:

##  General Problems:

1. Problem: 'Active' class not being applied to classes.html when on the page. 

* Solution: Missed a space between 'active' and 'nav-item'.

2. Problem: Social links not leading to facebook, instagram etc. pages.

* Solution: Use of 'youtube.com' as opposed to 'https://www.youtube.com/'. Problem down to rushing. Also added target _blank to all footer socials.

3. Problem: Sign up modal when on mobile dropdown menu does not reveal modal when clicked. 

* Solution: Added "data-toggle="modal" data-target="#signUpModal"" after the classes. Now working.

## Index.html Problems: 

1. Problem: Can not get hero.jpg to display/ cover the jumbotron. 

* Solution: Used tutorial in course to help with the code needed. Lesson: "Updating Our Callout" Module: "User Centric Frontend Development"

2. Problem: Can not get the gallery section to appear next to the classes. 

* Solution: implemented the bootstrap grid system. 

3. Problem: 'See more' buttons for classes and gallery not leading to the pages. 

* Solution: Changed the button element to an anchor tag and styled like a button.

## Classes.html Problems:

1. Problem: Can not get the text for the classes information to move to the left of the div.

* Solution: Created 2 columns, one for the image and class name, and one for the paragraph about the class. Added a class and some padding to each paragraph
and seems to be working fine now.

2. Problem: Could not get part of div to move to the right of the rest of the content for the quotes. Found a piece of code to help fix it with position: right;.

* Solution: "position:absolute; right:0;" Source - https://stackoverflow.com/questions/12710843/want-to-move-a-particular-div-to-right . Plus some other margins put in place 
by myself to make sure it looked good.

## Gallery.html Problems:

1. Problem: Can not get images to appear equal widths apart using bootstrap columns.

* Solution: Put them all in a class and gave them the same margin %'s to create equal spacing.

## Contact.html Problems:

1. Problem: map.png is not loading into page.

* Solution: used .jpg instead of .png as image name within code.

## Images used and sources I got them from:

#### Image Name |           Photographer Name           | Link to Photo

hero.jpg       | Photo by Anastase Maragos on Unsplash      | https://unsplash.com/photos/9dzWZQWZMdE

class.jpg      | Photo by Andrea Piacquadio from Pexels     | https://www.pexels.com/photo/selective-focus-photography-of-woman-in-white-sports-brassiere-standing-near-woman-sitting-on-pink-yoga-mat-864939/

weight.jpg     | Photo by Pixabay from Pexels               | https://www.pexels.com/photo/adult-athlete-body-bodybuilding-414029/

space.png      | Image by Shafin_Protic on Pixabay          | https://pixabay.com/vectors/covid-19-corona-awareness-epidemic-5306538/

sanitiser.png  | Image by HaticeEROL on Pixabay             | https://pixabay.com/illustrations/hand-sanitizer-corona-covid-19-4978511/

mask.png       | Image by febrianes86 on Pixabay            | https://pixabay.com/vectors/face-mask-mask-coronavirus-covid-19-5562104/

roll.png       | Image by dapple-designers on Pixabay       | https://pixabay.com/illustrations/toilet-paper-paper-roll-toilet-5000684/

runningpic.jpg | Photo by Gustavo Fring on Pexels           | https://www.pexels.com/photo/photo-of-people-jogging-4148937/

gympic1.jpg    | Photo by Leon Ardho on Pexels              | https://www.pexels.com/photo/man-and-woman-holding-battle-ropes-1552242/

gympic2.jpg    | Photo by Victor Freitas on Pexels          | https://www.pexels.com/photo/person-holding-barbell-841130/

gympic3.jpg    | Photo by Allan Mas on Pexels               | https://www.pexels.com/photo/asian-man-in-climbing-gym-with-girlfriend-5383781/

gympic4.jpg    | Photo by Andrea Piacquadio on Pexels       | Could not find link after revisiting publishers Pexels account. :(

gympic5.jpg    | Photo by Karl Solano on Pexels             | https://www.pexels.com/photo/woman-doing-push-ups-2780762/

gympic7.jpg    | Photo by Jonathan Borba on Pexels          | https://www.pexels.com/photo/woman-doing-sit-ups-3076516/

gympic8.jpg    | Photo by ShotPot on Pexels                 | https://www.pexels.com/photo/man-in-red-t-shirt-riding-a-stationary-bike-4046657/

gympic9.jpg     | Photo by Andrea Piacquadio on Pexels       | https://www.pexels.com/photo/young-female-athlete-training-alone-on-treadmill-in-modern-gym-3768916/

gympic10.jpg   | Photo by bruce mars on Unsplash            | https://unsplash.com/photos/pFyKRmDiWEA
