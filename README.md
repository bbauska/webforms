<!------------------------------------------------------------------------------------------------>
<!----------------------------- readme.md in webforms.bauska.org --------------------------------->
<!------------------------------------------------------------------------------------------------>
<h2 align="center" width="100%">Front-end Web Developer - webforms - mdn web docs</h2>
<!------------------------------------------------------------------------------------------------>
<!--------------------------------- webforms logo (01) ----------------------------------->
<!------------------------------------------------------------------------------------------------>
<p align="center" width="100%">
<img src="./images/image001.png"
   alt="web forms logo"
   width="65%" />
</p>
<div align="center">
<h1>Front-end web developer</h1>
</div>
<a href="https://developer.mozilla.org/en-US/docs/Learn/Front-end_web_developer"></a>
<!------------------------------------------------------------------------------------------------>
Developer guides
There are a number of guides within MDN docs. These articles aim to add additional usage examples, or teach you how to use an API or feature. This page links to some of the most popular material.

HTML
Structuring the web with HTML
The HTML learning area offers tutorials to help you learn HTML from the ground up.

HTML basics
This article will give you a basic understanding of HTML. After following this guide, you can further explore the material in the HTML Learning Area.

CSS
Learn to style HTML using CSS
Our complete CSS tutorial, taking you from first steps through styling text, creating layouts, and more.

CSS Layout Guides
There are a large number of guides to CSS Layout across MDN, this page collects them all together.

Using CSS animations
CSS animations make it possible to animate transitions from one CSS style configuration to another. This guide will help you get started with the animation properties.

JavaScript
JavaScript learning area
Whether you are a complete beginner, or hoping to refresh your skills, this is the place to start.

AJAX
AJAX is a term that defines a group of technologies allowing web applications to make quick, incremental updates to the user interface without reloading the entire browser page. This makes the application faster and more responsive to user actions.

Media
Graphics on the web
Modern web sites and applications often need to present graphics of varying sophistication.

Audio and video delivery
We can deliver audio and video on the web in several ways, ranging from 'static' media files to adaptive live streams. This article is intended as a starting point for exploring the various delivery mechanisms of web-based media and compatibility with popular browsers.

Audio and video manipulation
The beauty of the web is that you can combine technologies to create new forms. Having native audio and video in the browser means we can use these data streams with technologies such as <canvas>, WebGL or Web Audio API to modify audio and video directly, for example adding reverb/compression effects to audio, or grayscale/sepia filters to video. This article provides a reference to explain what you need to do.

APIs
Using FormData objects
The FormData object lets you compile a set of key/value pairs to send using XMLHttpRequest. It's primarily intended for sending form data, but can be used independently from forms to transmit keyed data. The transmission is in the same format that the form's submit() method would use to send the data if the form's encoding type were set to "multipart/form-data".

Progressive web apps
Progressive web apps (PWAs) use modern web APIs along with traditional progressive enhancement strategy to create cross-platform web applications. These apps work everywhere and provide several features that give them the same user experience advantages as native apps. This set of guides tells you all you need to know about PWAs.

Parsing and serializing XML
The web platform provides different methods of parsing and serializing XML, each with its pros and cons.

Performance
Optimization and performance
When building modern web apps and sites, it's important to make your content work quickly and efficiently. This lets it perform effectively for both powerful desktop systems and weaker handheld devices.

Mobile web development
Mobile web development
This article provides an overview of some of the main techniques needed to design web sites that work well on mobile devices.

Fonts
Variable fonts guide
Find out how to use variable fonts in your designs.

The Web Open Font Format (WOFF)
WOFF (Web Open Font Format) is a font file format that is free for anyone to use on the web.

User interface development
User input and controls
Modern web user input goes beyond simple mouse and keyboard: think of touchscreens for example. This article provides recommendations for managing user input and implementing controls in open web apps, along with FAQs, real-world examples, and links to further information for anyone needing more detailed information on the underlying technologies.

<!------------------------------------------------------------------------------------------------>

<h3>Web forms — Working with user data</h3>
This module provides a series of articles that will help you master the essentials of web forms. Web forms are a very powerful tool for interacting with users — most commonly they are used for collecting data from users, or allowing them to control a user interface. However, for historical and technical reasons it's not always obvious how to use them to their full potential. In the articles listed below, we'll cover all the essential aspects of Web forms including marking up their HTML structure, styling form controls, validating form data, and submitting data to the server.

<h3>Looking to become a front-end web developer?</h3>
We have put together a course that includes all the essential information you need to work towards your goal.

<h4>Get started</h4>

<h4>Prerequisites</h4>
Before starting this module, you should at least work through our <a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML">Introduction to HTML</a>. At this point you should find the <a href="https://developer.mozilla.org/en-US/docs/Learn/Forms#introductory_guides">Introductory guides</a> easy to understand, and also be able to make use of our <a href="https://developer.mozilla.org/en-US/docs/Learn/Forms/Basic_native_form_controls">Basic native form controls</a> guide.

Mastering forms however requires more than just HTML knowledge — you also need to learn some specific techniques to style form controls, and some scripting knowledge is required to handle things like validation and creating custom form controls. Therefore, before you look at the other sections listed below we'd recommend that you go away and learn some <a href="https://developer.mozilla.org/en-US/docs/Learn/CSS">CSS</a> and <a href="https://developer.mozilla.org/en-US/docs/Learn/JavaScript">JavaScript</a>  first.

The above text is a good indicator as to why we've put web forms into its own standalone module, rather than trying to mix bits of it into the HTML, CSS, and JavaScript topic areas — form elements are more complex than most other HTML elements, and they also require a close marriage of related CSS and JavaScript techniques to get the most out of them.

<b>Note:</b> If you are working on a computer/tablet/other device where you don't have the ability to create your own files, you could try out (most of) the code examples in an online coding program such as <b>JSBin</b> or <b>Glitch</b>.

<h3>Introductory guides</h3>

<h3>Your first form</h3>
https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form
The first article in our series provides your very first experience of creating a web form, including designing a simple form, implementing it using the right HTML elements, adding some very simple styling via CSS, and how data is sent to a server.

<h3>How to structure a web form</h3>
With the basics out of the way, we now look in more detail at the elements used to provide structure and meaning to the different parts of a form.
The different form controls

<h3>Basic native form controls</h3>
We start off this section by looking at the functionality of the original HTML <input> types in detail, looking at what options are available to collect different types of data.

<h3>The HTML5 input types</h3>
Here we continue our deep dive into the <input> element, looking at the additional input types provided when HTML5 was released, and the various UI controls and data collection enhancements they provide. Additionally, we look at the <output> element.

<h3>Other form controls</h3>
Next we take a look at all the non-<input> form controls and associated tools, such as <select>, <textarea>, <meter>, and <progress>.

<h3>Form styling guides</h3>

<h3>Styling web forms</h3>
This article provides an introduction to styling forms with CSS, including all the basics you might need to know for basic styling tasks.

<h3>Advanced form styling</h3>
Here we look at some more advanced form styling techniques that need to be used when trying to deal with some of the more difficult-to-style form elements.
UI pseudo-classes
An introduction to the UI pseudo-classes enabling HTML form controls to be targeted based on their current state.
Validating and submitting form data
Client-side form validation
Sending data is not enough — we also need to make sure that the data users enter into forms is in the correct format to process it successfully, and that it won't break our applications. We also want to help our users to fill out our forms correctly and not get frustrated when trying to use our apps. Form validation helps us achieve these goals — this article tells you what you need to know.
Sending form data
This article looks at what happens when a user submits a form — where does the data go, and how do we handle it when it gets there? We also look at some of the security concerns associated with sending form data.
Advanced articles
The following articles aren't essential to the learning pathway, but they'll prove interesting and useful when you've mastered the above techniques and want to know more.
How to build custom form controls
You'll come across some cases where the native form widgets just don't provide what you need, e.g. because of styling or functionality. In such cases, you may need to build your own form widget out of raw HTML. This article explains how you'd do this and the considerations you need to be aware of when doing so, with a practical case study.
Sending forms through JavaScript
This article looks at ways to use a form to assemble an HTTP request and send it via custom JavaScript, rather than standard form submission. It also looks at why you'd want to do this, and the implications of doing so. (See also Using FormData objects.)
CSS property compatibility table for form controls
This last article provides a handy reference allowing you to look up what CSS properties are compatible with what form elements.
See also
•	HTML forms element reference
•	HTML <input> types reference
•	HTML attribute reference
Found a problem with this page?
•	Edit on GitHub
•	Source on GitHub
•	Report a problem with this content on GitHub
•	Want to fix the problem yourself? See our Contribution guide.
Last modified: Mar 13, 2022, by MDN contributors
Advanced articles
The following articles aren't essential to the learning pathway, but they'll prove interesting and useful when you've mastered the above techniques and want to know more.
How to build custom form controls
You'll come across some cases where the native form widgets just don't provide what you need, e.g. because of styling or functionality. In such cases, you may need to build your own form widget out of raw HTML. This article explains how you'd do this and the considerations you need to be aware of when doing so, with a practical case study.
Sending forms through JavaScript
This article looks at ways to use a form to assemble an HTTP request and send it via custom JavaScript, rather than standard form submission. It also looks at why you'd want to do this, and the implications of doing so. (See also Using FormData objects.)
CSS property compatibility table for form controls
This last article provides a handy reference allowing you to look up what CSS properties are compatible with what form elements.
See also
HTML forms element reference
HTML <input> types reference
HTML attribute reference
Tools and testing
Once you've started to become comfortable programming with core web technologies (like HTML, CSS, and JavaScript), and you start to get more experience, read more resources, and learn more tips and tricks, you'll start to come across all kind of tools, from JavaScript frameworks, to testing and automation tools, and more besides. As your web projects become larger and more complex, you'll want to start taking advantage of some of these tools, working out a reliable toolchain to give your development process superpowers.
On top of that, we still need to keep cross-browser support in the forefront of our minds, and make sure that our code follows best practices that allow our projects to work across different browsers and devices that our users are using to browse the Web, and be usable by people with disabilities.
Working out what tools you should be using can be a difficult process, so we have written this set of articles to inform you of what types of tool are available, what they can do for you, and how to make use of the current industry favorites.
Note: We have referenced a number of tools in this topic, not because we endorse them or think they are the best, but because we know they work and have good industry support. In most cases there are other tools available, old ones will go out of fashion, and new ones will no doubt appear.
Modules
Understanding client-side web development tools
Client-side tooling can be intimidating, but this series of articles aims to illustrate the purpose of some of the most common client-side tool types, explain the tools you can chain together, how to install them using package managers, and control them using the command line. We finish up by providing a complete toolchain example showing you how to get productive.
Understanding client-side JavaScript frameworks
JavaScript frameworks are an essential part of modern front-end web development, providing developers with tried and tested tools for building scalable, interactive web applications. Many modern companies use frameworks as a standard part of their tooling, so many front-end development jobs now require framework experience. This module gives you some fundamental background knowledge about how client-side frameworks work and how they fit into your toolset, before moving on to tutorial series covering some of today's most popular ones.
Git and GitHub
All developers will use some kind of version control system (VCS), a tool to allow them to collaborate with other developers on a project without danger of them overwriting each other's work, and roll back to previous versions of the code base if a problem is discovered later on. The most popular VCS (at least among web developers) is Git, along with GitHub, a site that provides hosting for your repositories and several tools for working with them. This module aims to teach you what you need to know about both of them.
Cross browser testing
This module looks specifically at the area of testing web projects across different browsers. Here we look at identifying your target audience (e.g. what users, browsers and devices do you most need to worry about?), how to go about testing, the main issues that you'll face with different types of code and how to fix/mitigate those, what tools are most useful in helping you test and fix problems, and how to use automation to speed up testing.
Introduction to client-side frameworks
Overview: Client-side JavaScript frameworks
Next
We begin our look at frameworks with a general overview of the area, looking at a brief history of JavaScript and frameworks, why frameworks exist and what they give us, how to start thinking about choosing a framework to learn, and what alternatives there are to client-side frameworks.
Prerequisites:	Familiarity with the core HTML, CSS, and JavaScript languages.

