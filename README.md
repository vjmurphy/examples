# Code Examples from Various Projects

## Interactions

Most of this site is either my work, or based on my work for the 2018/2019 redesign of the site. Though I was the sole developer, we brought in a few freelancers to help split up the work. 

* https://www.interactions.com/

There are still things we are implementing to help with SEO and performance. We used LESS on the older site, and switched over to SCSS on the newer one. I set up and managed the Bitbucket repository for the site and documented the "rules of engagement" for other developers to give them an idea how the site worked. We set up a decent flow for requests, as well. 

The site is built using WordPress, with a custom theme and a few custom plugins (and a mess of other plugins). 

## Contant Contact

Much of the work I did on Constant Contact is still there: we used a Bootstrap-influenced system, but, over time, it because more customized. These pages use a page-building system created in Angular to enable people to rapidly create new pages. It would pull from templates created by the front-end team to assemble the pages.

We used Jira to manage tickets, and used Kanban as our agile methodology (which worked extremely well with the web work we did). 

### Constant Contact About Site
* https://about.constantcontact.com/company

### Constant Contact Brand Site
* https://brand.constantcontact.com

## HTML/CSS/JS Samples

### HTML

This is a responsive header/footer combination that we used on third-party or secondary sites. Since they had to work on sites that we had no idea how they'd be coded, we pretty aggressively id'ed things and tried to make it self-contained. I always hate using !important, but sometimes you have to do what you have to do. 

* https://static.ctctcdn.com/lp/external-sites/v1/ctct-header-footer.html
* https://static.ctctcdn.com/lp/external-sites/v1/css/ctct-header-footer.css

### CSS

We were working on refactoring the CSS when I left, but most of it is the same as it was. We used LESS on the backend to generate the front-end files. They tended to be more bloated than we'd like. We were trying to create something that would handle the design team's creativity.

* https://www.constantcontact.com/site/next/css/ctct-website-base.css

### Javascript

Again, because of our collaborative environment, we'd adjust and rewrite each other's code along the way. These two files contain some of my original javascript.

* https://www.constantcontact.com/site/common/_script/external_sites/navigation.js
* https://www.constantcontact.com/site/common/_script/modules/cc-utils.js

## Performance

Much of my work was related to performance and site health; for example, I implemented Google's mod_pagespeed module and helped to automate image optimization. While invisible, they helped with getting the site to download in less than 3 seconds, generally.

I set up various Google Analytics and Omniture reports for improving site speed, as well as for reporting on 404 and 500 errors, then using Splunk to delve into those errors more closely. Due to my efforts, Constant Contact had very few 404s on the site, and any server errors were prioritized and fixed.

I also created the CSS style guide for the site which we enforced using various Grunt tasks and code reviews.

## SEO, Analytics and Tag Management

At both Constant Contact and Interactions, I worked on getting a sane SEO process in place and managed tickets related to adding new content and keywords along with the copy writers. I set up analytics using Google Analytics and managed third party tags via Google Tag Manager and Tealium. At Constant Contact, I also used Adobe's analytics product to set up various alerts on 404 and 500 errors on the site. 
