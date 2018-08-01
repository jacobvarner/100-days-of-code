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