Objective:	To understand how client-side JavaScript frameworks came to exist, what problems they solve, what alternatives there are, and how to go about choosing one.
A brief history
When JavaScript debuted in 1996, it added occasional interactivity and excitement to a web that was, up until then, composed of static documents. The web became not just a place to read things, but to do things. JavaScript's popularity steadily increased. Developers who worked with JavaScript wrote tools to solve the problems they faced, and packaged them into reusable packages called libraries, so they could share their solutions with others. This shared ecosystem of libraries helped shape the growth of the web.
Now, JavaScript is an essential part of the web, used on 95% of all websites, and the web is an essential part of modern life. Users write papers, manage their budgets, stream music, watch movies, and communicate with others over great distances instantaneously, with text, audio or video chat. The web allows us to do things that used to be possible only in native applications installed on our computers. These modern, complex, interactive websites are often referred to as web applications.
The advent of modern JavaScript frameworks has made it much easier to build highly dynamic, interactive applications. A framework is a library that offers opinions about how software gets built. These opinions allow for predictability and homogeneity in an application; predictability allows software to scale to an enormous size and still be maintainable; predictability and maintainability are essential for the health and longevity of software.
JavaScript frameworks power much of the impressive software on the modern web – including many of the websites you likely use every day. MDN Web Docs, which you are currently reading this on, uses the React/ReactDOM framework to power its front end.
What frameworks are out there?
There are many frameworks out there, but currently the "big four" are considered to be the following.
Ember
Ember was initially released in December 2011 as a continuation of work that started in the SproutCore project. It is an older framework that has less users than more modern alternatives such as React and Vue, but it still enjoys a fair amount of popularity due to its stability, community support, and some clever coding principles.
Start learning Ember
Angular
Angular is an open-source web application framework led by the Angular Team at Google and by a community of individuals and corporations. It is a complete rewrite from the same team that built AngularJS. Angular was officially released on the 14th of September 2016.
Angular is a component-based framework which uses declarative HTML templates. At build time, transparently to developers, the framework's compiler translates the templates to optimized JavaScript instructions. Angular uses TypeScript, a superset of JavaScript that we'll look at in a little more detail in the next chapter.
Start learning Angular
Vue
After working on and learning from the original AngularJS project, Evan You released Vue in 2014. Vue is the youngest of the big four, but has enjoyed a recent uptick in popularity.
Vue, like AngularJS, extends HTML with some of its own code. Apart from that, it mainly relies on modern, standard JavaScript.
Start learning Vue
React
Facebook released React in 2013. By this point, it had already been using React to solve many of its problems internally. Technically, React itself is not a framework; it's a library for rendering UI components. React is used in combination with other libraries to make applications — React and React Native enable developers to make mobile applications; React and ReactDOM enable them to make web applications, etc.
Because React and ReactDOM are so often used together, React is colloquially understood as a JavaScript framework. As you read through this module, we will be working with that colloquial understanding.
React extends JavaScript with HTML-like syntax, known as JSX.
Start learning React
Getting started with React
In this article we will say hello to React. We'll discover a little bit of detail about its background and use cases, set up a basic React toolchain on our local computer, and create and play with a simple starter app — learning a bit about how React works in the process.
Prerequisites:	Familiarity with the core HTML, CSS, and JavaScript languages, knowledge of the terminal/command line.
React uses an HTML-in-JavaScript syntax called JSX (JavaScript and XML). Familiarity with both HTML and JavaScript will help you to learn JSX, and better identify whether bugs in your application are related to JavaScript or to the more specific domain of React.
Objective:	To set up a local React development environment, create a start app, and understand the basics of how it works
	
Hello React
As its official tagline states, React is a library for building user interfaces. React is not a framework – it's not even exclusive to the web. It's used with other libraries to render to certain environments. For instance, React Native can be used to build mobile applications.
To build for the web, developers use React in tandem with ReactDOM. React and ReactDOM are often discussed in the same spaces as — and utilized to solve the same problems as — other true web development frameworks. When we refer to React as a "framework", we're working with that colloquial understanding.
React's primary goal is to minimize the bugs that occur when developers are building UIs. It does this through the use of components — self-contained, logical pieces of code that describe a portion of the user interface. These components can be composed together to create a full UI, and React abstracts away much of the rendering work, leaving you to concentrate on the UI design.
Use cases
Unlike the other frameworks covered in this module, React does not enforce strict rules around code conventions or file organization. This allows teams to set conventions that work best for them, and to adopt React in any way they would like to. React can handle a single button, a few pieces of an interface, or an app's entire user interface.
While React can be used for small pieces of an interface, it's not as easy to "drop into" an application as a library like jQuery, or even a framework like Vue — it is more approachable when you build your entire app with React.
In addition, many of the developer-experience benefits of a React app, such as writing interfaces with JSX, require a compilation process. Adding a compiler like Babel to a website makes the code on it run slowly, so developers often set up such tooling with a build step. React arguably has a heavy tooling requirement, but it can be learned.
This article is going to focus on the use case of using React to render the entire user interface of an application, using tooling provided by Facebook's own create-react-app tool.
How does React use JavaScript?
React utilizes features of modern JavaScript for many of its patterns. Its biggest departure from JavaScript comes with the use of JSX syntax. JSX extends JavaScript's syntax so that HTML-like code can live alongside it. For example:
const heading = <h1>Mozilla Developer Network</h1>;
This heading constant is known as a JSX expression. React can use it to render that <h1> tag in our app.
Suppose we wanted to wrap our heading in a <header> tag, for semantic reasons? The JSX approach allows us to nest our elements within each other, just like we do with HTML:
const header = (
  <header>
    <h1>Mozilla Developer Network</h1>
  </header>
);
Note: The parentheses in the previous snippet aren't unique to JSX, and don't have any effect on your application. They're a signal to you (and your computer) that the multiple lines of code inside are part of the same expression. You could just as well write the header expression like this:
const header = <header>
    <h1>Mozilla Developer Network</h1>
</header>
However, this looks kind of awkward, because the <header> tag that starts the expression is not indented to the same position as its corresponding closing tag.
Of course, your browser can't read JSX without help. When compiled (using a tool like Babel or Parcel), our header expression would look like this:
const header = React.createElement("header", null,
  React.createElement("h1", null, "Mozilla Developer Network")
);
It's possible to skip the compilation step and use React.createElement() to write your UI yourself. In doing this, however, you lose the declarative benefit of JSX, and your code becomes harder to read. Compilation is an extra step in the development process, but many developers in the React community think that the readability of JSX is worthwhile. Plus, popular tooling makes the JSX-to-JavaScript compilation part of its setup process. You don't have to configure compilation yourself unless you want to.
Because JSX is a blend of HTML and JavaScript, some developers find it intuitive. Others say that its blended nature makes it confusing. Once you're comfortable with it, however, it will allow you to build user interfaces more quickly and intuitively, and allow others to better understand your codebase at a glance.
To read more about JSX, check out the React team's JSX In Depth article.
Setting up your first React app
There are many ways to use React, but we're going to use the command-line interface (CLI) tool create-react-app, as mentioned earlier, which expedites the process of developing a React application by installing some packages and creating some files for you, handling the tooling described above.
It's possible to add React to a website without create-react-app by copying some <script> elements into an HTML file, but the create-react-app CLI is a common starting point for React applications. Using it will allow you to spend more time building your app, and less time fussing with setup.
Requirements
In order to use create-react-app, you need to have Node.js installed. It's recommended that you use the long-term support (LTS) version. Node includes npm (the node package manager), and npx (the node package runner).
You may also use the Yarn package manager as an alternative, but we'll assume you are using npm in this set of tutorials. See Package management basics for more information on npm and yarn.
If you're using Windows, you will need to install some software to give you parity with Unix/macOS terminal in order to use the terminal commands mentioned in this tutorial. Gitbash (which comes as part of the git for Windows toolset) or Windows Subsystem for Linux (WSL) are both suitable. See Command line crash course for more information on these, and on terminal commands in general.
Also bear in mind that React and ReactDOM produce apps that only work on a fairly modern set of browsers — IE9+ by way of some polyfills. It is recommended that you use a modern browser like Firefox, Microsoft Edge, Safari, or Chrome when working through these tutorials.
Also, see the following for more information:
•	"What is npm" on nodejs.org
•	"Introducing npx" on the npm blog
•	The create-react-app documentation
Initializing your app
create-react-app takes one argument: the name you'd like to give your app. create-react-app uses this name to make a new directory, then creates the necessary files inside it. Make sure you cd to the place you'd like your app to live on your hard drive, then run the following in your terminal:
npx create-react-app moz-todo-react
This creates a moz-todo-react directory, and does several things inside it:
•	Installs some npm packages essential to the functionality of the app.
•	Writes scripts for starting and serving the application.
•	Creates a structure of files and directories that define the basic app architecture.
•	Initializes the directory as a git repository, if you have git installed on your computer.
Note: if you have the Yarn package manager installed, create-react-app will default to using it instead of npm. If you have both package managers installed and explicitly want to use NPM, you can add the flag --use-npm when you run create-react-app:
npx create-react-app moz-todo-react --use-npm
create-react-app will display a number of messages in your terminal while it works; this is normal! This might take a few minutes, so now might be a good time to go make a cup of tea.
When the process is complete, cd into the moz-todo-react directory and run the command npm start. The scripts installed by create-react-app will start being served at a local server at localhost:3000, and open the app in a new browser tab. Your browser will display something like this:
 
