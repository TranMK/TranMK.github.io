# WAPH-Web Application and Hacking

## Instructor: Mr. Phu Phung

## Student

**Name**: Khoi Tran  

**Email**: [mailto:tran2ki@mail.uc.edu](tran2ki@mail.uc.edu)  

**Short bio**: Second year student with an interest in Computer Science and games.  

![My headshot](images/Actual%20150x150%20headshot.png)

## The project's overview

Individual Project 1 gives a focus on front-end web development for the purpose of building a personal web development for career purposes. After completing this project, I've had a newfound acknowledgement of the difficulty that goes into developing a webpage, how to make every component in a webpage present well and implementing programming to turn the website into something more dynamic than what I expected.  

Deployed website on github.io: [https://tranmk.github.io/index.html](https://tranmk.github.io/index.html)

All code and documents used for this lab is available in [https://github.com/TranMK/TranMK.github.io](https://github.com/TranMK/TranMK.github.io).  

## General Requirements (30 pts)

I created a deployable website for my github page by naming the repo "TranMK.github.io", then added two files, index.html(main site) and waph.html(WAPH course-specific site). By doing [https://tranmk.github.io/index.html](https://tranmk.github.io/index.html) or [https://tranmk.github.io/waph.html](https://tranmk.github.io/waph.html), I can display those two files on my browser.  

## Non-technical requirements (20 pts)

I used Bootstrap framework to implement a theme for my index.html display. The original theme used for my website is [https://startbootstrap.com/theme/agency](https://startbootstrap.com/theme/agency). I also implemented a page tracker, FlagCounter by detecting the country the IP accessing the site. (testing for functionality)

## Technical requirements

### Basic JavaScript Code (20 pts)

jQuery code has already been present in Lab 2's code, so I only needed to copy it over. For the second framework/library, I used React to improve the script as well as adding another functionality, being a manual "Refresh Joke" button instead of having to refresh page or wait for a minute.

### Web APIs integration (20 pts)

I integrated xkcd's website to display his comics onto my page using a simple jQuery's getJSON method.

### JavaScript cookies to remember client (10 pts)

I used document.cookie property of my website to store the last time this website was visited by that IP. If user visits website for the first time, the text on the top of the page would be "Welcome to my homepage for the first time!". Subsequent responses would be "Welcome back! Your last visit was (insert last time this site was visited)".