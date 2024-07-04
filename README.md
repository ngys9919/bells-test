<!-- .md means markdown -->

<!-- README.md -->
<!-- This file documents the information about the portfolio project. -->
<!-- It should be READ ME first!!! -->

<!-- Heading level 1 -->
# BELLS-TEST
**(SCTP) Full Stack Developer**

Module 2: **UX (User Experience) Design and User Interface Theory**

***Project Assignment - Portfolio***

<!-- Heading level 3 -->
### Project File Structure:

* HTML Files (hypertext markup language)

>>> Home page (Landing Page)
: index.html

>>> About page
: about.html

>>> Contact Us page
: contact-us.html

* CSS Folder (cascading style sheets)
: bootstrap.css
: main.css
: reset.css
: style.css

* IMG Folder (images)
: bells_logo.jpg
: bellstech_logo.png
: sctp-series.jpg
: cybersecurity.jpg
: datascience.jpg
: fullstack.jpg
: blockchain.jpg
: coder.jpg
: sctp-salary.jpg
: home.png
: index.png
: button-LearnMore.png
: one.png
: two.png
: three.png
: four.png
: five.png
: telephone-blend.png
: whatsapp-blend.png
: email-blend.png

* RES Folder (resources)
: bells.ico

* MEDIA Folder (multimedia)
: \<empty\>

* JS Folder (javascript)
: \<empty\>

* UNUSE Folder (unused, obsolete)
: phone.png
: mobile.png
: email.png
: six.png
: seven.png
: eight.png
: nine.png
: phone-app.png
: whatsapp-app.png
: outlook-app.png
: index-bells.png

<!-- Heading level 1 -->
# Project Guide
For the purpose of the portfolio project, a landing page is created for the following:

```json
{
1. "An educational school" : in our case "Educational School: BELLSTECH"
}
```

This project is about *SkillsFuture Career Transition Programme (SCTP)* at **BELLSTECH**. 

The application of this project caters to the needs of a specific target user group, the mid-career switchers,
who are looking for information on SCTP Courses at BELLSTECH, a tech business unit of [Bells Institute of Higher Learning][1].

The website provides an one-stop entry point to the SCTP Courses available, namely:

***
1. *(SCTP) Cyber-Security*
2. *(SCTP) Data-Science*
3. *(SCTP) Full-Stack*
4. *(SCTP) Block-Chain*
***

It also explains the tech roles [^bignote] and its briefing on these domain areas[^1], with contents created using AI Tool [Microsoft Copilot][2].

The web development is done using [Visual Studio Code][3] with responsive design concepts that provide media query breakpoints based on the following screen sizes:

***Bootstrap Breakpoints***
    
| Device(s) | Description | Prefix | Screen Sizes |
| :--- | :---: | :---: | ---: |
| phones | Extra small | None | <576px |
| portrait tablets and large phones | Small | sm | ≥576px |
| landscape tablets | Medium | md | ≥768px |
| laptops/desktops | Large | lg | ≥992px |
| large laptops and desktops | Extra large | xl | ≥1200px |
| large tv screens | Extra extra large | xxl | ≥1400px, max:1580px |


This simple website has a BellsTech logo and navigational bar with Home, About and Contact Us links in the landing page.\
This provides an inner site navigation that allows the user to view the different pages in the site.\
It also uses navbar, carousel, container, cards, form, badge, button and radio buttons from CSS Bootstrap.

