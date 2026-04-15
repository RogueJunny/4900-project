# Brooklyn College CIS Connect Developer Guide
This is a guide to help any future students who decide to continue this website

## Table of contents
* [A brief introduction](#a-brief-introduction)
* [Getting Started](#getting-started)
* [Themes](#themes)
* [Editing the website](#editing-the-website)
* [CSS](#css)
* [Plugins](#plugins)

## A brief introduction

This project started as a continuation of a [previous student's work last semester](https://github.com/suraiyapm/Brooklyn-College-CIS-Connect).
A week or so into this semester, we decided that we would rather create a new website from scratch.

## Getting Started
> Learn the basics of CUNY Academic Commons

CUNY Academic commons allows CUNY students to make their own websites with WordPress.
Here's some official resources that you can look at before getting started.

[BC Knowledge Employees Guide](https://employees.brooklyn.edu/base/cuny-academic-commons/)

[CUNY Academic Commons Guide](https://help.commons.gc.cuny.edu/getting-started-with-the-commons/)

## Themes
> You have to pick a theme when you first make your website.

A theme in WordPress is a set of .php files that dictate what your website will look like before you do any further editing. We chose the "Twenty Twenty-Four" theme, since it looked modern and had the features we needed. Each page will have various default colors and themes based on what theme you chose. 

### Starter content

Whenever you make a new page, you will have the option to pick a preset pattern. For example, you can set up a "home" page or a "coming soon" page with a single click. The problem you'll come across very quickly is that these default pages never match the aesthetic of your website. You would either have to modify these pages heavily, or just create your page from scratch using the blocks you want, which is what we did.

## Editing the website
> You set up your theme, now how do you add content to your website?

For our project, we used the block editor exclusively. You may have seen something similar used elsewhere. Basically, there are blocks with different functions (Paragraph, Image, Spacer, etc.), and you add them together in a hierarchy to create your website. You could use the classic editor and write the website in HTML, but that's too much work for no benefit.

Each content block has a "Settings" & "Styles" section that you can change.

### Settings

There is only one section by default: Advanced. In it, you'll find two text boxes:

HTML ANCHOR - gives the block a name that turns it into a link to that section of the page
ADDITIONAL CSS CLASS(ES) - read more in the CSS section

### Styles

Here you can change different properties of the content block, including color and typography. There are three dots to the right of each tab that lets you see more style options, including font and font size, which we used a lot.

### Fonts

You can import .otf files to your website to add new fonts. Here's how to import them:

`Customize > Use Site Editor > Styles > Typography > Click any font > Upload`

## CSS
> You can add custom CSS to add unique features to your website.

[Coming Soon]

## Plugins
> You can use the included plugins to add special features to your website.

CUNY Academic Commons has over 200 plugins available for you to use on your website.

The plugins we've used so far include:


* [Advanced Excerpt](http://wordpress.org/plugins/advanced-excerpt/)
* [Better Font Awesome](http://wordpress.org/plugins/better-font-awesome)
* Blog as PDF
* [Contact Form 7](https://contactform7.com/)
* [Popup Maker](https://wppopupmaker.com/?utm_campaign=plugin-info&utm_source=plugin-header&utm_medium=plugin-uri)
* [The Events Calendar](https://evnt.is/1x) THIS ONE WON'T WORK AUTOMATICALLY, READ MORE BELOW
* ~~[WP Hide Post](http://scriptburn.com/wp-hide-post)~~ We didn't end up needing this one, but it works fine.
* WP Multisite Request Membership
* ~~[Yet Another Related Posts Plugin (YARPP)](https://yarpp.com/)~~ This one cause some problems, so we removed it
* [Yoast Duplicate Post](https://yoast.com/wordpress/plugins/duplicate-post/)

To add more, send an email to commonshelpsite@gmail.com with the following information

* The name of the plugin
* The link to the plugin
* When the plugin was most recently updated
* The number of active installations
* The URL for your website

### A note about The Events Calendar

This plugin doesn't work on its own, and it took me (Sammy) HOURS to find out what the problem was. Basically, you'll have to email the CUNY Academic Commons support team (commonshelpsite@gmail.com) and tell them to run some code on their end to get the calendar database running. Many other students have had this problem apparently, as seen in [this forum thread about the issue](https://redmine.gc.cuny.edu/issues/20863).
