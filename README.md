# tech-documentation
Tech Documentation for freeCodeCamp.org Responsive Web Design project.
I am learning to use Git with Visual Studio and Github so that I can use Version Control on my projects, so that I don't lose good work.  
I was experimenting with how to use CSS to keep the navigation menu (in the left column) in a fixed position, so that when I scroll down
the page I don't lose the navigation menu.  I need to rework the project, so that it meets all the User Stories provided in the challenge.  
I want to use the Technical Documentation page as a Sandbox to explore and document coding ideas for my Tribute Page, my Portfolio page, 
my web form page, and my Product page.

## Learning from freeCodeCamp.org
I want to spend one to two weeks on each project, so that I keep moving through the curriculum in freeCodeCamp.org.  
I want to move onto Javascript and also the the various JS Libraries.  I want to learn React.  
But most importantly, I want to make things with what I learn, not just learning more and more and never doing anything with it.  

I also want to incorporate my art skills, both conventional and digital, into my digital design and programming work.

--@7:09 p.m., Saturday, January 26, 2019.

## Using Github with Git and Visual Studio Code
Next step:  I want to learn how to take my HTML and CSS from my CodePen and in Visual Studio, Commit it to a version so that I can back up my work.  

--@7:19 p.m., Saturday, January 26, 2019.


@7:32 p.m.:

I just finished:  
1.  Copying my HTML code from my CodePen for the Technical Documentation project.
2.  Pasted it into Visual Studio, saved it as tech-documentation.html file.
3.  Copied my CSS code from my CodePen for the Technical Documentation project.
4.  Pasted it into Visual Studio, saved it as tech-documentation.css file.
5.  Committed the changes to the HTML file and the CSS file and saved the commit
    both to my local file and to Github.
6.  Using Visual Studio, the process was simple, once I got everything set up.

@7:37 p.m.:

Reflecting upon this process, what I don't understand, is how there are different versions of the same file, 
and how you can retrieve a previous version.  What happens if I create a new branch for each commit?  
What is the difference between committing directly to the master branch and creating a new branch for each commit?

@7:41 p.m.:
I'm going to try creating a new branch for this next commit.  

@7:44 p.m.:

I'm thinking that as far as working with my code from CodePen, everything that I'm committing is stuff I want to keep.  If I screw something up, it would be from working in CodePen, and then I can come back to Github to retrieve the previous version.
Save files with dates as part of the name. 
## Next Steps
@7:46 p.m.:
I like this place for documenting my work flow.
Next steps for the Technical Documentation project:  Work on fixing the position of the left column.  Making sure the right column works in its proper space.  Make sure the font-size is comparable to what it was previously, and make sure the design is beautiful as it was previously.  

## Reflection
@8:04 p.m.:

I'm getting frustrated.  I'm basically guessing, doing trial and error to get the positioning of each column working properly and it's basically a mess.  Need to regroup, and take it slowly, step by step.  Do my research to figure it out, before I just slosh around trying stuff.  freeCodeCamp is my reference.  So is w3cschools.org.

Perhaps try a new code pen with two simple columns with 35% and 65% widths.  Simulate my conditions, but make them simpler so all the other code doesn't get in the way.  Boil it down to the barest essentials.  

Reflections on today:

1.  I learned that I need to use Git and Github for version control, so that I don't lose what I've created.
2.  I've learned how to use Git and Github with Visual Studio Code.  


@11:24 p.m.:
  Can't figure out the CSS for the positioning of the two columns.  Tried Grid layout and I tried Flexbox.  Neither is 
  doing what I would like it to do.  Try looking at my HTML and CSS book by Cengage.
  
  It's ironic.  Yesterday, I felt like a professional developer with my felt sense of color and form for the web page.  
  Today, after my design collapsed, I feel like a beginner, wandering in circles...
  
 ## HTML and CSS for two-column layout with fixed position NavBar in left column.
 
 @12:24 p.m.:
 
 I finally found a video walkthrough on YouTube that worked.  I tried it with simple boxes.
 
 Here's the CSS:
 
 .page {
  
  display:grid;
  grid-template-columns: 30vw auto;
  
}

