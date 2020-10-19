# **Gareth John – Professional Portfolio and Resume**

The purpose of this website is to create an online presence for an individual (myself in this case) to highlight skills, experience, work history and to showcase projects to potential employers. This must be achieved in a visually appealing UX, which enables the user to easily navigate and locate the information irrespective of the device they are using.
The ultimate aim is to assist the individual to secure future employment opportunities as a software developer, by showcasing acquired skills of the commomn technologies used.


Table of contents

______

## **UX**

My aim is to provide a simple yet intuitive user experience, which requires the minimum amount of scrolling to locate information. I see this as particularly important on mobile screens.

For this reason I had elected to 
- maintain a fixed menu bar at the top of the screen.
- limit the amont of detail in thw rok histroty section 

### **User Stories**

1. **_As a_** job seeker, **_I need to_** promote my skills and experience in an efficient and visually appealing way; **_in order to_** increase my chances of being interviewed and ultimately employed.

1. **_As a_** Hiring Manager/HR, **_I need to_** quickly establish if the candidate has the required skills and experience; **_in order to_** recommend them to the business and select them for interview

1. **_As a_** Technical Manager, **_I need to_** determine technical proficiency and if the candidate has the skills and experience, I am looking for; **_in order to_** bring them into my team be confident they can add value

1. **_As a_** Recruiter, **_I need to_** quickly establish if the candidate has the required skills and experience; **_in order to_** increase my chances of successfully placing the candidate with my portfolio of clients.

#### **Strategy**  
As previously stated, the aim of this project is 3 fold:
 - To create an online presence
 - To highlight skills, and work experience 
 - To showcase projects  
 ... all with the aim of increasing the individuals employability

It is also important that potential employers, recruiters or clients can easily make contact with the individual. This is achieved through the use of:
- email links
- social media links
- contact form
 
My intention is to provide some basic general information on the landing page sufficient to generate some curiosity; then to  make the key information easily accessible through an intuitive and repeating UX design. The intention is to provide multiple routes top the skills, experience and work history as well as multiple links to the downloadable CV.
- Multiple links to Experience section from Landing page.
- Consice listing of skills
- Abridged version of work history
- Multiple links to a downloadable CV
- Portfolio page with Porject summaries and links to the deployed pages

#### **Scope**  
I want to challenge myself to produce something I am proud to put my name on, without overextending myself and causing scope creep. I was aware that I needed to keep the content within the scope of my current knowledge; this would be critical if I encountered any issues during the build and needed to troubleshoot on the fly.
I had originally planned to use an image carousel on the home page, and although I was able to get this to function on large screens it would become useless on mobile. Thus I opted for the current, simpler stacked configuration.

#### **Structure**  
I plan to maintain a common navbar and footer section throughout the website to create an intuitive UX.  
 - In the end, there was a deliberate change to the 'CONTACT'; section of the contact.html page. Given that this page will have all the necessary contact information on it I decided to change the footer section to an 'ABOUT ME' box, where the user is reminded of some of the candidates key skills (as opposed to repeating the contact information).

I liked the idea of splitting the information into two sections with 1/3 and 2/3 widths respectively as we had done in the UCD Resume Walkthrough project. I intend to recreate this basic structure without copying the code from that exercise.
I will use the left hand 1/3 to list the shorter strings of data which could be bulletted or short paragraphs and reserve the remaining 2/3 portion of the page for the bulk of the information like work history. 
 - I believe I have achieved this whithout directly copying the code. 

#### **Skeleton** 
The website will comprise four distinct pages navigable through the 'navbar' menu: 
- Home | Experience | Portfolio | Contact
The navbar will also incorporate a link to a downloadable version of my CV.

A Footer section will provide additional information with links to social media sites and email, and another download link for the CV. I have also included a copyright statement.  