Application structure
create-react-app gives us everything we need to develop a React application. Its initial file structure looks like this:
moz-todo-react
├── README.md
├── node_modules
├── package.json
├── package-lock.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    ├── reportWebVitals.js
    └── setupTests.js
The src directory is where we'll spend most of our time, as it's where the source code for our application lives.
The public directory contains files that will be read by your browser while you're developing the app; the most important of these is index.html. React injects your code into this file so that your browser can run it. There's some other markup that helps create-react-app function, so take care not to edit it unless you know what you're doing. You very much should change the text inside the <title> element in this file to reflect the title of your application. Accurate page titles are important for accessibility!
The public directory will also be published when you build and deploy a production version of your app. We won't cover deployment in this tutorial, but you should be able to use a similar solution to that described in our Deploying our app tutorial.
The package.json file contains information about our project that Node.js/npm uses to keep it organized. This file is not unique to React applications; create-react-app merely populates it. You don't need to understand this file at all to complete this tutorial, however, if you'd like to learn more about it, you can read What is the file `package.json`? on NodeJS.org; we also talk about it in our Package management basics tutorial.
Exploring our first React component — <App/>
In React, a component is a reusable module that renders a part of our app. These parts can be big or small, but they are usually clearly defined: they serve a single, obvious purpose.
Let's open src/App.js, since our browser is prompting us to edit it. This file contains our first component, App, and a few other lines of code:
import React from 'react';
import logo from './logo.svg';
import './App.css';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          Edit <code>src/App.js</code> and save to reload.
        </p>
        <a
          className="App-link"
          href="https://reactjs.org"
          target="_blank"
          rel="noopener noreferrer"
        >
          Learn React
        </a>
      </header>
    </div>
  );
}
export default App;
The App.js file consists of three main parts: some import statements at the top, the App component in the middle, and an export statement at the bottom. Most React components follow this pattern.
Import statements
The import statements at the top of the file allow App.js to use code that has been defined elsewhere. Let's look at these statements more closely.
import React from 'react';
import logo from './logo.svg';
import './App.css';
The first statement imports the React library itself. Because React turns the JSX we write into React.createElement(), all React components must import the React module. If you skip this step, your application will produce an error.
The second statement imports a logo from './logo.svg'. Note the use of ./ at the beginning of the path, and the .svg extension at the end — these tell us that the file is local and that it is not a JavaScript file. Indeed, the logo.svg file lives in our source directory.
We don't write a path or extension when importing the React module — this is not a local file; instead, it is listed as a dependency in our package.json file. Be careful of this distinction as you work through this lesson!
The third statement imports the CSS related to our App component. Note that there is no variable name and no from directive. This particular import syntax is not native to JavaScript module syntax — it comes from Webpack, the tool create-react-app uses to bundle all our JavaScript files together and serve them to the browser.
The App component
After the imports, we have a function named App. Whereas most of the JavaScript community prefers camel-case names like helloWorld, React components use pascal-case variable names, like HelloWorld, to make it clear that a given JSX element is a React component, and not a regular HTML tag. If you were to rename the App function to app, your browser would show you an error.
Let's look at App more closely.
function App() {
  return (
    <div className="App">
      <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          Edit <code>src/App.js</code> and save to reload.
        </p>
        <a
          className="App-link"
          href="https://reactjs.org"
          target="_blank"
          rel="noopener noreferrer"
        >
          Learn React
        </a>
      </header>
    </div>
  );
}
The App function returns a JSX expression. This expression defines what your browser ultimately renders to the DOM.
Some elements in the expression have attributes, which are written just like in HTML, following a pattern of attribute="value". On line 3, the opening <div> tag has a className attribute. This is the same as the class attribute in HTML, but because JSX is JavaScript, we can't use the word class — it's reserved, meaning JavaScript already uses it for a specific purpose and it would cause problems here in our code. A few other HTML attributes are written differently in JSX than they are in HTML too, for the same kind of reason. We'll cover them as we encounter them.
Take a moment to change the <p> tag on line 6 so that it reads "Hello, world!", then save your file. You'll notice that this change is immediately rendered in the development server running at http://localhost:3000 in your browser. Now delete the <a> tag and save; the "Learn React" link will be gone.
Your App component should now look like this:
function App() {
  return (
    <div className="App">
      <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          Hello, World!
        </p>
      </header>
    </div>
  );
}
Export statements
At the very bottom of the App.js file, the statement export default App makes our App component available to other modules.
Interrogating the index
Let's open src/index.js, because that's where the App component is being used. This file is the entry point for our app, and it initially looks like this:
1.	import React from 'react';
2.	import ReactDOM from 'react-dom';
3.	import './index.css';
4.	import App from './App';
5.	import * as serviceWorker from './serviceWorker';

6.	ReactDOM.render(
7.	<React.StrictMode>
8.	<App />
9.	</React.StrictMode>,
10.	document.getElementById('root')
11.	);

12.	// If you want your app to work offline and load faster, you can change
13.	// unregister() to register() below. Note this comes with some pitfalls.
14.	// Learn more about service workers: https://bit.ly/CRA-PWA
15.	serviceWorker.unregister();
As with App.js, the file starts by importing all the JS modules and other assets it needs to run. src/index.css holds global styles that are applied to our whole app. We can also see our App component imported here; it is made available for import thanks to the export statement at the bottom of App.js.
Line 7 calls React's ReactDOM.render() function with two arguments:
•	The component we want to render, <App /> in this case.
•	The DOM element inside which we want the component to be rendered, in this case the element with an ID of root. If you look inside public/index.html, you'll see that this is a <div> element just inside the <body>.
All of this tells React that we want to render our React application with the App component as the root, or first component.
Note: In JSX, React components and HTML elements must have closing slashes. Writing just <App> or just <img> will cause an error.
Service workers are interesting pieces of code that help application performance and allow features of your web applications to work offline, but they're not in scope for this article. You can delete line 5, as well as most of the code below it.
Your final index.js file should look like this:
import React from 'react';
import ReactDOM from 'react-dom';
import './index.css';
import App from './App';

