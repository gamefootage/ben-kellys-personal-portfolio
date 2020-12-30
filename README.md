<h1 align="center"><strong>Milestone Project:</strong> <br>Ben Kelly's Personal Portfolio</h1>

[Live project can be viewed here.](https://gamefootage.github.io/ben-kellys-personal-portfolio/)
## **Overview**
My project is a portfolio for myself, Ben Kelly, that essentially displays the information found on my [CV](./docs/ben-kelly-cv-sept-2020.pdf) in a creative way through the means of this webpage.  
It tells the user all about me, my background, my interests, and my work and work history. It portrays an accurate and positive view of me and my life.
## **User Experience**

 - ## User Stories
>    - ### First Time User Goals
>       1. As a first time user, I want to be presented with an eye-catching, yet understandable, layout and colour scheme, when first opening the site.
>       2. As a first time user, I want to be able to easily navigate the site and gather information about Ben as I go.
>       3. As a first time user, I want to see Ben's skill set and qualifications, to know that he is capable and good at what he does.
>       4. As a first time user, I want to see Ben's work history, how long he worked there, and what he did, to see if he is a reliable employee.
>       5. As a first time user, I would like to see Ben's relevant social media and business related accounts, to determine if they are known and trustworthy.
  
>    - ### Returning User Goals
>       1. As a returning user, I want to be able to quickly get to the part of the site I need and the information I would like to access.
>       2. As a returning user, I want to be able to remember how to navigate and use the site with little to no effort.
>       3. As a returning user, I want to still be impressed at the layout and colour scheme of the site.
>       4. As a returning user, I want to be able to quickly access Ben's social links if I have forgotten or misplaced them.
  
>    - ### Potential Employer Goals
>       1. As a potential employer, I want to get enough information about Ben so that I feel like I have already interviewed him briefly.
>       2. As a potential employer, I want to see Ben's skills, not just in the area I am employing him from, to see if his work rate translates across multiple interests and if he is at a high level in everything he does.
>       3. As a potential employer, I want to know where Ben has worked before, if his responsibilities there were of importance to the business, and if he has a good work ethic.
>       4. As a potential employer, I want methods of contacting Ben and seeing the social accounts he has, and the projects he's worked on.

>    - ### Recruitment Agent Goals
>       1. As a recruitment agent, I would like to be able to navigate to the information about Ben that shows he is capable of doing the job I am trying to allocate to him.
>       2. As a recruitment agent, I would like to be able to show this site to the company that is using me as a medium as evidence of the work Ben can do.
>       3. As a recruitment agent, I would like to be able to find easily and clearly Ben's skills and work history, to show to companyies looking to employ.
>       4. As a recruitment agent, I would like relevant links to Ben's accounts for myself and the company hiring to determine Ben's reliability and trustworthiness.

- ## Design
   - ### **Colour Scheme**
      * The main background colour of the site is a slate gray (#2c2c2c).
      * The other main colours are red, yellow, blue and green.
      * The gradients on images are of the main colour variaties moving from bottom to top getting darker as it rises.
      * The colours in the skill section buttons are taken from the logos of the teams I played on for the sport buttons and CodeInstitute red for the technology button.
    - ### **Typography**
      * The main fonts I use are Bebas Neue, Julius Sans One, and Source Sans Pro, I got them from [Google Fonts](https://fonts.google.com).
      * Source Sans Pro is a clean sans-serif typeface, I like it's readability in small font sizes, whereas Bebas Neue and Julius Sans One is better in larger sizes. Bebas Neue I use for section headers, and Julius Sans One for medium size text. My fallback font is sans-serif.


- ## [**Wireframe** (note that tablet layout is the same as mobile)](https://wireframepro.mockflow.com/view/M001cd26c723c36ed609942092aed0a071607105289735)
## **Features**
### Existing Features
- The site incorporates what is known as parallax scrolling. This is where elements are scrolling at different speeds to create a 3D effect.
- The navigation bar is fixed at the top of the page, on screens smaller than 1200px it becomes collapsable and has a burger icon to toggle it.
- The "About" section uses 3 images at different points on the Z axis that, when hovered on, reveal paragraphs relevant to the photo of me.
- The skill section has 4 buttons for different areas of skill I have (basketball, Gaelic football, rugby, and technology). When these buttons are pressed they display the information relevant to the subject, pressing ones deactivates the others.
- The work experience timeline shows all the jobs I've had and the periods I worked in them, when hovered on they reveal more information about the subsequent job.
- Lastly the fixed footer at the bottom has links to my [Facebook](https://www.facebook.com/ben.kelly.7509), [LinkedIn](https://www.linkedin.com/in/ben-kelly-a36b001b2/), [Instagram](https://www.instagram.com/benkelly___/), [GitHub](https://github.com/gamefootage), a ["mailto" link](benskelly10@gmail.com), a [WhatsApp link](https://wa.me/353852030033), and a [Google map link](https://goo.gl/maps/LJCFoNLXqws8qawE8) of Galway, Ireland.

### Possible Future Features
- Having a portfolio section of the site with all my future projects, with a demo of each and a link to each project as well.
- Having a recommendations section full of reviews and comments from other people on my work and character.
- Having an education button in the skills/achievements section once I have attained more diplomas/degrees.

## **Technologies Used**
- [**Bootstrap 4.0**](https://getbootstrap.com/docs/4.0/getting-started/introduction/)  
  - Bootstrap CSS allows for ease in responsive sizing and compononents such as nav bars and collapsable elements.
  - Using Bootstrap JS allowed me to make the skill section buttons show and hide information and make the nav bar expandable on small devices.
- [**Font Awesome**](https://fontawesome.com/)
    - Using Font Awesome's provided link tag I could use their icons on the buttons in the skill section and for my footer links.
    >     <link rel="stylesheet" href="https://use.fontawesome.coreleases/v5.13.0/css/all.css">
- [**Stack Overflow**](https://stackoverflow.com/)
    - Many of the questions I had during the creation of this site had already been asked and answered on stack overflow, I found it a great tool to solve many problems I had.
- [**Google Fonts**](https://fonts.google.com/)
    - Google Fonts is a vast library of fonts that I used to test and pair the fonts I ended up using in this project.

## **Testing**
### **Validators**
The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.
   - [W3C Markup Validator](https://validator.w3.org/) - [Results](./docs/markup-validator-results.png)
   - [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - [Results](./docs/css-validator-results.png)**
     
***Note:** Section does have a header (h2) but it is just outside the section to account for parallax effect.

****Note:** Mozilla themselves state that text is a valid value of background-clip [here](https://developer.mozilla.org/en-US/docs/Web/CSS/background-clip). All browsers, bar Internet Explorer, accept the text value of -webkit-background-clip. Also -webkit-overflow-scrolling is used on iOS Safari, as described on [Mozilla's article](https://developer.mozilla.org/en-US/docs/Web/CSS/-webkit-overflow-scrolling) on it. [Here](./docs/safari-overflow-scrolling.png) is a screenshot of the compatability of it.

### **Tesing User stories from User Experience Section**
 - ### First Time User Goals
    * As a first time user, I want to be presented with an eye-catching, yet understandable, layout and colour scheme, when first opening the site.
      
         * On loading the site, users are presented with a large image of me. The main and sub text is faded in.
         * The navigation bar is fixed to the top with clear and distinct words relating to the 4 relevant sections.
         * The user can either scroll down through the site or click one of the [navigation buttons](./docs/navbar.png), to direct them to the relevant section.
         * At the bottom of the page is a [fixed footer](./docs/footer.png) with relevant social and contact links with colours taken from each company's logo and white for email. There is also a map link for where I am living, Galway, Ireland.
    * As a first time user, I want to be able to easily navigate the site and gather information about Ben as I go.
         * The one page scrolling format of the site allows easy navigation and presentation of information as you scroll.
         * The navigation and footer are always fixed both top and bottom to allow for access to important links and sections of the site in one click.
    * As a first time user, I want to see Ben's work history, how long he worked there, and what he did, to see if he is a reliable employee.
         * The work experience section shows a timeline in the reverse order in which I got the jobs I've worked in.
         * When a user hovers on one of the timeline items it expands and shows more detailed information on each job.
    * As a first time user, I would like to see Ben's relevant social media and business related accounts, to determine if they are known and trustworthy.
         * The fixed footer allows for constant easy access to these necessary links, when clicked they open a new tab.
  
 - ### Returning User Goals
    * As a returning user, I want to be able to quickly access the relevant part of the site and the information I would like to access.
         * The navigaion bar buttons are clear and understable, they allow navigation to the relevant section easily and quickly.
    * As a returning user, I want to be able to remember how to navigate and use the site with little to no effort.
         * The one page scrolling and navigation is very intuitive and easy to follow for a returning user.
    * As a returning user, I want to still be impressed at the layout and colour scheme of the site.
         * The initial loading of the site has a large image with a gradient and a colourful fixed footer that allows a vibrance that strikes the user, as they scroll the more colourful the site becomes.
    * As a returning user, I want to be able to quickly access Ben's social links if I have forgotten or misplaced them.
         * The fixed footer displays all links clearly and beautifully allowing for easy access from every section.
  
- ### Potential Employer Goals
    * As a potential employer, I want to get enough information about Ben so that I feel like I have already interviewed him briefly.
         * The about section displays brief information on my upbrining, interests, and current job.
         * The skill section dives more thoroughly into my interests and what I've done in those areas.
         * The work section gives a complete timeline on my work history and the details of each job.      
    * As a potential employer, I want to see Ben's skills, not just in the area I am employing him from, to see if his work rate translates across multiple interests and if he is at a high level in everything he does.
         * The skill section shows off my range of skills and dives into the qualifications and achievements I have in each.
         * It shows I am at a high level in my areas of interest.
    * As a potential employer, I want to know where Ben has worked before, if his responsibilities there were of importance to the business, and if he has a good work ethic.
         * The work history timeline shows exactly where I've worked before and what I've done at each place of work.
    * As a potential employer, I want methods of contacting Ben and seeing the social accounts he has, and the projects he's worked on.
         * The fixed footer contains an email, and WhatsApp, link as a way of contacting me.
         * My GitHub link is also there to show off any public projects I have worked on, and my LinkedIn will provide greater details on projects done for other companies.
  
- ### Recruitment Agent Goals
    * As a recruitment agent, I would like to be able to navigate to the information about Ben that shows he is capable of doing the job I am trying to allocate to him.
         * The navigation bar and one page scrolling allows for quick navigation to parts of the site for new and returning recruitment agents.
    * As a recruitment agent, I would like to be able to show this site to the company that is using me as a medium as evidence of the work Ben can do.
         * This site is deployed on GitHub Pages and is easy to share a link to others if necessary.
         * The cross browser and device support allows the recruitment agent to not worry what technology the employer may be using.
    * As a recruitment agent, I would like to be able to find easily and clearly Ben's skills and work history, to show to companies looking to employ.
         * The navigation bar has clear buttons for easy navigation to those sections.
         * When clicking the navigation links the page lines up to display the section without any other scrolling necessary.
    * As a recruitment agent, I would like relevant links to Ben's accounts for myself and the company hiring to determine Ben's reliability and trustworthiness.
         * The fixed footer displays the relevant links beautifully and succinctly, opening in a new tab and easy to copy to one's clipboard.

### **Further Testing**
* The website was tested for cross-browser compatability on Firefox, Chrome, Internet Explorer, Safari, and Microsoft Edge.
* A media query was added in the CSS to test if the browser supports parallax and if the browser is IE 10+.
* The website was tested on multiple devices and screen widths using browser developer tools, and actual devices (Samsung A21, iPhone 7, iPad Pro, Macbook Pro, Windows 10 PC, Moto G7 Power).

### **Known Issues**
* Slight glitch when initially clicking on buttons in skill section where the image takes a few seconds to load.
* Wesbite doesn't function on IE <= version 9.
* On IE 10+ the Gaelic Football stock image fails to load and browser doesn't support 'object-fit: cover' so work images are at different widths to avoid stretching, and background images for the hidden section are now just gray.



## **Deployment**

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/gamefootage/ben-kellys-personal-portfolio)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://gamefootage.github.io/ben-kellys-personal-portfolio/) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/gamefootage/ben-kellys-personal-portfolio)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/gamefootage/ben-kellys-personal-portfolio.git
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/gamefootage/ben-kellys-personal-portfolio.git
> Cloning into `ben-kellys-personal-portfolio-clone`...
```

Click [here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## **Credits**
### Contents
All content was written by the developer.

### Images*
The images of me were taken from my phone. The stock photos were taken from [Pexels](https://www.pexels.com/), [The Sun](https://www.thesun.ie), [OTB Sports](https://www.otbsports.com), [Basketball Ireland](https://www.basketballireland.ie), and [WikiQuote](https://simple.wikiquote.org).

***Note:** This project is for educational purposes and any images used are not subject to copyright claims.

### Acknowledgemnts
- [**Keith Clark**](https://keithclark.co.uk/)
  > Parallax scrolling is a modern website design aspect with increasing popularity. It was something I wanted to implement in my project without JavaScript, and [Keith's article](https://keithclark.co.uk/articles/pure-css-parallax-websites/) came to my rescue with detailed information on how to do pure CSS parallax.

- [**Ignatius Ukwuoma**](https://www.linkedin.com/in/ignatiusukwuoma/)
  > Ignatius was the mentor assigned to me by CodeInstitute, he helped me realise my full potential and gave me valuable information at the beginning and middle of my project.

- [**Aaron Sinnot**](https://www.linkedin.com/in/aaronsinnott/)
  > Aaron was assigned to me as a temporary mentor at the end of my project when Ignatius was unavailable, he reviewed all the work I had done, helped me clean up my work to ensure it was all presentable and ensured I was ready for my deadline date.