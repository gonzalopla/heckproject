
# Hub of Interesting Things.
**Gonzalo Plascencia, Chukwudi Ikem, Lloyd Blazina**
Hub of Interesting Things is the culmination of three creative minds at work. We initially did not know what to make as a project, so we creatively designed our own projects and hosted them at the hub. I used HTML, JavaScript, and CSS. I found programming interfaces to be interesting, so I google searched the recipe search API that I used in the project. Chukwudi created **First Precedence**, a to-do list with active user authentication. He used Embedded JavaScript, CSS, JavaScript, and a generous number of open-source frameworks to accomplish his site. Lloyd built his website using WordPress, his goal to recreate **First Precedence** as a backup to Chukwudi's.
​
​
## Installation - Recipe Search
​
1. Clone Repository - https://github.com/gonzalopla/heckproject
2. Double click on search.html to open up the website.
3. Click the search bar on the page.
4. Click on any desired options.
5. Scroll down to see the results.
6. You can modify the search register at https://adamam.com and get a subscription for access to more API queries and filters.
7. You can post the files to another GitHub page in order to access it on the website and go into functions for the project to build the HTML in the browser.
8. Or for your own URL post project still on Github
9. Register for a URL anywhere (free on freenom.com)
10. Find a host(free on netifly.com)
11. Link the three together by searching through the settings
​
## Installation - First Precedence - *For Unix-like Environments*
- Make sure to have [Visual Studio Code](https://code.visualstudio.com/) installed.
- Make sure you create a .env file after you have cloned the First Precedence. It needs to contain data in this format.
- SESSION_SECRET=anythingyouwant
### We need to install Node.js
```bash
$ sudo apt install nodejs
$ sudo apt install npm
```
**If you are not on Mac OS or Linux. [Follow this guide](https://nodejs.org/en/download/package-manager/).**
​
### Check that you have node and npm installed
```bash
node -v
npm -v
```
### Clone Repository
​
```bash
$ git clone https://github.com/254-Project1/FirstPrecedence
```
​
### Open the folder inside of Visual Studio Code
```bash
$ cd FirstPrecedence
$ code .
```
- This should've opened up Visual Studio Code. After this, you will need to open up a terminal inside of VS Code. Then, you can install all of the dependencies and get started.
### Run First Precedence
```bash
$ npm install
$ npm run start
```
- Navigate to your browser, enter this url.
```
http://localhost:3000
```
### Now Have Fun!

Sources :
1- https://www.w3schools.com
About W3schools:
W3Schools is a web developers site, with tutorials and references on web development languages such as HTML, CSS, JavaScript, PHP, SQL, Python, jQuery, Java, C++, C#, React, Node.js, XML, W3.CSS, and Bootstrap, covering most aspects of web programming.
The site derives its name from the World Wide Web (W3), but is not affiliated with the W3C.
W3Schools was originally created in 1998 by Refsnes Data, a Norwegian software development and consulting company.

2-https://developer.edamam.com
About Edamam:
The Edamam B2B API is accessed by sending HTTPS requests on specific URLs as described below. The base URL is https://api.edamam.com and you obtain the full URL by appending request’s path to the base URL, like https://api.edamam.com/search for references

3-https://app.netifly.com to host a website

4-https://freenom.com for a free .tk url heckproject.tk