ReactDOM.render(<App />, document.getElementById('root'));
Variables and props
Next, we'll use a few of our JavaScript skills to get a bit more comfortable editing components and working with data in React. We'll talk about how variables are used inside JSX, and introduce props, which are a way of passing data into a component (which can then be accessed using variables).
Variables in JSX
Back in App.js, let's focus on line 9:
<img src={logo} className="App-logo" alt="logo" />
Here, the <img /> tag's src attribute value is in curly braces. This is how JSX recognizes variables. React will see {logo}, know you are referring to the logo import on line 2 of our app, then retrieve the logo file and render it.
Let's try making a variable of our own. Before the return statement of App, add const subject = 'React';. Your App component should now look like this:
function App() {
  const subject = "React";
  return (
    <div className="App">
      <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          Hello, World!
        </p>
      </header>
    </div>
  );
}
Change line 8 to use our subject variable instead of the word "world", like this:
function App() {
  const subject = "React";
  return (
    <div className="App">
      <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          Hello, {subject}!
        </p>
      </header>
    </div>
  );
}
When you save, your browser should display "Hello, React!" instead of "Hello, world!"
Variables are convenient, but the one we've just set doesn't make great use of React's features. That's where props come in.
Component props
A prop is any data passed into a React component. React props are comparable to HTML attributes. Where HTML elements have attributes, React components have props. Props are written inside component calls, and use the same syntax as HTML attributes — prop="value". In React, dataflow is unidirectional: props can only be passed from Parent components down to Child components; and props are read-only.
Let's open index.js and give our <App/> call its first prop.
Add a prop of subject to the <App/> component call, with a value of Clarice. When you are done, your code should look something like this:
ReactDOM.render(<App subject="Clarice" />, document.getElementById('root'));
Back in App.js, let's revisit the App function itself, which reads like this (with the return statement shortened for brevity):
function App() {
  const subject = "React";
  return (
    // return statement
  );
}
Change the signature of the App function so that it accepts props as a parameter, and delete the subject const. Just like any other function parameter, you can put props in a console.log() to print it to your browser's console. Go ahead and do that before the return statement, like so:
function App(props) {
  console.log(props);
  return (
    // return statement
  );
}
With this change, {subject} becomes undefined, so comment out the line Hello, {subject}! for now. Save your file and check your browser's JavaScript console. You should see something like this logged:
Object { subject: "Clarice" }
The object property subject corresponds to the subject prop we added to our <App /> component call, and the string Clarice corresponds to its value. Component props in React are always collected into objects in this fashion.
Now that subject is one of our props, let's utilize it in App.js. Change the subject constant so that, instead of defining it as the string React, you are reading the value of props.subject. Now, you can also uncomment the line Hello, {subject}! and, if you wish, delete your console.log().
function App(props) {
  const subject = props.subject;
  return (
    // return statement
  );
}
When you save, the app should now greet you with "Hello, Clarice!". If you return to index.js, edit the value of subject, and save, your text will change. Note that if you wanted to leave in the Hello line throughout this change, you could also have updated the JSX variable to {props.subject}.
Summary
This brings us to the end of our initial look at React, including how to install it locally, creating a starter app, and how the basics work. In the next article, we'll start building our first proper application — a todo list. Before we do that, however, let's recap some of the things we've learned.
In React:
•	Components can import modules they need and must export themselves at the bottom of their files.
•	Component functions are named with PascalCase.
•	You can read JSX variables by putting them between curly braces, like {so}.
•	Some JSX attributes are different than HTML attributes so that they don't conflict with JavaScript reserved words. For example, class in HTML translates to className in JSX. Note that multi-word attributes are camel-cased.
•	Props are written just like attributes inside component calls and are passed into components.
In this module
Introduction to client-side frameworks
Framework main features
React
•	Getting started with React
•	Beginning our React todo list
•	Componentizing our React app
•	React interactivity: Events and state
•	React interactivity: Editing, filtering, conditional rendering
•	Accessibility in React
•	React resources
Ember
•	Getting started with Ember
•	Ember app structure and componentization
•	Ember interactivity: Events, classes and state
•	Ember Interactivity: Footer functionality, conditional rendering
•	Routing in Ember
•	Ember resources and troubleshooting
Vue
•	Getting started with Vue
•	Creating our first Vue component
•	Rendering a list of Vue components
•	Adding a new todo form: Vue events, methods, and models
•	Styling Vue components with CSS
•	Using Vue computed properties
•	Vue conditional rendering: editing existing todos
•	Focus management with Vue refs
•	Vue resources
Svelte
•	Getting started with Svelte
•	Starting our Svelte Todo list app
•	Dynamic behavior in Svelte: working with variables and props
•	Componentizing our Svelte app
•	Advanced Svelte: Reactivity, lifecycle, accessibility
•	Working with Svelte stores
•	TypeScript support in Svelte
•	Deployment and next steps
Angular
•	Getting started with Angular
•	Beginning our Angular todo list app
•	Styling our Angular app
•	Creating an item component
•	Filtering our to-do items
•	Building Angular applications and further resources
Beginning our React todo list
Let's say that we've been tasked with creating a proof-of-concept in React – an app that allows users to add, edit, and delete tasks they want to work on, and also mark tasks as complete without deleting them. This article will walk you through putting the basic App component structure and styling in place, ready for individual component definition and interactivity, which we'll add later.
Note: If you need to check your code against our version, you can find a finished version of the sample React app code in our todo-react repository. For a running live version, see https://mdn.github.io/todo-react-build/.
Our app's user stories
In software development, a user story is an actionable goal from the perspective of the user. Defining user stories before we begin our work will help us focus our work. Our app should fulfill the following stories:
As a user, I can
•	read a list of tasks.
•	add a task using the mouse or keyboard.
•	mark any task as completed, using the mouse or keyboard.
•	delete any task, using the mouse or keyboard.
•	edit any task, using the mouse or keyboard.
•	view a specific subset of tasks: All tasks, only the active task, or only the completed tasks.
We'll tackle these stories one-by-one.
Pre-project housekeeping
create-react-app has made a few files we won't be using at all for our project.
•	We're not going to write per-component stylesheets, so first delete the App.css import from the top of App.js.
•	We are also not going to be using the logo.svg file, so remove that import too.
Then, copy and paste the following commands into your terminal to delete some unneeded files. Make sure you're starting in the app's root directory!
# Move into the src directory of your project
cd src
# Delete a few files
rm -- App.test.js App.css logo.svg serviceWorker.js setupTests.js
# Move back up to the root of the project
cd ..
Notes:
•	Two of the files we're deleting are for testing the application. We will not cover testing here.
•	If you stopped your server to do the terminal tasks mentioned above, you'll have to start it again using npm start.
Project starter code
As a starting point for this project, we're going to provide two things: An App() function to replace the one you have now, and some CSS to style your app.
The JSX
Copy the following snippet to your clipboard, then paste it into App.js so that it replaces the existing App() function:
function App(props) {
  return (
    <div className="todoapp stack-large">
      <h1>TodoMatic</h1>
      <form>
        <h2 className="label-wrapper">
          <label htmlFor="new-todo-input" className="label__lg">
            What needs to be done?
          </label>
        </h2>
        <input
          type="text"
          id="new-todo-input"
          className="input input__lg"
          name="text"
          autoComplete="off"
        />
        <button type="submit" className="btn btn__primary btn__lg">
          Add
        </button>
      </form>
      <div className="filters btn-group stack-exception">
        <button type="button" className="btn toggle-btn" aria-pressed="true">
          <span className="visually-hidden">Show </span>
          <span>all</span>
          <span className="visually-hidden"> tasks</span>
        </button>
        <button type="button" className="btn toggle-btn" aria-pressed="false">
          <span className="visually-hidden">Show </span>
          <span>Active</span>
          <span className="visually-hidden"> tasks</span>
        </button>
        <button type="button" className="btn toggle-btn" aria-pressed="false">
          <span className="visually-hidden">Show </span>
          <span>Completed</span>
          <span className="visually-hidden"> tasks</span>
        </button>
      </div>
      <h2 id="list-heading">
        3 tasks remaining
      </h2>
      <ul
        role="list"
        className="todo-list stack-large stack-exception"
        aria-labelledby="list-heading"
      >
        <li className="todo stack-small">
          <div className="c-cb">
            <input id="todo-0" type="checkbox" defaultChecked={true} />
            <label className="todo-label" htmlFor="todo-0">
              Eat
            </label>
          </div>
          <div className="btn-group">
            <button type="button" className="btn">
              Edit <span className="visually-hidden">Eat</span>
            </button>
            <button type="button" className="btn btn__danger">
              Delete <span className="visually-hidden">Eat</span>
            </button>
          </div>
        </li>
        <li className="todo stack-small">
          <div className="c-cb">
            <input id="todo-1" type="checkbox" />
            <label className="todo-label" htmlFor="todo-1">
              Sleep
            </label>
          </div>
          <div className="btn-group">
            <button type="button" className="btn">
              Edit <span className="visually-hidden">Sleep</span>
            </button>
            <button type="button" className="btn btn__danger">
              Delete <span className="visually-hidden">Sleep</span>
            </button>
          </div>
        </li>
        <li className="todo stack-small">
          <div className="c-cb">
            <input id="todo-2" type="checkbox" />
            <label className="todo-label" htmlFor="todo-2">
              Repeat
            </label>
          </div>
          <div className="btn-group">
            <button type="button" className="btn">
              Edit <span className="visually-hidden">Repeat</span>
            </button>
            <button type="button" className="btn btn__danger">
              Delete <span className="visually-hidden">Repeat</span>
            </button>
          </div>
        </li>
      </ul>
    </div>
  );
}
Now open public/index.html and change the <title> element's text to TodoMatic. This way, it will match the <h1> at the top of our app.
<title>TodoMatic</title>
When your browser refreshes, you should see something like this:
 
It's ugly, and doesn't function yet, but that's okay — we'll style it in a moment. First, consider the JSX we have, and how it corresponds to our user stories:
•	We have a <form> element, with an <input type="text"> for writing out a new task, and a button to submit the form.
•	We have an array of buttons that will be used to filter our tasks.
•	We have a heading that tells us how many tasks remain.
•	We have our 3 tasks, arranged in an un-ordered list. Each task is a list item (<li>), and has buttons to edit and delete it and a checkbox to check it off as done.
The form will allow us to make tasks; the buttons will let us filter them; the heading and list are our way to read them. The UI for editing a task is conspicuously absent for now. That's okay – we'll write that later.
Accessibility features
You may notice some unusual attributes here. For example:
<button type="button" className="btn toggle-btn" aria-pressed="true">
  <span className="visually-hidden">Show </span>
  <span>all</span>
  <span className="visually-hidden"> tasks</span>
</button>
Here, aria-pressed tells assistive technology (like screen readers) that the button can be in one of two states: pressed or unpressed. Think of these as analogs for on and off. Setting a value of true means that the button is pressed by default.
The class visually-hidden has no effect yet, because we have not included any CSS. Once we have put our styles in place, though, any element with this class will be hidden from sighted users and still available to screen reader users — this is because these words are not needed by sighted users; they are there to provide more information about what the button does for screenreader users that do not have the extra visual context to help them.
Further down, you can find our <ul> element:
<ul
  role="list"
  className="todo-list stack-large stack-exception"
  aria-labelledby="list-heading"
>
The role attribute helps assistive technology explain what kind of element a tag represents. A <ul> is treated like a list by default, but the styles we're about to add will break that functionality. This role will restore the "list" meaning to the <ul> element. If you want to learn more about why this is necessary, you can check out Scott O'Hara's article, "Fixing Lists".
The aria-labelledby attribute tells assistive technologies that we're treating our list heading as the label that describes the purpose of the list beneath it. Making this association gives the list a more informative context, which could help screen reader users better understand the purpose of it.
Finally, the labels and inputs in our list items have some attributes unique to JSX:
<input id="todo-0" type="checkbox" defaultChecked={true} />
<label className="todo-label" htmlFor="todo-0">
  Eat
