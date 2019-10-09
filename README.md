# Peter Kellett - User Centric Frontend Development Milestone Project

## PROJECT PURPOSE
The purpose of this project is to construct a website in order to provide a brief overview about a musical band. It includes short intro, the band discography, a brief bio on each band member, and a selection of videos. There is also provision for a user to sign up to an electronic fanzine editorial.
It shall also demonstrate my ability to structure and compile the necessary HTML and CSS code to construct a website to showcase the above features and which is responsive to various devices.

## Technologies
### Bootstrap v4.3.1
https://getbootstrap.com/docs/4.3/getting-started/introduction/  
Bootstrap is used in this project for the following:
- navbar
- Grid Layout
- Discography cards
- Horizontal Biography cards
- Contact Us form

### FontAwesome v5.11.2
https://fontawesome.com/icons?d=gallery  
FontAwesome was used for the Social Media icons
- Facebook
   fab fa-facebook
- Twitter
    fab fa-twitter
- Instagram
    fab fa-instagram
- Youtube
    fab fa-youtube

### Google Fonts
https://fonts.google.com  
Google fonts is used for the following font purposes:
- Section Headings Permanent+Marker
- Paragraphs Rubik

### AWS Cloud9
This website has been constructed using AWS Cloud9 IDE.

### GitHub repository 
This website is hosted on GitHub  
Project name: PeterKellett/Project-1  
Demo link: https://peterkellett.github.io/Project-1/

## USER STORIES (Requirements)
A user requires the need to be able to easily navigate between the respective sections in any order without the need to return to a home section.
A user needs to be able to read an overview of the band.
A user needs to be able to view information on the bands albums.
A user needs to be able to view information on the band members.
A user needs to be able to view videos of the band.
A user needs to be able to sign up to a fanzine electronic magazine.

## UX
This website shall contain 1 consisting of 5 sections.
1. Home page
    - Navigation menu
    - Intro (Home)section
    - Discography section
    - Biography section
    - Videos section
    - Contact Us section

## WIREFRAMES
![home page wireframe](https://res.cloudinary.com/dfboxofas/image/upload/v1570030578/Project-1-readme/project-1-wireframe-1.1_wzxcoy.jpg)


## FEATURES
### Navigation bar
The nav bar is positioned sticky top so it is always visible. it consists of:
- Navbar brand image:![home page wireframe](https://res.cloudinary.com/dfboxofas/image/upload/v1570020458/thin-lizzy/thin-lizzy-logo-red-black_s6s5hm.jpg)
- Social media icons
Sourced from FontAwesome https://fontawesome.com/icons?d=gallery
    - Facebook
    - Twitter
    - Instagram
    - Youtube
- Nav links
    - Home
    - Discography
    - Biography
    - Videos
    - Contact Us

### Navigation Menu
The navigation menu is composed of pill style links directing users to the relevant section of the page selected.
- background-color: black (#000)
- link color: (#e61f02)
- link color active: #fff
- link background-color active: #a90e0e

### Home Page/home
index.html#home-bookmark
The main section of the homepage contains a hero image and a brief overview description of the band Thin Lizzy.
- ![Home section image](https://res.cloudinary.com/dfboxofas/image/upload/v1570014696/thin-lizzy/thin-lizzy-eyes-closed_1_mf8jvp.jpg)
- ![Thin Lizzy header image](https://res.cloudinary.com/dfboxofas/image/upload/v1570021502/thin-lizzy/thin-lizzy-landscape-logo_u6fxfh.jpg)
- Section text
    - font-family: Rubik;
    - color: #fff;
    - text-align: left;
- Paragraph image ![James Hetfield Metallica](https://res.cloudinary.com/dfboxofas/image/upload/v1570021620/thin-lizzy/james-hetfield-phil-lynnot_xtgjug.jpg)
    - float: right


### Home Page/Discography
index.html#discography-bookmark
The discography section contains a bootstrap card for each of the 12 albums the band has released. They are styled bootstrap cards consisting of an image, an album title, and a button which opens a model displaying the album song list.

#### Discography items
- Thin Lizzy
- Shades of a Blue Orphanage
#### Album images

### Home Page/Biography
index.html#biography-bookmark
The biography section displays 4 no. band members on horizontal bootstrap cards.
- ![background image](./images/Thin_Lizzy_1978-Live_and_Dangerous_lineup.jpg)
- card background-color: #00000085;

### Home Page/Videos
index.html#videos-bookmark
6 no. videos are displayed.
- ![background image](../images/video-background.jpg)
- width: 100%;
- height: 350px;

### Contact Us page
contact.html#contact-us-bookmark
The contact us page consists of a form with 3 input fields and a submit button.
- ![background image](../images/thin-lizzy-live-bw.jpg)
- form background-color #00000085
- Input fields have attribute [required]

### Footer
The footer consits of 3 section.
- Sponsors
- Newsletter
    - Email field
    - Submit button
- Social media links
    - Facebook icon link
    - Twitter icon link
    - Instagram icon link
    - Youtube icon link


# Testing
## Tools
Testing has been carried out using the following devices/browsers
- Desktop
    - Chrome
    - Edge
    - Mozilla
- Desktop Chrome emulator
- Huawei P30 lite

## Testing screenshots
### Desktop
- Chrome #Home
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570031803/Project-1-readme/screenshot-xl-home_gmlxbf.jpg)
- Chrome #Discography
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570032208/Project-1-readme/screenshot-xl-discography_lv9tw0.jpg)
- Chrome #Biography
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570032394/Project-1-readme/screenshot-xl-biography_rw4oel.jpg)
- Chrome #Videos
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570032503/Project-1-readme/screenshot-xl-videos_wz8hhi.jpg)
- Chrome #Contact-us
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570032669/Project-1-readme/screenshot-xl-contact_us_jce4ia.jpg)
- Chrome #Footer
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570032759/Project-1-readme/screenshot-xl-footer_hwbktp.jpg)

### @ medium breakpoint
- Chrome emulator #Home
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570033071/Project-1-readme/screenshot-md-home_hu2qoc.jpg)
- Chrome emulator #Discography
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541268/Project-1-readme/screenshot-md-discography_e4whoe.png)
- Chrome emulator #Discography-songlist
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541292/Project-1-readme/screenshot-md-song-list_eynx7b.png)
- Chrome emulator #Biography
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541280/Project-1-readme/screenshot-md-biography_mezvw7.png)
- Chrome emulator #Videos
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541307/Project-1-readme/screenshot-md-videos_tvfqct.jpg)
- Chrome emulator #Contact us & Footer
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541344/Project-1-readme/screenshot-md-contact-us-footer_sghjts.jpg)

