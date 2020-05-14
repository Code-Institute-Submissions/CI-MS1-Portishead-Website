
# [Portishead (Band) Website](https://kieran-murray-code.github.io/CI-MS1-Portishead-Website/)

This is an assignemnt project for [https://codeinstitute.net/](https://codeinstitute.net/). The project aims to develop a modern mobile first website for long time fans as well new fans of the UK band Portishead. It helps them to find out information on the bands music and tour dates as well as the band's history and information on band members. See Portishead's offical website here -[Portishead's Official Webiste](https://www.portishead.co.uk/home/).

## UX:

### Design choices

The color scheme was chosen based on the band most recent album artwork -[Third Artwork](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website/blob/master/assets/media/images/Music/third.jpg).

I used [https://imagecolorpicker.com/en/](https://imagecolorpicker.com/en/) to generate a colour palette from the artwork image.

I looked at many popular band websites and noticed a lot of common design patterns such as the grid of music releases and photo grid.

The main site that I took design choices from were .

- [https://www.imaginedragonsmusic.com/](https://www.imaginedragonsmusic.com/)

- [https://cypresshill.com/](https://cypresshill.com/)

- [https://www.thekillersmusic.com/](https://www.thekillersmusic.com/)

### User Stories

  1. As a fan of the band I wish to find out about if can see them play live.
 
 2. As a new fan of the band I want to find out all the music that the band has made and where to listen to or buy the music.
 3. As fan of the band or a member of the press I want to see and download photos of the band.
 4. As a new fan I want to find out about the bands history and information on the band members. 
 5. As a fan I wish to find out news on the band, if they are working on new music, if a new tour is happening etc.
6. As a fan I wish to purchase merchandise from the band such as t-shirts, posters and music releases.

## Features:

### Common Features

- Each page has a responsive navigation bar that collapses down to a hamburger menu when on small screen sizes. The navigation bar contains the band name logo, the band symbol logo and the site navigation links.

- The band name logo is fixed to the left which uses the same font that the band uses on all promotional material, the name logo gets hidden on small screens.
- The band symbol logo is placed in the center of the navigation bar and is hidden on tablet size devices when the navigational links get too close, it reappears on mobile devices and becomes the primary logo. This logo expands with the hamburger expandable menu.
- Each page contains a footer with the record label logo, social media links and legal/copyright information.

### Home Page

- A Carousel is used in place of a static hero image, this allows multiple call to actions to be presented in a short time frame.

- Newsletter Signup Form
- Embedded Youtube Video
- Samples of Tour and Music pages with call to action to see more.

### Music Page
- A header and footer image with a gradient fade

- A Grid of the band's music releases.
- Each music release has a hover over effect that blurs the image as well as bringing up an overlay with the release name, date as well as a Spotify link to listen to the album/single.

### Tour Page

- A header and footer image with a gradient fade.

- A Grid of the band's upcoming tour dates.
- Each tour date has a grayscale effect on hover as well as bringing up an overlay with the venue name and links to RSVP or buy tickets.

### Photos Page

- A header and footer image with a gradient fade

- A Grid of band photos.
- Each photo has a hover over effect that blurs the image as well as bringing up an overlay with the text VIEW as call to action to get the user to click on it to view it full screen in a lightbox

### About Page

- A header and footer image with a gradient fade

- Band Member profiles are presented as a circular profile picture with the members name at the bottom.
- The Member Profiles have a hover effect that inverts the color and brings up an overlay with more info on what instruments they play as well as other projects they’re involved with.
- A biography of the band.

### Features To Implement

- A News page where users can read past news stories that they have missed before signing up for the newsletter.
- A Store page where users can buy merchandise from the band.

### Wireframes

Below are wireframes for the site developed in [https://balsamiq.com/](https://balsamiq.com/)
Each images contains a wireframe for the mobile and desktop versions of the site.

- [Home Page](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website/blob/master/wireframes/MS1%20Home%20Page.png)

- [Musci Page](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website/blob/master/wireframes/MS1%20Music%20Page.png)
- [Tour Page](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website/blob/master/wireframes/MS1%20Tour%20Page.png)
- [Photos Page](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website/blob/master/wireframes/MS1%20Photos%20Page.png)
- [About Page](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website/blob/master/wireframes/MS1%20About%20Page.png)


## Technologies Used

### Languages Used

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)

- [CSS3](https://developer.mozilla.org/en-US/docs/Archive/CSS3)

### Tools Used
- [Visual Studio Code](https://code.visualstudio.com/) -  The project used the **Visual Studio** IDE to develop the website linked with **Github** for version control.
- [Bootstrap 4](https://getbootstrap.com/) -  The project used the **Bootstrap 4** for a responsive grid system.
- [Font Awrsome 5](https://fontawesome.com/) - The project used the **Font Awesome 5** for a icons throughout the site.
- [Photo Swipe](https://photoswipe.com/) - The project used the **Photo Swipe** for a lightbox photo gallery.
- [Favicon.io](https://favicon.io/favicon-converter/) - The project used the **Favicon.io** the favicon icons or the site.
- [Autoprefixer CSS](https://autoprefixer.github.io/) - The project used the **Autoprefixer CSS** to ensure CSS compatibility with all browsers.
- [HTML Validator](https://validator.w3.org/) - The project used the **HTML Validator** to validate and find errors in the HTML.
- [CSS Validator](https://jigsaw.w3.org/css-validator/) -The project used the **CSS Validator** to validate and find errors in the CSS.
- [Balsamiq](https://balsamiq.com) https://balsamiq.com) -The project used the **Balsamiq** to generate wireframes for the site.

## Testing

### Testing User Stories

#### 1. As a fan of the band I wish to find out about if can see them play live.

- The Carousel header on the home page has a slide that informs the user of a 2020 tour and has a call to action button that asks to user to see the dates, this will link them to the Tour page.

	- Try click on the See Dates button to check if it brings you to the Tour page.
- The next 2 upcoming tour dates on the home page with a call to action button to see all tour dates this will link them to the Tour page. The user can also interact with the Tour Date Cards to get an overlay with the venue name and links to RSVP or Buy Tickets.
	- Try to click the See All Tour Dates button to check if it bring you to the Tour page.
	- Try to hover(tap on mobile) over tour date cards to check if the overlay displays.
	- Try to click on venue name to check if it brings you to the venue website.
	- Try to click on RSVP button to see if it brings you to Ticketmaster.
	- Try to click on Tickets button to see if brings you to Ticketmaster.

- The Tour page provides the user with Tour Date Cards for all the bands upcoming shows, the Tour Date Cards have the city, country and dates visible and then on hover the reveal the venue with a link to it as well as links to to RSVP or Buy Tickets.
	- Try to hover(tap on mobile) over tour date cards to check if the overlay displays.
	- Try to click on venue name to check if it brings you to the venue website.
	- Try to click on RSVP button to see if it brings you to Ticketmaster.
	- Try to click on Tickets button to see if brings you to Ticketmaster.

#### 2. As a new fan of the band I want to find out all the music that the band has made and where to listen to or buy the music.

- The Carousel header on the home page has a slide that informs the user of a vinyl repress of the bands latest album and a call to action button that brings the user to a site to buy it.
	- Try to click on the *Buy Now* button to see if it brings you brings you to Amazon to buy the album.

- Some of the bands music is shown on the home page with a call to action button to see all music that leads the Music page. The music releases have a hover effect that reveals the album name, release year and Spotify link to listen to it.
	- Try click on the *See All Music* but to see if it leads to the Music page.
	- Try to hover (tap on mobile) over the music albums to see if the overlay appears with album name, release year and Spotify link.
	- Try click on the Spotify link in the overlay to see if it takes you to Spotify to listen to the album.
	- The Music page has a grid of all the albums and singles the band has released, The music releases have a hover effect that reveals the album name, release year and Spotify link to listen to it.

-  - Try to hover (tap on mobile) over the music albums to see if the overlay appears with album name, release year and Spotify link.

- Try click on the Spotify link in the overlay to see if it takes you to Spotify to listen to the album.

#### 3. As a fan of the band or a member of the press I want to see and download photos of the band.

- The Photos page has gallery of images from the band that can be viewed fullscreen in a Lightbox, the Lightbox allows the users to share the image on Facebook, Twitter, Pinterest or Download the image directly to their device.

	- Try to hover (tap on mobile ) over the photos to see if the overlay with the call to action views appears. (On mobile this just cause the lightbox to open and you dont see the hover effect), needs to be switched to a click event using JS to work as intended on mobile.
	- Try to click on a photo to see if the is made fullscreen in the lightbox.
	- Try to to use the left and right arrows (or swipe on mobile) to browse through the whole gallery without exiting the lightbox.
	- In the lightbox click on the share button, try to share to, Facebook, Twitter, Pinterest and Download directly.

#### 4. As a new fan I want to find out about the bands history and information on the band members.

- The About the page has a biography summary of the bands history.
	- Test the paragraphy formatting on different sizes screen to make sure it is still readable.
- The About page has band member profiles that are presented as profile images of each member with their name over it, when hovered over more information on what instrument they play and other projects that they are involved with are revealed on an overlay.
	- Try to hover over (tap on mobile) on the band member profiles to see if overlay appears with more info on the band members.

#### 5. As a fan I wish to find out news on the band, if they are working on new music, if a new tour is happening etc.

- The Home page has a Newsletter Sign Up form which allows the user to input an email and select their country in order to receive relevant information in a newsletter sent directly to their email
	- Try to submit with an empty email input.
	- Try to submit with an invalid email.
	- Try to submit with no country selected.
	- Try to submit no checkbox option selected.
	- All invalid options prevent the user from submiting the form and popup messages telling the user how complete the form sucessfully.

- The site fails to provide any news to a user that does not wish to sign up by email for a newsletter, the site needs a dedicated News page that will archive all news posts.

#### 6. As a fan I wish to purchase merchandise from the band such as t-shirts, posters and music releases.

- The site fails to provide a page for merchandise, other than the call to action in the carousel on the home page to buy the latest album on an external site there is no way to buy merchandise from the band. The site needs a dedicated Store page.

### HTML & CC Validation

#### HTML

The following error were found and fixed after running my **HTML** through [https://validator.w3.org/](https://validator.w3.org/)

- Empty id and href attributes were found.

-  *div* and *span* were used as child elements of *ul*, only *li* can be the direct child of *ul*.

- Duplicate attributes were used.

- Attribute X not allowed on element Y at this point, such as an *alt* attribute on a *div*.

#### CSS

The following errors were found when running were found when running my **CSS** through [https://jigsaw.w3.org/css-validator/validator](https://jigsaw.w3.org/css-validator/validator)

- Parse Error on an -- variables that were used, this is a non issue as the validator just hasn't been updated to allow variables that are now fully accepted as CSS standard practice.

- Unknown Vendor extension warnings, this is a non issue as these prefixes are required to improve browser compatibility.

### Browsers

The following browsers were tested for compatiblity
- Google Chrome (Xiaomi Mi Mix 2s (Android) ,Honor 20 (Android), Windows 10 Laptop)
- Firefox (Windows 10 Laptop)
- Opera (Windows 10 Laptop)
- Microsoft Edge (Windows 10 Laptop)
- Internet Explorer 11 (Windows 10 Laptop)

#### Issues Found

- All gradients and filter effects not working on Internet Explorer 11.
	- Stautus: Pending a fix,  use solid colour backgrounds were gradients cant be used. 

## Deployment

#### To deploy a live version of this site using Github the following steps are needed..

1. Log into Github.

2. User Dropdown > Your Repositories.

3. Select the repository for this project [CI-MS1-Portishead-Website](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website)

4. From the repository top menu select [Settings](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website/settings), which is the last option in the right.

5. In [Settings](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website/settings) scroll down to the Github pages section.

6. In the Github pages section, for Source select master branch.

7. In the Github pages section, for Theme leave blank.

8. In the Github pages section, for Custom Domain leave blank.

9. In the Github pages section, tick Enforce HTTPS, this is required when you are using the default domain.

10.After the [Settings](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website/settings) refreshes the Github Pages section will contain a link to the live site. https://kieran-murray-code.github.io/CI-MS1-Portishead-Website/

Currently there are no differences between the delayed branch and master branch.

#### To deploy a local version the following steps are required.

1. Git can clone a repository using $ git clone https://github.com/User/Repository-To-Clone

2. Use the above command in Git Bash in your IDE such as Visual Studio Code

3. To get the url for cloning this repository go to [CI-MS1-Portishead-Website](https://github.com/Kieran-Murray-Code/CI-MS1-Portishead-Website)

4. Click on the Clone or Download button.

5. Copy the link from Clone with the HTTPS section.

6. Use the command in step 1 in Git Bash, add the correct url and hit enter.

7. You now have a local copy of the repository.

8. More information on cloning a Git Repository can be found [here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).
9. Once you have a local version pulled from Github, browse to that directory using your OS's file borwser, locate index.html in the root directory of the project and open it with your internet browser of choice.

## Credits

### Content

- Content in the biography in the About Page taken from [https://www.allmusic.com/artist/portishead-mn0000301619/biography](https://www.allmusic.com/artist/portishead-mn0000301619/biography)

### Media

#### Home Page

- Carousel Images

	- [https://unsplash.com/photos/NYrVisodQ2M](https://unsplash.com/photos/NYrVisodQ2M)

	- [https://cdn.shopify.com/s/files/1/0117/4483/7728/products/PORTISHEADTHIRD_2019-11-06_13-19-30_vTMtxAzKWP_2000x.png?v=1587965307](https://cdn.shopify.com/s/files/1/0117/4483/7728/products/PORTISHEADTHIRD_2019-11-06_13-19-30_vTMtxAzKWP_2000x.png?v=1587965307)

	- Screenshot taken of video [https://www.youtube.com/watch?v=WVe-9VWIcCo](https://www.youtube.com/watch?v=WVe-9VWIcCo)

	- Portishead "P" logo - [https://commons.wikimedia.org/wiki/File:Portishead.svg](https://commons.wikimedia.org/wiki/File:Portishead.svg)

- Island Records logo - [https://commons.wikimedia.org/wiki/File:Island_Records_logo.svg](https://commons.wikimedia.org/wiki/File:Island_Records_logo.svg)

- SOS Video - [https://www.youtube.com/watch?v=WVe-9VWIcCo](https://www.youtube.com/watch?v=WVe-9VWIcCo)
 #### Music Page

- Albums

	- Dummy - https://images-na.ssl-images-amazon.com/images/I/713j89t%2BDkL._SX522_.jpg

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

	- London - https://www.iq-mag.net/wp-content/uploads/2019/10/The-O2.jpg

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

- HTML Country List (Used in the Newsletter Signup form)- https://gist.github.com/danrovito/977bcb97c9c2dfd3398a

- Custom Checkboxes(Modified the code from here) - https://css-tricks.com/custom-styling-form-inputs-with-modern-css-features/

- At least one checkbox required validdation. - [https://vyspiansky.github.io/2019/07/13/javascript-at-least-one-checkbox-must-be-selected/](https://vyspiansky.github.io/2019/07/13/javascript-at-least-one-checkbox-must-be-selected/)

- PhotoSwipe Lightbox (Modified code from here) [https://photoswipe.com/documentation/getting-started.html](https://photoswipe.com/documentation/getting-started.html)

### Acknowledgements

- Inspiration

- Gradient faded header and footer images - [https://cypresshill.com/](https://cypresshill.com/)

- Carousel Header - [https://www.imaginedragonsmusic.com/](https://www.imaginedragonsmusic.com/)

- Newsletter subscription form - [https://www.imaginedragonsmusic.com/](https://www.imaginedragonsmusic.com/)

- Album hover effect - [https://www.thekillersmusic.com/music](https://www.thekillersmusic.com/music)

## Disclaimer

This website was created for a milestone project for The Code Institute Full Stack Software Development Diploma. The content of this Website is for educational purposes only. Kieran Murray and this website our not associated with Portishead, Island Records or Universal Music, all copyrights owned by the relevant parties.