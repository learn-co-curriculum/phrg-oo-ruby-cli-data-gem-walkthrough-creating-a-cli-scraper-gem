## Overview

This video lessons walks through the process of building a CLI Gem with a focus on classes that collaborate. 

## Objectives

1. Describe and map out our classes
2. Create our models
3. Create our Scraper
4. Make our classes collaborate
5. Scrape our data
6. Implement app functionality


## Video

<iframe width="100%" height="720" src="https://www.youtube.com/embed/Y5X6NRQi0bU?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

[MP4](Find learn s3 source?)


## Summary

* Explain objects collaborate
* Describe our classes/objects domain
 * map out domain
 * decouple classes
* Create our newsletter and article models
 * define our objects attributes
* Set up gem environment
 * create rake console task
 * create dummy data in console 
 * make objects collaborate!
* Enforce type for newsletters articles array
 * raise error in Array class
 * enforce within newsletter class itself
 * freezing arrays
 * create custom error to raise for invalid type 
 * statically typed languages
 * is_a? method
 * argument and variable names
* Add scraper class
 * describe desired functionality - set expectations
 * map out our specs for the Scraper class
 * set up initialize method
 * add gem dependencies
 * test in console
 * add scraping methods to scrape data and build objects
* Scrape through CSS selectors
 * oh no... tables!!!!
 * use xpath?!
 * use search method
 * use `gsub` for formatting
* scrape_articles method
 * should scraper know about newsletter and articles, or newsletter know how to scrape internal data?
* Find the css selectors to scrape the articles
* Create iterator for articles
 * find selectors to grab individual attributes from table
 * create article instances with these attributes
* Our objects are collaborating!
* Create executable file
 * add functionality to run the application
* Abstract application running logic to a controller class
 * add user interaction
* Add functionality to open article url in browser based on user selection
* Program in the place that's most immediate to you
 * make it work, then make it abstract and clean.
 * make sure it works post refactor!
* Take it one object at a time 
 * make 'em then make 'em interact then make more!
 * power of objects come from their collaboration
 * dominoes!
 * Onside out development vs outside in
   * restaurant analogy - outside in
* Models views controllers
* Push to github!
* Github's hub gem

## Code

[Application Source Code](https://github.com/aviflombaum/rubyweekly-cli)
<p class='util--hide'>View <a href='https://learn.co/lessons/oo-ruby-cli-data-gem-walkthrough-creating-a-cli-scraper-gem'>OO Ruby CLI Data Gem Walkthrough: Creating a CLI Scraper Gem </a> on Learn.co and start learning to code for free.</p>
