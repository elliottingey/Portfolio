

<html lang="en">
<head>
</head>
  
<body>

  <h1>ChangeLog:</h1>

  <div class="container-fluid"> 
  <h3>9/30/21 - Adding features and using react hooks</h3>
    <ul class="a">
        <li>github pages project up at <a href="https://elliottingey.github.io/colors/">my github.io</a>. Here is the 
	<a href="https://github.com/elliottingey/colors/tree/master">source code</a> for this project. I was planning on having this be a smaller project and do others
	    as well, but I got really into it. I spent all my time trying to optimize it and get it running like I envisioned.</li>
        <li>Did a lot of work with react hooks today. Varying success. <a href="https://reactjs.org/docs/hooks-state.html">This site</a> was very helpful.</li>
        <li>Fixed randomize() so that it is better random and doesnt cause issues elsewhere in my code</li>
        <li>Added console printing hex codes on button press to make testing easier</li>
        <li>Began adding functions to allow custom colors to be input using hooks. Want to allow hex, rgb, and
        a color wheel selector</li>
        <li>Added dynamic text that changes depending on what color input mode is chosen. Currently does
        not allow input after pushing Customize button</li>
        <li>Wrote CSS to allow for a much nicer formatted dropdown menu. I should have tried to find
        more info online for this. It was not fun.</li>
        <li>Began adding functionality to record color history for recently chosen colors. Button doesnt do anything yet. </li>
        <li>Seperated CSS for button and dropdown buttons to help make it easier to deal with</li>
        <li>Removed a lot of the default code from the react-app initalization</li> 

    </ul>
  </div>

  <div class="container-fluid"> 
  <h3>9/29/21 - CSS and some TypeScript Functions</h3>
    <ul class="a">
        <li>added bootstrap to the site</li>
        <li>I formatted the site a little. I added CSS buttons with base styling from <a href="https://freefrontend.com/bootstrap-code-examples">here</a> and <a href="https://getcssscan.com/css-buttons-examples">here.</a></li>
        <li>Added some code to make a drop down button</li>
        <li>Added random button. Background will now change colors at random when pressed</li>
        <li>Added reset button to return to default coloration</li>
        <li>Created randomize(), insertRandomColor(), and resetColor() to do this</li>
        <li>Added black borders around text so it can be seen on any color background</li>
        <li>Many small assorted CSS tweaks</li>
    </ul>
  </div>

  <div class="container-fluid"> 
  <h3>9/28/21 - diving fully into react</h3>
    <ul class="a">
        <li>Made an instance of react with the typescript template. I will be making my next project in this.</li>
        <li>I want to make a site where you can change the background color in a couple different ways. I got
        the idea <a href="https://www.freecodecamp.org/news/javascript-projects-for-beginners/">here</a>, 
        although I am not going to look at or use the code. For one, its in JavaScript and two, I would rather
        try building it myself.</li>
        <li>Added buttons to my site. Very basic so far. I referenced this site <a href="https://react.school/ui/button">here.</a></li>
    </ul>
  </div>

  <div class="container-fluid"> 
  <h3>9/27/21 - project not deploying to gh-pages</h3>
    <ul class="a">
        <li>Im having trouble getting my react project to deploy. I will try following the tutorial posted
        on canvas. I tried following it once before and still had issues so im not sure whats wrong</li>
        <li>update: I'm not sure what the issue is. May be with my PATH or nodejs being installed somewhere
        weird on my laptop. Ive given up and Just reinstalled everything on my desktop. Seems to be working
        so far.</li>
    </ul>
  </div>