### Huawei P30 lite mobile devices
- Android Chrome #Home
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541692/Project-1-readme/Screenshot_home_1_.android.chrome_xskbl4.jpg)
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541697/Project-1-readme/Screenshot_home_2_.android.chrome_lxowie.jpg)
- Android Chrome #Discography
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541709/Project-1-readme/Screenshot_discography_1_.android.chrome_egbbja.jpg)
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541708/Project-1-readme/Screenshot_discography_2_.android.chrome_vssapw.jpg)
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541709/Project-1-readme/Screenshot_discography_3_.android.chrome_vsdmxg.jpg)
- Android Chrome #Discography-Song list
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541946/Project-1-readme/Screenshot_song-list.android.chrome_auasf3.jpg)
- Android Chrome #Biography
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541730/Project-1-readme/Screenshot_biography_1_.android.chrome_sz81oe.jpg)
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541731/Project-1-readme/Screenshot_biography_2_.android.chrome_wejs8r.jpg)
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541730/Project-1-readme/Screenshot_biography_3_.android.chrome_vkyyzi.jpg)
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570541730/Project-1-readme/Screenshot_biography_4_.android.chrome_jsrfqi.jpg)
- Android Chrome #Videos
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570542063/Project-1-readme/Screenshot_videos_1_.android.chrome_hbiae6.jpg)
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570542064/Project-1-readme/Screenshot_videos_2_.android.chrome_siemum.jpg)
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570542064/Project-1-readme/Screenshot_videos_3_.android.chrome_trqxlz.jpg)
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570542064/Project-1-readme/Screenshot_videos_4_.android.chrome_toqpib.jpg)
- Android Chrome #Contact Us
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570542116/Project-1-readme/Screenshot_contact-us.android.chrome_jvcecs.jpg)
- Android Chrome #Footer
![Screenshot](https://res.cloudinary.com/dfboxofas/image/upload/v1570542167/Project-1-readme/Screenshot_footer.android.chrome_aubiev.jpg)

## Functional tests
### Test Nav bar navigation
1. Click on 'Home' link in navbar
2. Verify page navigates to Home section

1. Click on 'Discography' link in navbar
2. Verify page navigates to Discography section

1. Click on 'Biography' link in navbar
2. Verify page navigates to Biography section

1. Click on 'Videos' link in navbar
2. Verify page navigates to Videos section

1. Click on 'Contact Us' link in navbar
2. Verify page navigates to Contact Us section

### Test Scroll spy indexing and offset
1. Scroll to top of page
2. Verify 'Home' link in navbar is highlighted with color background
3. Scroll down the page until 'Albums' header is at center of screen
4. Verify 'Discography' link in navbar is hightlighted with color background
5. Scroll down the page until 'Biography' header is at center of screen
6. Verify 'Biography' link in navbar is hightlighted with color background
7. Scroll down the page until 'Videos' header is at center of screen
8. Verify 'Videos' link in navbar is hightlighted with color background
9. Scroll down the page until 'Contact Us' header is at center of screen
10. Verify 'Contact Us' link in navbar is hightlighted with color background

### Test Social Media Links
1. Click on 'Facebook' icon in navbar and footer
2. Verify https://www.facebook.com/ThinLizzyOfficial/ opens in a new tab
3. Click on 'Twitter' icon in navbar and footer
4. Verify https://twitter.com/thinlizzy_?lang=en opens in a new tab
5. Click on 'Instagram' icon in navbar and footer
6. Verify https://www.instagram.com/explore/tags/thinlizzy/top/ opens in a new tab
7. Click on 'Youtube' icon in navbar and footer
8. Verify https://www.youtube.com/results?search_query=thin+lizzy opens in a new tab

### Test Videos functionality
1. Navigate to Videos section
2. Click the 'Play' icon in the video frame
3. Verify video plays
4. Verify audio is played
5. Click on imported video settings - Pause, Replay, and Full Screenshot
6. Verify imported video settings functionality

### Test Contact Us Form
1. Test that fields are set as Required Fields
    1. Navigate to 'Contact Us' section
    2. Click the 'Submit' button
    3. Verify 'Field required' message is displayed for empty field [First Name]
    4. Enter text to First Name field
    5. Click 'Submit' button
    6. Verify 'Field required' message is displayed for empty field [Surname]
    7. Enter text to Surname field
    8. Click 'Submit' button
    9. Verify 'Field required' message is displayed for empty field [Email]

2. Test that Email field is set for email format
    1. Navigate to 'Contact Us' section
    2. Enter text to First Name field
    3. Enter text to Surname field
    4. Enter text without @ symbol to Email field
    5. Verify error message is displayed
    6. Enter text with @ symbol to Email field
    7. Verify Form submission accepted (for test purposes the page page refreshes)

# Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

# Credits
## Content
- The text for the Home section was sourced courtesy of the Irish Rock n Roll Museum website home page https://irishrocknrollmuseum.com/museum/thin-lizzy/
- The text for the Philip Lynnot biography section section was sourced from Wikipedia https://en.wikipedia.org/wiki/Phil_Lynott
- The text for the Scott Gorham biography section section was sourced from Wikipedia https://en.wikipedia.org/wiki/Scott_Gorham
- The text for the Brian Robertson biography section section was sourced from Wikipedia https://en.wikipedia.org/wiki/Brian_Robertson_(guitarist)
- The text for the Brian Downey biography section section was sourced from Wikipedia https://en.wikipedia.org/wiki/Brian_Downey_(drummer)

## Media
The discography images used in this site were obtained from:
- Thin Lizzy album cover By Source, Fair use, https://en.wikipedia.org/w/index.php?curid=1066111
- Shades of a Blue Orphanage album cover By Source, Fair use, https://en.wikipedia.org/w/index.php?curid=1066198
- Vagabonds of the Western World album cover By Source, Fair use, https://en.wikipedia.org/w/index.php?curid=12433589
- Nightlife album cover By Source, Fair use, https://en.wikipedia.org/w/index.php?curid=1066281
- Fighting album cover By Source, Fair use, https://en.wikipedia.org/w/index.php?curid=23489104
- Jailbreak album cover By Scan, Fair use, https://en.wikipedia.org/w/index.php?curid=1066653
- Johnny the Fox album cover By Source, Fair use, https://en.wikipedia.org/w/index.php?curid=1066656
- Bad Reputation album cover By Source, Fair use, https://en.wikipedia.org/w/index.php?curid=1066657
- Live & Dangerous album cover By Source, Fair use, https://en.wikipedia.org/w/index.php?curid=1066660
- Black Rose album cover By Source, Fair use, https://en.wikipedia.org/w/index.php?curid=1066665
- Chinatown album cover By Source, Fair use, https://en.wikipedia.org/w/index.php?curid=1066668
- Thunder & Lightning album cover By Source, Fair use, https://en.wikipedia.org/w/index.php?curid=1066687

The Biography images used on this site were obtained from:
- Phil Lynott By Helge Øverås - Own work, CC BY 3.0, https://commons.wikimedia.org/w/index.php?curid=3474417
- Scott Gorham https://www.musicradar.com/news/guitars/me-and-my-guitar-scott-gorham-634804
- Brian Robertson https://images.app.goo.gl/4kzw6SD9MKdCmDNq6
- Brian Downey https://images.app.goo.gl/xsTnUkudm1AvCT4bA

Acknowledgements