</label>
The defaultChecked attribute in the <input/ > tag tells React to check this checkbox initially. If we were to use checked, as we would in regular HTML, React would log some warnings into our browser console relating to handling events on the checkbox, which we want to avoid. Don't worry too much about this for now — we will cover this later on when we get to using events.
The htmlFor attribute corresponds to the for attribute used in HTML. We cannot use for as an attribute in JSX because for is a reserved word, so React uses htmlFor instead.
Notes:
•	To use boolean values (true and false) in JSX attributes, you must enclose them in curly braces. If you write defaultChecked="true", the value of defaultChecked will be "true" — a string literal. Remember — this is actually JavaScript, not HTML!
•	The aria-pressed attribute used in our earlier code snippet has a value of "true" because aria-pressed is not a true boolean attribute in the way checked is.
Implementing our styles
Paste the following CSS code into src/index.css so that it replaces what's currently there:
/* RESETS */
*,
*::before,
*::after {
  box-sizing: border-box;
}
*:focus {
  outline: 3px dashed #228bec;
  outline-offset: 0;
}
html {
  font: 62.5% / 1.15 sans-serif;
}
h1,
h2 {
  margin-bottom: 0;
}
ul {
  list-style: none;
  padding: 0;
}
button {
  border: none;
  margin: 0;
  padding: 0;
  width: auto;
  overflow: visible;
  background: transparent;
  color: inherit;
  font: inherit;
  line-height: normal;
  -webkit-font-smoothing: inherit;
  -moz-osx-font-smoothing: inherit;
  -webkit-appearance: none;
}
button::-moz-focus-inner {
  border: 0;
}
button,
input,
optgroup,
select,
textarea {
  font-family: inherit;
  font-size: 100%;
  line-height: 1.15;
  margin: 0;
}
button,
input {
  overflow: visible;
}
input[type="text"] {
  border-radius: 0;
}
body {
  width: 100%;
  max-width: 68rem;
  margin: 0 auto;
  font: 1.6rem/1.25 Arial, sans-serif;
  background-color: #f5f5f5;
  color: #4d4d4d;
}
@media screen and (min-width: 620px) {
  body {
    font-size: 1.9rem;
    line-height: 1.31579;
  }
}
/*END RESETS*/
/* GLOBAL STYLES */
.form-group > input[type="text"] {
  display: inline-block;
  margin-top: 0.4rem;
}
.btn {
  padding: 0.8rem 1rem 0.7rem;
  border: 0.2rem solid #4d4d4d;
  cursor: pointer;
  text-transform: capitalize;
}
.btn.toggle-btn {
  border-width: 1px;
  border-color: #d3d3d3;
}
.btn.toggle-btn[aria-pressed="true"] {
  text-decoration: underline;
  border-color: #4d4d4d;
}
.btn__danger {
  color: #fff;
  background-color: #ca3c3c;
  border-color: #bd2130;
}
.btn__filter {
  border-color: lightgrey;
}
.btn__primary {
  color: #fff;
  background-color: #000;
}
.btn-group {
  display: flex;
  justify-content: space-between;
}
.btn-group > * {
  flex: 1 1 49%;
}
.btn-group > * + * {
  margin-left: 0.8rem;
}
.label-wrapper {
  margin: 0;
  flex: 0 0 100%;
  text-align: center;
}
.visually-hidden {
  position: absolute !important;
  height: 1px;
  width: 1px;
  overflow: hidden;
  clip: rect(1px 1px 1px 1px);
  clip: rect(1px, 1px, 1px, 1px);
  white-space: nowrap;
}
[class*="stack"] > * {
  margin-top: 0;
  margin-bottom: 0;
}
.stack-small > * + * {
  margin-top: 1.25rem;
}
.stack-large > * + * {
  margin-top: 2.5rem;
}
@media screen and (min-width: 550px) {
  .stack-small > * + * {
    margin-top: 1.4rem;
  }
  .stack-large > * + * {
    margin-top: 2.8rem;
  }
}
.stack-exception {
  margin-top: 1.2rem;
}
/* END GLOBAL STYLES */
.todoapp {
  background: #fff;
  margin: 2rem 0 4rem 0;
  padding: 1rem;
  position: relative;
  box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.2), 0 2.5rem 5rem 0 rgba(0, 0, 0, 0.1);
}
@media screen and (min-width: 550px) {
  .todoapp {
    padding: 4rem;
  }
}
.todoapp > * {
  max-width: 50rem;
  margin-left: auto;
  margin-right: auto;
}
.todoapp > form {
  max-width: 100%;
}
.todoapp > h1 {
  display: block;
  max-width: 100%;
  text-align: center;
  margin: 0;
  margin-bottom: 1rem;
}
.label__lg {
  line-height: 1.01567;
  font-weight: 300;
  padding: 0.8rem;
  margin-bottom: 1rem;
  text-align: center;
}
.input__lg {
  padding: 2rem;
  border: 2px solid #000;
}
.input__lg:focus {
  border-color: #4d4d4d;
  box-shadow: inset 0 0 0 2px;
}
[class*="__lg"] {
  display: inline-block;
  width: 100%;
  font-size: 1.9rem;
}
[class*="__lg"]:not(:last-child) {
  margin-bottom: 1rem;
}
@media screen and (min-width: 620px) {
  [class*="__lg"] {
    font-size: 2.4rem;
  }
}
.filters {
  width: 100%;
  margin: unset auto;
}
/* Todo item styles */
.todo {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}
.todo > * {
  flex: 0 0 100%;
}
.todo-text {
  width: 100%;
  min-height: 4.4rem;
  padding: 0.4rem 0.8rem;
  border: 2px solid #565656;
}
.todo-text:focus {
  box-shadow: inset 0 0 0 2px;
}
/* CHECKBOX STYLES */
.c-cb {
  box-sizing: border-box;
  font-family: Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  font-weight: 400;
  font-size: 1.6rem;
  line-height: 1.25;
  display: block;
  position: relative;
  min-height: 44px;
  padding-left: 40px;
  clear: left;
}
.c-cb > label::before,
.c-cb > input[type="checkbox"] {
  box-sizing: border-box;
  top: -2px;
  left: -2px;
  width: 44px;
  height: 44px;
}
.c-cb > input[type="checkbox"] {
  -webkit-font-smoothing: antialiased;
  cursor: pointer;
  position: absolute;
  z-index: 1;
  margin: 0;
  opacity: 0;
}
.c-cb > label {
  font-size: inherit;
  font-family: inherit;
  line-height: inherit;
  display: inline-block;
  margin-bottom: 0;
  padding: 8px 15px 5px;
  cursor: pointer;
  touch-action: manipulation;
}
.c-cb > label::before {
  content: "";
  position: absolute;
  border: 2px solid currentcolor;
  background: transparent;
}
.c-cb > input[type="checkbox"]:focus + label::before {
  border-width: 4px;
  outline: 3px dashed #228bec;
}
.c-cb > label::after {
  box-sizing: content-box;
  content: "";
  position: absolute;
  top: 11px;
  left: 9px;
  width: 18px;
  height: 7px;
  transform: rotate(-45deg);
  border: solid;
  border-width: 0 0 5px 5px;
  border-top-color: transparent;
  opacity: 0;
  background: transparent;
}
.c-cb > input[type="checkbox"]:checked + label::after {
  opacity: 1;
}
Save and look back at your browser, and your app should now have reasonable styling.
Summary
Now our todo list app actually looks a bit more like a real app! The problem is: it doesn't actually do anything. We'll start fixing that in the next chapter!
Componentizing our React app
At this point, our app is a monolith. Before we can make it do things, we need to break it apart into manageable, descriptive components. React doesn't have any hard rules for what is and isn't a component – that's up to you! In this article we will show you a sensible way to break our app up into components.
Defining our first component
Defining a component can seem tricky until you have some practice, but the gist is:
•	If it represents an obvious "chunk" of your app, it's probably a component
•	If it gets reused often, it's probably a component.
That second bullet is especially valuable: making a component out of common UI elements allows you to change your code in one place and see those changes everywhere that component is used. You don't have to break everything out into components right away, either. Let's take the second bullet point as inspiration and make a component out of the most reused, most important piece of the UI: a todo list item.
Make a <Todo />
Before we can make a component, we should create a new file for it. In fact, we should make a directory just for our components. The following commands make a components directory and then, within that, a file called Todo.js. Make sure you're in the root of your app before you run these!
mkdir src/components
touch src/components/Todo.js
Our new Todo.js file is currently empty! Open it up and give it its first line:
import React from "react";
Since we're going to make a component called Todo, you can start adding the code for that to Todo.js too, as follows. In this code, we define the function and export it on the same line:
export default function Todo() {
  return (

  );
}
This is OK so far, but our component has to return something! Go back to src/App.js, copy the first <li> from inside the unordered list, and paste it into Todo.js so that it reads like this:
export default function Todo() {
  return (
    <li className="todo stack-small">
      <div className="c-cb">
        <input id="todo-0" type="checkbox" defaultChecked={true} />
        <label className="todo-label" htmlFor="todo-0">
          Eat
        </label>
      </div>
      <div className="btn-group">
        <button type="button" className="btn">
          Edit <span className="visually-hidden">Eat</span>
        </button>
        <button type="button" className="btn btn__danger">
          Delete <span className="visually-hidden">Eat</span>
        </button>
      </div>
    </li>
  );
}
Note: Components must always return something. If at any point in the future you try to render a component that does not return anything, React will display an error in your browser.
Our Todo component is complete, at least for now; now we can use it. In App.js, add the following line near the top of the file to import Todo:
import Todo from "./components/Todo";
With this component imported, you can replace all of the <li> elements in App.js with <Todo /> component calls. Your <ul> should read like this:
<ul
  role="list"
  className="todo-list stack-large stack-exception"
  aria-labelledby="list-heading"
>
  <Todo />
  <Todo />
  <Todo />
</ul>
When you look back at your browser, you'll notice something unfortunate: your list now repeats the first task three times!
 
We don't only want to eat; we have other things to — well — to do. Next we'll look at how we can make different component calls render unique content.
Make a unique <Todo />
Components are powerful because they let us re-use pieces of our UI, and refer to one place for the source of that UI. The problem is, we don't typically want to reuse all of each component; we want to reuse most parts, and change small pieces. This is where props come in.
What's in a name?
In order to track the names of tasks we want to complete, we should ensure that each <Todo /> component renders a unique name.
In App.js, give each <Todo /> a name prop. Let's use the names of our tasks that we had before:
<Todo name="Eat" />
<Todo name="Sleep" />
<Todo name="Repeat" />
When your browser refreshes, you will see… the exact same thing as before. We gave our <Todo /> some props, but we aren't using them yet. Let's go back to Todo.js and remedy that.
First modify your Todo() function definition so that it takes props as a parameter. You can console.log() your props as we did before, if you'd like to check that they are being received by the component correctly.
Once you're confident that your component is getting its props, you can replace every occurrence of Eat with your name prop. Remember: when you're in the middle of a JSX expression, you use curly braces to inject the value of a variable.
Putting all that together, your Todo() function should read like this:
export default function Todo(props) {
  return (
    <li className="todo stack-small">
      <div className="c-cb">
        <input id="todo-0" type="checkbox" defaultChecked={true} />
        <label className="todo-label" htmlFor="todo-0">
          {props.name}
        </label>
      </div>
      <div className="btn-group">
        <button type="button" className="btn">
          Edit <span className="visually-hidden">{props.name}</span>
        </button>
        <button type="button" className="btn btn__danger">
          Delete <span className="visually-hidden">{props.name}</span>
        </button>
      </div>
    </li>
  );
}
Now your browser should show three unique tasks. Another problem remains though: they're all still checked by default.
 
Is it completed?
In our original static list, only Eat was checked. Once again, we want to reuse most of the UI that makes up a <Todo /> component, but change one thing. That's a good job for another prop! Give each <Todo /> call in App.js a new prop of completed. The first (Eat) should have a value of true; the rest should be false:
<Todo name="Eat" completed={true} />
<Todo name="Sleep" completed={false} />
<Todo name="Repeat" completed={false} />
As before, we must go back to Todo.js to actually use these props. Change the defaultChecked attribute on the <input /> so that its value is equal to the completed prop. Once you're done, the Todo component's <input /> element will read like this:
<input id="todo-0" type="checkbox" defaultChecked={props.completed} />
And your browser should update to show only Eat being checked:
 
