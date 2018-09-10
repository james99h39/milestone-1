# Dean Parker Blues Band Website
This project is a single page website for the Dean Parker Blues Band to showcase their music and publicise their availability to perform at different types of events such as parties, weddings and corporate events.

## UX
This website is for fans of the band, who may be interested in the band’s members, and Dean Parker’s background of how he got to where he is today, so they would click the link in the navigation bar/dropdown menu or scroll to the My Story section. They may want to see and hear previous shows and performances, listen to the band's back catalogue or see photos of the band, so would click the link in the navigation bar/dropdown menu or scroll to the Media section. They may also want to listen to any new material once it is made available, which will also be available in the Media section.
This website is also aimed at potential customers, who want the band to play at their events. They may be interested in Dean Parker’s history and in some information about the band’s members, so the user would click the link in the navigation bar/dropdown menu or scroll to the My Story section. They may want to listen to previous shows and listen to the band’s back catalogue, so would click the link in the navigation bar/dropdown menu or scroll to the Media section. They may want to read what previous customers’ reviews, so would click the link in the navigation bar/dropdown menu or scroll to the Testimonials section. They may want to get in contact with the band, so would click the link in the navigation bar/dropdown menu or scroll to the Contact section. To get in contact via phone, the user would either type out the number provided or, if on a mobile device, click on the number to automatically call. To get in contact via email, the user would fill out the email form and click ‘send’.

## Features
In the navigation bar, the navigation links scroll down the page when clicked on, which allows the user to click to a new section rather than scroll, so is more time efficient. When the user manually scrolls down the page and a certain section of the page is visible in the viewport, the navigation link that is linked with that section is highlighted, to let the user know which section of the page there are seeing.
In the Media section, I embedded YouTube videos to play, audio files to listen to and a picture carousel to navigate between different images of the band. I used a carousel so that the images take up real estate. If the user would prefer to see an image enlarged or in more detail, they can click on the image to open a new tab with the image enlarged (to full screen).
In the Contact section, I have included a mail form with required fields that, on clicking send, will open the mail application (if the mail app is connected to the browser), so the user can contact the band about any bookings. Also, on clicking the phone number in the description above the contact form, your device will give the option to ring the number (available on mobile devices only).
In the future, the mail form will be updated so that the mail form automatically sends, once completed, on clicking send (currently on clicking send, the user is directed to their mail application to send the email manually).

## Technologies Used
- I have used HTML in my project to structure my website.
- I have used CSS in my project to style my website.
- I have used the Bootstrap 3.3.7 for the grid system and lots of their pre-set classes, such as those in the navigation bar, and for the image carousel. (https://getbootstrap.com/)
- I have used the Font Awesome 4.7.0 library for the quote mark icons in the testimonials section. (https://fontawesome.com/)

## Testing
To test the navigation bar at the top of the page, I clicked on every link to test they all worked and took me to the right section of the page. I did the same for the 
To the test the embedded YouTube videos in the Media section, I clicked on each video link to check that the videos are playing as normal. I did the same with the audio files in the Media section. Testing all the controls in the videos/audio files was included in these tests.
To test the image carousel in the Media section, I used all the controls to switch between images, and clicked on each image to make sure the full screen version was working correctly and was opening a new tab to view the image at full screen.
To test the contact form in the Contact section, I first tried to submit an empty form, but I got an error message telling me to fill in the first text field (Full name). This was the same for all the fields I didn’t complete, except the Email field – the Email field’s error message said that I needed a format of text@text to be valid. Once I filled out the contact form correctly and submitted the form, I was taken to my mail app as expected.
These tests were performed on various browsers on my machine to ensure the website functioned properly at different screen sizes. I used a mobile device to verify.
My website looks and works the same on different browsers, however in some browsers the autoplay feature included in the first embedded YouTube video causes the video to play immediately once the page is loaded. In Microsoft Edge, the email field doesn’t require the text@text format, any text is valid. These are problems I haven’t fixed yet. 

## Deployment
The website is deployed and hosted on GitHub (https://jamesahorne.github.io/milestone-1/). To deploy, I used GitHub Pages. In my GitHub account, in the repository for this project, I went into Settings, scrolled down to the GitHub Pages area, and changed the source of my website from none to ‘master branch’. There are no differences between the deployed version and the development version.

## Credits
The photos used in this site were obtained from the Dean Parker Band (formerly Dean Parker Blues Band). (https://www.deanparkermusic.com/dpb)
I received inspiration for my carousel from Bootstrap's. I have also based my dropdown button (for mobile devices) off Bootstrap's examples, again keeping the HTML structure but using CSS to make it better fit my purposes.
