# Conversion of client site to plain HTML5 and CSS3

# Intro

Update of a simple website built over 10 years ago for a Brazilian accounting firm:

* Content was kept the same, coded in a more semantic HTML5
* Style was kept the same, just coded into a responsive single page layout in plain CSS3.

Before:
![Old](/dev/readme-old.png)

After:
![New in mobile](/dev/readme-new.png)

## Stack

HTML5/CSS3

## Install, demo and tests

Demo and tests: open index.html in browser or see http://immaginareservice.com.br/app/seadecon

## Comments

Notes below are basic obvious, just kept here as a personal reminder from small today's rare coding in simple and plain HSML/CSS with no javascript or any framework.

* HTML coded as semantic as possible, as favored by HTML5 docs but not highly found a priority in actual projects and frameworks
* Flexbox container fully implemented in header > nav
* Id for navigation through scrolling set as a div.anchor since put the id in the whole section created problems for the "margin-top: -heigntHeader/padding-top: heigntHeader" used to ajust fixed header.