If you change each <Todo /> component's completed prop, your browser will check or uncheck the equivalent rendered checkboxes accordingly.
Gimme some id, please
Right now, our <Todo /> component gives every task an id attribute of todo-0. This is bad HTML because id attributes must be unique (they are used as unique identifiers for document fragments, by CSS, JavaScript, etc.). This means we should give our component an id prop that takes a unique value for each Todo.
To follow the same pattern we had initially, let's give each instance of the <Todo /> component an ID in the format of todo-i, where i gets larger by one every time:
<Todo name="Eat" completed={true} id="todo-0" />
<Todo name="Sleep" completed={false} id="todo-1" />
<Todo name="Repeat" completed={false} id="todo-2" />
Now go back to Todo.js and make use of the id prop. It needs to replace the value of the id attribute of the <input /> element, as well as the value of its label's htmlFor attribute:
<div className="c-cb">
  <input id={props.id} type="checkbox" defaultChecked={props.completed} />
  <label className="todo-label" htmlFor={props.id}>
    {props.name}
  </label>
</div>
So far, so good?
We're making good use of React so far, but we could do better! Our code is repetitive. The three lines that render our <Todo /> component are almost identical, with only one difference: the value of each prop.
We can clean up our code with one of JavaScript's core abilities: iteration. To use iteration, we should first re-think our tasks.
Tasks as data
Each of our tasks currently contains three pieces of information: its name, whether it has been checked, and its unique ID. This data translates nicely to an object. Since we have more than one task, an array of objects would work well in representing this data.
In src/index.js, make a new const beneath the final import, but above ReactDOM.render():
const DATA = [
  { id: "todo-0", name: "Eat", completed: true },
  { id: "todo-1", name: "Sleep", completed: false },
  { id: "todo-2", name: "Repeat", completed: false }
];
Next, we'll pass DATA to <App /> as a prop, called tasks. The final line of src/index.js should read like this:
ReactDOM.render(<App tasks={DATA} />, document.getElementById("root"));
This array is now available to the App component as props.tasks. You can console.log() it to check, if you'd like.
Note: ALL_CAPS constant names have no special meaning in JavaScript; they're a convention that tells other developers "this data will never change after being defined here".
Rendering with iteration
To render our array of objects, we have to turn each one into a <Todo /> component. JavaScript gives us an array method for transforming data into something else: Array.prototype.map().
Above the return statement of App(), make a new const called taskList and use map() to transform it. Let's start by turning our tasks array into something simple: the name of each task:
const taskList = props.tasks?.map(task => task.name);
Let's try replacing all the children of the <ul> with taskList:
<ul
  role="list"
  className="todo-list stack-large stack-exception"
  aria-labelledby="list-heading"
>
  {taskList}
</ul>
This gets us some of the way towards showing all the components again, but we've got more work to do: the browser currently renders each task's name as unstructured text. We're missing our HTML structure — the <li> and its checkboxes and buttons!
 
To fix this, we need to return a <Todo /> component from our map() function — remember that JSX allows us to mix up JavaScript and markup structures! Let's try the following instead of what we have already:
 const taskList = props.tasks.map(task => <Todo />);
Look again at your app; now our tasks look more like they used to, but they're missing the names of the tasks themselves. Remember that each task we map over has the id, name, and checked properties we want to pass into our <Todo /> component. If we put that knowledge together, we get code like this:
const taskList = props.tasks.map(task => (
  <Todo id={task.id} name={task.name} completed={task.completed} />
));
Now the app looks like it did before, and our code is less repetitive.
Unique keys
Now that React is rendering our tasks out of an array, it has to keep track of which one is which in order to render them properly. React tries to do its own guesswork to keep track of things, but we can help it out by passing a key prop to our <Todo /> components. key is a special prop that's managed by React – you cannot use the word key for any other purpose.
Because keys should be unique, we're going to re-use the id of each task object as its key. Update your taskList constant like so:
const taskList = props.tasks.map(task => (
    <Todo
      id={task.id}
      name={task.name}
      completed={task.completed}
      key={task.id}
    />
  )
);
You should always pass a unique key to anything you render with iteration. Nothing obvious will change in your browser, but if you do not use unique keys, React will log warnings to your console and your app may behave strangely!
Componentizing the rest of the app
Now that we've got our most important component sorted out, we can turn the rest of our app into components. Remembering that components are either obvious pieces of UI, or reused pieces of UI, or both, we can make two more components:
•	<Form/>
•	<FilterButton/>
Since we know we need both, we can batch some of the file creation work together with a terminal command. Run this command in your terminal, taking care that you're in the root directory of your app:
touch src/components/Form.js src/components/FilterButton.js
The <Form />
Open components/Form.js and do the following:
•	Import React at the top of the file, like we did in Todo.js.
•	Make yourself a new Form() component with the same basic structure as Todo(), and export that component.
•	Copy the <form> tags and everything between them from inside App.js, and paste them inside Form()'s return statement.
•	Export Form at the end of the file.
Your Form.js file should read like this:
import React from "react";

function Form(props) {
  return (
    <form>
      <h2 className="label-wrapper">
        <label htmlFor="new-todo-input" className="label__lg">
          What needs to be done?
        </label>
      </h2>
      <input
        type="text"
        id="new-todo-input"
        className="input input__lg"
        name="text"
        autoComplete="off"
      />
      <button type="submit" className="btn btn__primary btn__lg">
        Add
      </button>
    </form>
  );
}

export default Form;
The <FilterButton />
Do the same things you did to create Form.js inside FilterButton.js, but call the component FilterButton() and copy the HTML for the first button inside the <div> element with the class of filters from App.js into the return statement.
The file should read like this:
import React from "react";

function FilterButton(props) {
  return (
    <button type="button" className="btn toggle-btn" aria-pressed="true">
      <span className="visually-hidden">Show </span>
      <span>all </span>
      <span className="visually-hidden"> tasks</span>
    </button>
  );
}

export default FilterButton;
Note: You might notice that we are making the same mistake here as we first made for the <Todo /> component, in that each button will be the same. That's fine! We're going to fix up this component later on, in Back to the filter buttons.
Importing all our components
Let's make use of our new components.
Add some more import statements to the top of App.js, to import them.
Then, update the return statement of App() so that it renders our components. When you're done, App.js will read like this:
import React from "react";
import Form from "./components/Form";
import FilterButton from "./components/FilterButton";
import Todo from "./components/Todo";

function App(props) {
  const taskList = props.tasks.map(task => (
    <Todo
        id={task.id}
        name={task.name}
        completed={task.completed}
        key={task.id}
      />
    )
  );
  return (
    <div className="todoapp stack-large">
      <h1>TodoMatic</h1>
      <Form />
      <div className="filters btn-group stack-exception">
        <FilterButton />
        <FilterButton />
        <FilterButton />
      </div>
      <h2 id="list-heading">3 tasks remaining</h2>
      <ul
        role="list"
        className="todo-list stack-large stack-exception"
        aria-labelledby="list-heading"
      >
        {taskList}
      </ul>
    </div>
  );
}

export default App;
With this in place, we're almost ready to tackle some interactivity in our React app!
Summary
And that's it for this article — we've gone into some depth on how to break up your app nicely into components, and render them efficiently. Now we'll go on to look at how we handle events in React, and start adding some interactivity.
React interactivity: Events and state
Accessibility in React
In our final tutorial article, we'll focus on (pun intended) accessibility, including focus management in React, which can improve usability and reduce confusion for both keyboard-only and screenreader users.
Objective:	To learn about implementing keyboard accessibility in React.
Including keyboard users
At this point, we've accomplished all of the features we set out to implement. A user can add a new task, check and uncheck tasks, delete tasks, or edit task names. And they can filter their task list by all, active, or completed tasks.
Or, at least: they can do all of these things with a mouse. Unfortunately, these features are not very accessible to keyboard-only users. Let's explore this now.
Exploring the keyboard usability problem
Start by clicking on the input at the top of our app, as if you're going to add a new task. You'll see a thick, dashed outline around that input. This outline is your visual indicator that the browser is currently focused on this element. Press the Tab key, and you will see the outline appear around the "Add" button beneath the input. This shows you that the browser's focus has moved.
Press Tab a few more times, and you will see this dashed focus indicator move between each of the filter buttons. Keep going until the focus indicator is around the first "Edit" button. Press Enter.
The <Todo /> component will switch templates, as we designed, and you'll see a form that lets us edit the name of the task.
But where did our focus indicator go?
When we switch between templates in our <Todo /> component, we completely remove the elements that were there before to replace them with something else. That means the element that we were focused on vanishes, and nothing is in focus at all. This could confuse a wide variety of users — particularly users who rely on the keyboard, or users who use a screen reader.
To improve the experience for keyboard and screen-reader users, we should manage the browser's focus ourselves.
Focusing between templates
When a user toggles a <Todo/> template from viewing to editing, we should focus on the <input> used to rename it; when they toggle back from editing to viewing, we should move focus back to the "Edit" button.
Targeting our elements
In order to focus on an element in our DOM, we need to tell React which element we want to focus on and how to find it. React's useRef hook creates an object with a single property: current. This property can be a reference to anything we want and look that reference up later. It's particularly useful for referring to DOM elements.
Change the import statement at the top of Todo.js so that it includes useRef:
import React, { useRef, useState } from "react";
Then, create two new constants beneath the hooks in your Todo() function. Each should be a ref – one for the "Edit" button in the view template and one for the edit field in the editing template.
const editFieldRef = useRef(null);
const editButtonRef = useRef(null);
These refs have a default value of null because they will not have value until we attach them to their respective elements. To do that, we'll add an attribute of ref to each element, and set their values to the appropriately named ref objects.
The textbox <input> in your editing template should be updated like this:
<input
  id={props.id}
  className="todo-text"
  type="text"
  value={newName}
  onChange={handleChange}
  ref={editFieldRef}
/>
The "Edit" button in your view template should read like this:
<button
  type="button"
  className="btn"
  onClick={() => setEditing(true)}
  ref={editButtonRef}
>
  Edit <span className="visually-hidden">{props.name}</span>
