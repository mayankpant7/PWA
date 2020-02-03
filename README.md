# Progressive Web App (PWA)
## Step by Step guide to create a PWA

Steps Involved :
* Create your website using HTML, CSS, JavaScript.
* Add [manifest.json](manifest.json) file and add a link to it in [index.html](index.html) .
* Add [serviceWorker.js](serviceWorker.js) file and link it in the [app.js](app.js) file as shown in the code. 
* Set the required variables in [manifest.json](manifest.json) and [serviceWorker.js](serviceWorker.js) .


## Service Worker


A service worker is a script that your browser runs in the background in a separate thread. That means it runs in a different place, it's completely separate from your web page. That's the reason why it can't manipulate your DOM element.


However, it's super powerful. The service worker can intercept and handle network requests, manage the cache to enable offline support or send push notifications to your users.

## Web App Manifest

The web app manifest is a simple JSON file that informs the browser about your web app and how it should behave when installed on the user's mobile device or desktop. And to show the Add to Home Screen prompt, the web app manifest is required.
