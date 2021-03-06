# #100DaysOfCode Log - Round 1 - Jacob Varner

The log of my #100DaysOfCode challenge. Restarted on July 9, 2018.

## Log

### R1D1
After trying to code each day for most of the summer, I decided to actually hold myself accountable and restart this challenge officially.

Today I finished the "Functional Javascript Programing" section of [freeCodeCamp](https://www.freecodecamp.org) and then completed 1 of the two remaining "Intermediate Algorithm Challenges" that was added after the new curriculum was released.

Work has been crazy busy this summer, but I don't need to keep using that as an excuse to just come home and watch TV.

### R1D2

I finished the last "Intermediate Algortithm Challenge" on [freeCodeCamp](https://www.freecodecamp.org) and then made it through most of the Sass modules. The Sass modules were a little buggy on FCC but it was nice learning how to use more of the Sass functionality and brush up on my SCSS formatting since I mostly just use Sass and the variable features that it offers.

I'm looking forward to finally diving into React soon since it has seemed like a lot of brushing up on Javascript skills up to this point. I am sure it will be well worth in the end though.

### R1D3

After completing the last few Sass modules that focused on Partials and Extended elements, I finally got started on the React portion of FCC.

I was able to quickly get through the modules covering basic things in React like JSX, Components, and Props. The syntax for React might take a little getting used to, especially with the few nuances, but overall the structure of the framework seems like it's going to be fairly easy to learn and fun to use.

### R1D4

Finished the last two FCC modules that were dealing with Props in React and then started learning about State.

State makes a little more sense to me than Props and I was able to make a "real" component with more functionality than just displaying a hard-coded variable to the DOM.

### R1D5

Today I knocked off a few more of the React modules on freeCodeCamp.

These covered more information on State and Props as well as getting to work with Component Lifecycle Methods. These modules focused on teaching when you can and often should make certain checks based on the State/Props and compare them to nextState and nextProp to allow or prevet changes to the UI or the Component. Using this knowledge as well as a refresh on JavaScript ternary conditions, I was able to make a simple UI that loaded a button first and then changed the button's text based on the number that was input.

### R1D6

I finished up the React section of freeCodeCamp which covered more conditional actions like styling CSS based on certain input.

The last few lessons were focused on using Array.map() and Array.filter() to dynamically render Components to the DOM. Once again, I was able to build things closer to real life use cases and applications.

### R1D7

Made it through my first week and made it through most of the Redux lessons on freeCodeCamp. I understand what Redux does, but freeCodeCamp doesn't do as great of a job of explaining why it's necessarily better than handling state in React other than it having more strict systems and rules. I wasn't able to figure out the Redux lesson that pulls it all together, so I'll probably havee to go back and read more about the basic State and Action syntax in order to pass the last few lessons.

### R1D8

Today I finished the last of the Redux lessons. I was struggling with the same challenge as last night, but finally figured it out. At first I was struggling with the immutability concept of Redux and was getting thrown off by all of the syntax that was creating copies before modifying. Once passing the "Create a Counter with Redux" lesson, the rest of the Redux lessons started to make a little more sense.

I look forward to seeing how Redux works in the context of React, becuase as of now, it still seems like a very foreign framework that will take a little bit more practice for me to get it.

### R1D9

I finished the freeCodeCamp lessons that start to show how React and Redux interact with eachother. I started making the components on both the React and Redux side that are needed to create a simple messagin app. Tomorrow I will learn how to tie the individual pieces from both frameworks together to make a functioning app.

### R1D10

Completed the last few lessons in the React and Redux section of freeCodeCamp which focused on tying the two frameworks together. After completing the final lessons of the front-end framework certificate, I am ready to complete the projects. I went ahead and started building the Random Quote Machine today but only had time to finish the HTML and CSS.

### R1D11

Today I finished up the Random Quote Machine project. I ended up going back to a similar project I had started earlier and modified it to pass the new tests this time around. This project is still using jQuery, but I plan to use React in the next projects as they are a little more advanced and suit React and more advanced frameworks better.

### R1D12

I began the ['Markdown Previewer' project](https://codepen.io/jacobvarner/pen/JBEbry) for the Front End Libraries certificate. Once again, I opted to set up the HTML and styling first before adding the functionality with React. I went ahead and configured some of the settings for Marked.js and stubbed out what I think will be my two components for React. I may end up having to combine them into one component, but I'd prefer to keep them separately and inject the React elements into the DOM which is already drawn with HTML.

### R1D13

I finished the ['Markdown Previewer' project](https://codepen.io/jacobvarner/pen/JBEbry), but it wasn't without frustration. I was beginning to doubt my React skills because I couldn't get it to work once I had rendered all of the components to the screen in what I thought was the correct way. It turns out I had called markdown() instead of marked() to make the conversion using Markdown.js. Once I figured that bug, I just then had to use dangerouslySetInnerHTML() in the component to get it to actually show up as HTML and not just plain text.

### R1D14

It wasn't the most productive day after finishing a project yesterday. Today I familiarized myself with the 'Drum Kit' project on freeCodeCamp as well as started to lay out what I think I'll need. I got hung up on the HTML5 <audio> element since I've never used it and ended up spending a good amount of time on reading up on how it works and how I'll need to use it in this project.

### R1D15

At the end of my hour and a half, I was able to get all of the basic React functionality working. There is zero styling on the appliation, but all but one fo the audio files plays (I'll need to look into the link on one because it's the only one giving me a CORB warning and not playing). Tomorrow I'll try to style the applicaiton and fix any last bugs.


### R1D16

Finished the ['Drum Machine'](https://codepen.io/jacobvarner/pen/zLZqmN) freeCodeCamp project by styling the React components. I also had to go back and add a simple change of styles when each button is pressed. I did this through a timeout because I think it looks cool when the active style stays in place for a few miliseconds after the key is pressed and allows multiple keys to be lit up at once.

### R1D17

The first of many busy days of moving, so not the most time for code. However, I managed to squeeze in an hour where I went over the requirements for the Calculator project on freeCodeCamp and then stubbed out my components. I can already tell one of the bigger challenges in this project will be coming up with a method to handle the actual calculator functions.

### R1D18

I got quite a bit done today and it made me more confident in my ability to write React components. I have a fully rendered and themed application and now just need to handle the button presses and the calculator logic which will be a different challenge altogether. I think I have my React components set up to where I shouldn't have to tweak much tomorrow.

### R1D19

Today I handled all of the button presses for my ['React Calculator' project](https://codepen.io/jacobvarner/pen/GBvrGB). Every button, including the equals button does what it should do. All that is missing now is the actual calculation. I'm hoping to find a quick way to take a string and interpret it as a formula, otherwise I'll have to write more complex code to split and parse the string.

### R1D20

I managed to finish my ['React Calculator' project](https://codepen.io/jacobvarner/pen/GBvrGB) and while the basic calculation portion was easy with the use of the eval() function, I had to spend a lot of time adding checks for edge cases such as only using the last opperator and using the previous answer when an opperator is immediately pressed. Once done with the project, I'm sure I could have made it cleaner from the beginning, but I was focused on getting it working before any plans to refactor.

### R1D21

In starting my final project for the [freeCodeCamp](https://www.freecodecamp.org) Front End Frameworks certificate, I managed to lay out most of the React Components to display the Pomodoro clock in it's start state. The app can effectively update the session and break times and the timer updates to the correct session time before being started.

### R1D22

Spent some more time on my 'Pomodoro Clock' project. I managed to format the timer correctly using the JavaScript Date object and its methods and then styled the entire application, including a nice simple button animation that I liked. I stubbed out the function to start, stop, and reset the timer, but I will add their functionality tomorrow.

### R1D23

I spent my entire hour today coding in circles getting things to partially work. I think I have a way to decrement the timer, but I still seem to have issues with where I should control state and when I should pass things as props instead. I ended up having to scratch a lot of what I did, but I think I know where to start from tomorrow.

### R1D24

I finished my ['Pomodoro Clock'](https://codepen.io/jacobvarner/pen/xJPMEj) which was the final project in the [freeCodeCamp](https://www.freecodecamp.org)'s Front End Libraries certification. It took me about an hour to figure out how to get the timer working like I wanted and I ultimately settled witha solution that used setInterval() so that I could updated the clock accordingly every second while it was 'running.' I had my struggles with this project, but I definitely came away learning even more about JavaScript and React.

### R1D25

After completing the 'Front End Libraries' certificate, I wanted to go ahead and go back to the 'Responsive Web Design' certification since freeCodeCamp added a ton of new lessons and it looks odd that I have the following certifications but not the first one although I should already have the skills. Today I went through half of the 'Applied Visual Design' section which was a nice refresher into exactly what certain CSS attributes can do.

### R1D26

While I intended to go back to complete the first certicate quickly as part of a refresher on things I already knew, I actually learned a lot about more advanced CSS propterties today. It was cool to really see how gradients and transformations work and how I can use them to make some pretty cool graphical animations with just pure CSS.

### R1D27

Today I started and finished the accessibility seciton in the freeCodeCamp Responsive Web Design certification. Some of these practices I already knew about and do my best to use them, but I was made aware of more advanced features added in HTML5 that I should use in my projects going forward.

### R1D28

I decided to play around with the CSS animation stuff I was learning a few days ago and made a simple bouncing basketball with just CSS3. I hope to add animations soon.

### R1D29

Spent another day fiddling with my bouncing basketball animation but still didn't make much progress. I couldn't get the curved stripes of the basketball to scale or fit correctly so I tried to just ignore the stripes and focus on the bouncing animaiton. I eventually found @keyframes combination that worked to make a decent looking bounce with ball compression and everything, but I still couldn't make it work for when the viewport is changed. While this little project helped me play with CSS animations more, I think I'm going to abandon it for now and go back to freeCodeCamp lessons tomorrow.

### R1D30

Today I got back into the freeCodeCamp CSS lessons. I started and finished the media queries section and then the Flexbox section. Flexbox has always been something I've neglected but meant to learn. Now that I've gone through the basics, I started a ['cheat sheet' on Codepen](https://codepen.io/jacobvarner/pen/VBEWyb) so that I can refer back to it for the basic Flexbox properties.

### R1D31

I continued to work on the [Flexbox Cheat Sheet](https://codepen.io/jacobvarner/pen/VBEWyb) that I started yesterday. I'm using the time to practice some of the things I've learned in the past few days including more advanced CSS properties and Flexbox while trying a slightly new design pattern. Tomorrow I'll begin to make each of the Flexbox examples.

### R1D32

Did more work on the [Flexbox Cheat Sheet](https://codepen.io/jacobvarner/full/VBEWyb/) which actually meant filling in content on the site and adding styles to each of the eamples. I made it through the first three properties: flex-direction, justify-content, and align-items.

### R1D33

Finished the [Flexbox Cheat Sheet](https://codepen.io/jacobvarner/pen/VBEWyb) for my reference later. The last few sections were straightforward to fill out, but I got stuck on trying to make my links in the footer rotate like the navigation links but eventually figured out that I couldn't use transform on the inline element.

### R1D34

I started and finished the CSS Grid lessons on freeCodeCamp. It seems like a pretty powerful addition to CSS and I can totally see it making my life easier for basic websites going forward. The downside might be that it gives a lot of wholistic control and might seem a little overkill for a lot of projects. It'll certainly take a new way of thinking when designing websites.

### R1D35

Today I started and put a lot of time into my [concept survey form](https://codepen.io/jacobvarner/pen/wxOBXX) for the second project of the freeCodeCamp responsive web design certificiate. I took a lot of time on this to focus on design and almost completely custom fields. I got hung up on styling the radio buttons and decided to stop for the day.


### R1D36

Other than one little bug with the slanted footer when viewed in the browser, I finished my [concept survey form](https://codepen.io/jacobvarner/pen/wxOBXX) and am really pleased with how it turned out. This form is definitely optimized for mobile (which I believe forms should be) and even has a fun submit animation at the end. The only thing I would like to eventually go back and add are some validation indicators to show whether fields pass validation as the user inputs them.

### R1D37

I started creating a concept product landing page today for the next project towards my freeCodeCamp responsive web design certificate. I am making a mock page for a MyTodos todo list application that I want to eventually make. This will give me an idea of what direction I want to take that app if I get around to making it. I've already learned how to embed video and actually found a cool stock video from a free site and was able to link it to CodePen from my Google Drive.

### R1D38

Got home late from work today, but still managed to spend an hour styling the header and navbar for my concept product landing page. I went with a pretty basic header that I typically use, but this time I styled it all with Flexbox to make sure I really feel comforable with it (and the freeCodeCamp specs required it for this project).

### R1D39

I had another pretty unproductive day, but still managed to finish styling the intro section of my concept product landing page which included adding the text overlay to the video and making sure it scaled correctly.

### R1D40

I finished my concept product landing page today and am now just one more project away from my freeCodeCamp Responsive Web Design certification. I got a little tired of the design towards the end so I feel like I rushed it, but it looks good enough. I still like the color scheme and will probably use it again. I wish the video would still load like it did originally...

### R1D41

To make up for a less productive week, I spent a lot of time today in order to start and finish the final project of my Responsive Web Design certification from freeCodeCamp. I am very pleased with how my [concept documentation page](https://codepen.io/jacobvarner/pen/RYbroq) turned out. I love the color scheme and the way I figured out how to make the navbar and links work with the scroll correction.

### R1D42

Before starting the the next freeCodeCamp certification, I took a moment to complete my coding challenge for the Twitter job application process. It was three simple algorithms and I managed to write them in Node.js. I passed all the test for the first two, but on the last one, I passed a few of the tests and then failed the later ones because I'm sure my solution was not efficient enough.

### R1D43

Today was the first day of class for the fall semester, but after a day full of class and meetings, I made it home and started on the D3.js section of freeCodeCamp. D3 seems way more flexible than I expected and could be used for much more than just graphs and other data displays. Along with learning D3, the modules are also teaching me about creating SVGs. It's nice to be learning totally new things once again.

### R1D44

I finished up the D3 lessons and learned about the scaleLinear() function which can fit the data to the SVG area using a given domain and range. After completing the D3 lessons, I got started on the freeCodeCamp lessons covering the basics of JSON. At this point I have just gotten to where we are parsing values and converting it to HTML to make it look slightly better.

### R1D45

I completed the last few JSON lessons and got started on the D3 bar chart project for the US GDP. I understand the basic funcitons of D3, but it's taking me a little bit to understand how to really start a project from scratch and pull in the data that I need.

### R1D46

Today I was able to get the axes and bar data laid out on the chart despite having to mess around with the padding attribute that I had set in order to get it all lined up. The padding was needed in order to fit the axes on the chart, but it made scaling the GDP data a little bit tricky. Tomorrow I'll just need to style the bars and add a tooltip on hover.


### R1D47

Finished up my [bar chart showing the US GDP using D3.js](https://codepen.io/jacobvarner/pen/vzOBwo). Today I added the tooltip that appears when you mouse over a certain point of data and this disappears or changes when the mouse moves outside that piece of data. D3 still seems like jQuery for SVGs, but I can see how it has more use and can be more performant than jQuery was.

### R1D48

I started and finished developing my personal website update. I challenged myself to re-design and re-develop my site in one weekend in order to prepare for recruiting season where I will be applying to jobs in hopes of finding a team to contribute to starting in the spring.

### R1D49

I made a few last-minute adjustments and wrote a blog post on my process of completing a personal challenge to re-design and re-develop my personal site in just one weekend. The new site is now live at www.jacobvarner.com.

### R1D50

Started and finished my [cycling related scatter plot](https://codepen.io/jacobvarner/pen/oPxLeM) using D3.js. D3 is starting to make a little more sense I am starting to see its usefulness. I'm looking forward to the next project becasue it seems to use a higher concentration of data that D3 is more suitable for.

### R1D51

I got started on another D3.js project. This time I am trying to make a heat map of the global temperature variance over the past two centuries. I've got my x-axis set up correctly because it's just the years again but I'm having trouble with the y-axis. I am given months as integers and need to display the month name. For some reason I got it to convert correctly, but it labeled every tick on the axis as December.

### R1D52

Finished the heat map for global temperature using D3.js. I figured out how to use the .scaleBand to scale each section to be 'center aligned' and line up like the example.

### R1D53

Today I started to set up my next project that aims to map the US education rates by county. Once again I am using D3.js and getting more and more advanced. So far, I figured out how to pull in multiple data sources using Promises in the new D3 v5. I've read a little bit about mapping the counties and states using GeoJSON and TopoJSON and will attempt to do that tomorrow.

### R1D54

Finished up my [chloropeth showing US education data by county](https://codepen.io/jacobvarner/pen/yxVREj). This was by far the coolest data graphic I've made using D3.js so far. The ability to map out each county in the US using TopoJSON is pretty remarkable.

### R1D55

Distracted by football, but managed to start the setup and do some research on treemaps for my final D3 project.

### R1D56

I was much more productive today and finished up the [tree map showing the top 100 video games sold all time](https://codepen.io/jacobvarner/pen/bxqeaa). The tree map was an interesting visual, but I'm glad to be done with the D3 projects. I could see if being more useful if I used data in my projects more often. I'm looking forward to getting on to backend stuff and finally learning some Node.

### R1D57

Set up and familiarized myself with [my Glitch environment](https://rhinestone-author.glitch.me/) used for the Node.js and npm challenges on freeCodeCamp. Glitch seems nice an convenient, but I also tried to set up one Github repository that could track all of my challenges. I hopefully will be able to do this for the projects.

### R1D58

Today I really got started with Node.js and began to learn about routing with Express. I learned how to respond to different HTTP requests, send JSON, and insert middleware functions at the root or on specific HTTP requests. It's making sense now, but definitely a step up in bew material compared to front end technologies.

### R1D59

I finished up the sections on Express and handling HTTP requests today. I learned the useful ability to send data to the 'database' and then also receive information from the server using GET and POST methods along with URL parameters. I know there is a long way to go, but this little bit of information can go a long way.

### R1D60

Today I set up my database with mLab for my next few freeCodeCamp projects dealing with MongoDB and Mongoose. However, after that, I wasn't even able to pass the first lesson. I've set up my person schema exactly how the Mongoose docs had it, but I'm getting no result on freeCodeCamp. None of the app seems to be working and it just tells me that the model is incorrect. I'm going to have to call it quits for today, but it's annoying how freeCodeCamp seems to still have no solution or help for this problem.

### R1D61

I figured out that the freeCodeCamp tests wanted me to also create a model from my schema, which is why the tests would not pass yesterday. After that, I had a much easier time learning about doing usful CRUD operations on the database with the help of Mongoose functions.

### R1D62

I started and finished my first API and Mircoservices project for freeCodeCamp. I build a simple timestamp API that took a millisecond value or date string and returned a json object with both the Unix timecode and the UTC datetime string. The API is live [here](https://varner-timestamp-api.glitch.me).

### R1D63

I was able to start and finish an [API microservice](https://varner-header-parser.glitch.me/api/whoami) that returns header information about the user (IP, language, browser) in JSON format. I then started to lay out my next project which will be a very simple URL shortener.

### R1D64

Spent way too much time looking into how to pull the data from the form element when the POST method was called with the /api/shortened/new url was sent. I plan to be more productive and focused tomorrow.

### R1D65

I'm still working on the URL shortener API and it's reminding me a lot of my frustrations in my networking class in undergrad. I have figured out how to verify the URL and store it in the database and then return the 'short url' key, but I can't get the counter to update correctly no matter how I do it. I've tried using a separate counters collection using a few different docs online, but couldn't get it to work. I'm almost positive this is how I need to do it, so hopefully I'll figure it out tomorrow.

### R1D66

I was able to figure out how to correctly implement the counter and got the URL redirect working. I had to verify the url without using HTTP/HTTPS when using DNS.lookup, but then needed to store the original URL in order for the redirect to work correctly. The finished project can be found at https://varner-url-shortener.glitch.me.

### R1D67

I started my next project which will be a REST API for tracking users and their exercises. I set up an mLab database and imported and modified the basic template code from freeCodeCamp. I'm looking forward to this project because it seems like something I can come back later and add a nicer frontend.

### R1D68

A couple of minutes until I figured out that I was returning an error for every instance, but I did have the User functionality of my exercise tracker working the entire time. I can now add users through the User creation form.

### R1D69

I added the GET function to return an array of all users and then also added the ability to add a new exercise to a user. I have set it up to have two models, User and Exercise, and the exercises are all connected to a User through the userId field.

### R1D70

I finished up my [exercise tracker API](https://varner-exercise-tracker.glitch.me) by adding the ability to pull all exercises for a given user and narrow them down either from a certain date and/or to a certain date and/or limit the total number of exercises returned. I learned a lot about routes, parameters, and queries with this last functionality. 

### R1D71

I set up my final API freeCodeCamp certification project. This will be a simple microservice that returns the metadata of an uploaded file in a JSON object. I will likely be using the multer npm package to handle the file upload.

### R1D72

Today I finished the [file metadata microservice](https://varner-file-metadata.glitch.me) project that takes a file uploaded to the server and returns a JSON object with the file name and the file size. This project is the last project in my APIs and Microservices project from [freeCodeCamp](https://www.freecodecamp.org).

### R1D73

I took a slight break before completing my last freeCodeCamp certification to do a coding challenge for my Google interview process. The challenge had a simple string manipulation problem first that I solved pretty quickly. The next problem was an interesting algorithm problem that was really interesting and something I hadn't seen before. My solution passed all of the tests I came up with and the ones Google provided and I think my solution was fairly optimal.

### R1D74

I got started on the HelmetJS challenges which is the first part of the Information Security and Quality Assurance certification from freeCodeCamp. I only made it through the first three challenges today because I had to spend a goog amount of time investigating and submitting an issue on Github because the tests for the second challenge would not pass until I submitted the code a second time after waiting a few minutes. I at least learned how to insptect HTTP headers in the Chrome Dev Tools though.

### R1D75

Finished up the remaining challenges going over the options for HelmetJS and then did a little bit of hashing with bcrypt. I learned how to use bcrypt to has both asynchronously and synchronously, while async is the recommended method on most sites.

### R1D76

I made it through all of the Chai unit test challenges. It was a nice refresher on how JavaScript handles different types and comparisons while also learning all of the different assetions that Chai has to offer.

### R1D77

I continued to work with Chai for testing and completed the challenges relating to functional testing until I reached the point that I will need to work with a headless browser for tomorrow.

### R1D78

I finished up the last Chai testing lessons using the headless browser to simulate actions on the web page and test the output. Tomorrow I'll get started on the advanced Node.js and Express challenges.

### R1D79

Today I set up another MongoDB for my Advanced Node.js and Express lessons. The first lessons dealt with installing and setting up Pug, Passport, and the database connection. I learned how to serialize and deserialize when information is sent back and forth from the database.

### R1D80

I managed to get through a few of the user authentication challenges on freeCodeCamp before having to spend a bunch of time figuring out how to pass one of the obscure test cases. I eventually found the work around that was posted in the Github issues for freeCodeCamp, but the tests were not passing for a very obscure reason not even related to the challenge.

### R1D81

Added the ability for users to register and then added password encryption with BCrypt for storying password hashes. The application now checks for hashed passwords when a user attempts to login or register a new account. I also had to glitch my way through another challenge when the test cases wouldn't pass for no reason at all.

### R1D82

I moved all of my route and authorization code to separate modules in order to start cleaning up my application arhitecture. I also spent some time finishing up my [blog post](https://medium.com/@jacobvarner/my-name-is-jacob-varner-and-this-is-why-you-should-hire-me-d967181a7fe0) that summarizes my skills and experiences for employers.

### R1D83

Today I added the ability to login with Github. This required me setting up an authorization application on Github and then handling the routes in my web app. If a user was authenticated via Github, they are updated in the database and sent to their profile similar to before.

### R1D84

I finished up the final freeCodeCamp challenges in the Advanced Node and Express section of the Information Security and Quality Assurance certification by building a simple chat client using Socket.IO. Now all I need to do is complete the five remaining projects and I will have attained all of the freeCodeCamp certifications and can move on to studying and preparing more for job interviews.

### R1D85

Started to layout functional tests for my unit converter application. Tomorrow I will try to finish writing the tests and start adding functionality to the application.


### R1D86

I finished the tests and the functionallity for my unit converter Node.js application. The tests were helpful in knowing which things were working as soon as I implemented them, but a few tests I had to go back and tweak because there was clearly an error in the test instead of the code. I like the idea of writing tests before I start, but it is clear that won't be the last time I touch the tests.

### R1D87

I started my issue tracker project for my freeCodeCamp certification and set up the database and wrote my first version of the functional tests. It'll be interesting to see how much I have to tweak the tests to make them work correctly after last time.

### R1D88

I fixed the front end of the issue tracker and got the forms to link with the API. I am still working to confirm that the data is coming through as expected so that I can then store it in the database.

### R1D89

After a few days of a break due to a very busy week and getting burned out on the freeCodeCamp projects, I finally made it back to my project. I ended up switching to Mongoose for the database and then finishing the post route which creates an issue on a project.

### R1D90

I completed the functionailty for the PUT, GET, and DELETE routes. I then fixed the wording in my code and tests in order to make sure all 11 tests were passsing. This completes my Issue Tracker project.

### R1D91

Starting to get a hang of these simple Node.js apps. Today I was able to write my tests, build all of the functionality for my personal library project, and then make all tests past in one sitting. Two more projects to go.

### R1D92

I started my stock price checking app by completing the functional tests. I then spent quite a bit of time trying to figure out how to do the price lookups with an API call the right way. Promises and callbacks keep throwing me for a loop, and I'm going to try and approach it with async/await tomorrow to see where I can get with that.

### R1D93

After another hiatus due to school and other life craziness, I made it back to put some more time into my stock price checker application. Once again, I struggled to stay focus. I think I have wrapped my head around the Promises for the http request, although I swear it should be easier just to get one tiny bit of data. Because most of my time is wasted on these last projects that have no meaning to me, I've decided to abandon the final freeCodeCamp certification for now and plan to focus on algorithms and working on bigger personal projects to practice React and a little bit of Node.js when needed. It has gotten hard for me to justify working on weird random projects when I have so little time and desire to work on them just for a certification. I'm hoping I can get in another groove and finish out the #100DaysOfCode, even if it ended on a struggling note.
