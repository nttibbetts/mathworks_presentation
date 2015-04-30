# Nathan Tibbetts <!-- .element: style="color: #fdf6e3;" -->
## Front End Developer
`nttibbetts@gmail.com | github.com/nttibbetts`

<!--/-->
# Education
## Worcester Polytechnic Institute
- Bachelor of Science in Computer Science
- MQP Project
  - An Analysis of Playability and Fairness for Group Game Server Selection
  - focused on average ping of clients from different locations as a means of determining the ideal game server for a group of players to play

<!--/-->
# Experience
## Black Duck Software
- Software Engineer
- worked mostly on Code Center
  - primarily back end java development
- last ~1.5 years working on new product
  - purely front end javascript development
  - assisted with decisions on libraries to be used
    - backbone.js, backbone-marionette.js, bootstrap, less

<!--//-->
# Experience
## Embed.ly
- Software Engineer
- Analytics Dashboard
  - primarily front end javascript development
  - occasional back end python development
  - ember.js, foundation, handlebars

<!--/-->
## Code Center Overview
- component request and approval process
- encourage identification of 3rd party dependencies at start of project
- provides a bill of materials for project/application

<!--//-->
## Code Center Architecture
![Code Center Architecture][cc_arch]
[cc_arch]: img/cc_architecture.svg "Code Center Architecture"

<!--//-->
## Code Center Responsibilities
- initially worked on backend using spring, ibatis, hibernate, postgresql
- eventually started helping with UI work through spring mvc
- after UI framework developed, gradually shifted to primarily UI
  - develop new views
  - modify existing ones
  - maintain/extend framework

<!--/-->
## Performance Problem
- Typical page load
  - 1-3 seconds on chrome/firefox
  - 5-15 seconds on IE
- Request UI page load <!-- .element: class="fragment" -->
  - 3-5 seconds on chrome/firefox
  - 10-30 seconds on IE8/IE9
  - minutes on IE7

<!--/-->
# Problem Background
## Typical Usage
- design approval workflow
  - determine stages and what information is needed
  - layout the flow of the stages
- developers request use of software components (e.g. OSS, licensed)
  - provide information as defined in workflow
- components approved/disapproved based on outcome of workflow

<!--//-->
# Problem Background
## Request Workflow UI
- each stage of workflow could require information from requester
- the generated form fields would often be dynamically shown/hidden
- fields to be shown based on current form data determined by back end

<!--//-->
# Problem Background
## Request Form Example
![Starting Request Form Wireframe][start_frame] <!-- .element: style="vertical-align: top;" -->
![Changed Request Form Wireframe][changed_frame] <!-- .element: class="fragment" -->
[start_frame]: img/starting_request_form.svg "Starting Request Form Wireframe"
[changed_frame]: img/changed_request_form.svg "Changed Request Form Wireframe"

<!--/-->
## Process
- Used DynaTrace AJAX Edition to profile javascript
  - slow IE performance hampered using the profiler
  - very little discovered from profiler
- Manual static analysis on gwt java code
  - primarily focused on the view rendering lifecycle

<!--//-->
## Solution
- Rewrite this view without the UI framework
  - really no other options that didn't involve replacing the UI framework completely
- Potential Risks <!-- .element: class="fragment" -->
  - no guarantee that it would be significantly faster
  - never done on any other view, so limited time estimate
- Known Challenges <!-- .element: class="fragment" -->
  - making GWT RPC calls to get and update data
  - binding to framework events
- Discovered Challenges <!-- .element: class="fragment" -->
  - problems making generated html comply with QA needs
  - various idiosyncrasies of IE7s javascript implementation

<!--//-->
## Outcome
- Significant decrease in page load time <!-- .element: class="fragment" -->
  - < 1 second on chrome/firefox
  - 1-3 seconds on IE8/IE9
  - ~5 seconds on IE7
- Side effects <!-- .element: class="fragment" -->
  - page interaction much smoother
  - form updated quicker

<!--/-->
# Why Nathan?
- High attention to detail <!-- .element: class="fragment roll-in" -->
- Enthusiastic <!-- .element: class="fragment roll-in" -->
- Eager to learn <!-- .element: class="fragment roll-in" -->
- Great team player <!-- .element: class="fragment roll-in" -->
- Up to date with latest js libraries <!-- .element: class="fragment roll-in" -->

<!--//-->
# Why MathWorks?
- Potential for giant impact on large userbase <!-- .element: class="fragment roll-in" -->
- Opportunities to learn new technologies <!-- .element: class="fragment roll-in" -->
- Plenty of room to grow <!-- .element: class="fragment roll-in" -->
- Great work environment for developers <!-- .element: class="fragment roll-in" -->
- Stable and growing company <!-- .element: class="fragment roll-in" -->

<!--/-->
<!-- .slide: style="height: 100%;" data-autoslide="3000" -->

# Thanks! <!-- .element: class="thanks" -->
Liked the presentation? The code is available at github.com/nttibbetts/mathworks_presentation <!-- .element: class="fragment pull-down roll-in" -->
