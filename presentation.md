# Nathan Tibbetts <!-- .element: style="color: #fdf6e3;" -->
## Front End Developer

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
- component request/approval process
- encourage identify 3rd party dependencies at start of project
- provided a bill of materials for project/application

<!--//-->
Insert Tech Stack Diagram

<!--//-->
## Code Center Responsibilities
- initially on backend (e.g. spring, ibatis, hibernate, postgresql)
- eventually started helping with UI work through spring mvc
- after framework developed, gradually shifted to primarily UI
  - maintain/extend framework

<!--/-->
# Problem Background
## UI Framework
 - describe framework and original purpose
  - few people that had signficant js knowledge
  - leverage existing java knowledge
  - provide very rigid, very predictable html for QA

<!--//-->
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
Insert Initial Request Form Wireframe

<!--//-->
Insert Changed Request Form Wireframe

<!--/-->
## Performance Problem
- Typical page load
  - 1-3 seconds on chrome/firefox
  - 5-15 seconds on IE
- Request UI page load
  - 3-5 seconds on chrome/firefox
  - 10-30 seconds on IE8/IE9
  - minutes on IE7

<!--/-->
## Process
- Used DynaTrace AJAX Edition to profile javascript
  - slow IE performance hampered using the profiler
  - very little discovered from profiler

<!--//-->
## Solution
- Rewrite this UI without the framework
  - potential risks
  - known challenges (e.g. binding to gwt rpc to get/update data)
  - discovered challenges (e.g. generated html being QA compliant)

<!--//-->
## Outcome
- Significant decrease in page load time
  - < 1 second on chrome/firefox
  - 1-3 seconds on IE8/IE9
  - ~5 seconds on IE7
- Side effects
  - page interaction much smoother
  - form updated quicker

<!--/-->
# Thanks! <!-- .element: style="color: #268bd2;" -->
### for your time and consideration
