# PRESENTATION: MEAN Architecture 2.0

The phrase "MEAN Stack" -- short for MongoDB, Express, Angular, and Node -- is only a few years old. In that time, it has quickly become convenient shorthand to describe a modern web technology stack that features a NoSQL database and pervasive JavaScript across all tiers of the app. "MEAN" is also a way to contrast your tech stack with the older, more traditional "LAMP Stack" that includes Linux, Apache, MySQL, and Perl/Python/PHP.

While expressive, MEAN may not be expressive enough to fully describe the architectural patterns in play in your application:

* Is your app fully server-side, fully client-side, or does it split the responsibilities between the client and the server?
* Is your app a Single Page App (SPA), or a more traditional multi-page app?
* Does it offer equivalent functionality when both online and offline?
* Can it replicate the user experience of native mobile apps written in Objective-C, Swift, or Java with only HTML, CSS, and JavaScript? This recently introduced architecture -- popularly called a Progressive Web App (PWA) -- features the PRPL Pattern (Push, Render, Pre-cache, and Lazy Load), Service Workers, and a preference for HTTP/2.

In this talk, Scott Davis (Principal Engineer with ThoughtWorks) presents several common web architectures for MEAN apps and the corresponding production-ready libraries and frameworks that will help you implement them. You will leave this talk with a better understanding of what is possible within the broad definition of the MEAN stack, and how you can most quickly reach your goals with popular standards-based, open source solutions.
