# Project Automation using JENKINS

<img src = "Screenshots/raspi.jpg" width=180> <img src = "Screenshots/site-index.png" width=320> <img src = "Screenshots/NY-data-page.png" width=320>

## Purpose:

1. Low-cost, self-maintained data parsing server.
2. Which can do data acces from internet.
3. Do data manipulation
4. Host a web app/site to present that data.
5. Use third party APIs

## Project Structure:

1. **SERVER SETUP (back-end)** 
   - HARDWARE
     - RASPBERRY PI
     - ROUTER
   - SOFTWARE
     - APACHE
     - PHP
     - MARIA DB
     - GIT
     - OTHERS
   - SECURITY
     - ACCESS CONTROLS
     - HEADLESS & PASSWORDLESS SETUP
     - AUTO UPDATE
   - ACCOUNT SETUP
     - DOMAIN NAME CREATION
     - API FOR HOSTING SITE ON DNS
     - AUTO UPDATE IP ADDRESS 
     <img src = "Screenshots/domainAPI.png" width=400>
     <img src = "Screenshots/lamp.png" width=300>
     
2. **WEB ACCESS / DATA RETRIEVEL**
   - API
     - GOOGLE MAPS
       - ACCOUNT
       - API KEY SETUP
       - .
       <img src = "Screenshots/map1.png" width=200> <img src = "Screenshots/map2.png" width=200> <img src = "Screenshots/map3.png" width=180>
   - DATA RETRIEVEL
     - THE NEW YORK TIMES (git repo)
       - https://github.com/nytimes/covid-19-data
     - GIT
       - CLONE
       - AUTO UPDATE
       - CRON JOBS
       <img src = "Screenshots/pull.png" width=300>
3. **DATA MANIPULATION**
   - SHELL SCRIPTS
     - CONVERT DOWNLOADED DATA
     - SPLIT DATA
       - ACCORDING TO THE STATES
       - ACCORDING TO THE COUNTIES
     - STORE AT SERVER
       - DATA INTEGRITY IN MIND
     - SYNC WITH WEB SERVER
       - SECURE DATA TRANSFER
     <img src = "Screenshots/split.png" width=300>     

4. **WEB APP/SITE (front-end)**
   - SOFTWARE
     - HTML
     - CSS
     - JAVASCRIPT
   - DOMAIN NAME
     - www.HeemsResources.com

5. **USAGE**
   - GO TO: www.HeemsResources.com
   - GOOGLE MAPS IS INTEGRATED
   - FOR STATE COVID-19 DATA CLICK ON THE NAME
   - CLICK ON 'LOAD DATA'
   - WEB SCREEONSHOTS
   <img src = "Screenshots/cell1.jpg" width=300> <img src = "Screenshots/cell2.jpg" width=300>
   <img src = "Screenshots/site-index.png" width=800>
   <img src = "Screenshots/NY-data-page.png" width=800>
