# MEAN Architecture 2.0

The phrase "MEAN Stack" -- short for MongoDB, Express, Angular, and Node -- is only a few years old. In that time, it has quickly become convenient shorthand to describe a modern web technology stack that features a NoSQL database and pervasive JavaScript across all tiers of the app. "MEAN" is also a way to contrast your tech stack with the older, more traditional "LAMP Stack" that includes Linux, Apache, MySQL, and Perl/Python/PHP.

While expressive, MEAN may not be expressive enough to fully describe the architectural patterns in play in your application:

* Is your app fully server-side, fully client-side (the fashionable Serverless pattern), or does it split the responsibilities between the client and the server?
* Is your app a Single Page App (SPA), or a more traditional multi-page app?
* Does it offer equivalent functionality when both online and offline?
* Can it replicate the user experience of native mobile apps written in Objective-C, Swift, or Java with only HTML, CSS, and JavaScript? This recently introduced architecture -- popularly called a Progressive Web App (PWA) -- features the PRPL Pattern (Push, Render, Pre-cache, and Lazy Load), Service Workers, and a preference for HTTP/2.

And how about your data lifecycle?

* Is your dataset so large and frequently updated that it must live solely in the Cloud?
* Can it be cached on the client side for occasional offline use, or even better -- fully synchronized between the client and the Cloud so that your user has a comparable experience both in and out of Airplane Mode?

In this workshop, Scott Davis (author/presenter of O'Reilly videos "Architecture of the MEAN Stack", "Mobile Web Architecture", and "On the Road to Angular 2") presents several common web architectures for MEAN apps and the corresponding production-ready libraries and frameworks that will help you implement them:

* If you need strong data synchronization capabilities, perhaps CouchDB and PouchDB are better options than MongoDB.
* If you want a fully serverless data solution, maybe swapping in Firebase has some appeal.
* If HTTP/2 is a top priority, replacing Express with Hapi might be something to consider.
* If Angular (1 or 2) doesn't fully meet your needs, would you rather turn the dial towards a more JavaScript-centric solution like React and Redux, or a more HTML-like solution that leverages Web Components, Polymer, and Material Design?
* And how do modern security solutions like OAuth, Auth0, and JSON Web Tokens (JWT) compare?

You will leave this workshop with a better understanding of what is possible within the broad definition of the MEAN stack, and how you can most quickly reach your goals with popular standards-based, open source solutions.


## Biography

Scott Davis is a Principal Engineer with ThoughtWorks, where he focuses on leading-edge / innovative / emerging / non-traditional aspects of web development. This includes serverless web apps, mobile web apps (Responsive PWAs), HTML5-based SmartTV apps, Conversational UIs (like Siri and Alexa), and using web technologies to build IoT solutions.

Scott founded ThirstyHead.com, a Denver-based training and software development consultancy, in 2006. Scott co-founded the HTML5 Denver User Group in 2011.

Scott has been writing about web development for over 10 years. His books include "Getting Started with Grails", "Groovy Recipes", "GIS for Web Developers", "The Google Maps API: Adding Where to Your Web Applications", and "JBoss at Work". Scott is also the author of several popular article series at IBM developerWorks, including "Mastering MEAN", "Mastering Grails", and "Practically Groovy". His videos include "Architecture of the MEAN Stack", "Responsive Mobile Architecture", and "On the Road to Angular 2".
