# The MeatSeed Fund - Milestone Project 1

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
The whole website is designed with the purpose of invoking a deep sense of suistainability, progress and positivity through colors, images and shapes.
The color scheme consists in the contrast of black, white and greens shown below. Moreover, category colors stand out to visually identify the three main technologies involved.

![Color Scheme](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/color-panel/colors.png)

## Features 

In the following paragraphs you will find athe description of the different section of the site, in order to understand how the Site Aims were put to practice.

### Navigation Bar
  - It is a common element of all the three pages. The navigation bar allows a smooth surfing through webpages via links applied to Logo, Home, About and Gallery elements. The active page is signalled in the menu with bright green and an underline. 
  - The bar is fully responsive across devices and fixed to the top of the page: the user can access all the content through it, without need to press any back key.    

![Nav Bar](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/navigation-bar.PNG)

### The Hero Image
  - The hero image section includes an animated background image with text overlay which sums up in few words the main purpose of the project.
  - A button to the About page is included to stimulate user curiosity and call to action to learn more about the subject.
  - The image represents a zoomed in broccoli and has been chosen for its (quite unexpected) capacity to invoke nature and science at the same time.

![Hero Image](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/home-hero.png)

### Home Page Main Section
  - This section contains an overview of the fund along with its business activity.
  - A second button to the Invest page is included as a call to action to learn more about the investment process.
  - An image of Singapore's *Gardens by the Bay* has beed added to reinforce the mankind progress idea of the site. 

![Home Main](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/home-main.png)

### Featured In Section
  - In this section the user can click to newspaper logos in order to see their coverage about the MeatSeed Fund.
  - The purpose is to build credibility over the company by showing that it is supported by important press names specialized in the field of investing and finance. 

![Featured In](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/home-featured.png)

### About Page Main Section
  - The structure is similar to the Home Main Section to mantain consistency of design across web pages.
  - Its purpose is to explain why it is important to take action towards a more sustainable future.

![About Main](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/about-main.png)

### Three Innovations Section
  - This section illustrates the three meat alternatives innovations with images and descriptions.
  - The three categories, namely Plant-Based, Cultured and Insect-Based Meat, are visually identified through the colors of their images and borders (green, red and yellow respectively).

![Innovations](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/about-innovations.png)

### Portfolio Companies Section
  - This section resembles the Featured In one in the Home page, however the design is enhanced with more CSS properties.
  - When the user hovers with the cursor, the category of the company will appear below its name and the background color of the tile will change based on it, creating a visual link with the above section.
  - Clicking on the tiles, a new tab will open leading to the company site. 

![Portfolio Companies](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/about-portfolio.png)

### Invest Page Main Section
  - The structure is similar to the Home and About Main Sections, to mantain consistency of design across web pages.
  - Its aim is to back the noble purpose of the subject presented with the expected financial results.

![Invest Main](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/invest-main.png)

### Three Investment Steps Section
  - The structure is similar to the Three Innovations Section. 
  - The section is mainly descriptive and illustrates the steps to invest in the MeatSeed Fund.

![Investment Steps](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/invest-process.png)

### Form Section
  - As anticipated by the Step 1 of the above section, a form is available at the bottom of the Invest page.
  - The user will insert Personal Data (Text Input), his Investor Profile (Radio Button) and can select a Soft Commitment Range (Select).

![Form](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/invest-form.png)

### Footer
  - The footer section includes the company logo, contact details and links to (future) social media profiles.
  - The footer follows the same design of the header: their dark backgrounds frame the page and visually invite the user to focus on the main content. 

![Footer](https://github.com/MaxRan92/the-meatseed-fund/blob/main/docs/screenshots/footer.png)

## Testing 

### Validator Testing 
- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/) 
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/)

### Cross Browser Testing
The site is correctly shown on Firefox, Chrome, Edge and Safari web browsers.

### Cross Device Testing
The responsiveness has been largely tested. The CSS code contemplates several breakpoints to adapt to various screen sizes, from ultrawide to several smartphone models (Samsung Galaxy S III included, with its 360px width). For this purpose, Chrome emulator has been used.
Making the three column sections responsive (in the Innovation and Investment Steps sections) was particularly challenging: at first they were designed with the display float property, however the display flex one was much better in order to transform an horizontal grid to a vertical one. My mentor Malia Havlicek gave me important hints providing this linked [relevant material](https://codepen.io/taniarascia/pen/rOLEGe/).

### Lighthouse Grades
All the pages received 100/100 on Accessibility, Best Practices and SEO requirements, both in mobile and desktop view.
Performance scores are close to 100 and, in any case, over 90. [Click Here](https://raw.githubusercontent.com/MaxRan92/the-meatseed-fund/main/docs/screenshots/lighthouse.PNG) to see an example of a scoring result obtained.
Initially the Performance score of the Home mobile view was around 75 due to large image size. As suggested by Lighthouse in their review, the images have been copied and converted from .jpg to .avif, to be used only in the mobile view.

### Unfixed Bugs
To be inserted if and when they will be discovered.

## Deployment

- The site is deployed on GitHub at the followin [link](https://maxran92.github.io/the-meatseed-fund/index.html)
- The deployment process is the following
  1. In the GitHub [repository](https://github.com/MaxRan92/the-meatseed-fund), navigate to the **Settings** tab
  2. Select **Pages** from the left hand navigation tab, then select **Source** > **Branch: main**
  3. Once the main branch has been selected and the **Save** button is clicked, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.   

The live link can be found [here](https://maxran92.github.io/the-meatseed-fund/index.html)

## Credits 

### Acknowledgements
I would like to sincerely thank my mentor [Malia Havlicek](https://github.com/maliahavlicek): her great experience in the field helped me to better understand the purpose of the project and how to obtain the desired output.

### Content
- Working in an asset management company which actively invests in the themes presented, the text content for the MeatSeed Fund has been elaborated by me looking at my direct job experience. The main document that I have consulted is the *[Food for thought, the protein transformation](https://web-assets.bcg.com/a0/28/4295860343c6a2a5b9f4e3436114/bcg-food-for-thought-the-protein-transformation-mar-2021.pdf)* report published by Boston Consulting Group, even if no text was copied.
- As per the design of the web pages, I was inspired by the Love-Running site created during the course, especially for the three-column-sections and for the forms.

### Media
- The images are taken from [Pexels](https://www.pexels.com/) and [Unsplash](https://unsplash.com/), both open source sites.
- The logos are from [Flyclipart](https://flyclipart.com/)
- The icons in the footer are taken from [Font Awesome](https://fontawesome.com/)
- The icon on the web page tab are made with [Favicon](https://favicon.io/)  
