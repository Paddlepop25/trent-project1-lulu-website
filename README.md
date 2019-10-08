# Lulu | Once In A Lifetime #

### Interactive Front-end Web Development Project - Code Institute ###
By: Linda Hsu

## Demo
A live demo of the finished project can be found [here](https://paddlepop25.github.io/trent-project1-lulu-website/).

![Desktop Demo](https://raw.githubusercontent.com/Paddlepop25/trent-project1-lulu-website/master/assets/images/lulu-website-updated.gif)

## Aim ##

The aim of this project is to build a static website of an imaginary Asian tour of the Scottish singer Lulu. I discovered her music in my late teens and even though she was from a much older era, I found that I enjoyed many of her songs. I have not and probably would not experience her performace in a live concert so this is a figment of my imagination of which cities would have hosted her in this part of the world, as well as the materials used to introduce and promote her to the Asian audience. I named this 'Once In A Lifetime' because as the name suggest, it would be a dream come true if she would ever tour in my region.

## UX ##
This project is designed starting with a mobile-first approach, with extra features for medium and larger sized screens. I intended this website to be modern looking, comfortable on the eyes and easy to navigate around.

Colors were especially used to achieve this objective. I wanted the website to have a primary orange theme color (#ed7d33) which is used to accentuate important information related to the singer with black and white as supporting colors. The bright orange in contrast to the dark tones would highlight elements like buying tickets for her concert tour and reading more news on her life. On the hover state for links and buttons, the orange color would change to a darker orange tone to indicate that a 'call for action' from the user is possible. 

Also, I specifically chose a dark, textered background to set a comfortable mood and smooth reading flow with her pictures in non greyscaled colors. 

To have the users' eyes level to follow the website smoothly downwards, I placed the titles and important information towards the center of the screen 

## UI ##
The navigation bar is responsive for small, medium and large screens following Bootstrap's breakpoints. A hamburger icon with Lulu's theme orange color is available for small and medium screen on the top right corner of the website. A dropdown menu with links to different parts of the website allows the user to navigate there swiftly. When the screen is large-sized and above, the navigation bar displays the links on top of the screen instead. 

At the bottom right corner of the website, there is a small button highlighted with a border of the theme color to allow users to scroll swiftly back up the page. 

Three google [fonts](https://fonts.google.com/?query=poppin&selection.family=Poppins|Rubik|Ubuntu) were chosen for this website. These were chosen for their rounded features which I wanted to represent to the users some traits of Lulu; fun, warm, caring, and satisfying.

The [landing](https://paddlepop25.github.io/trent-project1-lulu-website/) page is designed to 'wow' the user at first glance, so I decided to use a full-width carousel with stock pictures of full-house concerts. To give the user sufficient time to soak in the details of each picture, it is displayed with a comfortable duration before it transits smoothly to the next one. There are also interactive arrows on the left and right sides which enables the user to see the previous/next picture quicker if he/she chooses to. For medium and large screens, the fictional venus are indicated at the bottom part of the photo. This leads to a more intimate picture of Lulu belting her lungs out with information of her first top no. 1 hit with chosen attractive words describing her such as "legendary" and "internationally known." 

Riding on the opening introduction of her dazzling musical career, information of some of her ficiticious Asian tour is displayed in the [tour](https://paddlepop25.github.io/trent-project1-lulu-website/#tour) section. I used Bootstrap's cards to display the tour information for mobile view and Bootstrap's tables to display the tour information for medium and large sized screens. Media queries were used to adjust the grouped buttons as the layout changes over some screen sizes. When the user hovers over the buttons, the theme color changes a darker tone to indicate that they could be clicked on and the user would be directed to Lulu's official fan page which lists more information.

The first parallax image is introduced to suggest to the user a closer look of the audience in Lulu's concerts enjoying themselves and professing their love and admiration for the singer. I deliberately chose audience with hands raised in the air because that is what audiences usually do when they sing along to a familiar song or when they cheer for the singer. 

The [life in pictures](https://paddlepop25.github.io/trent-project1-lulu-website/#lifeinpics) section give a brief description of some of Lulu's acheivements over the years with accompanying pictures, because a picture tell a thousand words. A "read more" link in the theme color is provided for the user to find out more information. The images in this section were strategically placed so they show a transition of a teen Lulu, a young adult Lulu and an older lady Lulu. Also, the first and last pictures are considerably longer in height than the middle one and in the bigger screens, they would seem to 'wrap' around the center picture.

A second parallax of an image with bright lights and hands raised leads the user to some of Lulu's famous albums, and this is followed by the [music](https://paddlepop25.github.io/trent-project1-lulu-website/#music) section with various cd covers and the respective titles. Due to space constraint, I limited the number of cds for small screens, and featured more for medium and larger screens. The images of the cd covers were deliberately arranged to have the ones closer to greyscale placed in the center, where the user's eye line of sight usually would be. The top row features albums with reddish tones and the bottom row features those with greenish tones. When the cd images are hovered over, it does a little spin to inject an element of surprise to the user. The cd titles are linked to amazon so the user could purchase the cd if he/she wishes to. Since the title is a link, when hovered over, it changes to a darker orange color to indicate that a call of action from the user is possible. 

## Wireframes ##
Wireframes were created initially to help me visualise the website in different sized screens. They can be viewed via this [link](https://github.com/Paddlepop25/trent-project1-lulu-website/tree/master/assets/wireframes).

## User Stories ##
These are the user stories that I intended to achieve while building this website:
1. To highlight Lulu's vast music career through pictures, albeit using some stock photos of her concert performances, information of her journey to stardom and recent news to users not familiar with this artiste 
2. To curate Lulu's music, news and information on this website for current Asian fans
3. To build a modern looking website that is easy for the user to navigate around, with links to external sources on purchasing her tour UK tickets, cd albums and other information
4. To get repeated attention from mobile and tablet users about Lulu by having her social media links available in the navigation bar's dropdown menu as well as the footer
5. To showcase my current skills utilizing HTML5, CSS3, Bootstrap and other tools to make a website of one of my favorite singers

## Features ##
* The links in the navigation bar changes to the theme orange color (#ed7d33) when hovered over to indicate that it is a link that the user could click on. This brings them to different sections of the website
* I introduced a smooth scrolling effect so the transition to another section of the website is not abrupt. This applies to the scroll-up button at the bottom right side of the website as well
* When hovering over any links, the cursor changes from a pointer to a hand to indicate that it is not a static word. An action could be made on the link to give the user more information on another page
* A scroll button is provided at the bottom right hand side of the screen to allow the user to scroll to the top of the page without he/she having to manually scroll upwards
* The music section has a short, fun surprise for the user when he/she hovers over it. It stimulates a cd spinning when played. The title of the cd is provided below and it is in the theme orange color which would enable the user to view more information on amazon as well as purchase the cd
* A form is provided for the user to be updated on news of Lulu as well as contact details if he/she wishes to have a reply from an administrator of the fan club.
* The google map indicates where Lulu's first Asian concert would kick off in Singapore
* A social media section is displayed in the footer section which allows the user to look at more Lulu photos and news instantly (caveat is one should have a Spotify app or account for it's link to work)

Future features
* After the current date's concert, the embeded google map would changed to reflect the next concert venue / city
* Display a few videos of Lulu's most famous and notable performances
* Quotes from producers, musicians and other notable artistes whom have worked with Lulu displayed in a picture montage with eye catching styling
* Provide a short clip of some of Lulu's songs when each cd is being hovered over in the music section

## Technologies Used ##
Here are a list of programming languages, frameworks, technologies and tools used for this website.

* HTML5
* CSS3
* JavaScript
* JQuery
* Markdown
    * Used for writing this README.md file
* [Visual Studio Code](https://code.visualstudio.com/)
    * Used as the IDE to write the codes for this website   
* [Bootstrap 4.3.1 framework](https://getbootstrap.com/)
    * Used for it's grid system, page layout with styling and responsive navigation bar.
* [Google Fonts](https://fonts.google.com/)
    * Used 'Ubuntu,' 'Rubik' and 'Poppins'
* [Font Awesome](https://fontawesome.com/)
    * Used for social media icons and other icons
* [Favicon & App Icon Generator](https://www.favicon-generator.org/)
    * Used for generating Lulu's favicon 
* [Microsoft Word](https://products.office.com/en/word) 
    * Used for creating Lulu's brand logo by drawing a rectangle with the theme orange color full in and choosing the [apple chancery](https://fontsgeek.com/fonts/Apple-Chancery-Regular) font for Lulu's iconic "L."
* [Mockflow](https://mockflow.com/)
    * Used to design and create the wireframes for this project
* [Git](https://git-scm.com/)
    * Used for version control to commit to Github
* [Github](https://github.com)
* [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
* [Am I Responsive?](http://ami.responsivedesign.is/?url=#)
    * Used to see across multiple devices with different screen sizes the responsiveness of the website
* [Screen To Gif](https://www.screentogif.com/)
    * Used to capture the responsive screens into a gif file

## Testing ##
This website was tested on different web browsers and on different devices. I also requested friends and co-workers for feedback on what they liked and didn't like about this website. Adjustments were made accordingly until the final product upon project submission.

Devices and browesers:
* iPad 3
    * Safari
* MacBook Air
    * Google Chrome
    * Safari
* MacBook Pro
    * Google Chrome
    * Safari
* MacPro
    * Google Chrome
    * Firefox
* Windows 10 Enterprise
    * Google Chrome
    * Mircosoft Edge
* Samsung Galaxy 8
    * Google Chrome
    * Samsung web browser

Additionally, Google Chrome Devtools was used throughout the project to view this website on a number of stimulated mobile, tablet, laptop and desktop devices to ensure compatibility and responsiveness. Devices include Galaxy S5, Pixel 2, Pixel 2 XL, iPhone 5 / SE, iPhone 6/7/8, iPhone 6/7/8 plus, iPhone X, iPad, and iPad Pro.

I found that a standard font size does not work for all screen sizes, so I added a base `font-size: 16px` on the `html` in the css file, and adjusted accordingly. Where needed to fit the elements neatly in place, I used media queries as well.

A standard table size does not show up neatly for all screen sizes so I used bootstrap's cards for the [tour](https://paddlepop25.github.io/trent-project1-lulu-website/#tour) section and tables for medium and large screens. To have the rows fit neatly in the table, I used media queries to adjust the placement of the fonts and buttons.

All links will open in a new tab having used `target="_blank"` for each 'a tag.' They have been manually tested in each browser to ensure that they point to the correct destination. In cases where the links are related to ficticious information such as booking tour tickets for an Asian tour, the user is directed to Lulu's official [website](https://www.luluofficial.com/).

The form's two inputs are required to be filled up, else an error message would show for each. This was achieved by adding a `required` field in the `input` tag of the form in the `index.html` form.

#### Bugs ####
The scroll button doesn't work well on my iphone and in the other browsers except for Chrome, and I searched for fixes on stackoverflow. I implemented the codes in my files but due to time contrainst, was unable to successfully get it working.

## Deployment ##
Git was used for version control and [Github]((https://github.com)) hosts the repository for all commits

Please click on [Lulu | Once In A Lifetime](https://paddlepop25.github.io/trent-project1-lulu-website/) to find the deployed  website, using Github pages. The pages will automatically be updated upon new commits to the master branch

### How to save the project to a local computer ###
These are steps to follow if you would like to run this code locally: 

#### Download ####
1. Download this repository from the Github repository from [https://github.com/Paddlepop25/trent-project1-lulu-website](https://github.com/Paddlepop25/trent-project1-lulu-website)
2. At the right hand side, click on green button *Clone or download* then *Download ZIP*. The repository will automatically be downloaded into a ZIP folder on your computer
3. Uncompress the ZIP folder
4. Double click on the HTML file to open with the default browser of your computer or right click on the HTML file to choose a preferred browser
5. The rest of the files are available if you would like to make changes to the website according to your liking

#### Clone ####
1. Clone this repository from the Github repository from [https://github.com/Paddlepop25/trent-project1-lulu-website](https://github.com/Paddlepop25/trent-project1-lulu-website)
2. At the right hand side, click on green button *Clone or download* then copy the URL shown in the input box
3. In your IDE of choice, paste `git clone https://github.com/Paddlepop25/trent-project1-lulu-website.git` into your terminal.
4. This repository will automatically be cloned into a folder on your computer
5. To break the connection with this Github repository, enter `git remote rm origin` into your terminal

## Credits ##
Many of the sections describing Lulu were taken from [wikipedia](https://en.wikipedia.org/wiki/Lulu_(singer)) as well as [imdb](https://www.imdb.com/name/nm0525801/bio).

### Codes ###
* Making the CDs spin on hover from [stackoverflow](https://stackoverflow.com/questions/23695090/spin-or-rotate-an-image-on-hover)
* Embeded google map from [embedgooglemap](https://www.embedgooglemap.net/)
* Scroll to the top button from [stackoverflow](https://stackoverflow.com/questions/51536384/how-to-animate-scrolling-to-top-of-page-using-javascript-no-jqueryasp)

### Images ###

Background image
1. https://www.tokkoro.com/5226227-dark-texture-grain-sand-black-pattern-ripple-textured-wallpaper-black-wallpapers-black-background-se.html

Images of Lulu
1. https://www.pinterest.com/pin/198651033546146963/
2. https://www.northernsoul.me.uk/still-waiting-to-be-discovered-pop-royalty-lulu-talks-to-northern-soul/
3. https://www.popexpresso.com/2018/11/03/british-singer-and-actress-lulu-turns-70-today/
4. https://www.last.fm/music/Lulu/+images/91f6988a1f344da59e92f2b077704640

Images of Lulu CDs
1. https://www.amazon.com/Sir-Love-Best-1967-1968/dp/B000089Y9L
2. https://www.amazon.com/Lulu-World-Single-Polydor-Press/dp/B0055SFYVC
3. https://www.amazon.com/Crayons-Perfume-Best-Lulu/dp/B0000033EZ
4. https://www.amazon.com/Collection-Lulu/dp/B0018RCPOS
5. https://www.discogs.com/Lulu-The-Most-Of-Lulu/release/1770838
6. https://www.amazon.com/To-Sir-with-Love/dp/B0028300N4

Carousel images
1. https://unsplash.com/photos/m1WZS5ye404
2. https://pixabay.com/photos/concerts-audience-spectators-lights-1150042/
3. https://pixabay.com/photos/audience-backlit-concert-crowd-1850119/

Parallax images
1. https://unsplash.com/photos/hzgs56Ze49s
2. https://unsplash.com/photos/X1Y9XmMq9wI

**This is for educational use**