<div class="container-fluid">
    <h3>9/23/21 - painful errors</h3>
    <ul class="a">
        <li>Spent about 4 hours trying to get React running and properly using github pages. I was getting a ton of weird errors and ran into problems with git. I had to manually delete the github_pages folder in .cache for some reason. I ended up with a working page but I didnt finish the project I was planning on doing with the react page.</li>
        <li>Now have git correctly set up to push updates to my repository. I also have a remote branch for my react project to have updates sent through. Now that I know the process and the solutions to the errors I was running into, it should be easier to make react sites for the projects I want to finish next week. </li
        <li>React site is hosted in a seperate repository. Not sure if it has to be or not.</li>
        <li>Updated links to go to most current versions of pages.</li>
    </ul>
  </div>



  <div class="container-fluid">
    <h3>9/22/21 - React</h3>
    <ul class="a">
        <li>after 3 installations, I got an instance of React working on my PC. I played around with react for a while by editing the default page. I broke something eventually when trying to get it working on github pages. Getting lots of errors that im not sure how to fix.</li>
        <li>I went through a <a href="https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes-oop.html"></a>TypeScript tutorial</a> I mentioned on my last TODO list. I went through the Page for JavaScript programers and for OOP programers. </li>
    </ul>
  </div>

  <div class="container-fluid">
    <h3>9/21/21 - git errors</h3>
    <ul class="a">
        <li>Did a bunch of googling and finally got git to work properly on my system. </li>
        <li>Made an ssh key so i could use it between git bash and github</li>
        <li>Small improvements on portfolio site. Portfolio need more dedicated attention though.</li>
    </ul>
  </div>
  



  <div class="container-fluid">
    <h3>9/19/21 - Fixed Weird Errors</h3>
    <ul class="a">
        <li>Got VSCode running correctly and react is now properly installed. Will be working with typescript and react over the next few days</li>
	<li>git, bash, and node are now being recognized in my command terminal.</li>
    </ul>
  </div>
  
  
  <div class="container-fluid">
    <h3>9/18/21 - Weird Errors</h3>
    <ul class="a">
        <li>Trying to get my VSCode running correctly. Having issues where its not recognizing git, bash or node. Maybe a PATH issue</li>
    </ul>
  </div>
  
  <div class="container-fluid">
    <h3>9/16/21 - Variety of Updates</h3>
    <ul class="a">
        <li>Made a ton of CSS and Bootstrap updates to improve functionality.
          Learned a lot of it from <a href="https://www.w3schools.com">https://www.w3schools.com</a>. 
          <a href="https://www.w3schools.com/bootstrap4/">This</a> was helpful for Bootstrap,
          and <a href="https://www.w3schools.com/css/">this</a> was helpful for CSS.</li>
        <li>Figured out how to make and edit my theme</li>
        <li>Changed my <a href="https://github.com/elliottingey/Portfolio/blob/main/docs/_layouts/default.html">default page layout</a></li>
        <li>Added bootstrap functionality in this <a href="https://github.com/elliottingey/Portfolio/blob/main/docs/_includes/head-custom.html">head-custom.html</a>.
            This lets me not have to copy the same things into every head in every web page</li>
        <li>Rearranged and Organized my portfolio files</li>
        <li>Made a navigation bar fixed to top of every page. This is in
            <a href="https://github.com/elliottingey/Portfolio/blob/main/docs/_layouts/default.html">default.html</a>.</li>
        <li>Added dropdown menu to some pages to see version history. See bottom of <a href="https://elliottingey.github.io/Portfolio/htmltestingWeek2">this page</a>
            for an example.</li>
        <li>Added home button to navigation bar</li>
        <li>Moved Portfolio home page code from README.md to home.md for clarity</li>
        <li>Moved images into a seperate dedicated folder <a href="https://github.com/elliottingey/Portfolio/tree/main/docs/images">here</a>.</li>
        <li>Added picture of JavaScript tutorial site mentioned on 9/11/21 onto <a href="https://elliottingey.github.io/Portfolio/learningJavaScriptWeek2">here</a> page.</li>
        <li>Changed Text on site Banner</li>
        <li>Used Bootstrap to make <a href="https://elliottingey.github.io/Portfolio/home">home page</a> less ugly. Now, the projects exist in clickable boxes with
            a title and some basic info about them.</li>
        <li>Updated my original <a href="https://elliottingey.github.io/Portfolio/htmltestingWeek2">html project</a> a little. I fixed the picture and added some
            explanation text about it. I also added a couple paragraphs about bootstrap.</li>
        <li>Started using bootstrap on just about every page on the website. Can be seen in the 
            <a href="https://github.com/elliottingey/Portfolio/tree/main/docs">.md files</a>.</li>
      <li>Updated home page links to Week 2 files</li>
      <li>Updated page links so everything directs to the correct places</li>
        
    </ul>
  </div>
 
  
  <div class="container-fluid">
    <h3>9/14/21 - Custom Theme 2</h3>
    <p>Found the <a href="https://github.com/pages-themes/slate">github pages theme repository</a> that I am using. 
    I also found someone having the same issues that I was. Ill copy over files from the repository that I want to edit and
    that should fix it.</p>
  </div>
      
    
  <div class="container-fluid">
    <h3>9/13/21 - Custom Theme</h3>
    <p>Gave myself a headache trying to make my site less ugly. I was trying to fix the header but I was fighting with
    the Jekyll theme I had installed. Figured out a work around or two, but it was time consuming and not ideal.</p>
  </div>
  
   <div class="container-fluid">
    <h3>9/11/21 - JavaScript Tutorial</h3>
    <p>Began Looking into JavaScript. I used a website I found called <a href="https://www.w3schools.com/bootstrap5/">javascript.info</a>.
     They had a great explination of the basics of JavaScript. I talk about it a little more
      <a href="https://elliottingey.github.io/Portfolio/learningJavaScriptWeek2">here</a>.</p>
  </div>
  
  
  <div class="container-fluid">
    <h3>9/9/21 - Bootstrap and Portfolio Setup</h3>
    <p>Added basic portfolio functionality and began learning bootstrap to help some of the CSS headaches I was going through. I used <a href="https://www.w3schools.com/bootstrap5/">w3schools</a> again since I liked their CSS tutorials. After reading that for a while, I applied some of the knowledge to make containers and grouped buttons for the portfolio website. Some examples of bootstrap can be seen in the source code for this changelog<a href="https://raw.githubusercontent.com/elliottingey/Portfolio/main/changelog.md"> here.</a> My portfolio now has links to my inital html project and its code, as well as links to my TODO and changelog. I also added functionality to return to the home page of the portfolio site. It is still pretty ugly, so my next goal is proabably to clean up the looks a bit. I also wrote out the changelog and TODO list today. </p>
  </div>
  
  
  <div class="container-fluid">
    <h3>9/8/21 - CSS tutorial</h3>
    <p> I felt fairly comfortable with HTML at a base level after the previous day, so I moved onto trying to learn basic CSS. I used <a href="https://www.w3schools.com/w3css/">w3schools</a> and started reading up on how to create buttons and dropdown menus. My eventual plan being to add a drop down menu on applicable pages with every change that is specific to that project. Below is the source code to a simple button and dropdown with code changed slightly from the tutorial site. There is no github page containing this code since it is just a test file.</p>
    
      <a href="https://github.com/elliottingey/Portfolio/blob/main/HTML%26CSS/CSS%20Testing.html" type="button" class="btn btn-primary">CSS Source Code</a>
  </div>
  
  
<div class="container-fluid">
  <h3>9/7/21 - HTML tutorial</h3>
  <p>I followed an html tutorial on marksheet.io. At the end, I used what I had learned to make a basic HTML site.
  The tutorial, my site, and the source code are linked below.</p>
  <p> NOTE: I had a steep learning curve and a lot of issues with the intial github pages setup so some of the timestamps on github for file uploads and edits may not be accurate. Not Sure. </p>
     <div class="btn-group">
     <a href="https://marksheet.io/html-basics.html" type="button" class="btn btn-primary">Tutorial</a>
     <a href="https://elliottingey.github.io/Portfolio/htmltesting" type="button" class="btn btn-primary">Site</a>
     <a href="https://github.com/elliottingey/Portfolio/blob/main/HTML%26CSS/HTMLtutorial.html" type="button" class="btn btn-primary">Source Code</a>
     </div> 
</div>
  
  
  
  <div class="container-fluid">
    <h3>9/2/21 - github pages setup</h3>
  <p>I made a github pages and fought with the setup. Over the next few days, I got it working correctly and configured in the ways I could figure out. I added a theme provided  by github. </p>
</div>
    </body>
  </html>

