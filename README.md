# Angular 2 ASP.NetCore Multi-SPA framework

This repository holds the source of a framework in progress. 

Currently it uses an ASP.Net Core backend, Angular 2.0.0 front end, and will be styled with the latest Bootstrap 4.0.

TODO 
(not neccessarily in this order):

- Add Angular templates using ASP.Net Core partials, to allow use of razor and tage helpers, to inject server side goodness into the client side markup.
- Add Tag Helpers to automatically create boiler-plate client code based on view models, attributes decorating view model properties will generate code directly, from one place in the code.
- Switch from Bootstrap 3 to Bootstrap 4 
- Add ng-bootstrap?
- Add JWT token authentication
- Add Swagger to create a map of Web API calls.
- Add EF and SQL seeding, hope to use Chuck Norris Roundhouse to version SQL generated by EF

## Prerequisites

Latest ASP.Net Core (currently 1.0.1) see http://asp.net
Visual Studio 2015 Update 3, with ASP.Net core tooling updates, or Visual Studio code.

Node.js and npm are essential to Angular 2 development and used by Visual Studio. 
    
More instructions to come.

## Running

Pull a copy of the repo, load the solution into Visual Studio, build (which will restore dependencies), and hit F5 or ctrl-F5

The original about and contact ASP.Net pages have now been removed, the default home/index page now loads the angular dependencies through layout, replacing the index.html in previous drop.
To view just clone, build and browse http://localhost:7010/ to see the Angular 2 using an ASP.Net partial page, with CSHTML running razor into the Angular template.