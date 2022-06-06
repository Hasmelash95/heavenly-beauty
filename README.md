# Hermon Asmelash 

## Heavenly Beauty 

[Check out the live website here. ](https://hasmelash95.github.io/heavenly-beauty/)

A website for those looking for cost effective beauty tips and tricks, as well as a subscribe and pay service that sends customers personalised beauty regimens monthly for only 3.99 (GBP). An algorithm uses the information collected from users who fill out a form to ensure the beauty regimen is well suited to the client. 

Business goals are to become a trusted source for clients looking for affordable beauty regimens and encourage subscription with periodic special offers and discounts (due to partnerships with beauty brands) and algorithm-assisted routines sent monthly. 

![Screenshot 2022-06-06 at 12 28 33](https://user-images.githubusercontent.com/103432143/172152295-22885c8e-9020-4b77-8af6-4c8fe8474c5b.png)

## Table of Contents

[User Experience (UX)](#user-experience)

[Features](#features)

[Testing](#testing)

[Technologies Used](#technologies-used)

[Deployment](#deployment)

[Acknowledgements](#acknowledgements)

## User Experience (UX) <a name="user-experience">

### Strategy

#### User Stories

1. I've been perusing the web in search of makeup tutorials but very often it appears expensive makeup is needed to achieve any of the looks. I wish to visit a site that can offer cost saving tips and tricks. 

2. I've been searching the web in the hopes of finding a source that can redirect me to the cheaper beauty brands available. 

3. I want to find a beauty regimen that is tailor suited to me, my skin type, my means and my tastes. 

4. I appreciate that this website gives specialised beauty regimen but would like a bit more incentive to subscribe to this beauty site as opposed to others.

5. I would like to find a site with easy navigation and accessibility. 

#### Why Heavenly Beauty?

Heavenly Beauty will send emails to subscribers with special offers and vouchers. For only 3.99 (GBP) a month, customers will receive monthly beauty regimens tailor suited to them, created with the help of an algorithm that uses information from the form. There will also be a chance to win a free makeover from an expert beauticians. 

Easy navigation between the three pages in the website. Homepage provides links to the different sections of the site in addition to the navigation bar. The website is also friendly to those with impaired vision. 

### Scope

The website has three pages, the landing page, the second page with articles and the final page with the subscription form. 

Two articles in the second page to avoid overload, with images for decoration. Enough to give visitors of the website useful information that they can use in their day to day lives. 

Aria-labels for each of the unlabelled links to allow accessibility. 

Links to three social media platforms so users have multiple ways to contact Heavenly Beauty as well as learn more about them. 

Form with multiple sections in subscription page to ensure as much information can be taken from the user as possible without overwhelming them.

### Structure 

Three navigation bars underneath the header that link to different pages in the site, with the an underline indicating which page is the active page. 

A hero image that makes the purpose of the website clear with a link to the second page of the website for ease. 

A 'why subscribe' section under the hero image with a concise list with a link to the subscription page for ease. 

A footer with social media icons that open in another tab to the social media pages of Heavenly Beauty.

Articles in the second page with tips and tricks and external links to recommended brand websites.

A third page with a form to fill out that provides information to the algorithm and the staff at Heavenly Beauty.

### Skeleton

#### Wireframes

[Header and Navigation](https://user-images.githubusercontent.com/103432143/169900430-7b3b1a64-234e-40a6-9fba-928835e5407d.png)

[Hero Image](https://user-images.githubusercontent.com/103432143/169900587-0c5ddea2-4980-4328-9b3f-b431cfad425b.png)

[Why Subscribe and Footer](https://user-images.githubusercontent.com/103432143/169901093-2ef44339-887c-4eef-bb12-e9905e9591a2.png)

[Articles](https://user-images.githubusercontent.com/103432143/170581774-28f4ee4f-0f5b-4309-b1bc-7f7198923283.png)

[Aside and Recommended Brands](https://user-images.githubusercontent.com/103432143/170581849-46e81162-db6f-40c8-aa02-3ff330e8a997.png)

[Form](https://user-images.githubusercontent.com/103432143/170581894-92da499f-aa32-446e-a0b7-5eaf4ce77d00.png)

### Surface

The website has a dark purple foreground `#140A27` and backgrounds both white and `rgb(186, 177, 200)`. Chosen for the [good contrast ratio](https://webaim.org/resources/contrastchecker/?fcolor=140A27&bcolor=BAB1C8) (9.26:1).

Headings used Georgia (serif) as a font while the rest of the text used Verdana (sans-serif) with Geneva and Tahoma as back ups.

Animation effects on the hero image draws the attention of the user as soon as the page loads. A white hallway was used as the background image for flair, and to evoke a heavenly hallway, yet remaining subtle enough to not draw attention away from the contents of the website.

Font awesome icons were added using:

```<script src="https://kit.fontawesome.com/86de956f5a.js" crossorigin="anonymous"></script>```
  
## Features <a name="features">

### Header and Navigation

A translucent header background color with bold dark text centered. The navigation buttons with links to the three different pages in the site are underneath the header with a bold style to stand out in the page. The menu text is underlined whenever the mouse hovers over the link and the active page (the page the user is currently on) is indicated by an underline that remains.

![Header and Nav - Home Page](https://user-images.githubusercontent.com/103432143/170696541-31b6ad67-3061-48c8-bd5a-b6b368038e16.png)

![Header and Nav - Beauty Hacks](https://user-images.githubusercontent.com/103432143/170696560-312c05a2-2296-4fdb-acb2-5451f3fd9ee3.png)

![Header and Nav - Subscribe Now](https://user-images.githubusercontent.com/103432143/170696590-5f344bf5-5cc0-4309-8abc-b7561f0a0021.png)

### Home Page

#### Quote

An inspirational quote by Dante Alighieri on the main page: "Beauty awakens the soul to act." Written in italics to differentiate it from the rest of the test on the site.

#### Call to Action

A hero image of a hand holding a compact mirror with powder fades in when the screen loads with a call to action, encouraging the user to click on the link (within the image) to check out the beauty tips and tricks on the Beauty Hacks page. A background color matching the header was used in case the image never loads.

![Allow No Barrier](https://user-images.githubusercontent.com/103432143/170694088-ba9ce095-2a35-4f0f-8b1d-e77a0ea0eb44.png)

A box with a translucent background (like the header) with another call to action, given the user reasons why they should consider subscribing. An encouragement to click the link (within the box) that will take them to the Subscription page. Cloud icons taken fromt Font Awesome are used in lieu of bullet points.

![Why Subscribe](https://user-images.githubusercontent.com/103432143/172259712-45970bce-bd3a-4144-b9ef-53e0430594c2.png)

The links on both of these sections have aria labels for the visually impaired.

### Beauty Hacks

The second page, which can be accessed either navigation button or the hero image, provides articles with cost saving beauty tips and tricks in addition to links to external articles which emphasize the importance of low income shoppers to the market and external links to Recommended Brands with affordable beauty products. The links open in a different tab and have aria labels for the visually impaired

![Articles](https://user-images.githubusercontent.com/103432143/170695744-ec6e644a-e17e-470b-bbb8-7230d6b8cfb9.png)

![Recommended Beauty Brands](https://user-images.githubusercontent.com/103432143/170695836-994504b7-79cf-45e5-bb71-7266d59a46ad.png)

The background with the purple lipstick provides added flair and remains in keeping with the color theme of the website. It's opacity is 0.9 to ensure that although it stands out against the background, some of the background image can still be glimpsed.

### Subscribe Now

The Subscribe Now page can be accessed either through the box in the Home Page or the navigation button. It takes the user to a page with a form to fill out. The text inputs are marked as required, so users cannot leave them blank. The personal details fieldset asks typical personal questions: Name, Age, Gender, Email. The latter through which Heavenly Beauty will contact the client. 

![Personal Details](https://user-images.githubusercontent.com/103432143/171049222-e564046d-9e17-4897-b74d-9bfeb853175b.png)

Gender uses a drop down menu (as it takes up less space than radio labels), with options Male, Female and Other, which gives a beautiful view of the calming background image. 

The second fieldset asks additional questions related to the users routine, tastes and means - as well as interest in certain brands. The information taken from the client and stored in the database will be analysed by an algorithm which will produce the best suited regimens for the client in question. In addition, the special offers will be refined to their tastes, especially regarding the brands that they're interested in. Drop down menus are used instead of radio labels to take up less space on the page.

Options for What skin type do you have?:
Normal, Sensitive, Dry, Oily, Combination

Options for What is your skin's undertone?:
Cool, Warm, Neutral

Options for How often do you apply makeup every week?:
Once a Week, Twice a Week, Several Days a Week, Every Day

Options for What's your preferred style?:
Natural, Dramatic, Glamorous, Sweet, Quirky
  
![Additional](https://user-images.githubusercontent.com/103432143/172260085-58290b26-58ac-4688-a183-5d06ff61ecea.png)

Multi-select checkboxes allow the user to select as many options (or no options) as they'd like. 

![Checkbox](https://user-images.githubusercontent.com/103432143/172260104-df727eea-3b0e-4897-b0d3-881f5f3671dd.png)

When the mouse hovers over the submit button, the colors reverse. Cloud icons from font awesome are added to the text for style.

![Submit Hover](https://user-images.githubusercontent.com/103432143/172260122-5c255bb4-b256-4dbe-9a81-0226387bdb40.png)

Attempting to submit without filling in the required fields, gets an error message.

![Required](https://user-images.githubusercontent.com/103432143/171049505-ded803b7-2f69-4928-bd61-a7d87e6195dd.png)

### Footer

Social media icons (fron Font Awesome) are centered and when clicked, take the users to the Heavenly Beauty social media websites (Facebook, Instagram, Discord) in a new tab with aria labels for those who are visually impared. 
Copyright is just below the social media links.

![Footer](https://user-images.githubusercontent.com/103432143/170702630-8acb37e1-e4fc-489e-94b6-954f83a8a3a8.png)
  
### Future Features
  
As the website customer base grows, more pages can be added with more in depth beauty advice. Perhaps expand into hair and nail care too. More subscribers might also be an opportunity to provide different deals. Maybe more perks if they upgrade to a 7.99 (GBP) membership. The website and algorithm will need better upkeep with the increasing client base.

## Testing <a name="testing">

### Validation

HTML code was run through [The W3C Markup Validation Service](https://validator.w3.org/). With all three pages passing with no error or warning.

![HTML Validation 1](https://user-images.githubusercontent.com/103432143/170784438-947aa566-3d03-44f9-a6cb-6680bfea896e.png)

![HTML Validation 2](https://user-images.githubusercontent.com/103432143/170784466-4496acda-6c07-4468-89fa-fdf37508e156.png)

![HTML Validation 3](https://user-images.githubusercontent.com/103432143/170784485-64458ab3-81fd-4742-9e69-d0420e2d778f.png)

CSS code was run through [Jigsaw](https://jigsaw.w3.org/css-validator/), passing with no error or warning. 

![CSS Validation](https://user-images.githubusercontent.com/103432143/170783014-56f8a198-7fc0-496b-9d87-7de9e41d1b9d.png)

### Performance 

Lighthouse tests were carried out to test website performance, accessibility, good practices and search engine optimization. The tests were carried out on each page - Home Page, Beauty Hacks and Subscribe Now. In order:
  
![Page 1](https://user-images.githubusercontent.com/103432143/172252488-5cf09b46-68f6-45cd-a34f-47324368f5a0.png)

![Page 2](https://user-images.githubusercontent.com/103432143/172252501-9b4fbd77-7a59-41d2-a374-e68f723cc885.png)

![Page 3](https://user-images.githubusercontent.com/103432143/172252526-8e5b16f8-8240-4026-b7c9-be2011dfc3cd.png)
  
Image dimensions were reised to get those performance values. 

### Functionality
![Tests 1-8](https://user-images.githubusercontent.com/103432143/172149953-8cddfa50-7fb0-410e-aff1-692b5b55aae1.png)
![Tests 9-11](https://user-images.githubusercontent.com/103432143/172149966-aa94aa35-e767-4bba-ab3e-ee522813e6a8.png)
![Tests 12-17](https://user-images.githubusercontent.com/103432143/172149971-e800bf56-7597-40a1-9a50-8134d07300c0.png)

### Browser Compatibility 

Functional tests carried out on Chrome, Safari, Firefox and Microsoft Edge.
All tests PASSED. Only difference between browsers was, when using Firefox and Safari the user is able to input letters into the age field. When they attempt to submit, however, a message pops up asking them to input a number.

Website is compatible with iPhones and Samsung smart phones. 

### Responsive Design

Web Developer Tools were used on Google Chrome to ensure the website maintained structural integrity in different screen sizes. Viewing the website on smart phones with smaller widths confirmed the maintenance of layout. Max-width: 2000px was used to ensure that the website would stop expanding with very large screen sizes. 

#### Am I Responsive? Screenshots
![Screenshot 2022-06-06 at 23 36 54](https://user-images.githubusercontent.com/103432143/172260639-cab539a6-989e-4f59-a524-44e5be70ec70.png)
![Screenshot 2022-06-06 at 12 24 32](https://user-images.githubusercontent.com/103432143/172152344-4b5d5a0f-4fa2-4d7f-8b12-3562e4d89b02.png)
![Screenshot 2022-06-06 at 23 39 14](https://user-images.githubusercontent.com/103432143/172260823-f36efb6b-9544-494c-aa1c-95f02e1bcbe4.png)

### Testing User Stories

1. I've been perusing the web in search of makeup tutorials but very often it appears expensive makeup is needed to achieve any of the looks. I wish to visit a site that can offer cost saving tips and tricks.

PASS - The makeup offers cost saving advice on the second page and the subscription page asks the user to check off the makeup items they do already have so as not to give them a regimen beyond their means.

2. I've been searching the web in the hopes of finding a source that can redirect me to the cheaper beauty brands available.

PASS - The Recommended Brands section on the Beauty Hacks page has external links to websites for the economical brands.

3. I want to find a beauty regimen that is tailor suited to me, my skin type, my means and my tastes.

PASS - The information given to the database and the algorithm will ensure the regimen is as well suited to the user as possible. Asking questions about skin type, undertones and preferred style. 

4. I appreciate that this website gives specialised beauty regimen but would like a bit more incentive to subscribe to this beauty site as opposed to others.

PASS - They will get periodic special offers and vouchers through email and the chance to win a free makeover. 

5. I would like to find a site with easy navigation and accessibility.

PASS - The website has a navigation bar to take the user to different pages in the site. The underline under the menu buttons ensure they know where they are in the site. This will be useful for whenever the site grows. Aria labels are used for the links, for users who are visually impaired. 

## Technologies Used <a name="technologies-used">

HTML5

CSS3

Git

Gitpod

Github

Balsamiq Wireframes

## Deployment <a name="deployment">
 
1. Set up Github Pages by clicking on the Settings tab, clicking on 'Pages' under 'code and automation'. Change the branch under 'Source' from 'None' to 'Main'. Click on 'Save'.
2. You can navigate to the page now using ```http://<your-username>.github.io/<repository-name>```
2. Ensure the directory is in the correct location to commit the changes to the right place. 
3. Use Git to commit changes from Gitpod by typing 'git add .' for every feature added and changes made and 'git commit -m "message here" ' on the Gitpod terminal with a clear but concise message explaining the changes made. 
4. Type 'git push' and refresh the website (updates may take a few minutes) and the changes will appear on the deployed site. Github Pages will pick up the latest commit pushed to the main branch.

To clone the repository: 
1. Log on to your Github account and head to the main page of the repository you wish to clone. 
2. Click on the 'Code' button above the list of files and choose from HTTPS, SSH or Github CLI, to copy the URL provided. 
3. Open terminal and ensure you are in the correct location. 
4. Type in 'git clone' and paste the URL you'd copied in step 2 and press enter. 

## Acknowledgements <a name="acknowledgements">

My mentor Brian Macharia - for giving lots of constructive feedback and offering code help to improve the website's styling. I have learned a lot from our sessions and I'm truly grateful. 

Code Institute - for all of the resources provided and the walkthroughs that helped me get used to technologies. 

Daniel Jones - for giving periodic advice on style choices and pointing out typos. 

Alemtsehay Tekle - for giving feedback regarding subscription page from her experience in designing forms. 

READMEs of Anna, Haley, Caroline and Elaine for inspiration on what sections to include on my README. 

[Pexels for Images: ](https://www.pexels.com/)

[Photo by Kristina Paukshtite](https://www.pexels.com/photo/person-holding-compact-powder-2417855/)

Photo by Oleg Magni: Purple Lipstick against White Background

[Photo by Robin Schreiner](https://www.pexels.com/photo/arches-hallway-inside-building-2261166/)

[Font Awesome for icons](https://fontawesome.com/icons)

[HubSpot for Fade In Animation Effect](https://blog.hubspot.com/)

[W3Schools for Code Help](https://www.w3schools.com/)

[For Beautifying code](https://www.freeformatter.com/)

[Am I Responsive?](https://ui.dev/amiresponsive)

[Stephanie Lange on YouTube for some useful makeup tips.](https://www.youtube.com/c/stephanielange) 

[Cosmopolitan](https://www.cosmopolitan.com/style-beauty/beauty/)

[Beauty Bay](https://www.beautybay.com/)

[Revolution Beauty London](https://www.revolutionbeauty.com/uk/en/home?gclid=Cj0KCQjwhLKUBhDiARIsAMaTLnGwszVDjxEcYBid95cIltu8vNy_LLMXN7_l9_eZ7ZGIwRa1TrmrOAQaAq9GEALw_wcB)

[Nyx Cosmetics](https://www.nyxcosmetics.co.uk/)

[Lottie London](https://lottie.london/?gclid=Cj0KCQjw4PKTBhD8ARIsAHChzRIlq7G2mHVUX3fLJ_JurfA27vdCVFU99pKyWDUHmcrGtdQK6RY0LhsaAuVgEALw_wcB)

[L'Oréal Paris](https://www.loreal-paris.co.uk/makeup)

[This article](https://www.gcimagazine.com/brands-products/color-cosmetics/news/21866514/lowincome-shoppers-lead-beauty-spend-nielseniq)





