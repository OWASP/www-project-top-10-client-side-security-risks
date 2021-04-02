---

layout: col-sidebar
title: OWASP Top 10 Client-Side Security Risks
site_side: true
tags: top10
project: true
level: 2
type: documentation
pitch: The client-side of browser based web applications has different security challenges than [the server-side](https://owasp.org/www-project-top-ten/).

## OWASP Top 10 Client-Side Security Risks

Browser side applications are frequently a complex combination of custom HTML and JavaScript, leveraging numerous 3rd party libraries that are both served by the custom application, and also frequently integrated with 3rd party services that supply their own custom code and libraries into the same client-side application. And all of this runs in the customer's browser in the wild, rather than on application owner controlled, managed, and secured servers. Browser applications frequently interact with numerous servers, not just the original server hosting the server application and serving the core elements of the client-side JavaScript application to the user's browser.

This results in numerous risks for client-side code that are very different from the server-side applications. Therefore, the security of the client-side web application code requires a dedicated Top 10.  This is similar to the [OWASP Mobile Top 10](https://owasp.org/www-project-mobile-top-10/) which is a dedicated Top 10 for mobile apps. Mobile apps are frequently the client-side of a web app, where the server-side of the web app provides REST services to the mobile app.

This project will focus on identifying and organizing a prioritized set of security risks for client-side browser code (e.g., JavaScript, Web Assembly, etc.).

## Initial Plans

Are first priority is to identify a few more coleaders and other contributors willing to work on this project. We will then identify candidates for this Top 10 list, and vet this list through surveys, working groups, or other means.

Our goal is to then produce a draft Top 10 for public comment. We hope to produce PDF, Wiki and/or GitBook versions of the final document so it can be consumed in the format most helpful to the reader.
