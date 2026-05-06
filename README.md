Here's a clean README you can copy and paste directly into GitHub:

Team Request Tracker
A lightweight browser-based tool for logging, assigning, and tracking team requests in real time. Built as a single HTML file, hosted on GitHub Pages, and embedded in SharePoint.
Features

Log requests by type and assign to a team member
Track status: Incomplete, In process, Complete
All tasks sync live across all users via Firebase Realtime Database
Works embedded in SharePoint via iframe

Setup
This tool requires a free Firebase project for shared data storage.

Go to console.firebase.google.com and create a free project
Enable Realtime Database in test mode
Go to Project Settings, add a Web app, and copy the config
Open index.html and paste your config into the firebaseConfig block
Commit the updated file — the live site will redeploy automatically

Embedding in SharePoint
Add an Embed web part to any SharePoint page and paste the following, replacing the URL with your own:
<iframe src="https://yourusername.github.io/team-request-tracker" width="800" height="800" frameborder="0"></iframe>
Team Members

Tiffanie O'Brien
Cameron Wood
Zach Rothenberger

Tech Stack

HTML, CSS, JavaScript
Firebase Realtime Database
Hosted on GitHub Pages
Sonnet 4.6