.sidebar {
  position: fixed;
  width: 30vw;
  
}

.main {
  grid-column-start:2;
}

.headerMain {
  height:200px;
  background-color:MidnightBlue;
  color:Turquoise;
  font-size: 50px;
}

.mainBackground {
  background-color:AliceBlue;
  margin-top: -16px;
}

x--------------------------------------------x
And here's the HTML:


     
    <div class="sidebar">
      <p>sidebar</p>
</div>

      <div class="page">
        
        <div class="main">
          <header class="headerMain">Banner</header>
          <div class="mainBackground">
          <p>Lorem ipsum dolor sit amet, malis iracundia ne ius, vel possit verear cu. Ex erat tibique philosophia nec, lorem ullum bonorum ex eos, ius an impetus dolorem imperdiet. Ut nec stet decore oportere. Sea eu ferri vituperata accommodare, vel no veri electram. Partem principes argumentum vis eu.

Cibo aliquando intellegebat ius no, at debitis placerat vim. Rebum electram ut nam, fastidii dignissim ut sed, usu an laudem nostrum. Nostro mandamus vim at, sit appetere reprimique no. Et his dicunt antiopam, sed eu vidit gloriatur, vis ea putant legimus nusquam. Te mel nonumy doming aperiam, tota lorem dolore per id, an ferri harum expetendis mea. Eu sit cibo necessitatibus, inermis delectus no mea, volumus persequeris eloquentiam mea ea. Quaeque iudicabit no vim.

Vel an splendide interesset, ad sea partem timeam principes. Ne has urbanitas argumentum signiferumque, aeterno praesent instructior vim in, duo platonem conceptam deseruisse ne. Mei no meis perfecto reprehendunt, facer facilisi consequuntur mea id. Nam consul consulatu moderatius ad, assum nihil animal nam te. Sit ex dicunt iuvaret intellegam, mutat definitionem at pro. Vix sint simul voluptua eu.

Tation sententiae quo cu, duo ea clita tation, duo malis prompta tibique ea. Cu eam illud oratio iuvaret, zril quaestio ex vim, meliore definiebas intellegebat mea ea. Vis congue munere accommodare no. In singulis deserunt nam, at sea justo corpora signiferumque, quis persius no duo. Vel consequat deterruisset eu, falli fastidii democritum eum cu, dico denique contentiones eos an. Harum causae albucius nec ad, quo et veritus molestiae.

Justo feugait ad vix. Vis ne sapientem dissentiunt, soleat commune convenire ne sit. Meis elaboraret pri at, eu iusto vivendum molestiae est. Simul fabulas ne has, mea at case tantas commune, case error duo et. Nec ne eripuit dignissim prodesset, commune splendide te nam, numquam elaboraret cu per. Graeci dignissim ius ea. Ut malis iusto noluisse vel, agam propriae vel Lorem ipsum dolor sit amet, malis iracundia ne ius, vel possit verear cu. Ex erat tibique philosophia nec, lorem ullum bonorum ex eos, ius an impetus dolorem imperdiet. Ut nec stet decore oportere. Sea eu ferri vituperata accommodare, vel no veri electram. Partem principes argumentum vis eu.

Cibo aliquando intellegebat ius no, at debitis placerat vim. Rebum electram ut nam, fastidii dignissim ut sed, usu an laudem nostrum. Nostro mandamus vim at, sit appetere reprimique no. Et his dicunt antiopam, sed eu vidit gloriatur, vis ea putant legimus nusquam. Te mel nonumy doming aperiam, tota lorem dolore per id, an ferri harum expetendis mea. Eu sit cibo necessitatibus, inermis delectus no mea, volumus persequeris eloquentiam mea ea. Quaeque iudicabit no vim.

