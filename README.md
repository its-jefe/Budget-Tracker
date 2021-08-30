# Budget Tracker Starter Code

Giving users a fast and easy way to track their money is important, but allowing them to access that information at any time is even more important. Having offline functionality is paramount to the success of an application that handles users’ financial information.


## Task
    Your challenge this week is to update an existing budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online. Once you’ve made these changes, you’ll deploy the application to Heroku.

## User Story (DELETE)
    AS AN avid traveler

    I WANT to be able to track my withdrawals and deposits with or without a data/internet connection

    SO THAT my account balance is accurate when I am traveling 


## Acceptance Criteria (DELETE)

    GIVEN a budget tracker without an internet connection

    WHEN the user inputs an expense or deposit
    THEN they will receive a notification that they have added an expense or deposit

    WHEN the user reestablishes an internet connection
    THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

## Getting Started
### <u>Offline Functionality</u>
    
   You’ll need to use `IndexedDB` to add offline functionality. Review Module 18: NoSQL, Lesson 4: Add Offline Persistence with IndexedDB as a refresher on how to add this to your application.

   You’ll also need to add a service worker to your application. Review Module 19: Progressive Web Applications (PWA), Lesson 4: Using `Service Workers` as a refresher on how to add this to your application.

### <u>REWIND</u>

## ` ¡¡¡ YOU ARE NOT USING WEBPACK !!! ` 

So...

Test `service workers` on localhost in development.


### <u>IMPORTANT</u>

<blockquote>

---
You should add your `idb.js` file to the public/js/ directory of your application.

---
You should add your `service worker` to the root of the public/ directory of your application.

---
Once you’ve updated the existing budget tracker, it should provide the following functionality:
- The ability to enter deposits offline.
- The ability to enter expenses offline.

---
Offline entries should be added to the tracker when the application is brought back online.

---
In the module project, you used webpack to create the manifest.json file. <br>
BUT! <br>
For this application, you’ll need to create it manually and add it to the root of the public/ directory of your application. 

---
You can also review Module 19: Progressive Web Applications (PWA), Lesson 5: Convert the App to a PWA as a refresher on web manifests.

---

## <u>Web Manifest</u>
This will be a mobile-first application, so you’ll also need to add a web manifest to your application with the app’s metadata, to let users’ devices know what they’re installing and how the app should look on the home screen.

### `manifest.json` will contain the following properties:

---
> `name`

> `short_name`

> `icons`

> `theme_color`

> `background_color`

> `start_url`

> `display`

</blockquote>