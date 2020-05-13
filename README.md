# [Portishead (Band) Website](https://kieran-murray-code.github.io/CI-MS1-Portishead-Website/)

This is a project website for the UK band Portishead. The project aims to develop a modern mobile first website for the band for long time fans as well new fans just discovering thier music to find out information on the bands music and tour dates and band memebers.


## UX:

###  User Stories 
- 1. As a fan of the band I wish to find out about if can see them play
    live.
 
 - 2. As a new fan of the band I want to find out all the music that the band has made and where to listen to or buy the music.

- 3.  As fan of the band or a memeber of the press I want to see and download photos of the band.

-  4. As a new fan I want to find out about the bands history and information on the band memebers.

- 5.  As a fan I wish to find out news on the band, if they are working on new music, if a new tour is happening etc.

- 6.  As a fan I wish to purchase **merchandise** from the band such as t-shirts, posters and music releases.


## Features:

  

### Common Features

  

-  Each page has a responsive navigation bar that collapses down to a hamburger menu when on small screen sizes. The navigation bar contains the band name logo, the band symbol logo and the site navigation links.

-  The band name logo is fixed to the left which uses the same font that the band uses on all promotional material, the name logo gets hidden on small screens.

-  The band symbol logo is placed in the center of the navigation bar and is hidden on tablet size devices when the navigational links get too close, it reappears on mobile devices and becomes the primary logo. This logo expands with the hamburger expandable menu.

-  Each page contains a footer with the record label logo, social media links and legal/copyright information.

  ### Home Page

  

-  A Carousel is used in place of a static hero image, this allows multiple call to actions to be presented in a short time frame.

-  Newsletter Signup Form

-  Embedded Youtube Video

-  Samples of Tour and Music pages with call to action to see more.

  

### Music Page

  

-  A header and footer image with a gradient fade

-  A Grid of the band's music releases.

-  Each music release has a hover over effect that blurs the image as well as bringing up an overlay with the release name, date as well as a Spotify link to listen to the album/single.

  

### Tour Page
-  A header and footer image with a gradient fade.

-  A Grid of the band's upcoming tour dates.

-  Each tour date has a grayscale effect on hover as well as bringing up an overlay with the venue name and links to RSVP or buy tickets.

  

### Photos Page

-  A header and footer image with a gradient fade

-  A Grid of band photos.

-  Each photo has a hover over effect that blurs the image as well as bringing up an overlay with the text VIEW as call to action to get the user to click on it to view it full screen in a lightbox

  
  

### About Page

-  A header and footer image with a gradient fade

-  Band Member profiles are presented as a circular profile picture with the members name at the bottom.

-  The Member Profiles have a hover effect that inverts the color and brings up an overlay with more info on what instruments they play as well as other projects they’re involved with.

-  A biography of the band.

  

### Features To Implement

-  A News page where users can read past news stories that they have missed before signing up for the newsletter.

-  A Store page where users can buy merchandise from the band.

  

## Technologies Used

  

-  <a  href="https://code.visualstudio.com/"  rel="noopener"  target="_blank">**Visual Studio**</a>

	- The project used the **Visual Studio** IDE to develop the website linked with **Github** for version control.

  

-  <a  href="https://getbootstrap.com/"  rel="noopener"  target="_blank">**Bootstrap 4**</a>

	- The project used the **Bootstrap 4** for a responsive grid system.

  

-  <a  href="https://fontawesome.com/"  rel="noopener"  target="_blank">**Font Awesome 5**</a>

	- The project used the **Font Awesome 5** for a icons throughout the site.

  

-  <a  href="https://photoswipe.com/"  rel="noopener"  target="_blank">**Photo Swipe**</a>

	- The project used the **Photo Swipe** for a lightbox photo gallery.

  

-  <a  href="https://favicon.io/favicon-converter/"  rel="noopener"  target="_blank">**Favicon.io**</a>

	- The project used the **Favicon.io** the favicon icons or the site.

  

