# The Mindful Way

The Mindful Way website is a website for people who are both interested in and curious about mindfulness. The Mindful Way website provides information about upcoming courses and events lead by the team and offers those who are intersted to sign up to a newsletter and receive meditation videos also. This site is targeted towards anyone who is interested in Mindfulness and encourages a community spirit among those who are members of it.

The concept of this website was to maintain a mindful design theme to further enshance the main theme of the website.

![Am I Responsive Image](/assets/images-readme/am-i-responsive.jpg)

## Features

### Navigation
- At the top of the screen, within the navigation bar, at the left corner is the wesbite name, which is also an active link that brings you to the home page of the website when clicked.
- Within the navigation on the right side of the screen contains the other navigation links which are: Home, Courses and Events and Sign Up which when clicked bring you to different pages within the Mindful Way website.
- The font chosen for the navigation is clearly seen on the white background and also further enhances the mindful tone of this website by not being a calming colour that is not too loud. 
- The navigation links are clearly laid out and once hovered over increase in size making it very clear to see which link is about to be selected.
- When completing the responsive design of this website the navigation bar was changed slightly so that the logo appeared on the top line and the navigation links appeared on the line below this when viewed on smaller screens, this allowed all content to be esaily viewed without needing to be unnecessarily reduced in size to fit into the space. 

![Navigation Bar](/assets/images-readme/navigation.png)

## What is Mindfulness Section

- Once this website is opened the main image here zooms in to draw in the attention of the users.
- Within this image there is a definition of mindfulness from Jon Kabat-Zinn, a mindfulness leader, to provide users with a brief overview of what mindfulness is.
- The colours chosen here for the text box and the image were blue to aid in the creation of a mindful mood for users.
- The font is the same here as the header to maintain consistency and the flow of this website.
- The opacity selected for the textbox was chosen to allow the text to be easily read by all users and screenreaders.

![What is Mindfulness Section](/assets/images-readme/what-is-mindfulness.jpg)

## Reasons to Practise Mindfulness Section
- This section consists of four main reasons to practise mindfulness as well as a small explanation for each. 
- This section maintains the design of the rest of the webpage by using the same font and background colour.
- The Flex property was used for the styling of this section which made it possible for each of the four reasons to sit alongside one another each taking up the same width of the screen(25%). This was proving next to impossible to achieve while using the Float property so the Flex property really helped here.
- The layout of this section was also changed for smaller screen sizes which changed the four vertical columns to four horizontal rows. This allowed for the size of the text here to not be dramatically reduced to keep them in column format and therefore allowed these to be easily read on smaller screen sizes. 

### Screens larger than 1350px
![Reasons Section](/assets/images-readme/reasons.png)

### Screens of 1350px and below
![Reasons Section with Media Queries](/assets/images-readme/reasons-media-query.jpg)

## Meditation Video Section

- This video is a brief meditation which provides users of the website with a taster of what to expect as they embark on their mindfulness journey.
- The background to this video maintains the similar blue background colour to the above section in order to further mainiain consistency as you move through this webiste.
- The video is an embedded video from YouTube containing controls for pausing, playing and changing the volume of this video.

![Meditation Video](/assets/images-readme/video.jpg)

## Footer

- The footer contains social media links to encourage users to stay connected with The Mindful Way.
- The social media links for Facebook, Twitter and Instagram are displayed as icons from Font Awesome which are easily identifiable.
- The font style and colour as well as the background colour in this section is the same as the header section to maintain uniformity throughout the website.

![Footer](/assets/images-readme/footer.png)

## Courses and Events Page

- This page is accessed when "Courses and Events" is selected from the header navigation.
- Both the header and footer remain the same as the homepage to maintain consistency.
- This page consists of a quote on the importance of retreats from a Mindfulness Leader, Thich Nhat Hanh, a list of upcoming courses and events coming up lead by The Mindful Way and contact details for users interested in these courses and events.
- These are displayed on a background image of a country cottage in order to further emphasise the significance of nature in mindfulness and to show users the type of setting to expect when they sign up for any course with The Mindful Way.
- The background colour of the text boxes have sufficient opacity in order to allow the font of both the quote ond the courses and events to be easily read.
- The font size and style remained the same here to maintain the flow of the website between pages.

![Courses and Events Page](/assets/images-readme/events.jpg)

## Sign Up Page