</button>
Focusing on our refs with useEffect
To use our refs for their intended purpose, we need to import another React hook: useEffect(). useEffect() is so named because it runs after React renders a given component, and will run any side-effects that we'd like to add to the render process, which we can't run inside the main function body. useEffect() is useful in the current situation because we cannot focus on an element until after the <Todo /> component renders and React knows where our refs are.
Change the import statement of Todo.js again to add useEffect:
import React, { useEffect, useRef, useState } from "react";
useEffect() takes a function as an argument; this function is executed after the component renders. Let's see this in action; put the following useEffect() call just above the return statement in the body of Todo(), and pass into it a function that logs the words "side effect" to your console:
useEffect(() => {
  console.log("side effect");
});
To illustrate the difference between the main render process and code run inside useEffect(), add another log – put this one below the previous addition:
console.log("main render");
Now, open the app in your browser. You should see both messages in your console, with each one repeating three times. Note how "main render" logged first, and "side effect" logged second, even though the "side effect" log appears first in the code.
main render (3)                                     Todo.js:100
side effect (3)                                     Todo.js:98
That's it for our experimentation for now. Delete console.log("main render") now, and lets move on to implementing our focus management.
Focusing on our editing field
Now that we know our useEffect() hook works, we can manage focus with it. As a reminder, we want to focus on the editing field when we switch to the editing template.
Update your existing useEffect() hook so that it reads like this:
useEffect(() => {
  if (isEditing) {
    editFieldRef.current.focus();
  }
}, [isEditing]);
These changes make it so that, if isEditing is true, React reads the current value of the editFieldRef and moves browser focus to it. We also pass an array into useEffect() as a second argument. This array is a list of values useEffect() should depend on. With these values included, useEffect() will only run when one of those values changes. We only want to change focus when the value of isEditing changes.
Try it now, and you'll see that when you click an "Edit" button, focus moves to the corresponding edit <input>!
Moving focus back to the edit button
At first glance, getting React to move focus back to our "Edit" button when the edit is saved or cancelled appears deceptively easy. Surely we could add a condition to our useEffect to focus on the edit button if isEditing is false? Let's try it now — update your useEffect() call like so:
useEffect(() => {
  if (isEditing) {
    editFieldRef.current.focus();
  } else {
    editButtonRef.current.focus();
  }
}, [isEditing]);
This kind of mostly works. Head back to your browser and you'll see that your focus moves between Edit <input> and "Edit" button as you start and end an edit. However, you may have noticed a new problem — the "Edit" button in the final <Todo /> component is focussed immediately on page load, before we even interact with the app!
Our useEffect() hook is behaving exactly as we designed it: it runs as soon as the component renders, sees that isEditing is false, and focuses the "Edit" button. Because there are three instances of <Todo />, we see focus on the last "Edit" button.
We need to refactor our approach so that focus changes only when isEditing changes from one value to another.
More robust focus management
In order to meet our refined criteria, we need to know not just the value of isEditing, but also when that value has changed. In order to do that, we need to be able to read the previous value of the isEditing constant. Using pseudocode, our logic should be something like this:
if (wasNotEditingBefore && isEditingNow) {
  focusOnEditField()
}
if (wasEditingBefore && isNotEditingNow) {
  focusOnEditButton()
}
The React team had discussed ways to get a component's previous state, and has provided an example custom hook we can use for the job.
Paste the following code near the top of Todo.js, above your Todo() function.
function usePrevious(value) {
  const ref = useRef();
  useEffect(() => {
    ref.current = value;
  });
  return ref.current;
}
Now we'll define a wasEditing constant beneath the hooks at the top of Todo(). We want this constant to track the previous value of isEditing, so we call usePrevious with isEditing as an argument:
const wasEditing = usePrevious(isEditing);
With this constant, we can update our useEffect() hook to implement the pseudocode we discussed before — update it as follows:
useEffect(() => {
  if (!wasEditing && isEditing) {
    editFieldRef.current.focus();
  }
  if (wasEditing && !isEditing) {
    editButtonRef.current.focus();
  }
}, [wasEditing, isEditing]);
Note that the logic of useEffect() now depends on wasEditing, so we provide it in the array of dependencies.
Again try using the "Edit" and "Cancel" buttons to toggle between the templates of your <Todo /> component; you'll see the browser focus indicator move appropriately, without the problem we discussed at the start of this section.
Focusing when the user deletes a task
There's one last keyboard experience gap: when a user deletes a task from the list, the focus vanishes. We're going to follow a pattern similar to our previous changes: we'll make a new ref, and utilize our usePrevious() hook, so that we can focus on the list heading whenever a user deletes a task.
Why the list heading?
Sometimes, the place we want to send our focus to is obvious: when we toggled our <Todo /> templates, we had an origin point to "go back" to — the "Edit" button. In this case however, since we're completely removing elements from the DOM, we have no place to go back to. The next best thing is an intuitive location somewhere nearby. The list heading is our best choice because it's close to the list item the user will delete, and focusing on it will tell the user how many tasks are left.
Creating our ref
Import the useRef() and useEffect() hooks into App.js — you'll need them both below:
import React, { useState, useRef, useEffect } from "react";
Then declare a new ref inside the App() function. Just above the return statement is a good place:
const listHeadingRef = useRef(null);
Prepare the heading
Heading elements like our <h2> are not usually focusable. This isn't a problem — we can make any element programmatically focusable by adding the attribute tabindex="-1" to it. This means only focusable with JavaScript. You can't press Tab to focus on an element with a tabindex of -1 the same way you could do with a <button> or <a> element (this can be done using tabindex="0", but that's not really appropriate in this case).
Let's add the tabindex attribute — written as tabIndex in JSX — to the heading above our list of tasks, along with our headingRef:
<h2 id="list-heading" tabIndex="-1" ref={listHeadingRef}>
  {headingText}
</h2>
Note: The tabindex attribute is great for accessibility edge-cases, but you should take great care to not overuse it. Only apply a tabindex to an element when you're absolutely sure that making it focusable will benefit your user in some way. In most cases, you should be utilizing elements that can naturally take focus, such as buttons, anchors, and inputs. Irresponsible usage of tabindex could have a profoundly negative impact on keyboard and screen-reader users!
Getting previous state
We want to focus on the element associated with our ref (via the ref attribute) only when our user deletes a task from their list. That's going to require the usePrevious() hook we already used earlier on. Add it to the top of your App.js file, just below the imports:
function usePrevious(value) {
  const ref = useRef();
  useEffect(() => {
    ref.current = value;
  });
  return ref.current;
}
Now add the following, above the return statement inside the App() function:
const prevTaskLength = usePrevious(tasks.length);
Here we are invoking usePrevious() to track the length of the tasks state, like so:
Note: Since we're now utilizing usePrevious() in two files, a good efficiency refactor would be to move the usePrevious() function into its own file, export it from that file, and import it where you need it. Try doing this as an exercise once you've got to the end.
Using useEffect() to control our heading focus
Now that we've stored how many tasks we previously had, we can set up a useEffect() hook to run when our number of tasks changes, which will focus the heading if the number of tasks we have now is less than with it previously was — i.e. we deleted a task!
Add the following into the body of your App() function, just below your previous additions:
useEffect(() => {
  if (tasks.length - prevTaskLength === -1) {
    listHeadingRef.current.focus();
  }
}, [tasks.length, prevTaskLength]);
We only try to focus on our list heading if we have fewer tasks now than we did before. The dependencies passed into this hook ensure it will only try to re-run when either of those values (the number of current tasks, or the number of previous tasks) changes.
Now, when you delete a task in your browser, you will see our dashed focus outline appear around the heading above the list.
Finished!
You've just finished building a React app from the ground up! Congratulations! The skills you've learned here will be a great foundation to build on as you continue working with React.
Most of the time, you can be an effective contributor to a React project even if all you do is think carefully about components and their state and props. Remember to always write the best HTML you can.
useRef() and useEffect() are somewhat advanced features, and you should be proud of yourself for using them! Look out for opportunities to practice them more, because doing so will allow you to create inclusive experiences for users. Remember: our app would have been inaccessible to keyboard users without them!
Note: If you need to check your code against our version, you can find a finished version of the sample React app code in our todo-react repository. For a running live version, see https://mdn.github.io/todo-react-build/.
In the very last article we'll present you with a list of React resources that you can use to go further in your learning.
React resources
Component-level styles
Although this tutorial doesn't use this approach, many React applications define their styles on a per-component basis, rather than in a single, monolithic stylesheet.
create-react-app makes it possible to import CSS files into JavaScript modules, so that CSS is only sent to your user when the corresponding component is rendered. For this app, we could have for example written a dedicated Form.css file to house the styles of those respective components, then imported the styles into their respective modules like this:
import Form from './Form';
import './Form.css'
This approach makes it easy to identify and manage the CSS that belongs to a specific component. However, it also fragments your stylesheet across your codebase, and this fragmentation might not be worthwhile. For larger applications with hundreds of unique views and lots of moving parts, it makes sense to limit the amount of irrelevant code that's sent to your user. You'll likely have app-wide styles and specific component styles that built on top of those.
You can read more about component stylesheets in the create-react-app docs.
React DevTools
We used console.log() to check on the state and props of our application in this tutorial, and you'll also have seen some of the useful warnings and error message that React gives you both in the CLI and your browser's JavaScript console. But there's more we can do here.
The React DevTools utility allows you to inspect the internals of your React application directly in the browser. It adds a new panel to your browser's developer tools, and with it you can inspect the state and props of various components, and even edit state and props to make immediate changes to your application.
This screenshot shows our finished application as it appears in React DevTools:
 
On the left, we see all of the components that make up our application, including some unique keys for the things that are rendered from arrays. On the right, we see the props and hooks that our App component utilizes. Notice, too, that the Form, FilterButton, and Todo components are indented to the right – this indicates that App is their parent. In more complex apps, this view is great for understanding parent/child relationships at a glance.
React DevTools is available in a number of forms:
•	A Chrome browser extension.
•	A Firefox browser extension.
•	A Microsoft Edge browser extension.
•	A stand-alone application you can install with NPM or Yarn.
Try installing one of these, then using it to inspect the app you've just built!
You can read more about React DevTools on the React blog.
The Context API
The application that we built in this tutorial utilized component props to pass data from its App component to the child components that needed it. Most of the time, props are an appropriate method for sharing data; for complex, deeply nested applications, however, they're not always best.
React provides the Context API as a way to provide data to components that need it without passing props down the component tree. There's also a useContext hook that facilitates this.
If you'd like to try this API for yourself, Smashing Magazine has written an introductory article about React context.
Class components
Although this tutorial doesn't mention them, it is possible to build React components using ES6 classes – these are called class components. Until the arrival of hooks, ES6 classes were the only way to bring state into components or manage rendering side effects. They're still the only way to handle certain other, more edge-case features, and they're very common in legacy React projects. The official React docs are a great place to start learning about them.
•	State and Lifecycle in the React Docs
•	Intro To React in the React Docs
•	Read about JavaScript classes at MDN
Testing
create-react-app provides some tools for testing your application out of the box — you may have deleted the relevant files earlier in the tutorial. The documentation for create-react-app covers some basics for testing.
Routing
While routing is traditionally handled by a server and not an application on the user's computer, it is possible to configure a web application to read and update the browser's location, and render certain user interfaces. This is called client-side routing. It's possible to create many unique routes for your application (such as /home, /dashboard, or login/).
The React community has produced two major libraries for client-side routing: React Router and Reach Router.
•	React Router is well-suited to applications with complex routing needs, and it meets some edge cases better than Reach Router. React Router is a larger library, however.
•	Reach Router is well-suited to simpler applications, and automatically manages focus as the user navigates from page to page.
Focus management is essential in client-side routing — without it, keyboard users can be trapped in focus limbo, and screen-reader users may have no idea that they have moved to a new page. Because Reach Router is better for accessibility, it's a good place to start.
There's one caveat, however: these projects will be merging in the near future. When this merge happens, React Router will be the surviving project (with the addition of the focus management features of Reach).
Getting started with Ember
In our first Ember article we will look at how Ember works and what it's useful for, install the Ember toolchain locally, create a sample app, and then do some initial setup to get it ready for development.
Objective:	To learn how to install Ember, and create a starter app.
Introducing Ember
Ember is a component-service framework that focuses on the overall web application development experience, minimizing the trivial differences between applications — all while being a modern and light layer on top of native JavaScript. Ember also has immense backwards and forwards compatibility to help businesses stay up to date with the latest versions of Ember and latest community-driven conventions.
What does it mean to be a component-service framework? Components are individual bundles of behavior, style, and markup — much like what other frontend frameworks provide, such as React, Vue, and Angular. The service side provides long-lived shared state, behavior, and an interface to integrating with other libraries or systems. For example, the Router (which will be mentioned later in this tutorial) is a service. Components and Services make up the majority of any EmberJS application.
Use cases
Generally, EmberJS works well for building apps that desire either or both of the following traits:
•	Single Page Applications, including native-like web apps, and progressive web apps (PWAs)
o	Ember works best when it is the entire front end of your application.
•	Increasing cohesion among many team's technology stacks
o	Community-backed "best practices" allow for faster long-term development speed.
o	Ember has clear conventions that are useful for enforcing consistency and helping team members get up to speed quickly.
Ember with add-ons
EmberJS has a plugin architecture, which means that add-ons can be installed and provide additional functionality without much, if any, configuration.
Examples include:
•	PREmber: Static website rendering for blogs or marketing content.
•	FastBoot: Server-side rendering, including improving search-engine optimization (SEO), or improving initial render performance of complex, highly interactive web pages.
•	empress-blog: Authoring blog posts in markdown while optimizing for SEO with PREmber.
•	ember-service-worker: Configuring a PWA so that the app can be installed on mobile devices, just like apps from the device's respective app-store.
Native mobile apps
Ember can also be used with native mobile apps with a native-mobile bridge to JavaScript, such as that provided by Corber.
Opinions
EmberJS is one of the most opinionated front-end frameworks out there. But what does it mean to be opinionated? In Ember, opinions are a set of conventions that help increase the efficiency of developers at the cost of having to learn those conventions. As conventions are defined and shared, the opinions that back those conventions help reduce the menial differences between apps — a common goal among all opinionated frameworks, across any language and ecosystem. Developers are then more easily able to switch between projects and applications without having to completely relearn the architecture, patterns, conventions, etc.
As you work through this series of tutorials, you'll notice Ember's opinions — such as strict naming conventions of component files.
How does Ember relate to vanilla JavaScript?
Ember is built on JavaScript technologies and is a thin layer on top of traditional object-oriented programming, while still allowing developers to utilize functional programming techniques.
Ember makes use of two main syntaxes:
•	JavaScript (or optionally, TypeScript)
•	Ember's own templating language, which is loosely based on Handlebars.
The templating language is used to make build and runtime optimizations that otherwise wouldn't be possible. Most importantly, it is a superset of HTML — meaning that anyone who knows HTML can make meaningful contributions to any Ember project with minimal fear of breaking code. Designers and other non-developers can contribute to page templates without any knowledge of JavaScript, and interactivity can be added later.
This language also enables lighter asset payloads due to compiling the templates into a "byte code" that can be parsed faster than JavaScript. The Glimmer VM enables extremely fast DOM change tracking without the need to manage and diff a cached virtual representation (which is a common approach to mitigating the slow I/O of DOM changes).
For more information on the technical aspects of The Glimmer VM, the GitHub repository has some documentation — specifically, References and Validators may be of interest.
Everything else in Ember is just JavaScript. In particular, JavaScript classes. This is where most of the "framework" parts come into play, as there are superclasses, where each type of thing has a different purpose and different expected location within your project.
Here is a demonstration the impact Ember has on the JavaScript that is in typical projects: Gavin Demonstrates how < 20% of the JS written is specific to Ember.
 
Getting started
The rest of the Ember material you'll find here consists of a multi-part tutorial, in which we'll make a version of the classic TodoMVC sample app, teaching you how to use the essentials of the Ember framework along the way. TodoMVC is a basic to-do tracking app implemented in many different technologies.
Here is the completed Ember version, for reference.
A note on TodoMVC and accessibility
The TodoMVC project has a few issues in terms of adhering to accessible/default web practices. There are a couple of GitHub issues open about this on the TodoMVC family of projects:
•	Add keyboard access to demos
•	Re-enable Outline on focusable elements
Ember has a strong commitment to being accessible by default and there is an entire section of the Ember Guides on accessibility on what it means for website / app design.
That said, because this tutorial is a focus on the JavaScript side of making a small web application, TodoMVC's value comes from providing pre-made CSS and recommended HTML structure, which eliminates small differences between implementations, allowing for easier comparison. Later on in the tutorial, we'll focus on adding code to our application to fix some of TodoMVC's biggest faults.
Installing the Ember tooling
Ember uses a command-line interface (CLI) tool for building and scaffolding parts of your application.
1.	You'll need node and npm installed before you can install ember-cli. Go here to find out how to install node and npm, if you haven't already got them.
2.	Now type the following into your terminal to install ember-cli:
3.	npm install -g ember-cli
This tool provides the ember program in your terminal, which is used to create, build, develop, test, and scaffold your application (run ember --help for a full list of commands and their options).
4.	To create a brand new application, type the following in your terminal. This creates a new directory inside the current directory you are in called todomvc, containing the scaffolding for a new Ember app. Make sure you navigate to somewhere appropriate in the terminal before you run it. (Good suggestions are your "desktop" or "documents" directories, so that it is easy to find):
5.	ember new todomvc
Copy to Clipboard
Or, on Windows:
npx ember-cli new todomvc
Copy to Clipboard
This generates a production-ready application development environment that includes the following features by default:
•	Development server with live reload.
•	Plugin-architecture that allows for third-party packages to richly enhance your application.
•	The latest JavaScript via Babel and Webpack integration.
•	Automated testing environment that runs your tests in the browser, allowing you to test like a user.
•	Transpilation, and minification, of both CSS and JavaScript for production builds.
•	Conventions for minimizing the differences between applications (allowing easier mental context switching).
Getting ready to build our Ember project
You'll need a code editor before continuing to interact with your brand new project. If you don't have one configured already, The Ember Atlas has some guides on how to set up various editors.
Installing the shared assets for TodoMVC projects
Installing shared assets, as we're about to do, isn't normally a required step for new projects, but it allows us to use existing shared CSS so we don't need to try to guess at what CSS is needed to create the TodoMVC styles.
1.	First, enter into your todomvc directory in the terminal, for example using cd todomvc in macOS/Linux.
2.	Now run the following command to place the common todomvc CSS inside your app:
3.	npm install --save-dev todomvc-app-css todomvc-common
4.	Next, find the ember-cli-build.js file inside the todomvc directory (it's right there inside the root) and open it in your chosen code editor. ember-cli-build.js is responsible for configuring details about how your project is built — including bundling all your files together, asset minification, and creating sourcemaps — with reasonable defaults, so you don't typically need to worry about this file. We will however add lines to the ember-cli-build.js file to import our shared CSS files, so that they become part of our build without having to explicitly @import them into the app.css file (this would require URL rewrites at build time and therefore be less efficient and more complicated to set up).
5.	In ember-cli-build.js, find the following code:
6.	let app = new EmberApp(defaults, {
7.	    // Add options here
8.	  });
Copy to Clipboard
9.	Add the following lines underneath it before saving the file:
10.	  app.import('node_modules/todomvc-common/base.css');
11.	  app.import('node_modules/todomvc-app-css/index.css');
Copy to Clipboard
For more information on what ember-cli-build.js does, and for other ways in which you can customize your build / pipeline, the Ember Guides have a page on Addons and Dependencies.
12.	Finally, find app.css, located at app/styles/app.css, and paste in the following:
13.	:focus,
14.	.view label:focus,
15.	.todo-list li .toggle:focus + label,
16.	.toggle-all:focus + label {
17.	  /* !important needed because todomvc styles deliberately disable the outline */
18.	  outline: #d86f95 solid !important;
19.	}
This CSS overrides some of the styles provided by the todomvc-app-css npm package, therefore allowing keyboard focus to be visible. This goes some way towards fixing one of the major accessibility disadvantages of the default TodoMVC app.
Starting the development server
You may start the app in development mode by typing the following command in your terminal, while inside the todomvc directory:
ember server
This should give you an output similar to the following:
Build successful (190ms) – Serving on http://localhost:4200/

Slowest Nodes (totalTime >= 5%)          | Total (avg)
-----------------------------------------+-----------
BroccoliMergeTrees (17)                  | 35ms (2 ms)
Package /assets/vendor.js (1)            | 13ms
Concat: Vendor Styles/assets/vend... (1) | 12ms
The development server launches at http://localhost:4200, which you can visit in your browser to check out what your work looks like so far.
If everything is working correctly, you should see a page like this:
 
Note: on Windows systems without Windows Subsystem for Linux (WSL), you will experience slower build-times overall compared to macOS, Linux, and Windows with WSL.
Summary
So far so good. We've got to the point where we can start build up our sample TodoMVC app in Ember. In the next article we'll look at building up the markup structure of our app, as a group of logical components.
Ember app structure and componentization
In this article we'll get right on with planning out the structure of our TodoMVC Ember app, adding in the HTML for it, and then breaking that HTML structure into components.
Objective:	To learn how to structure an Ember app, and then break that structure into 
components.