-  <a  href="https://autoprefixer.github.io/"  rel="noopener"  target="_blank">**Autoprefixer CSS**</a>

	- The project used the **Autoprefixer CSS** to ensure CSS compatability with all browsers.

## Testing
### Testing User Stories

#### 1. As a fan of the band I wish to find out about if can see them play live.
- The **Carousel** header on the home page has a slide that informs the
   user of a 2020 tour and has a call to action button that asks to user
   to see the dates, this will link them to the **Tour** page. 

 - The next 2 upcoming  tour dates on the home page with a call to action button to see all tour dates this will link them to the **Tour** page. The user can also interact with the **Tour Date Cards** to get an overlay with the venue name and links to **RSVP** or **Buy Tickets**.	

- The **Tour** page provides the user with **Tour Date Cards** for all the bands upcoming shows, the **Tour Date Cards**  have the city, country and dates visable and then on hover the reveal the venue with a link to it as well as links to to **RSVP** or **Buy Tickets**.

#### 2. As a new fan of the band I want to find out all the music that the band has made and where to listen to or buy the music.
- The **Carousel** header on the home page has a slide that informs the
   user of a vinyl repress of the bands latest album and a call to action button that brings the user to a site to buy it.
	 
 - Some of the bands music is shown on the home page with a call to action button to see all music that leads the **Music** page. The music releases have a hover effect that reveals the album name, release year and **Spotify** link to listen to it.
	   
- The **Music** page has a grid of all the albums and singles the band has released, The music releases have a hover effect that reveals the album name, release year and **Spotify** link to listen to it.

####  3. As fan of the band or a memeber of the press I want to see and download photos of the band.
- The **Photos** page has gallery of images from the band that can be viewed fullscreen in a **Lightbox**,  the **Lightbox** allows the users to share the image on **Facebook**, **Twitter**, **Pinterest** or **Download** the image directly to thier device.

#### 4. As a new fan I want to find out about the bands history and information on the band memebers.
- The **About** page has a biography summary of the bands history.

- The **About** page has band memeber profiles that are presented as profile images of each member with thier name over it, when hovered over more information on what instrument they play and other projects that they are involved with are revealed on an overlay.

#### 5.  As a fan I wish to find out news on the band, if they are working on new music, if a new tour is happening etc.
- The **Home** page has a **Newsletter Sign Up** form which allows the user to input an **email** and select thier **country** in order to recieve relevant information in a **newsletter** sent directly to thier **email**

- The site fails to provide any news to a user that doesnt wish to sign up by email for a newsletter, the site needs a dedicated **News** page that will archive all news posts.

#### 6.  As a fan I wish to purchase **merchandise** from the band such as t-shirts, posters and music releases.
- The site fails to provide a page for **merchandise**, other than the call to action in the carorusel on the home page to buy the latest album on an exteral site there is no way to buy **merchandise** from the band. The site needs a dedicated **Store** page.


## Deployment
 #### To deploy a live version of this site using Github the following steps are needed..
1. Log into Github.
2. User Dropdown > Your Repositories.
3. Select the respository for this project  [CI-MS1-Portishead-Website](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website)
4. From the repository top menu select [Settings](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website/settings), which is the last option in the right.
5. In [Settings](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website/settings) scroll down to the Github pages section.
6. In the Githib pages section, for Source select master branch.
7. In the Githib pages section, for Theme leave blank.
8. In the Githib pages section, for Custom Domain leave blank.
9. In the Githib pages section,  tick Enforce HTTPS, this is required when you are using the default domain.
10.After the [Settings](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website/settings) refreshes the Github Pages section will contain a link to the live site. https://kieran-murray-code.github.io/CI-MS1-Portishead-Website/