![Educational School: BELLSTECH's Landing Page. This website is so cool!](img/index.png "index.html Landing Page")

The website is deployed using [GitHub Pages][4] so that it is available via a public web address.

<!-- Heading level 4 -->
#### The url for the portfolio project is here:

- [Educational School: BELLSTECH](https://ngys9919.github.io/bells-test/ "My project-website!")
: Click the hyperlink <https://ngys9919.github.io/bells-test/>

<!-- Heading level 4 -->
#### The source codes is hosted as public on a Github repository and the link is as follows: 

- [Source Codes Github Link](https://www.github.com/ngys9919/bells-test "My source-codes!")
: Click the hyperlink <https://www.github.com/ngys9919/bells-test>

<!-- Heading level 2 -->
## Features

<!-- Heading level 3 -->
### Existing Features (initial phase with module 2 knowledge (html/css))
The user interface is provided by CSS Bootstrap framework. The special font is using Google Font library. The content is done up with HTML markup language whilst the style for the website is beautified with CSS stylesheets.

Home page:
1. Logo - to identify the brand of the organization via its logo image
2. Navigation Bars - to provide site navigation with tabs like About and Contact Us
3. Carousel Slides - to showcase slides on the SCTP programme and its courses
4. Badges - to do sale pitch for BellsTech on two points: offerings and contact
5. Cards - to explain in details the tech role and hyperlink to course details in Bells' website
6. Radio Button Group - to select the interested course (choose 1 out of 4 SCTP courses)
7. Email Input Form - to enter the email address for return reply
8. Check Box - to register for inclusion into mailing list

About page:
1. Flexbox - to list 5 points for about SCTP advantages
2. CSS Box - to present information about BELLSTECH
3. Home icon - to return to Home page

Contact Us page:
1. Bullet List - to list 5 points why sign-up
2. Contact Box - to name course consultant and his/her contacts
3. Home icon - to return to Home page

<!-- Heading level 3 -->
### New Features (advanced phase with module 3 knowledge (javascript))
The functionality for buttons clicked (Learn More button and Submit button) and radio button selected (for selection on one of the four SCTP courses) is not yet implemented. This requires logic that could only be done with front-end development.T 

1. Learn More button - to further provide trainees' review on the SCTP course and more course information on the next intake.
2. Submit button - to capture the radio button selection for the SCTP course selected and send email to the entered email address with course material.
   
<!-- Heading level 3 -->
### Future Implementation
The web design could expand to include new SCTP Courses like Business Digitalisation Specialist and Digital Marketing and AI Integration offered by Bells. Also, it could turn into an SCTP Infohub by including all the SCTP Courses (for example, SCTP AI & Cloud Services, SCTP Data Centre Professionals, SCTP Facilities Operations Management offered by SP PACE Academy; SCTP Data Analytics, SCTP Cybersecurity, Governance, & Compliance, SCTP Software Development & UX Design, SCTP Cloud & IT Infrastructure, SCTP Digital Marketing & E-Commerce, SCTP Project Management & Business Analysis offered by NTUC LearningHub; etc) that are availble in Singapore by different training providers (not just restricted to BellsTech only).

<!-- Heading level 2 -->
## Testing
1. Using HTML Validator   
   The html files are checked with W3C Markup Validation Service for any errors through Validate by File Upload method.

   https://validator.w3.org/#validate_by_upload

2. Using CSS Validator   
   The css files are checked with W3C CSS Validation Service for any errors via By file upload method.

   https://jigsaw.w3.org/css-validator/#validate_by_upload

3. Using Chrome Inspector (F12 function key)   
   3.1 The website is checked for responsiveness with Chrome browser for screen sizes through Toggle device toolbar (Ctrl + Shift + M).   
   3.2 The website is also checked with re-sizing the browser windows to see the effect of media query on screen dimensions. 

4. Actual Usage   
   4.1 The url is activated in real use-case for laptop (Acer notebook) via browsers (Google Chrome and Microsoft Edge).   
   4.2 The url is activated in real use-cases (portrait and auto-rotate) for mobile (Samsung Galaxy smartphone) via browser and short-cut.

<!-- Heading level 2 -->
## Credits

### resource
- The .ico file used for this website was converted from .png logo file with this site:

  https://www.freeconvert.com/png-to-ico

- The special font used in this site was obtained from:

  https://fonts.google.com/

### images
- The photos used in this site were obtained from:

  https://bells.sg/sctp/

- The numerical pictures used in this site were obtained from:

  https://thehappyprintable.com

### icons
- The icons used in this site were obtained from:

  https://www.flaticon.com/free-icons/

### content
- The text for tech roles (displayed inside cards under index.html) were generated with Copilot:

  https://copilot.microsoft.com/

- The text for why sign-up (bullet-list under contact-us.html) and about Bells SCTP (5 points under about.html) were copied from :

  presentation slides by Sherfeeq Razal

### Acknowledgements
Thanks to Bells for support!

<!-- Heading level 2 -->
## About
> This project work, part of **Module 2: UX (User Experience) Design and User Interface Theory**, 
> is an individual assessment done by Candidate’s Name (as in NRIC): **Ng Yew Seng** (Candidate’s NRIC: **S XXXX 3 5 3 / F**), 
> a trainee under the **(SCTP) Full Stack Developer** course, organized by **Bells Institute of Higher Learning**. 

>>
>> Coder: ***Ng Yew Seng***\
>> © Copyright 2024\
>> Bells Institute of Higher Learning


<!-- Heading level 2 -->
## Technologies Used
- [x] HTML5
- [x] CSS3
- [x] CSS Framework (Bootstrap v5.3.3)

<!-- Heading level 2 -->
## References
1.  [Microsoft Visual Studio Code](https://code.visualstudio.com)
    
2.  [Microsoft Copilot](https://copilot.microsoft.com)

3.  [Microsoft GitHub](https://www.github.com)
   
4.  [Bells Institute of Higher Learning](https://bells.sg)

5.  TECH TALK: Bells Trainers Symposium 2024

<!-- Heading level 6 -->
###### Footnotes
--------------
[^bignote]: Tech roles include Cyber-Security Professional (such as penetration testers, security engineers, incident responders, and security consultants), Data-Science Specialist (data engineers, data analysts, and data scientists), Full-Stack Developer (UX/UI designers, front-end developer, and back-end developer) and Blockchain Developer (\*blockchain software developer, and web3 developer).

[^1]: Domain areas include Cyber-Security, Data-Science, Full-Stack, and Block-Chain.

--------------

<!-- hyperlinks -->
[4]: https://github.com "GitHub"
[3]: https://code.visualstudio.com "Visual Studio Code"
[2]: https://copilot.microsoft.com "Microsoft Copilot"
[1]: https://bells.sg "Bells Institute of Higher Learning"
