

# TABLE OF CONTENT

1. <a href ="#about-this-website">ABOUT THIS WEBSITE</a>

2. <a href ="#features">FEATURES</a>

    <a href ="#quiz-instructions">Quiz Instructions</a>

    <a href ="#home-page">Home Page</a>

    <a href ="#quiz-page">Quiz Page</a>

    <a href ="#results-page">Results Page</a>

    <a href ="#future-features">Future Features</a>

3.  <a href ="#user-experience-ux">USER EXPERIENCE UX</a>

    - <a href ="#wire-frames">Wire Frames</a>

    - <a href ="#structure">Structure</a>

    - <a href ="#color-theme">Color Theme</a>

4. <a href ="#testing">TESTING</a>

    <a href ="#lighthouse-testing">Lighthouse Testing</a>

    <a href ="#console-testing">Console Testing</a>

    <a href ="#validator-testing">Validator Testing</a>

    <a href ="#responsiveness-test">Responsiveness Test</a>

    <a href ="#browser-compatibility">Browser Compatibility</a>

    <a href ="#unfixed-bugs">Unfixed Bugs</a>

5. <a href ="#technologies-used">TECHNOLOGIES USED</a>

6. <a href ="#deployment">DEPLOYMENT</a>

    <a href ="#### how-to-create-a-local-clone-of-this-project"></a>

7. <a href ="#credit">CREDIT</a>

    <a href ="#content">Content</a>

    <a href ="#footer">Footer</a>

8. <a href ="#acknowledgement">ACKNOWLEDGEMENT</a>

---

---



# QUIZ - FIFA WORLD CUP

## ABOUT THIS WEBSITE

This website is an interactive quiz for users to score themselves on their knowledge of the FIFA World Cup. There are 10 historical questions, with each question having 2 wrong answers and 1 correct answer. Upon completion of the quiz, the users'score is dispalyed out of a possible 10 points.  

