# Project information

This is my submission for a project of "Google Front-End Nanodegree Program" at Udacity and it is called "Feed Reader Testing".

In this project a web-based application that reads RSS feeds is given. Also, it includes [Jasmine](http://jasmine.github.io/) and the first test suite.

I complete the project with adding additional test suites which are given as a list by the instructor.


# To open and analyze the project

You can clone this repository or download the .zip file to your computer. Then, click on the index.html file to see the RSS feeds and also [Jasmine](http://jasmine.github.io/) results which are at the bottom of the page.

The specs on this list are written at the feedreader.js file as test suites.

There are 4 test suites with 7 specs / tests in total:
1) RSS Feeds
  <br>
  a) Test to make sure that the allFeeds variable has been defined and that it is not empty (this test is given by default).
  <br>
  b) Test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
  <br>
  c) Test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
2) The Menu
  <br>
  a) Test that ensures the menu element is hidden by default.
  <br>
  b) Test that ensures the menu changes visibility when the menu icon is clicked.
3) Initial Entries
  a) Test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
4) New Feed Selection
  a) Test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.

To run only one test, click one of the specs on the list. After that, you can click "run all" link to run all of these tests together.

Green = Pass
Red = Fail
