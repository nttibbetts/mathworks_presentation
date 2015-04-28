<!-- Slide -->
# Introduction

<!-- Slide -->
## Education
 - WPI 2003-2007
  - CS Major
  - MQP on affects of server/client location on game ping

## Experience

<!-- Slide -->
 - Black Duck Software
  - Software Engineer
  - Code Center for majority of tenure
   - primarily back end java development
  - last ~1.5 years working on new product
   - purely front end javascript development
   - assisted with decisions on libraries to be used
    - backbone.js, backbone-marionette.js, bootstrap, less

<!-- Slide -->
 - Embed.ly
  - Software Engineer
  - Analytics Dashboard
   - primarily front end javascript development
   - occasional back end python development
   - ember.js, foundation, handlebars

# Project

## Code Center

<!-- Slide -->
 - brief description of functionality
  - component request/approval process
  - encourage identify 3rd party dependencies at start of project

<!-- Slide -->
 - describe ui tech changes over time
  - YUI, spring mvc, in-house built framework on gwt

<!-- Slide -->
 - description of initial responsibilities
   - initially on backend (e.g. spring, ibatis, hibernate, postgresql)
   - eventually started helping with UI work through spring mvc
   - after framework developed, gradually shifted to primarily UI
    - maintain/extend framework

### Framework JS Performance in IE7

<!-- Slide -->
 - describe framework and original purpose
  - few people that had signficant js knowledge
  - leverage existing java knowledge
  - provide very rigid, very predictable html for QA

<!-- Slide -->
 - brief description of typical customer usage (e.g. requests, workflow)
  - design approval workflow
  - developers request use of software components (e.g. OSS, licensed)
  - components approved/disapproved based on outcome of workflow

<!-- Slide -->
 - brief description of workflow functionality
  - each stage of workflow could require information from requester
  - the generated form fields would often be dynamically shown/hidden
  - fields to be shown based on current form data determined by back end

<!-- Slide -->
 - identify problem that was found (i.e. slow performance on IE7)
  - typical page load
   - 1-3 seconds on chrome/firefox
   - 5-15 seconds on IE
  - wizard page load
   - 3-5 seconds on chrome/firefox
   - 10-30 seconds on IE8/IE9
   - minutes on IE7

<!-- Slide -->
 - discuss usage of dynatrace js profiler
  - highlight slow IE performance hampered using the profiler
  - very little discovered from profiler

<!-- Slide -->
 - discuss general solution that worked
  - potential risks
  - known challenges (e.g. binding to gwt rpc to get/update data)
  - discovered challenges (e.g. generated html being QA compliant)

<!-- Slide -->
 - performance improvements
  - < 1 second on chrome/firefox
  - 1-3 seconds on IE8/IE9
  - ~5 seconds on IE7
  - potentially contributed to company move to a pure JS UI