Vel an splendide interesset, ad sea partem timeam principes. Ne has urbanitas argumentum signiferumque, aeterno praesent instructior vim in, duo platonem conceptam deseruisse ne. Mei no meis perfecto reprehendunt, facer facilisi consequuntur mea id. Nam consul consulatu moderatius ad, assum nihil animal nam te. Sit ex dicunt iuvaret intellegam, mutat definitionem at pro. Vix sint simul voluptua eu.
erata accommodare, vel no veri electram. Partem principes argumentum vis eu.

Cibo aliquando intellegebat ius no, at debitis placerat vim. Rebum electram ut nam, fastidii dignissim ut sed, usu an laudem nostrum. Nostro mandamus vim at, sit appetere reprimique no. Et his dicunt antiopam, sed eu vidit gloriatur, vis ea putant legimus nusquam. Te mel nonumy doming aperiam, tota lorem dolore per id, an ferri harum expetendis mea. Eu sit cibo necessitatibus, inermis delectus no mea, volumus persequeris eloquentiam mea ea. Quaeque iudicabit no vim.

Vel an splendide interesset, ad sea partem timeam principes. Ne has urbanitas argumentum signiferumque, aeterno praesent instructior vim in, duo platonem conceptam deseruisse ne. Mei no meis perfecto reprehendunt, facer facilisi consequuntur mea id. Nam consul consulatu moderatius ad, assum nihil animal nam te. Sit ex dicunt iuvaret intellegam, mutat definitionem at pro. Vix sint simul voluptua eu.

Tation sententiae quo cu, duo ea clita tation, duo malis prompta tibique ea. Cu eam illud oratio iuvaret, zril quaestio ex vim, meliore definiebas intellegebat mea ea. Vis congue munere accommodare no. In singulis deserunt nam, at sea justo corpora signiferumque, quis persius no duo. Vel consequat deterruisset eu, falli fastidii democritum eum cu, dico denique contentiones eos an. Harum causae albucius nec ad, quo et veritus molestiae.


 


          </div>


x-----------------------------------------x
Tomorrow, I'll try out the solution with my layout. Then clean it up so it looks beautiful the way it did before.

x-----------------------------------------x

References:

Using Git with Visual Studio Code:
https://www.youtube.com/watch?v=6ai-CHkQP5g

Fixed Flexible Sidebar with CSS Grid:
https://www.youtube.com/watch?v=alsxCvrbeko

x------------------------------------------X
## Starting Version Control 2

Starting Version Control 2.

Goal for next step, which I will save as a version:

1. Get my two-column layout working with the fixed Navigation Bar in the first column.  
2. Save Code into freeCodeCamp.org template for project.
3. Save the version on Git.  

## Changes with sidebar and page code for fixed navbar and scrolling main section
HTML:

<!DOCTYPE html>
<html>
    <head>
        <title>HTML, CSS Documentation</title>
        <link rel="stylesheet" href="style.css">
        <meta charset="utf-8">
      <link href="https://fonts.googleapis.com/css?family=Exo+2" rel="stylesheet">
     
    <div class="sidebar">
      <p>sidebar</p>
      
        <nav id="navbar">
       
        <header class="navHeader">HTML, CSS Documentation</header>
        <br>
        <hr>
        <p><a href="#Introduction">Introduction</a></p>
        
        <hr>
        
         <p><a href="#about">About the Coder</a></p>
        
        <hr>
        
       <a href="#references">References</a></p> 
       
        <hr>
          <p><a href="#code-editors">Code Editors</a></p>
        <hr>
      
      <p><a href="#tribute">The Tribute Project</a></p>
        
        <hr>
      
      <p><a href="#HTML">HTML</a></p>
        <hr>
      </nav>
        
      
      
      
      
