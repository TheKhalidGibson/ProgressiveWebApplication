# Text Editor: a Progressive Web Application (PWA)

## My Task

This challenge that we have been given showcases some of the concepts that we have been building upon throughout the course of this Bootcamp. It is not only the culmination of some key expressions and concepts but also a great project to display to potential employers.

My task was to build a text editor that runs in the browser. This is a single page application and follows the PWA criteria. This application runs with data persistence techniques that hold up in the event that one of the options are not supported by the browser. This is also an application that will run offline as well.

To build this text editor I started an existing application with implementing methods for getting and storing data within a database. I used a package called `idb`, this is a lightweight wrapper around the IndexedDB API. This wrapper includes many methods for storing and retrieving data, and you can see this being used by companies like Google and Mozilla.

I have deployed this application using the [Heroku Deployment Guide on The Full-Stack Blog](https://coding-boot-camp.github.io/full-stack/heroku/heroku-deployment-guide).

**Important**: Note that my submission does includes the `.npmrc` file in this starter code.  This ensures that my application deploys properly to heroku.

## User Story

```md
AS A Full-Stack Developer
I WANT a text editor to create snippets of code or take notes even if there is no internet connection
SO THAT I can reliably store and retrieve them later
```

## Acceptance Criteria

```md
GIVEN an application for editing text on the web
WHEN I open my application 
THEN I see a folder structure for the client server 
WHEN I run `npm run start` from the root directory
THEN my application starts up the backend and serves the client
WHEN I run the text editor application from my terminal
THEN with using webpack my JavaScript files have been bundled 
WHEN I run my webpack plugins
THEN a generated HTML file, service worker, and a manifest file is created
WHEN I use next-gen JavaScript in my application
THEN the text editor functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from my IndexedDB
WHEN I click on the Install button
THEN my web application downloads and appears as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with ensuing pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Mock-Up

In this Mock-Up section of this README you can see the example that was provided to me as a guide to help reach completion

The following animation demonstrates the application functionality:

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](./assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](./assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](./assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](./assets/03-idb-storage.png)


## Review 

The following has been placed here to meet requirements for review:


Refer to this link [Heroku Deployed Application]() to view and explore the application and functions on deployed site on Heroku

Refer to this link [GitHub Repository]() to view and explore the GitHub repo for this assignment


## Screenshots

The following images reflect the functionality and final results of development for this deployed application:

![Image showing the URL where the deployed application landing page can be found](./assets/image-4.png)

![Image showing a landing page for a note taker application](./assets/image-1.png)

![Image showing the URL where the deployed application can be found](./assets/image-3.png)

![Image showing a note taker application with stored data](./assets/image-2.png)