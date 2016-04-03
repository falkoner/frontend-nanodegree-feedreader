# Udacity Front-End Nanodegree Project 6: Feed Reader Testing with JasmineJS

Hands on project to practice Java Script testing using Jasmine framework. Includes elements of Test Driven Development.

## Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.

## Initial instructions for project completion

1. Take the JavaScript Testing course
2. Download the required project assets.
3. Review the functionality of the application within your browser.
4. Explore the application's HTML (./index.html), CSS (./css/style.css) and JavaScript (./js/app.js) to gain an understanding of how it works.
5. Explore the Jasmine spec file in ./jasmine/spec/feedreader.js and review the Jasmine documentation.
6. Edit the allFeeds variable in ./js/app.js to make the provided test fail and see how Jasmine visualizes this failure in your application.
7. Return the allFeeds variable to a passing state.
8. Write a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
9. Write a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
10. Write a new test suite named "The menu".
11. Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
12. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
13. Write a test suite named "Initial Entries".
14. Write a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
15. Write a test suite named "New Feed Selection".
16. Write a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.
17. No test should be dependent on the results of another.
18. Callbacks should be used to ensure that feeds are loaded before they are tested.
19. Implement error handling for undefined variables and out-of-bound array access.
20. When complete - all of your tests should pass.

## How to run

Open index.html in a browser.
