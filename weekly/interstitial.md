# Semester Interstitial 

<a id="overview" />

## I. Overview

1) What are we covering in the next 5 weeks (including finals week, because we don't have a final) ?
    - Up to now in the course, we have worked with the following media types:
      - a state-driven procedural drawing API (canvas)
      - bitmapped data and Photoshop-style effects (obtained via `canvas.getImageData()`)
      - audio - frequency and waveform data, as well as the applying of various effects such as bass, treble, and distortion
    - Moving forward through the rest of the course, we will work with:
      - A) *unstructured text* - and see how to catagorize and manipulate it
      - B) *structured text* - we will see how to create our own PHP-driven web API that returns data in the JSON format
      - C) *web APIs* such as Google Maps and MapBox
      - D) an [MVVM](https://en.wikipedia.org/wiki/Model–view–viewmodel) framework - [Vue.js](https://vuejs.org) - MVVM stands for "Model View View-Model" (kind of a super-powered MVC)
        - BTW: this MVVM architectural pattern is what the [React](https://reactjs.org) and [Angular](https://angular.io) frameworks use - and there is currently a big demand for developers who understand how to use these frameworks 
    - understanding these 4 remaining *units* of content is crucial to your success on Project 3
    - some of the content from previous semesters - using the "cloud storage" Firebase API for example - has been made optional and extra credit - see the myCourses dropboxes, and the links at the bottom of this page 

<hr>

2) Project 3 - Web App of Awesomeness
    - the requirements are here —> [Project 3](../projects/project-3.md)
    - we will show some example of completed projects soon
    - as before, for the presentation requirement, a 1 to 2-minute “demo reel” of the completed project will be required
    - no partners ARE allowed on this one unless pre-approved - mail me your (ambitious & "highly scoped") proposal
 
 
3) Project 3 Requirements:
    - This course is about the *intersection* between programming and multiple types of *media*
      - Project 1 was about procedural drawing (canvas) and "creative coding" that explored a theme
      - Project 2 worked with canvas, bitmapped images, and analyzing/manipulating audio 
      - Since the "break", we have worked with unstructured text (Word Cloud, Maddening Libs), "tagged" text (RiTa.js), text-based web services, and a mapping web service
      - Project 3, minimally:
        - is a mashup of two web APIs
        - but it could also draw on anything we've covered this semester - you have a lot of freedom - this IS a creative coding class - so if you have a cool idea - ASK us about it 
        - the Project 3 requirements are here --> https://github.com/tonethar/IGME-330-Spring-2020/blob/master/projects/project-3.md


<hr><hr>

<a id="outline" />

***IMPORTANT: All assignment due dates listed below are tentative, and are provided in order to communicate the expected flow of topics for the remainder of the semester. See myCourses for exact assignment particulars and due dates. Everything below is subject to revision.***

## II. Outline

