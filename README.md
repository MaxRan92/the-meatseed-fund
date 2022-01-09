# The MeatSeed Fund

## Overview

MeatSeed aims to create a more sustainable food system by informing users about meat alternatives and providing investment opportunites related to this new and growing industry. The site explains the rationale behind three main meat alternatives presented, shows the fund's underlying companies and allows users to make a soft commitment for investment purposes.  

![Responsive Mockup](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/am-i-responsive.PNG)

## Author
Massimo Ranalli

## Site Aims
- Inform the public about the importance of meat alternatives for the future of food supply chain and for an environmentally friendly production
- Present three main innovations that will reshape the industry in the next years
- Present the MeatSeed Fund supported with company information and media coverage
- Give investors the possibility to start the investment process by making a soft commitment 

## UX

### Site Structure
The site is organized in three pages:
- Home: this is the landing page, in which the user can get an overview about the fund and its main mission
- About: contains details about the investment case
- Invest: allows users to understand the investment process and start investing

### Design
The whole website is designed with the purpose of invoking to users a deep sense of suistainability, progress and positivity through colors, images and shapes.
The color scheme consists in a contrast of black, white and green shown below. Moreover, green, red and yellow stand out to visually identify the three main technologies involved.

![Color Scheme](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/color-panel/colors.png)

## Features 

In this section you may find a description of the main sections of the site

### Navigation Bar
  - It is a common element of all the three pages. The navigation bar allows a smooth navigation through webpages via links to Logo, Home, About and Gallery. The active page is signalled in the menu with bright green and an underline. 
  - The bar is full responsive across devices and fixed to the top of the page: the user can access all the content through it, without need to press any back key.    

![Nav Bar](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/navigation-bar.PNG)

### The Hero Image
  - The hero image section includes an animated background image with text overlay which sums up in few words the main purpose of the project.
  - A button to the About page is included as a call to action to learn more about the matter.
  - The image represents a zoomed in broccoli and has been chosen for its ability to invoke nature and science.

![Hero Image](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/home-hero.png)

### Home Page Main Section
  - This section contains an overview of the fund and its activity.
  - Also in this section, a button to the Invest page is included as a call to action to learn more about the investment process.
  - An image of Singapore's Gardens by the Bay has beed added to reinforce the human intervention factor. 

![Home Main](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/home-main.png)

### Featured In Section
  - In this section the user can click to newspaper logos in order to see their coverage about the MeatSeed Fund.
  - The purpose is to build credibility over the company by showing that it is supported by important press names in the field of investing and finance. 

![Featured In](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/home-featured.png)

### Footer
  - The footer section includes the company logo, contact details and links to (future) social media profiles.
  - The footer follows the same design of the header: their dark backgrounds frame the page and visually invite the user to focus on the main content. 

![Footer](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/footer.png)

### About Page Main Section
  - The structure is similar to the Home main section to mantain consistency of design across web pages.
  - Its purpose is to explain why it is important to take action towards a more sustainable future.

![About Main](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/about-main.png)

### Three Innovations Section
  - This section illustrates the three meat alternatives innovations with images and descriptions.
  - The three categories, namely Plant-Based, Cultured and Insect-Based Meat, are visually identified through the colors of their images and borders (green, red and yellow respectively).

![Innovations](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/about-innovations.png)

### Portfolio Companies Section
  - This section resembles the Featured In one in the Home page, however the design is enhanced with more CSS proerties.
  - When the user hovers with its cursor, the category of the company will appear below its name and the background color of the tile will change based on it, creating a visual link with the above section.
  - Clicking on the tiles, a new tab to the company site will open. 

![Portfolio Companies](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/about-portfolio.png)

### Invest Page Main Section
  - The structure is similar to the Home and About main sections, to mantain consistency of design across web pages.
  - Its aim is to back the noble purpose of the investment with expected financial results.

![Invest Main](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/invest-main.png)

### Three Investment Steps Section
  - The structure is similar to the About Three Innovations Section. 
  - The section is mainly descriptive and illustrates the steps to invest in the MeatSeed Fund.

![Investment Steps](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/invest-process.png)

### Form Section
  - Following the Step 1 of the above section, a form is available.
  - The user will insert Personal Data (Text Input), his Investor Profile (Radio Button) and can select a Soft Commitment Range (Select).

![Form](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/invest-form.png)

## Testing 

### Validator Testing 
- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/)

### Cross Browser Testing
The site is correctly shown on Firefox, Chrome, Edge and Safari web browsers.

### Cross Device Testing
The responsitivity has been largely tested. The CSS code contemplates several breakpoints to adapt to various screen sizes, from ultrawide to several smartphone (Samsung Galaxy S III included, with its 360px width). For this purpose, Chrome emulator has been used.
To make the three column sections responsive (Innovations and Investment Process) was particularly challenging: at first they were designed with the float property, however the display flex one was much better to easily transformation an horizontal grid to a vertical one. My mentor Malia Havlicek gave me important hints providing [relevant material](https://codepen.io/taniarascia/pen/rOLEGe/)

### Lighthouse Grades
All the pages received 100/100 on Accessibility, Best Practices and SEO requirements, both in mobile and desktop view.
Performance scores are close to 100 and, in any case, over 90. [Click Here](https://raw.githubusercontent.com/MaxRan92/the-meatseed-fund/main/docs/screenshots/lighthouse.PNG) for a scoring result.
Initially the Performance score of the Home mobile view was around 75 due to large image size. As suggested by Lighthouse developer, the images have been converted from jpg to avif and used only in the mobile view.

### Unfixed Bugs
To be inserted if and when they will be discovered.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  1. In the GitHub [repository](https://github.com/MaxRan92/the-meatseed-fund), navigate to the Settings tab
  
  ![image](https://user-images.githubusercontent.com/87261820/147862161-f979c2bc-aef7-4cfc-8f27-d8482588b85f.png)

  2. Select "Pages" from the left hand navigation tab, then select Source > Branch: main
  
  ![image](https://user-images.githubusercontent.com/87261820/147862180-01f7842d-9433-4c3c-b633-6baa43e18a11.png)
  
  3. Once the main branch has been selected and the Save button is clicked, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.   

  ![image](https://user-images.githubusercontent.com/87261820/147862238-5a62868d-be20-47f3-af20-500691c40406.png)

  
The live link can be found here - https://maxran92.github.io/the-meatseed-fund/


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 
