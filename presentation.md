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
- worked on 2 products, one released, one unreleased
- Code Center for majority of tenure
  - primarily back end java development
- last ~1.5 years working on new product
  - purely front end javascript development
  - assisted with decisions on libraries to be used
    - backbone.js, backbone-marionette.js, bootstrap, less

<!--//-->
##Embed.ly
- Software Engineer
- Analytics Dashboard
 - primarily front end javascript development
 - occasional back end python development
 - ember.js, foundation, handlebars

<!-- # Project
## Code Center -->

<!--/-->
## Code Center
 - brief description of functionality
  - component request/approval process
  - encourage identify 3rd party dependencies at start of project

<!--//-->
 - describe ui tech changes over time
  - YUI, spring mvc, in-house built framework on gwt

<!--//-->
 - description of initial responsibilities
   - initially on backend (e.g. spring, ibatis, hibernate, postgresql)
   - eventually started helping with UI work through spring mvc
   - after framework developed, gradually shifted to primarily UI
    - maintain/extend framework

<!--/-->
## Problem Background
 - describe framework and original purpose
  - few people that had signficant js knowledge
  - leverage existing java knowledge
  - provide very rigid, very predictable html for QA

<!--//-->
 - brief description of typical customer usage (e.g. requests, workflow)
  - design approval workflow
  - developers request use of software components (e.g. OSS, licensed)
  - components approved/disapproved based on outcome of workflow

<!--//-->
 - brief description of workflow functionality
  - each stage of workflow could require information from requester
  - the generated form fields would often be dynamically shown/hidden
  - fields to be shown based on current form data determined by back end

<!--/-->
## The Problem
 - identify problem that was found (i.e. slow performance on IE7)
  - typical page load
   - 1-3 seconds on chrome/firefox
   - 5-15 seconds on IE
  - wizard page load
   - 3-5 seconds on chrome/firefox
   - 10-30 seconds on IE8/IE9
   - minutes on IE7

<!--/-->
## The Process
 - discuss usage of dynatrace js profiler
  - highlight slow IE performance hampered using the profiler
  - very little discovered from profiler

<!--//-->
 - discuss general solution that worked
  - potential risks
  - known challenges (e.g. binding to gwt rpc to get/update data)
  - discovered challenges (e.g. generated html being QA compliant)

<!--//-->
 - performance improvements
  - < 1 second on chrome/firefox
  - 1-3 seconds on IE8/IE9
  - ~5 seconds on IE7
  - potentially contributed to company move to a pure JS UI

<!--/-->
# Thanks! <!-- .element: style="color: #268bd2;" -->
### for your time and consideration
