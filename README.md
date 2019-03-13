# Rock Band

Rock Band is a project that is designed to promote a ficticious version of the actual band The Monkees from the 60s. The website showcases
many of the features that I, as a novice web developer, have learned since starting this Full Stack Web Development course with the 
Code Institute.

The project brought on a steep learning curve as I attempted to apply many of the core concepts from the Labs and mini-projects of the first 
few modules. This required lots of problem solving, researching and some support theough Slack and from my mentor. 

## UX

As a fan of the Monkees, I would like to stay updated on the latest releases, news and events. The jumbotron on the hompeage catches my
eye and alerts me to a new album. Also, from the homepage I can get most of the information I need and find links to the latest music including from popular music streaming site, Spotify. I can view forthcoming events and follow links
to ticket selling websites so that I can purhcase online. I can listen to music from within the website or follow links elsewhere.

As a general music fan, I can learn all about The Monkees, from the biography page. I would like to know more about the band and hear samples of their 
music to see if this is a band that I would like to hear more. I can listen to the music on the relevant webpage. I can also view a selection
of photos so that I can visualise the band and get a flavour of their style, through a postive user experience.

As user looking for a band to play at their wedding, I can learn all about the band from the latest news on the home-page, read 
the biography, view photos of the band in the gallery and listen to their music to see of this is the sort of band I would like to book. 
Most importantly, I can sample their music through embedded audio and video files. I can also follow links to other albums on popular 
streaming servive, Spotify. I can then follow the links in the navbar or footer to the Contact page so that I can make an enquiry and 
book up the band to play at my event.


## Features

### Home-Page
- NavBar: I used Boostrap to create the NavBar and then customised this by changing the font styles  (from Google fonts) and text alignment, background colour, and 
the height. I chose to increase the height so that I could increase the size of website title. This has been made responsive 
using a hamburger menu. The NavBar is sticky so that it always stays at the top of the page. Colours were selected from Material.io

- Footer: The grey footer ties in with tht button colours. It provides links to the band's social media sites and includes a link to the
Contact page. The footer is responsive, removing the address on smaller devices. This was incporporated using a media query. 
The hover on the social media link matches that of the buttons.

- Jumbotron: I used a Bootrap Jumbotron and backgroun to catch the user's eye on landing, with a call-to-action button. This was customised
through font colour and transparent background (as well appropriate padding etc) so that the background image shows through.

- Card-deck: I used the boostrap Card deck to organise the 'latest news'. These then link to sections of the website. Three cards are shown
on larger devices and this changes to two on smaller devices to maximise the use of the screen and avoid one 'dropping' to the line below.

- Boostrap table: Again using Boostrap to provide the foundations. Font styles andf colours were customised and buttons were 
added as calls-to-action. The hover on the buttons ties in with the colour of the NavBar as do all buttons on the website. The table is 
made responsive throught the overflow feature that allows the user to scroll. 

#### Future developments-
- Increase the number of events available to view on the wevsite. This could be done through the addition of an events page.
- Improve how the reponsiveness of the table so that it collapses by rows.
- Include a latest news page so that more news and info can be added, perhaps including social media feeds, such as Twitter.
- Add a hover effect to the image links on the card decks


### Biography
This page is the least interactive but provides information on the band, and then on each band member. This page utilises the Boostrap 
Card deck again. Using the Bootsrap grid system this is made responsive so that the cards make two rows on smaller devices.

#### Future developments-
- consider how to make this page more interactive, perhaps, include interviews from band members.

### Music
This page showcases one of the latest albums so that users can sample their tunes. The album cover has shadow effect the bring it off 
the white background. 

- Audio: This page utilises an audio iframe from Spotify so that songs from the album can be sample. The user click on the album cover
to follow a link to Spotofy where they can listen to the album in full.

- Album track-listing: Using relevant header and body styles tracks are listed for users information

- Embedded Youtube video: This page also utlilises an iframe from YouTube so that the user can watch a video on the website. 

- at the foot of the page there is a selection of other albums each linking to Spotify so that can be listened to in full.

#### Future developments- 
More videos could be added to improve this page (or a feature that allows you to scroll through a selection)
A wider music selection could be added here or a tool for scrolling through songs.

### Photos 
This page samples what the a full page could look like. I have added a small selection of photos that can be viewed using a FancyBox viewer.
This also required jQuery to work. This allows users to view photos of the band.

- The layout of the photos is made responsive through an approprate media query. 

#### Future development- 
- Each 'group' of photos (i.e. photos from a recent event) could be added in folders for users to view. For example, 
Concert in London 2019. The sizing of the photos could be improved for smaller screens.

### Contact
- Form: The form was created using Boostrap. This allows users to contact the band and book an event.
- Jumbotron: Call-to-action to persuade users to get in touch

#### Future development- 
This page could be developed further to include photos of events to make it more attractive. Perhaps photos or live video
of a recent wedding or party.


## Technologies, frameorks and libraries Used

#### Boostrap (jumotron, form, tables, card-decks, navbar, grid)
https://getbootstrap.com/docs/4.3/getting-started/introduction/ 
I used Boostrao to provide framework to key features and to save developer time.

#### FancyBox3 / FancyApps / jQuery
https://fancyapps.com/fancybox/3/
I used Fancybox to improve tje user experience when viewing photos in the gallery. This needed the latest jQuery link to make it work.

#### Embedded YouTube video using iFrame
https://www.youtube.com/
I created an embedded link using the YouTube sharing tools so that users can watch videos directly from the website. This will enable
users to sample video before enticing them to find more.

#### Emedded Spotify player, using iframe
I created an embedded link using the Spotify player tools so that users can sample music directly from the website. This will enable
users to sample music before enticing them to find more.

#### Google fonts
I used two Google fonts to create a personal style for the website.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that 
the site works well. Essentially, in this part you will want to go over all of your user stories from the UX 
section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to 
achieve their goals. Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of 
your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. 
A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page by following the link in the footer
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits

#### Content
The text for Biography was copied from the Wikipedia article: https://en.wikipedia.org/wiki/The_Monkees
https://en.wikipedia.org/wiki/Micky_Dolenz
https://en.wikipedia.org/wiki/Michael_Nesmith
https://en.wikipedia.org/wiki/Davy_Jones_(musician)
https://en.wikipedia.org/wiki/Peter_Tork

#### Media
The photos used in this site were obtained from:
www.amazon.com
https://monkees.coolcherrycream.com/picturedb/albums/album-covers
https://passthepaisley.com/im-a-believer-by-the-monkees/
https://en.wikipedia.org/wiki/The_Monkees


#### Acknowledgements
I received inspiration for this project from:
https://snowpatrol.com/
https://www.backstreetboys.com/#!
https://www.thebeatles.com/