Currently there are no differences between the deplayed branch and master branch.
#### To deploy a local version the following steps are required.
1.Git can clone a repsoitory using $ git clone https://github.com/User/Repository-To-Clone
2. Use the above command in Git Bash in your IDE such as Visual Studio Code
3. To get the url for cloning this repository go to [CI-MS1-Portishead-Website](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website)
4. Click on the Clone or Download button.
5. Copy the link from Clone with HTTPS section.
6. Use the command in step 1 in Git Bash, add the correct url and hit enter.
7. You now have a local copy of the repository.
8. More information on cloning a Git Repsoitory can be found [here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).


## Credits
### Content

- Content in the biography in the **About Page** taken from [https://www.allmusic.com/artist/portishead-mn0000301619/biography](https://www.allmusic.com/artist/portishead-mn0000301619/biography)

### Media
#### Home Page
	
 - Carousel Images
	 - [https://unsplash.com/photos/NYrVisodQ2M](https://unsplash.com/photos/NYrVisodQ2M)
	 - [https://cdn.shopify.com/s/files/1/0117/4483/7728/products/PORTISHEADTHIRD_2019-11-06_13-19-30_vTMtxAzKWP_2000x.png?v=1587965307](https://cdn.shopify.com/s/files/1/0117/4483/7728/products/PORTISHEADTHIRD_2019-11-06_13-19-30_vTMtxAzKWP_2000x.png?v=1587965307)
	 - Screenshot taken of video [https://www.youtube.com/watch?v=WVe-9VWIcCo](https://www.youtube.com/watch?v=WVe-9VWIcCo)
	 
 - Portishead "P" logo - [https://commons.wikimedia.org/wiki/File:Portishead.svg](https://commons.wikimedia.org/wiki/File:Portishead.svg)
 - Island Records logo - [https://commons.wikimedia.org/wiki/File:Island_Records_logo.svg](https://commons.wikimedia.org/wiki/File:Island_Records_logo.svg)
 - SOS Video - [https://www.youtube.com/watch?v=WVe-9VWIcCo](https://www.youtube.com/watch?v=WVe-9VWIcCo)
 - #### Music Page

- Albums
	- Dummy -  https://images-na.ssl-images-amazon.com/images/I/713j89t%2BDkL._SX522_.jpg
	- Portishead - https://images-na.ssl-images-amazon.com/images/I/71k1xE7ELoL._SX522_.jpg
	- Third - https://images-na.ssl-images-amazon.com/images/I/314g8%2BGMLEL.jpg
	- Roseland NYC - https://images-na.ssl-images-amazon.com/images/I/518V5mlngPL.jpg
	- Chase The Tear - https://images-na.ssl-images-amazon.com/images/I/41UBUJ9xObL.jpg
	- Magic Doors - https://images-na.ssl-images-amazon.com/images/I/51CYTkRLE8L.jpg
	- The Rip - https://img.discogs.com/a8ZZbaoMW-mWIzHprwtCNlBhCts=/fit-in/600x600/filters:strip_icc():format(jpeg):mode_rgb():quality(90)/discogs-images/R-1392796-1216001446.jpeg.jpg
	- Machine Gun - https://images-na.ssl-images-amazon.com/images/I/71Kurtv6rLL._SX522_.jpg
	- Only You - https://img.discogs.com/ZriijXac2Z4WsAHAXTu-ERiZwZs=/fit-in/300x300/filters:strip_icc():format(jpeg):mode_rgb():quality(40)/discogs-images/R-75882-001.jpg.jpg
	- Over - https://images-na.ssl-images-amazon.com/images/I/81lUrLo6wFL._SX522_.jpg
	- All Mine - https://images-na.ssl-images-amazon.com/images/I/61fvVL-WGbL._SX522_.jpg
	- Glory Box - https://img.discogs.com/49EJC6lypma471tGzugbqGYHZ2A=/fit-in/600x515/filters:strip_icc():format(jpeg):mode_rgb():quality(90)/discogs-images/R-6163997-1413450521-5174.jpeg.jpg
	- Sour Times - https://images-na.ssl-images-amazon.com/images/I/41s8n48LWaL.jpg
	- Numb - https://images-na.ssl-images-amazon.com/images/I/61QGyixjXEL._SX522_.jpg

- Header[https://unsplash.com/photos/hAVodSB_GTo](https://unsplash.com/photos/hAVodSB_GTo) 
- Footer - [https://unsplash.com/photos/vGXHIh3URzc](https://unsplash.com/photos/vGXHIh3URzc)

#### Tour

 - Header - [https://upload.wikimedia.org/wikipedia/commons/9/92/Portishead13b.jpg](https://upload.wikimedia.org/wikipedia/commons/9/92/Portishead13b.jpg)
 - Footer - [https://live.staticflickr.com/3294/2379928392_4e5a84c33e_z.jpg](https://live.staticflickr.com/3294/2379928392_4e5a84c33e_z.jpg)
 - Venues
	 - London  - https://www.iq-mag.net/wp-content/uploads/2019/10/The-O2.jpg
	 - Paris -https://telecomdrive.com/wp-content/uploads/2016/04/AccorHotels-Arena-300x168.jpg
	 - Dublin - https://3arena.ie/images/made/4ce79fb25acbb687/corona-update-1300x630_1300_630_80auto_s_c1.jpg
	 - Berlin - https://live.staticflickr.com/1682/25723511762_778c070f29_b.jpg
	 - Venice - https://www.italybyevents.com/wp-content/uploads/2016/03/veneto-arena-di-verona.jpg
	 - Barcelona - https://www.barcelona-life.com/wp-content/uploads/2018/02/olympic-stadium-barcelona.jpg
	 - Lisbon - https://www.visitlisboa.com/rails/active_storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBa29PIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--6b816fe70e5f9be1f7feb1534d27397005e8474c/altice-arena-5.jpg
	 - Moscow - https://www.systemair.com/fileadmin/user_upload/systemair-b2b/References/Russia_ref/RU_Spartak_arena.jpg
	 - Helsinki -https://icdn.lenta.ru/images/2013/06/28/19/20130628193849550/pic_6027986f2c8d5d386651221ec37d29d1.jpg

#### Photos

 - Header - https://images.unsplash.com/photo-1536852926408-d079bc2c67d7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1355&q=80
 - Footer - https://images.unsplash.com/photo-1518353053542-7ea33d942319?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1351&q=80
 - Gallery Photos All From - [https://www.instagram.com/portisheadmusic/](https://www.instagram.com/portisheadmusic/)

#### About

 - Header - https://i2-prod.bristolpost.co.uk/incoming/article3250900.ece/ALTERNATES/s1200b/0_4385568-6.jpg
 - Footer - https://static-mag.itcher.com/mag/wp-content/uploads/2015/09/Portishead.jpg
 - Beth - https://bethgibbons.fr/wp-content/uploads/2019/06/Beth_Gibbons_-_Portishead_-_Roskilde_Festival_2011_-_Orange_Scene-1024x681.jpg
 - Geoff - https://upload.wikimedia.org/wikipedia/commons/6/60/Geoff_Barrow%2C_at_the_mixing_desk_in_State_of_Art_Studio%2C_Bristol.jpg

### Code

 - HTML Country List - https://gist.github.com/danrovito/977bcb97c9c2dfd3398a
 - Custom Checkboxes - https://css-tricks.com/custom-styling-form-inputs-with-modern-css-features/
### Acknowledgements
 
 - Inspiration
	 - Gradient faded header and footer images - [https://cypresshill.com/](https://cypresshill.com/)
	 - Carousel Header - [https://www.imaginedragonsmusic.com/](https://www.imaginedragonsmusic.com/)
	 - Newsletter subscription form - [https://www.imaginedragonsmusic.com/](https://www.imaginedragonsmusic.com/)
	 - Album hover effect - [https://www.thekillersmusic.com/music](https://www.thekillersmusic.com/music)
 
 
## Disclaimer
This website was created for a milestone project for The Code Institue Full Stack Software Development Diploma. The content of this Website is for educational purposes only.