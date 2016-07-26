# Code Examples from Various Projects

## Example Sites

### Constant Contact Marketing Site
* https://www.constantcontact.com/index.jsp
* https://www.constantcontact.com/email-marketing
* https://www.constantcontact.com/email-templates
* https://www.constantcontact.com/partners/solution-providers
* http://www.constantcontact.com/legal/security
* http://www.constantcontact.com/legal/report-vulnerability

### Constant Contact About Site
* http://about.constantcontact.com/company

## HTML/CSS/JS Samples

### HTML

I've added some short HTML samples of a global header and footer we used across third party sites (header.html and footer.html in this repo):

* https://jobs.constantcontact.com/
* https://community.constantcontact.com/

As well as previous iterations of the blogs site and the now defunct investor relations site.

Much of the work on Constant Contact is still there: we used a Bootstrap-influenced system, but, over time, it because more customized.

* https://www.constantcontact.com/index.jsp?ModPagespeed=off (turning off mod_pagespeed makes it easier to read the code)

### CSS

We were working on refactoring the CSS when I left, but most of it is the same as it was. We used LESS on the backend to generate the front-end files. They tended to be more bloated than we'd like. We were trying to create something that would handle the design team's ever changing

* https://www.constantcontact.com/site/next/css/ctct-website-base.css

### Javascript

Again, because of our collaborative environment, we'd adjust and rewrite each other's code along the way. These two files contain some of my original javascript.

* https://www.constantcontact.com/site/common/_script/external_sites/navigation.js
* https://www.constantcontact.com/site/common/_script/modules/cc-utils.js

## Performance

Much of my work was related to performance and site health; for example, I implemented Google's mod_pagespeed module and helped to automate image optimization. While invisible, they helped with getting the site to download in less than 3 seconds, generally.
I set up various Google Analytics and Omniture reports for improving site speed, as well as for reporting on 404 and 500 errors, then using Splunk to delve into those errors more closely. Due to my efforts, Constant Contact had very few 404s on the site, and any server errors were prioritized and fixed.