#### **Surface**
I had intended to use a darker colour scheme for this website. However as the build progressed it just didn't seem to suit; nor did it match the images I had selected. Of all aspects of this build I will freely admit this was the area I struggled with the most.  
In the end I sought inspiration from two websites:
- [10 Gorgeous Color Schemes for Websites](https://www.shutterstock.com/blog/10-gorgeous-color-schemes-for-websites?kw=&gclsrc=aw.ds&gclid=Cj0KCQjw2or8BRCNARIsAC_ppyaGHtDUv5oNSHP0th9gb8N6VBiGFAq-pYu1cFQFW5szceQETvoAnKgaAhwPEALw_wcB)
- [10 Trending 2020Website Color Schemes](https://www.quicksprout.com/trending-website-color-schemes/)

I decided on the "Scholar" colour scheme as it fitted the theme of the website and made some use of a darker blue, which had been my original intention. I had added the teal colour to provide another slightly brighter colour for contrast.
On reflection I am pleased with the result; it isn't too playful or childish, yet isn't cold and boring. The colours provide a decent amount of contrast.

I wanted to the look and functionality of the links to be intuitive so read a little about achieving the right aestheics
- [WebFX - Designing and styling hyperlinks](https://www.webfx.com/blog/web-design/designing-hyperlinks-tips-and-best-practices/)

##### **Typography**  
The only issue with typography is narrowing my chioce down to one or two fonts.
- I selectected **_Michroma_** because it has a squarer look, which appeals to me, is easy to read and looks professional.
- I complemented Michroma with the **_Cairo_** font after comparing various combinations on the Google Fonts page. The selection was primarily made on the aesthetics and ease of reading. Maybe it's my age but some font's were just a bit difficult to read, if that makes sense?

##### **Imagery** 
Given the intended purpose of this site is to convey my skills, experience and work history I have limited the use of images, prefering to focus on these other aspects. However, I want the few images I use to convey my journey from working on oil rigs and into coding websites; I have attempted to pick appropriate images.
  
The only section where I this rule doesn't apply is the 'PORTFOLIO' page. I want to use images of the projects in an attempt to generate interest and hopefully lead to user interaction.
I have reused the image of the rig for the contact page as it represents teamwork and links well with the heading "_How can we work together?_"
______

## **Features**

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

### **Existing Features**
- This is a static website comprising four distict pages, linked by the use of a navbar.
- Navbar – I have selected a bootstrap responsive navbar to achieve plug and play functionality. 
  - Despite having a logo I have chosen to retain the 'Home' link to reduce confusion (in case users don't intuitively know to click the logo to return to the Home page).
- A Resume page with links to individual company websites - enables the user to discover more about some of the companies I have worked for.
  - An 'accordion' feature simplifies the Work History section while enabling the user to selectively find out a little more about each role in the section.
- Portfolio page with Project 'Cards" linking to individual projects. Links have been disabled where appropriate. Placeholder cards are used to illustrate what the page could look like as the number of projects increases.
- A Contact page with a functioning google map iframe and a contact form (currently linked to the CI form dump)
- A footer section with Social Media and email links; as well as a link to a PDF of my CV.

### **Features Left to Implement**

- I would eventually like to complete the Contact form so it is connected to an email API (currently lacking the JavaScript skills).
- Depending on the number of projects which I reference on this site I may need to consider a different layout for the Portfolio Page.

______

## **Technologies Used**  

This static website has been built using the following core technologies:

Core coding languages

- ![alt text][logo]: https://www.google.co.uk/imgres?imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2F3%2F38%2FHTML5_Badge.svg&imgrefurl=https%3A%2F%2Fcommons.wikimedia.org%2Fwiki%2FFile%3AHTML5_Badge.svg&tbnid=P76qCIv4K8Y0iM&vet=12ahUKEwjOz-qq3b7sAhWQ2uAKHe3rCS0QMygAegUIARCAAg..i&docid=zE9j2C1bwI5DQM&w=800&h=800&q=html5&hl=en&safe=strict&ved=2ahUKEwjOz-qq3b7sAhWQ2uAKHe3rCS0QMygAegUIARCAAg "HTML 5"
- CSS3

Intergrations

- Bootstrap 4
- Font Awesome
- Google Fonts
- JQuery
- The project uses JQuery to simplify DOM manipulation.
- Hover.css for button hover effects

Version Control, storage and hosting

- Gitpod
- Git
- GitHub

Other

- Word to Markdown Converter
______

## **Testing**

The philosophy I have used throughout this build is to build and test each part of the website as I progressed, relying heavily on Google Dev tools throughout.

- Repeatedly tested the 'navbar' links throughout development to ensure correct navigation.
- I used DevTools extensively during development, changing devices, to ensure the desired responsive behaviour was achieved.
  - This helped to highlight an issue I had with Divs and whitespace on the right hand side.
- Once roughly 50% complete I deployed the website to Git Pages and started viewing the output on several real devices:
  - Samsung Galaxy S9
  - Samsung Tab A
  - HP Laptop with attached monitor
- I tested the functionality of the 'accordion' feature on the Experience page on these devices to ensure aesthetics and functionality were maintained.
  - This helped me make some changes to maintain responsiveness. 
- Repeatedly tested all links to ensure they function and correctly open up the required sites in new browser tabs.
- Tested Social Media icon to ensure they also link to the correct sites and open in new browser tabs.
- I have tested email links to ensure they open up the default email application and insert the email address.
  - Works on Samsung S9 – opening Gmail
  - Laptop – opening Outlook
- Tested the contact form on the Contact page to ensure correct functionality. This was linked to the CI Form dump page so I could verify the data sent.
- Testing of the 'required' attribute which ensures all contact form field get filled in before the data can be sent.
- I have tested the email address entry on the Contact form to ensure correctly formatted email addresses can be entered _e.g_ [_name@something.com_](mailto:name@something.com)
- Accessibility Test
  - Highlighted potential issue with the choice text color on the navbar
  - Highlighted an issue with the contrast of the text with links.
- HTML Validation
Each page has been checked and all errors have been corrected.
- CSS Validation
Returned several errors related to the use of vendor extensions. I have chosen to accept these errors based on the fact they increase compatibility. [Stack Overflow](https://stackoverflow.com/questions/52490004/what-are-all-of-these-w3c-css-validation-warnings-about)

- CSS Auto Prefixer
- Mobile Friendly
- Website speed test
  - Passed in all but Security
- I forwarded the link to the website to friends to view and provide feedback. This was initially done at about 75% complete and again once 100% complete.

______

## **Bugs and Issues**

- Initially the collapsed Menu items would not appear and disappear when clicking the 'burger'.
  - The solution to this was found in the [Slack community](https://code-institute-room.slack.com/archives/C7J2ZAVHB/p1592942356085000?thread_ts=1592936056.080800&cid=C7J2ZAVHB); and was simply a case of relocating one of the bootstrap JS CDN links to the 'head'


- While building the navbar toggler, the menu items would only appear on the right.
  - The solution was provided on [Stack Overflow](https://stackoverflow.com/questions/47518911/boostrap-4-navbar-collapse-menu-right-align/50881393)


- My navbar had a small amount of whitespace on the right-hand side.
  - The solution to remove this was again found on [Stack Overflow](https://stackoverflow.com/questions/48510609/remove-white-space-from-the-sides-and-top-of-my-navbar/48510687)


- When I initially created cards for my portfolio projects each one was sized dependent on the content, which was undesirable. I found a solution to ensure all cards were equal height here: [Codeply](https://www.codeply.com/go/jbcgzs2Nzq)  

- I used the code listed on this site to push the card button down to the bottom of the card. [Stack Overflow](https://stackoverflow.com/questions/48406628/bootstrap-align-button-to-the-bottom-of-card)

- Throughout the build I had an issue with there being whitespace down the right hand side of my pages. The issue wasn't immediately obvious, until I created boxes around every element; which highlighted some divs were wider than the remainder of the page.
 This was a useful method to visualise the interaction of all page elements. [Stack Overflow](https://stackoverflow.com/questions/46630191/white-space-on-right-side-of-page/46630298)

- I struggled to achieve fully responsive and fixed height images for my portfolio cards. In fact I'm not sure this is possible to achieve without changing aspect ratios so I resorted to the "image-fluid" class from [Bootstrap - images](https://getbootstrap.com/docs/4.0/content/images/). Equalising the image height might be something which I add to the "Features left to implement" section but realise there are compromises in play here.
______

## **Deployment**

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

______

## **Resources**

I have attempted to work independently as much as possible while building this website, choosing to solve my own issues, using web resources wherever possible. Thus my main resource throughout this project was the trusty Google search.
 Aside from Google I have made use of the following resources:-

- [Balsamiq](https://balsamiq.com/wireframes/) – Wireframing Tool
- [Free Logo Maker](https://logomakr.com/) - Simple drawing tool used to create a brand logo
- Code Institute course material and Walkthrough projects
- Google DevTools - for trouble shooting and 
- [StackOverFlow](https://stackoverflow.com/) – Web based coding 
- [CSS Tricks](https://css-tricks.com/) – Styling tips like https://css-tricks.com/styling-underlines-web/
- [W3Schools](https://www.w3schools.com/) – General coding resource
- [Pexels](https://www.pexels.com/) – Licence free image repository
- [TinyPNG](https://tinypng.com/) – Application for compressing image files
- [Color Picker](https://htmlcolorcodes.com/color-picker/) – HTML and CSS color codes
- [amCharts](https://pixelmap.amcharts.com/) - Pixelated map generator tool
- Shutterstock: 10 Gorgeous Color Schemes for Websites
- 10 Trending 2020 Website Color Schemes
- Am I responsive?

______

## **Credits**

### **Content**

- The text for section Y was copied from the Wikipedia article Z

### **Media**

The photos used in this site were obtained from:

- Image of the Rig – Was taken by me on a visit to West Texas in 2018
- The pixelated map was created in
- E6 Company logo was copied from [LinkedIn](https://www.linkedin.com/company/element-six/)
- The remaining images were downloaded from the Pexels App:
 - Blurred Code
 - Laptop
 - Under Construction from [Pixabay](https://pixabay.com/illustrations/under-construction-construction-sign-2408062/)

### **Code Snippets**

- Bootstrap responsive navbar - [Bootstrap 4 - navbar](https://getbootstrap.com/docs/4.0/components/navbar/)
- While building the navbar toggler, the menu items would only appear on the right.
  - The solution was provided on [Stack Overflow](https://stackoverflow.com/questions/47518911/boostrap-4-navbar-collapse-menu-right-align/50881393) 
- My navbar had a small amount of whitespace on the right-hand side.
  - The solution to remove this was again found on [Stack Overflow](https://stackoverflow.com/questions/48510609/remove-white-space-from-the-sides-and-top-of-my-navbar/48510687) 
- **Progress bars**
The progress bars used in resume.html were taken from [Bootstrap 4 - Progress](https://getbootstrap.com/docs/4.0/components/progress/)
- **Accordion Feature**
I copied and subsequently adapted the accordion feature fromthe tutorial provided on this webpage[**font-awesome-accordion-arrow-css**](https://supfort.com/font-awesome-accordion-arrow-css)
  - The reason for not using the standard Bootstrap accordion was that I wanted to visually indicate there was additional content hidden within each role.
- The code to achieve better looking bullets was taken from [Fontawsome](https://fontawesome.com/how-to-use/on-the-web/styling/icons-in-a-list)
- I copied a small piece of CSS code from Stack Overflow to help me equalise the image size on my portfolio cards.

### **Acknowledgements**

- The idea for this project originally came from a basic Resume exercise to illustrate ordered and unorder I had worked on while using the Mimo app&#39; (https://getmimo.com/playgrounds/812454) prior to starting the Full Stack Software Development course at the Code Institute. I subsequently expanded the basic exercise to create an online resume.

- I'd like to thank my mentor Sinead O'Brian for her direct feedback and advice in the run up to, and during this project.

- Further inspiration came from the UCD-Resume project in the CI User Centric Frontend module. I particularly identified with the thirds concept for separating the content.

- I'd like to acknowledge the guidance we received in an MS-1 planning call with :-
  - Jim Morel
  - John Traas
  - Anthony O'Brien
  ... the information they presented was regarding preparation for MS-1 projects was invaluable and helped calm the nerves somewhat before heading into the milestone project.
- Thanks to everyone at the Code Institute for helping to make this such an enjoyable and rewarding experience.
______
