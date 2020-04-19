# Offline Budget Tracker

This app is a Budget Tracker. Using the code provided, I applied my new skills in optimization and IndexDB to transistion this app from online only to have offline functionality. The user will be able to add expenses and deposits to the Budget Tracker, whether online or offline.  If offline, the transactions are stored until an internet connection is established.

## Optimized for Speed and Offline access

Using optimization methods, I was able to make this application run faster and use less data per reload. Below are what steps I took to create an optimized experience for this PNW.

- Ran the Lighthouse Audit
- Removed the Boostrap CDN, since it was not needed for this app
- Minified Javascript files
- Set up compression
- Created manifest.webmanifest file
- Set up the service-worker.js file

## Repository
Repo: https://https://github.com/dobbe2/offlineBudgetTracker

## Deployed App
App: https://offlinenuggettracker.herokuapp.com/