</div>
  
  /*End of Sidebar code */
  
  /# Begin Page code */
  
  
  
  

      <div class="page">
        
        
        
        <div class="main">
          
          <header class="headerMain">Banner</header>
          <div class="mainBackground">
            
            /* Inserting code for main section */
            
         <main id="main-doc">
     <header class="mainHeader" id="Introduction">
       Introduction</header>
       <br>
       
       <p>Having completed the coding exercises for HTML and CSS at freeCodeCamp.org, the purpose of this technical documentation now is to provide a sandbox for creative explorations with the code I have learned so far.  Doing this in the form of a project gives me the chance to revisit the code and discover what proves useful in the shaping of this project.  It's also a chance for me to summarize and reflect my current understanding.</p>
       <p class="time-date-stamp"><i>time: 11:56 p.m.; date: Wednesday, January 23, 2019; place: Boca Raton, FL.</i></p>
       <br>
        <header class="mainHeader" id="about">
       About the Coder</header>
       <p>My name is Andy Goldstein.  Long, long ago, in a galaxy far, far away, I studied journalism at Northwestern University.  During an internship at the Louisville Times, I became friends with Mike Covington, an artist who created illustrations for the Louisville Times, and that was the start of my lifelong love of art.  I studied art at Northwestern University under Ed Paschke, one of the leaders of the the Chicago Imagist movement.  I also studied at the University of Louisville, the New York Academy of Art and earned a Master of Fine Arts Degree from the Graduate School of Figurative Art of the New York Academy of Art.  After art school I painted at the Artist's Co-op in Delray, FL and exhibited at the Art of Africa in Delray, FL. </p>
       
 <p>Eventually, I became interested in teaching and earned my teaching degree from Florida Atlantic University.  I've been teaching ever since.  I currently teach a course in <i>Fundamentals of Web and Software Development</i> and <i>ICT Essentials.</i> You can view our class blog, which showcases my students' creative work at 