- This page is accessed when "Sign Up" is selected from the header navigation.
- The form here invites userd to sign up to the Mindful Way if they are interested in mindfulness and would like to receive their newsletter, some meditation videos and information about upcoming events.
- The form consists input boxes to collect the users first name, last name and email address. It also consists of two questions with radio button options for answers and a textbox for users to share anything else they would like to share. This form finishes with a submit button.
- This pages consists of an image of a pile of rocks in the foreground and a beach in the background further reinforcing the mindful theme of this website highlighting the significance of time in nature and stillness.
- The header and footer remain the same as the homepage to maintain consistency.
- The colour used for the background colour of the form as well as the font colour and style is the same as the home page and the courses and events page in order to maintain the consistency of the website.
- The layout of this page changes slightly for smaller screen sizes by changing to with of the form from covering a small area of the background image to being the full width of the screen with the background image visible at the top and bottom of the form as well as through the form itself. This layout works better for smaller screen sizes and users can now easily interact with the form without the need for scrolling left to right.

![Sign Up Form](/assets/images-readme/signup-form.jpg)

## Testing
- I tested this webpage and it works well on a number of browsers: Safari, Chrome and FireFox.
- I confirmed that this website is responseve and works on a number of screen sizes using the "Inspect" function.
- I confirmed that this site is easily accessible and that header and footer links are in proper working order.
- I tested the video on the homepage and it works perfectly.
- The form functions as required and both radio buttons and the submit button function as they should.
- I found the media queries challenging and found I did spend a lot of time on DevTools to resolve these issues whether it be amending text side or adding or reducing padding as well as the height of areas. I found this a particular challenge with the navigation bar as I wanted to keep both the logo and the navigation links on the same line as the srreen got smaller, however, the practicalities of that were not feasible and it would not have made for a very accessible navigation bar. I am glad I changed the layout to have the logo on one line and for the remaining navigation links to be on the next line instead. By doing this both lines remained large enough to bl clearly read and maintained their integrity.
![Media Query Navigation](/assets/images-readme/media-query-header.jpg)  
- I had an issue with the sizing of the sign up form as I completed the media queries for use on smaller screens. I could not get the position of the form to stay in such a way that the background image and the form coukd both be clearly seen. I decided then that I would change the layout of this page for smaller screen sizes for the form to take up 100% of the width of the page and to allow the background image to be seen at the top and bottom of the screen as well as what could be seen through the opacity of the form. I spoke with my tutor about my issues in achieving this but we came to a good resolution for the webapge. I feel this deicision was for the best as the accessibility of the form would have been greatly reduced if it had to dramatically reduce in size.

### Validator Testing

- I tested this webpage on Lighthouse and it scored high across all criteria including performance and accessibility.
![Lighthouse Testing Score](/assets/images-readme/lighthousetesting.png)
- I tested this website on the W3C Markup Validation Service and only one issue was highlighted which was the use of an iframe element to insert the video to the webpage instead of using CSS to do the same. I looked into this and found that for this particular video hosted on YouTube, the best way to display it would be by using an iframe tag. It can be seen within the website working without any major issue. 
- I tested thes website on the Jigsaw W3C CSS Validator and no errors were found.
![Jigsaw Testing Score](/assets/images-readme/jigsaw-testing.jpg)

## Technologies Used

- All code for this website is written in HTML5 and CSS3.
- The libraries and frameworks used for improved interaction, functionality and design were Font Awesome, Google Fonts, Coloors, Am I Responsive, GitHub and Codeanywhere.

## Unfixed Bugs
- No unfixed bugs within the code. 

## Deployment

- This site was deployed through GitHub by completing the following steps:
  - Sign into GutHub
  - From homepage select on repository to be deployed
  - From repository select __Settings__
  - On the settings page select __Pages__ from the menu of the left of the page
  - On the GitHub Pages under Build and Deployment ensure source reads *Deploy from a Branch*  and branch drop down menus read *main* and *root* respectively
  - Select *Save*
  - It may take a few moments for the wedpage to be deployed and for a box to appear under GitHub pages but once it appears the link can be copied and used as needed.
  - The live link can be found [here - The Mindful Way](https://aimeeallen94.github.io/Mindfulness/)

## Credits

- The set up and design of this website was based upon the Love Running and Coding Club webpages in order to get this website up and running. From there I applied my own style and design ideas.
- My tutor told me about the Flex function and [Flexbox Froggy](https://flexboxfroggy.com/) to use instead of the float function which greatly helped with the styling of the Reasons to Practise section to get the each reason to take up 25% of the width of the screen. I used [this](https://www.w3schools.com/css/css3_flexbox.asp) W3 Schools Flexbox tutorial to learn how to apply this style rule.
- I used [this thread](https://stackoverflow.com/questions/32426401/embeded-youtube-video-error) from Stack Overflow to embed the video in the webpage as I was having difficulty getting to work when attempting to copy and paste video link into an iframe tag.
- The images in this website were taken from [Pexels](https://www.pexels.com/).