[I. Week 10 - Computational Literature (Mon 10/25-Sun 11/01)](#week10)

[II. Week 11 - PHP - Build your own web service (Mon 3/30-Sun 4/5)](#week11)

[III. Week 12 - XHR Review & Maps API (Mon 4/6-Sun 4/12)](#week12)

[IV. Week 13 - Finish Map Unit & Vue.js (Mon 4/13-Sun 4/19)](#week13)

[V. Week 14 - Work on Project 3 (Mon 4/20-Sun 4/26)](#week14)

[VI. Extra Credit](#extra-credit)


<hr>

<a id="week10">

## I. Week 10 -  Computational Literature (Mon 10/25-Sun 11/01)
### Lecture Notes
- [Week 10A - Constrained Writing & Simple Text Analysis](week-10A-NEW.md)
- [Week 10B - Computational Literature & Context-free grammars with Rita.js](week-10B-NEW.md)

### Homework
- [HW - Palindrome Detector (Due: 3/26)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/HW-palindrome-detector.md)
- [HW - Word Cloud (Due: 3/29)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/HW-word-cloud.md)
- [HW - Maddening Libs (Due: 4/1)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/text-4.md#III)
- [HW - Ill-favored Coast (Due: 4/1)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/text-5.md#V)

### All Videos
- [Text-1: Six ways to load text (19:04)](https://video.rit.edu/Watch/text-1-six-ways-to-load-text)
- [Text-1: Palindrome HW (21:57)](https://video.rit.edu/Watch/text-1-palindrome-HW)
- [Text-3: Word Counter - part A (17:24)](https://video.rit.edu/Watch/text-3-word-counter-part-A)
- [Text-3: Word Counter - part B (06:57)](https://video.rit.edu/Watch/text-3-word-counter-part-B)
- [Text-4: Rita-1 - Intro to Rita (12:08)](https://video.rit.edu/Watch/rita-js-1-intro)
- [Text-4: Rita-2 - Getting parts-of-speech (06:39)](https://video.rit.edu/Watch/rita-js-2-getting-parts-of-speech)
- [Text-4: Rita-3 - Proper noun replacer (07:57)](https://video.rit.edu/Watch/rita-js-3-proper-noun-replacer)
- [Text-5: Rita-4 - Context-free Grammars (12:15)](https://video.rit.edu/Watch/rita-js-4-context-free-grammars)

<hr>

<a id="week11">

## II. Week 11 - PHP - Build your own web service (Mon 11/02-Sun 11/8)
### Lecture Notes
- [Week 11A - What is a Web Service? & PHP Intro](week-11A-NEW.md)
- [Week 11B - Creating a PHP Web Service & passing parameters to it](week-11B-NEW.md)

### Homework
- [HW - Make your own PHP Web Service - Parts I & II (Due: 4/4)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/HW-php-web-service-1.md)
- [HW - Make your own PHP Web Service - Parts III & IV (Due: 4/6)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/HW-php-web-service-3.md)

### All Videos
- [PHP and Web Services-1: Introduction (14:22)](https://video.rit.edu/Watch/php-and-web-services-1-introduction)
- [PHP and Web Services-2: Foundations - Intro to PHP (14:52)](https://video.rit.edu/Watch/php-and-web-services-2-foundations-intro-to-php)
- [PHP and Web Services-2: Foundations - PHP Variables and Data Types (15:25)](https://video.rit.edu/Watch/php-and-web-services-2-php-variables-and-data-types)
- [PHP and Web Services-2: Foundations - PHP Arrays (13:38)](https://video.rit.edu/Watch/php-and-web-services-2-php-arrays)
- [PHP and Web Services-2: Foundations - php.ini file (05:13)](https://video.rit.edu/Watch/php-and-web-services-2-php-ini-file)
- [PHP and Web Services-3: Foundations - coding get-random-joke.php (15:08)](https://video.rit.edu/Watch/php-and-web-services-3-coding-get-random-joke)
- [PHP and Web Services-4: Foundations - coding get-jokes.php (07:35)](https://video.rit.edu/Watch/php-and-web-services-4-coding-get-jokes)

<hr>

<a id="week12">

## III. Week 12 - XHR Review & Maps API (Mon 11/9-Sun 11/15)
### Lecture Notes
- [Week 12A - Week 12A - Client-side web applications & PHP Proxy Server](week-12A-NEW.md)
- [Week 12B - Mapbox API](week-12B-NEW.md)

### Homework

- [PHP Web Service Part V - creating a proxy server#submission (Due: 4/9)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/HW-php-web-service-5.md#submission)
- [HW - Improved Giphy Web Service App (Due: 4/12)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/HW-improved-gif-finder.md)
- [HW - Mapbox I - *Intro* (Due:  4/14)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/HW-mapbox-1.md)
- [HW - Mapbox II - *RIT Coffee Map* (Due:  4/16)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/HW-mapbox-2.md)
- [EXTRA CREDIT - HW - Mapbox III - *Virus Map* (Due: 4/20)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/HW-mapbox-3.md)


### All Videos
- [PHP and Web Services-5: Building a PHP proxy server I. (11:21)](https://video.rit.edu/Watch/php-proxy-server-1)
- [PHP and Web Services-5: Building a PHP proxy server II. (12:40)](https://video.rit.edu/Watch/php-proxy-server-2)

<hr>

<a id="week13">

## IV. Week 13 - MVVM (Mon 11/16-Sun 11/22)

- **Note that Vue.js and MVVM and now *optional* for Project 3**

### Lecture Notes
- [Week 13A - Intro to MVVM & Vue.js ](week-13A-NEW.md)
- [Week 13B - Vue.js Components](week-13B-NEW.md)

### Homework
- [HW - Vue.js Part I - Dynamic List (Due 5/5)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/vue-1.md)
- [HW - Vue.js Part II - Ajax App (Due 5/5)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/vue-2.md)
- [HW - Vue.js Part III - Simple Component (Due 5/5)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/vue-3.md)
- [HW - Vue.js Part IV - Nested Component (Due 5/5)](https://github.com/tonethar/IGME-330-Master/blob/master/notes/vue-4.md)

### All Videos
- [Vue.js - Part I - Intro - (10:47)](https://video.rit.edu/Watch/Rs48BbWz)
- [Vue.js - Part II - Intro - (6:49)](https://video.rit.edu/Watch/Qt7o3LZg)
- [Vue.js - Part III - Data Binding - (11:26)](https://video.rit.edu/Watch/y7SHt9i5)
- [Vue.js - Part IV - v-for Directive - (11:51)](https://video.rit.edu/Watch/f3CAa58R)
- [Vue.js - Part V - Better Button - (8:07)](https://video.rit.edu/Watch/s3F2Jqy9)
- [Vue.js - Part VI - Bootstrap Vue - (12:20)](https://video.rit.edu/Watch/Nk2m5M3X)
- [More Vue.js - Part I - Vue & Ajax - (26:29)](https://video.rit.edu/Watch/Ao8n6ZFf)
- [More Vue.js - Part II - Simple Vue Components - (15:17)](https://video.rit.edu/Watch/Jo2k6XDz)

<hr>

<a id="week14">

## V. Week 14 - Work on Project 3 (Mon 11/23-Tues 11/24)
- [Week 14A - ](week-14A-NEW.md)
- [Week 14B - ](week-14B-NEW.md)

### Homework


### All Videos
- These are a demo of how to build a "Yelp" clone with Vue.js:
  - [Yip-1: Setting up a Yelp clone with Vue (10:14)](https://video.rit.edu/Watch/330-yip-part-1)
  - [Yip-2: Adding a map, converting the app to ES6 modules (15:29)](https://video.rit.edu/Watch/330-yip-part-2)
  - [Yip-3: Downloading Yelp data, creating a POI model class, displaying data (15:38)](https://video.rit.edu/Watch/330-yip-part-3)
  - [Yip-4: Moving POI to an external module, coding `createPOIfromYelpBusiness()` (08:47)](https://video.rit.edu/Watch/330-yip-part-4)
  - [Yip-5: Moving map to an external module, adding markers and popups to the map (19:06)](https://video.rit.edu/Watch/330-yip-part-5)
  - [Yip-6: minor main.js refactor, styling markers with CSS (06:31)](https://video.rit.edu/Watch/330-yip-part-6)
  - [Yip-7: import Bootstrap Vue, add &lt;jumbrotron>, &lt;input> and &lt;button> (09:21)](https://video.rit.edu/Watch/330-yip-part-7)
  - [Yip-8: encapsulate &lt;jumbrotron>, &lt;input> and &lt;button> into a component named &lt;yip-header> (12:01)](https://video.rit.edu/Watch/330-yip-part-8) - See how to export 2 (or more) components from the same ES6 module file. Use `$emit()` to send a custom event from component to main Vue interface. 
  - [Yip-9: add `v-model` binding to <yip-header> (10:18)](https://video.rit.edu/Watch/330-yip-part-9)


<hr>

<a id="extra-credit">

## VI. Extra Credit (all due ??/??)
- Firebase (Cloud Storage) - see myCourses dropboxes for details:
  - [1 - Intro to Firebase - the Realtime Database](https://github.com/tonethar/IGME-330-Master/blob/master/notes/firebase-1.md)
  - [2 - Firebase Highscore App](https://github.com/tonethar/IGME-330-Master/blob/master/notes/firebase-2.md)
  - [3 - Firebase Highscore Viewer](https://github.com/tonethar/IGME-330-Master/blob/master/notes/firebase-3.md) - Worth 2 HW Assignments
  - [4 - Firebase "Draw & Share" App](https://github.com/tonethar/IGME-330-Master/blob/master/notes/firebase-4.md) - Worth 2 HW Assignments
- Node.js:
  - [HW - Node Web Service Command-line tool](https://github.com/tonethar/IGME-330-Master/blob/master/notes/node-and-web-services-1.md)
  - [HW - Transpiling from ES6 to ES5 with Node.js](https://github.com/tonethar/IGME-330-Master/blob/master/notes/node-and-transpiling.md)