<a href="http://weblogs.pbspaces.com/mrgoldstein/" target="_blank" style="text-decoration:underline"><i>Imagine</i></a>, and our class website, 
<a href="http://schools.firn.edu/websites/palm_beach/omni_middle_school/classrooms/andrew_goldstein/" target="_blank" style="text-decoration:underline"><i>OmniVision</i></a>.  I've also taught Yearbook, having earned the Walsworth publisher's award (awarded to its top 5 percent of yearbooks in the country) three years in a row.  You can view our <a href="http://weblogs.pbspaces.com/mrgoldstein/yearbook/" target="_blank" style="text-decoration:underline">yearbook covers</a>, designed by students, handrawn, or designed in Flash or Photoshop.  We used Adobe InDesign to layout the pages of the yearbook.  I've also taught robotics, structures, PowerPoint, animation with Flash, stop-motion animation on iMac computers, creating ClayMation. I've taught game programming in Scratch and in Flash, and video production using iMovie and GarageBand on iMac computers. I teach web development using <i>Khan Academy</i>, <i>Code.org</i>, <i>Notepad++</i> and working with Dreamweaver to post our students' web pages to our class website.  In 2012, I was named one of four "Innovator Educators of the Year" in a county-wide competition sponsored by the School District of Palm Beach County and Microsoft.  I earned a trip to Microsoft's headquarters in Redmond, Washington and showcased our students' work for our project, <i>Invent</i>.  I was one of 72 Regional winners that year for <a href="http://weblogs.pbspaces.com/mrgoldstein/2012/08/07/microsoft-partners-in-learning-u-s-forum-2012/" target="_blank" style="text-decoration:underline;"><i>Microsoft Partners in Learning U.S. Forum 2012</i></a> (Scroll down to Andy Goldstein in Florida). </p>
       <p>A brief selection of my work (I will compile a comprehensive selection in the freeCodecamp.org portfolio project):</p>
       <figure>
         <iframe title="Vodcast Player" width="480" height="270" src="https://vodcast.palmbeachschools.org/embed/ED7YR" frameborder="0" marginheight="0" marginwidth="0" scrolling="no" allowfullscreen="true" style="margin-left:30px; margin-top: 60px;"></iframe><figcaption><i>Gobble Gobble</i> by Andy Goldstein
       </figure>
       <br>
       <figure>
       <img src="http://weblogs.pbspaces.com/mrgoldstein/files/2009/12/Souls-on-Fire.png" alt="Souls on Fire, a painting by Andy Goldstein" style="margin:30px;"><figcaption ><i>Souls on Fire</i> by Andy Goldstein</figcaption>
         </figure>
                 
       <br>
  <figure>
       <img src="http://weblogs.pbspaces.com/mrgoldstein/files/2009/12/Sketch1.png" alt="Gemini Thinking, a drawing by Andy Goldstein" width="400" style="margin:30px;"><figcaption><i>Gemini Thinking </i>by Andy Goldstein</figcaption>
         </figure>     
       
       
       
        <header class="mainHeader" id="references">
       References</header>
       <br>
       <p>For reference, for learning, I am using freeCodeCamp.org's section on Responsive Web Design Certification, which includes the following sections:</p>
         <ul>
           <li>Introduction to Basic HTML and HTML 5</li>
            <li>Basic CSS</li>
            <li>Applied Visual Design</li>
            <li>Applied Accessibility</li>
            <li>Responsive Web Design Principles</li>
            <li>CSS Flexbox</li>
            <li>CSS Grid</li>
            <li>Responsive Web Design Projects</li>
       </ul>
       <p>I have completed all the exercises in the above sections, other than "Responsive Web Design Projects," which I am working on creating now.</p>
       <p>I have also studied Khan Academy's <i>Intro to HTML/CSS: Making Web Pages</i> course, completing all the exercises.  These are:</p>
        <ul>
           <li>Intro to HTML</li>
            <li>Intro to CSS</li>
            <li>More HTML tags</li>
            <li>CSS text properties</li>
            <li>Web development tools</li>
            <li>CSS layout</li>
            <li>More CSS selectors</li>
            <li>Other ways to embed CSS</li>
           <li>Further Learning</li>
           
       </ul>
       <p> I have also worked with Code.org's <i>Web Development Unit:</i></p>
       <h4>Web Content  and HTML</h4>
          <ul>
          
           <li>Exploring Websites</li>
            <li>Websites for Expression</li>
            <li>Intro to HTML</li>
            <li>Headings</li>
            <li>Digital Footprint</li>
            <li>Lists</li>
            <li>Intellectual Property and Images</li>
            <li>Clean code and debugging</li>
           <li>Project - Multi-Page Websites</li>
            
           
       </ul>
       <h4>Styling and CSS</h4>
        <ul>
          
           <li>Styling Text with CSS</li>
            <li>Styling Elements with CSS</li>
            <li>Sources and Search Engines</li>
            <li>RGB Colors and Classes</li>
            <li>Project - Personal Portfolio Website</li>
                    
           
       </ul>
       
       
       
       <p> In addition, I am using a book for reference, <i>New Perspectives on HTML 5 and CSS3, 7th Edition Comprehensive</i> by Patrick Carey, published by Cengage Learning.  There's a lot of information packed into this book, and I think going through the exercises on freeCodeCamp.org has helped me understand the book better.</p>
         
       <header class="mainHeader" id="code-editors">
       Code Editors</header>
       <br>
         <p>I'm working on this project using <a href="https://codepen.io/" target="_blank" style="text-decoration:underline"><i>CodePen</i></a>.  I started this project with the free version of <i>CodePen</i>, then switched to <i>CodePen Pro</i> because I wanted to embed editable pens.  I  like the ability to style the embedded pen, rather than always having the same colors (black, white and gray).  I love the ability to work simultaneously in four windows at once (HTML, CSS, JS ((which I haven't yet started in freeCodeCamp) and the resulting web page that updates instantly as you code.  Very nice!  I also use Visual Studio Code, and in my classes, we use <i>Notepad++</i> and I use <i>Dreamweaver</i> to post student work and update links as the site gets worked and re-worked. We also use online coding platforms on <i>Khan Academy</i> and <i>Code.org</i>    </p>
       <p>
         [It's 12:17 a.m., Eastern Standard Time, and while I would like to continue, I need to get some sleep so I can go to work tomorrow. Love how this is shaping up....]
         
       <p><i>Here's my code so far:</i></p>
       
       <p class="codepen" data-height="337" data-theme-id="35922" data-default-tab="html,result" data-user="andygo52" data-slug-hash="zeGpzR" style="height: 337px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid black; margin: 1em 0; padding: 1em;" data-pen-title="Technical Documentation">
  <span>See the Pen <a href="https://codepen.io/andygo52/pen/zeGpzR/">
  Technical Documentation</a> by Andy Goldstein (<a href="https://codepen.io/andygo52">@andygo52</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>
       
    <p>   [I'm creating this in CodePen and I am working on figuring out how to insert images.  I tried uploading a screenshot of my code to my Google Drive, but I was out of storage, so I upgraded the plan from 15 GB to 100 GB.  But it takes up to 24 hours to take effect.  Plus, I'm not yet 100 percent sure that that will even work.  We'll find out tomorrow.  Anyway, I need to get some sleep.]</p>
       
       <p class="time-date-stamp"><i>time: 12:53 a.m.; date: Thursday, January 24, 2019; place: Boca Raton, FL.</i></p>
       
       
         
       </p>
       
        <header class="mainHeader" id="tribute">
       The Tribute Project</header>
       <br>
  
  <header class="mainHeader" id="HTML">
       HTML</header>
       <br>
  
  <p>To code HTML, start with the basic tags, the "skeleton of a web page."
    
 <p class="codepen" data-height="350" data-theme-id="35922" data-default-tab="html" data-user="andygo52" data-slug-hash="aXdRKP" data-editable="true" style="height: 350px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid black; margin: 1em 0; padding: 1em;" data-pen-title="Basic Tags - Skeleton of a Web Page">
  <span>See the Pen <a href="https://codepen.io/andygo52/pen/aXdRKP/">
  Basic Tags - Skeleton of a Web Page</a> by Andy Goldstein (<a href="https://codepen.io/andygo52">@andygo52</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>
  
    <p class="time-date-stamp"><i>time: 12:20 a.m.; date: Saturday, January 26, 2019; place: Boca Raton, FL.</i></p>
       
  </main>   
            
            
            
            
            
 

          </div>
          
    x------------------------------------x
    
    CSS (needs to be reworked)
    
    .page {
  
  display:grid;
  grid-template-columns: 30vw auto;
  
}

.sidebar {
  position: fixed;
  width: 30vw;
  
}

.main {
  grid-column-start:2;
}

.headerMain {
  height:200px;
  background-color:MidnightBlue;
  color:Turquoise;
  font-size: 50px;
}

.mainBackground {
  background-color:AliceBlue;
  margin-top: -16px;
}

x---------------------------------------------------->
## freeCodeCamp.org - Project Testing


#Technology Stack
1. You can use HTML, JavaScript, and CSS to complete this project. Plain CSS is recommended because that is what the lessons have covered so far and you should get some practice with plain CSS. You can use Bootstrap or SASS if you choose. Additional technologies (just for example jQuery, React, Angular, or Vue) are not recommended for this project, and using them is at your own risk. Other projects will give you a chance to work with different technology stacks like React. We will accept and try to fix all issue reports that use the suggested technology stack for this project. Happy coding!
#Content
1. I can see a <main> element with a corresponding id="main-doc", which contains the page's main content (technical documentation).
2. Within the #main-doc ( <main> ) element, I can see several <section> elements, each with a class of "main-section". There should be a minimum of 5.
3. The first element within each .main-section should be a <header> element which contains text that describes the topic of that section.
4. Each <section> element with the class of "main-section" should also have an id that corresponds with the text of each <header> contained within it. Any spaces should be replaced with underscores (e.g. The <section> that contains the header "Javascript and Java" should have a corresponding id="Javascript_and_Java").
5. The .main-section elements should contain at least 10 <p> elements total (not each).
6. The .main-section elements should contain at least 5 <code> elements total (not each).
There are not at least 5 <code> elements throughout all of the elements with the class of 'main-section' : expected 0 to be at least 5
AssertionError: There are not at least 5 <code> elements throughout all of the elements with the class of 'main-section' : expected 0 to be at least 5
    at s.h (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:262:2072)
    at s.e.(anonymous function) [as least] (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:325:126)
    at Function.n.isAtLeast (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:224:844)
    at r.<anonymous> (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:154:58653)
    at c (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:31608)
    at o.f.run (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:31544)
    at m.runTest (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:37114)
    at https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:37976
    at s (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:36426)
    at https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:36495
7. The .main-section elements should contain at least 5 <li> items total (not each).
There are not at least 5 <li> elements throughout all of the elements with the class of 'main-section' : expected 0 to be at least 5
AssertionError: There are not at least 5 <li> elements throughout all of the elements with the class of 'main-section' : expected 0 to be at least 5
    at s.h (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:262:2072)
    at s.e.(anonymous function) [as least] (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:325:126)
    at Function.n.isAtLeast (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:224:844)
    at r.<anonymous> (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:154:58945)
    at c (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:31608)
    at o.f.run (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:31544)
    at m.runTest (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:37114)
    at https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:37976
    at s (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:36426)
    at https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:36495
8. I can see a <nav> element with a corresponding id="navbar".
9. The navbar element should contain one <header> element which contains text that describes the topic of the technical documentation.
10. Additionally, the navbar should contain link (<a>) elements with the class of "nav-link". There should be one for every element with the class "main-section".
11. The <header> element in the navbar must come before any link (<a>) elements in the navbar.
12. Each element with the class of "nav-link" should contain text that corresponds to the <header> text within each <section> (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world").
Check that these headers have corresponding .nav-link elements and be mindful of case! : HTML, CSS DOCUMENTATION : expected 1 to equal 0
AssertionError: Check that these headers have corresponding .nav-link elements and be mindful of case! : HTML, CSS DOCUMENTATION : expected 1 to equal 0
    at s.l (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:262:1134)
    at s.e.(anonymous function) [as equal] (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:325:126)
    at Function.n.strictEqual (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:224:568)
    at r.<anonymous> (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:154:61597)
    at c (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:31608)
    at o.f.run (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:31544)
    at m.runTest (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:37114)
    at https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:37976
    at s (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:36426)
    at https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:36495
13. When I click on a navbar element, the page should navigate to the corresponding section of the "main-doc" element (e.g. If I click on a "nav-link" element that contains the text "Hello world", the page navigates to a <section> element that has that id and contains the corresponding <header>.
Every .nav-link should have an href value that links it to its corresponding .main-section (e.g. href="#Introduction"). Check that these .main-section ids have corresponding href values : HTML,_CSS_Documentation,About_the_Coder,Code_Editors,The_Tribute_Project : expected 4 to equal 0
AssertionError: Every .nav-link should have an href value that links it to its corresponding .main-section (e.g. href="#Introduction"). Check that these .main-section ids have corresponding href values : HTML,_CSS_Documentation,About_the_Coder,Code_Editors,The_Tribute_Project : expected 4 to equal 0
    at s.l (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:262:1134)
    at s.e.(anonymous function) [as equal] (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:325:126)
    at Function.n.strictEqual (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:224:568)
    at r.<anonymous> (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:154:62523)
    at c (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:31608)
    at o.f.run (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:31544)
    at m.runTest (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:37114)
    at https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:37976
    at s (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:36426)
    at https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:36495
#Layout
1. On regular sized devices (laptops, desktops), the element with id="navbar" should be shown on the left half of the screen. It should always be visible to the user and should remain stationary. You may need to enlarge the viewport or zoom out to ensure the navbar doesn't scroll with the page content.
2. My Technical Documentation page should use at least one media query.
No media queries detected : expected 0 to be above 0
AssertionError: No media queries detected : expected 0 to be above 0
    at s.c (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:262:1704)
    at s.e.(anonymous function) [as above] (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:325:126)
    at Function.n.isAbove (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:224:789)
    at r.<anonymous> (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:154:64129)
    at c (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:31608)
    at o.f.run (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:31544)
    at m.runTest (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:37114)
    at https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:37976
    at s (https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:36426)
    at https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js:159:36495

