# budget-tracker
A budget-tracking application

# User Story
People used to travel a great deal (and will again soon, now that we have a vaccine!). As they do, they need to be able to access their applications even if they don't have access to the internet. The Budget-Tracker allows users to enter transactions into their tracker regardless of how good their internet access is, or if they have no access at all. A Progressive Web Application, Budget-Tracker uses IndexedDB, plus file and data caching for this functionality.


# Installation
Download the repo, using Git clone. Run NPM install from the command line at the root of the application. The application is a node app, using Express and MongoDB. Once the modules have been downloaded, just run npm start, then navigate to your localhost:3001.

# Testing
All testing was done through Chrome's Dev Tools.

# Help
Absolutely. Just send an email.

# Functionality
A simple program, Budget-Tracker provides an interface for the user to enter transactions. A graph is displayed showing the user their balance over time. If the internet connectivity is intermittant, or non-existant, the user is still able to use the application--the important files have been cached. They can enter transactions, and they are saved to the IndexedDB. When connectivity is returned, these are synced to the database.

# Images
The landing page, online, with data.

![landing-page](https://user-images.githubusercontent.com/52082187/101984406-8a3fad80-3c3e-11eb-97e4-b0cc800d81e4.jpg)

Offline functionality -- note that the data has been cached.

![offline-functionality](https://user-images.githubusercontent.com/52082187/101984409-8f9cf800-3c3e-11eb-99f2-fe2025446591.jpg)

After the connectivity is restored, the data is synced, and the user is notified.

![Data-Sync](https://user-images.githubusercontent.com/52082187/101984403-82800900-3c3e-11eb-9269-b80718534e24.jpg)

# URL to deployed application
https://mighty-mesa-85556.herokuapp.com/