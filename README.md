<h1 align="center">Fruit Locker<h1>



## Purpose

* This website is built to market a family business growing and selling their fruits. The aim is to present the family business's work and attract more customers to a home delivery service.
* This website is created as a Milestone 1 Project as part of the Code Institute's Full Stack Web Development course. It demonstrates skills learned in User-Centric Frontend Development part of the course, where HTML, CSS and Bootstrap as a CSS library were used.

This website is designed to be used across mobile and desktop devices.



## User Experience (UX)


### User Stories
####  First Time Visitor Goals
   a.  A primary goal of the first time visitor is to be able to access the website easily.
   b.  The first time visitor should be able to understand the website clearly as well as the purpose of the website.
   c.  The first time visitor should be able to easily navigate the website, understand the layout and find the wanted content.

####  Returning Visitor Goals
   a.  Returning visitor may wish to get more familiar with the products displayed.
   b.  The returning visitor may be interested in getting to know more about the business and to contact the owner.
   c.  The returning visito would like to find community links.

####  Frequent User Goals
   a.  The frequent user's goal would be to check to see which seasonal products are available.
   b.  The frequent user would be interested in purchasing the products.
   c.  They would be interested in leaving feedback.


### Design
####    Colour Scheme
   + Two primary colours used were orange and green (rgba(6, 104, 2, 0.75)). Those are natural, warm colours, and they reflect the business of growing fruits itself where the primary fruit is orange.

####    Typography
   + The Exo format is the main font used throughout the whole website with Sans-Serif as the fallback font if the font is not imported into the site correctly. Exo is a clean font which was picked as a good fit with the content and imagery used.
   + The larger font size was used for better visibility and design.

####    Imagery
   + Imagery is essential as the owner wants to showcase its products. There are three large full-width images breaking the content which give the user an exact representation of the subject matter.


### Wireframes
   + Wireframes were made using Balsamiq Wireframes.

   + Mobile Wireframes - [view](/assets/images/Wireframes/Mobile/).
   + Desktop Wireframes - [view](assets/images/Wireframes/Desktop/).
   ![Homepage](/assets/images/Wireframes/Desktop/Homepage.png)



##  Features
   + Responsive to be used on mobile, tablet and desktop devices.
   + Interactive elements.



##  Technologies Used


### Languages Used
   + [HTML5](https://en.wikipedia.org/wiki/HTML5)
   + [CSS3](https://en.wikipedia.org/wiki/CSS#CSS_3)

### Frameworks, Libraries & Programs Used
1. [Bootstrap 4.5.3](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
   + Bootstrap was used to assist with the responsiveness and styling of the website.
2. [Hover.css](https://ianlunn.github.io/Hover/)
   + Hover.css was used in the footer section to add the transition to social links while being hovered over.
3. [Google Fonts](https://fonts.google.com/)
   + Google Fonts were used to import "Exo" font into the style.css file which was used on the whole page.
4. [Font Awesome](https://fontawesome.com/)
   + Font Awesome was used throughout the page to add icons for UX purposes.
5. [Balsamiq](https://balsamiq.com/)
   + Balsamiq was used to create wireframes for the page.
6. [Visual Studio Code](https://code.visualstudio.com/)
   + Visual Studio Code was used as the IDE for coding and creation of the source files. Integrated terminal was used to commit and push changes to GitHub.
7. [Git](https://git-scm.com/)
   + Git was used for version control by utilizing the VSCode terminal to commit and push to GitHub.
8. [GitHub](https://github.com/)
   + GitHub was used to store project after being pushed from Git.



##  Testing

###  Further Testing
   + This website was tested on Google Chrome, Mozilla Firefox, Microsoft Edge and Safari Browsers.
   + The website was viewed on different devices and resolutions like Desktop, Tablet, iPhone 6,7,8 and Galaxy S10.
   + A large amount of testing was done to ensure that all pages were behaving as expected with different resolutions, and all were linking correctly.
   + Friend and family members were asked to review the website and documentation for any bugs or recommendations.

###  Bugs

   + Bug: White space appearing on the right side of the body.
   + Fix: Setting overflow-x to hidden removed the empty space.

   + Bug: The element button was placed inside the anchor tag, which reported the error.
   + Fix: Instead of using button element, anchor tag was used with the respective classes.

   + Bug: Custom cards providing offers of fruit had different heights on different resolutions.
   + Fix: The additional classes "d-flex align-items-stretch" were added to the parent column divs which made all the cards the same height.



##  Deployment


###  GitHub Pages

The project was deployed to GitHub Pages using the folowing steps:

1. Log in to [GitHub](https://github.com/) and locate the [GitHub Repository](https://github.com/idelija92/ms1)
2. At the top of the repository, locate the "Settings" button on the menu.
3. Go to "GitHub Pages" section.
4. Under "Source", click the dropdown menu, and select "Master Branch".
5. The page will automatically refresh.
6. Locate the new published site [link]() in the "GitHub Pages" section.

The following two sections were taken from the Code Institute's "Sample README.md" [template](https://github.com/Code-Institute-Solutions/SampleREADME/blob/master/README.md). 

###  Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps:

1. Log in to [GitHub](https://github.com/) and locate the GitHub Repository.
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to [GitHub](https://github.com/) and locate the GitHub Repository.
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type git clone, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

Click [Here](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.