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

Notes below are very basic, just kept here as reference from today rare coding in simple and plain HSML/CSS, with no javascript or any framework.

* HTML coded as semantic as possible, as favored by HTML5 docs but not highly found a priority in actual projects and frameworks
* Flexbox container in header > nav
* Navigation through scrolling. Id set in div.anchor since in section.anchor was createing problems for the "margin-top: -heigntHeader/padding-top: heigntHeader" use to ajust fixed header.