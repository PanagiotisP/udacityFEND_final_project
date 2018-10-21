# Heraklion Sites
---
## Introduction

In this Udacity Project I've built an app that provides some of the must-see sites in Heraklion.

The app was developed using create-react-app. The map is generated by the Google Maps API. Sites' information is provided by the [wikipedia media api](https://www.mediawiki.org/wiki/API:Main_page)

## Runnig the up

The project requires Node.js 
Once Node is installed, navigate to the directory where you saved the project's folder and enter the command
```
npm install
```
Once all of the dependencies have been installed you can launch the app with
```
npm start
```
This will open a new browser page which hosts the app. The page's URL should be [http://localhost:3000/](http://localhost:3000/)

To utilize service worker and offline-first feature, the app has to be loaded in production mode. That is done by typing
```
npm run build
```
at the project's folder and then, using Node **serve** (which can be install by
```
npm install -g serve
```
)
and then enter
```
serve -s build
```
In this case the site will be hosted at [http://localhost:5000](http://localhost:5000)

## Using the App
* The app will load displaying a map of Heraklion with markers for each site and a list of those markers on the side. The list appears by clicking the hamburger button 
* Click on a map marker or site on the site list to load details information about each site
* Select site type from the dropdown menu at the top left to filter sites.