Here is the link to the website: [QUIZ - FIFA WORLD CUP]( https://yemoalakija.github.io/QUIZ-FIFA-WORLD-CUP/)


![mediascreensizes](assets/images/Mediascreens.png)


## FEATURES

The website is very user friendly and responsive with high quality HTML, CSS and JavaScript features. These features enable the user to comfortably access the quiz using all devices including mobile, ipads, laptops and desktops computers.

### Quiz Instructions

Users are advised to read the Quiz instruction as seen here before starting the game:

![Instructions](assets/images/Instructionspage.png)

#### Home Page

The Front Page of this website has a background photo of The FIFA World Cup and it's interactive for the site user to sumbit USERNAME, START the quiz and get information about the quiz from the INSTURCTION button. 
This page also has a footer section at the bottom. There are social media links including Youtube, Twitter and Facebook. Here users can watch some great World Cup goals (see below Footer section of this README for clickable links).

![homepage](assets/images/Homepage.png)


#### Quiz Page

After clicking the "START QUIZ" button, the next page opens up to start the quiz. The player can start playing the quiz and will receive quiz-results at the end. The questions are also randomize for higher user experience. Users can refresh the page and a new question is displayed.  

![Quizpage](assets/images/Quizpage.png)

#### Results Page

On this last page, you will see your result out of 10 questions. There is also a "Back-Home" button to return to the Front Page or Start.

![Resultspage](assets/images/Resultspage.png)

### Future Features

Additional features in the near future shall include more quiz questions on the just-concluded FIFA World Cup 2022 hosted by Qatar. 

## USER EXPERIENCE UX

### Wire Frames

The Wire Frames for this website is seen here. There are 3 pages namely Index, Quiz and Results: 

![wireindex](assets/images/wireindex.jpg)

![wirequiz](assets/images/wirequiz.jpg)

![wireresults](assets/images/wireresults.jpg)


### Structure

The design for this website includes image references to The FIFA World Cup which includes The World Cup Trophy, A football with many country flags, and football-boots with many country flags. 
There is also a favicon "FIFA" icon added to the browser display. 
On the home page, there are social media icons that opens external pages to watch videos on The FIFA World Cup. User can also read Quiz instructions on this page. 
The Quiz shall only start after the user has submitted a name. 
The 10 Quiz questions on the Quiz page has been randomized. 
Finally the Results page displays user's result out of a possible 10 answers and there is a "Back Home" button to return the user to the home page. 


### Color-Theme

The idea of the color theme was to make this website as colorful as possible, thereby caputring as many country flag colors as possible. 

![color-theme](assets/images/ColorTheme.png)

## TESTING

This website was tested using Lighthouse Testing, Validator Testing (HTML and CSS), and JS Hints.  

### Lighthouse Testing

As shown in the picture below, this website passes all criteria including Performance, Accessibility, Best Practices and SEO. 


![LighthouseTest](assets/images/LighthouseTest.png)

### Console Testing

Javascript console has been tested with no errors as seen here:

![Console](assets/images/JSConsoleTest.png)

### Validator Testing 

- HTML Validator 
There were no errors found as seen here: [Validator W3](https://validator.w3.org/nu/?doc=https%3A%2F%2Fyemoalakija.github.io%2FQUIZ-FIFA-WORLD-CUP%2F)

![Validator W3](assets/images/HtmlValidator.png)

- CSS (Jigsaw validator)
There were no errors found as seen here. Although only manually input CSS codes were tested here. Bootstrap codes were not tested. 

![Jigsaw W3](assets/images/JigsawCSSValidator.png)

- Javascript Test 
There were 14 warning messages that returned as seen here:

![Jshint](assets/images/JavascriptTest.png)

However this error arises from a difference with the version only and does not affect the codes and its performances herein. 

### Responsiveness Test

The responsive design tests were carried out manually with [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/) and [Responsive Design Checker](https://www.responsivedesignchecker.com/). 
The following devices were all tested and passed: Desktop 15-24", Galaxy S5-S7, Galaxy A, iPhone 3-7, Sony Z2-Z3, iPad and iPad Mini

### Browser Compatibility

This website was succcesfully tested on the following browsers and there no errors found. Google Chrome, Microsoft Edge and Mozilla Firefox. Responsiveness were consistent on all above mentioned browsers and devices.

### Unfixed Bugs

- As mentioned above, the below code was added to setting.json in an attempt to remove this error.
    "jshint.options": {
        "esversions": 6
    }
Unfortunately this still does not clear warning message in (https://jshint.com/) i.e "	'let' is available in ES6 (use 'esversion: 6') or Mozilla JS extensions (use moz)."

- The below console error message displays on the Results page (only on the live deployment):
Error with Permissions-Policy header: Origin trial controlled feature not enabled: 'interest-cohort'
There was an attempt to fix this by including: <meta http-equiv="Permissions-Policy" content="interest-cohort=(reporting)"> to all html files. This did not fix it. 

Kindly note that all above has no negative effect on the codes functionality throughout the website. 

## TECHNOLOGIES USED

- HTML5 - provides the structure and content for the website.
- CSS - provides the styling for the website.
- Javascript - provides user interactivity on the website.
- Gitpod - used for deployment the website.
- Github - used for hosting and editing the website.

## DEPLOYMENT

The website was deployed to GitHub pages. The steps to deploy are as follows:


![Deployment](assets/images/Deployment.png)


- Enter the GitHub repository and navigate to the Settings tab
- In the source section, select the Master Branch

Here is the live link: - [QUIZ - FIFA WORLD CUP]( https://yemoalakija.github.io/QUIZ-FIFA-WORLD-CUP/)

### How to create a local clone of this project

Acces Github and follow below instructions:

- STEP 1 - Click on the code tab, under repository name. 
- STEP 2 - Click on the clipboard icon to copy URL. 
- STEP 3 - Open Git Bash in your chosen IDE. 
- STEP 4 - Change clone directory location.
- STEP 5 - Type git clone, and then paste the URL copied from GitHub.

## CREDIT

Specific contents and media (including photos and videos) were sourced from various websites as referenced below at the clickable links: 

#### Content

- [Kwizzbit](https://kwizzbit.com/fifa-world-cup-quiz-questions-and-answers/)

- [UNB](https://unb.com.bd/category/Sports/is-the-fifa-football-world-cup-trophy-made-of-solid-gold/103291)

- [WorldFlags Direct](https://www.worldflagsdirect.com/worldcup2022.html)

- [Teachwire](https://www.teachwire.net/news/fifa-world-cup-football-lesson-plans-resources-ideas/)

- [Wikipedia](https://en.m.wikipedia.org/wiki/File:FIFA_logo_without_slogan.svg)

- [Bootstrap](https://getbootstrap.com/)

- [Favicon](https://favicon.io/)

- [Cloud Flare](https://www.cloudflare.com/)



Others for general use includes: 


- Code Institute course modules 

- [W3Schools](https://www.w3schools.com/). This was used for general coding know-how. 

- [stackoverflow](https://stackoverflow.com). This was used for general coding know-how. 

- [CSSColorExtractor](http://www.css-color-extractor.com/). This was used to extract website color theme. 

- [AmIResponsive?](https://amiresponsive.co.uk/) - This was used to extract website mediascreen sizes. 

- [Balsamiq](https://balsamiq.com/) - This was used to achieve Wire Frames. 


#### Footer 

The footer is beneath the Front Page and has clickable social media icons links including Youtube, Twitter and Facebook. These all open external pages for the user to enjoying watching some great World Cup goals. 

- [Youtube](https://www.youtube.com/watch?v=0zIdoBvkiRk) - 10 of the best goals from the 2022 World Cup | ITV Sport

- [Twitter](https://mobile.twitter.com/i/events/1596100698092888065) - Best of the 2022 FIFA World Cup Group Stage (Part 2)

- [Facebook](https://www.facebook.com/watch/?v=1196866764271036) - An incredible and unforgettable goal 🇦🇷 #FIFAWorldCup | #Qatar2022


## ACKNOWLEDGEMENT 

This website was completed in accordance with the criteria for Portfolio 2 Project of The Full Stack Software Developer Diploma at the Code Institute. My gratitude goes to Code Institute. 

Thank You. 

