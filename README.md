# Nba_DashBoard
A FSD web application project showcasing a dashboard full of NBA stats, games, team rosters, news, standings and more.🏀
<br />

## App Demo
#### The app was deployed using the Firebase Hosting service
<a href="https://nba-1-480a7.web.app/" target="_blank"><img src="https://github.com/Zain27z/Nba_DashBoard/blob/main/miscellaneous/try-now-btn.png?raw=true" height="60px" /></a>
- BACKUP: [In case main hosting is down](https://nba-1-480a7.firebaseapp.com/)

#### Data last updated - Aug 2023
- Please note - the last data update was made in August 2023. The data will not be updated further as this is a showcase student project. If needed the scraping algorithms can be queued to perform an update regularily. Or better yet - be replaced with a real API. For this project I could not find a suitable and free API in order to showcase my skills. Using a real API would be much easier anyways. :)
<br />

# General App Overview
## Introduction
- The app provides all sorts of NBA information. 
- The user experience is nicely designed and styled with beautiful elements. 
- Both Light and Dark mode are available throughout the whole application pages.
- Mobile devices gain a specifically designed experience tuned for small screen devices.

## Key Features
- Light/Dark modes - selection is remembered
- Favorites/Likes for Logged in Users. Favorites are displayed in the User's Profile.
- Authentication
- Guest features/access are limited
- Users get an enhanced experience and twice as many available features
- Search with auto suggestions (show up as you type) 
- Dynamic navigation with animations and active highlight
- Special mobile device views and navigation show/hide button
- And much more...

## Page Map
- Dashboard (Some elements change depending on guest/user status)
- Standings
    - Western Conference Standings
    - Eastern Conference Standings
- Teams
    - Selected Team Details
        - Team Roster
        - Team Advanced Stats
- Players
    - Selected Player Details
- Transactions (Only for logged in Users)
- News (Only for logged in Users)
    - Current News Article Details (Only for logged in Users)
- Analysis (Only for logged in Users)
    - Current Analysis Article Details (Only for logged in Users)
- User Profile (Only for logged in Users)

## Sneak Peak Images 
- Dashboard (User View)
<p align="center"><a href="https://nba-1-480a7.web.app/"><img src="https://github.com/Zain27z/Nba_DashBoard/blob/main/miscellaneous/1.png?raw=true" alt="game-image" height="600px"></a></p>
- Dashboard (Guest View)
<p align="center"><a href="https://nba-1-480a7.web.app/"><img src="https://github.com/Zain27z/Nba_DashBoard/blob/main/miscellaneous/2.png?raw=true" alt="game-image" height="600px"></a></p>
- Teams (with nice hover effects)
<p align="center"><a href="https://nba-1-480a7.web.app/"><img src="https://github.com/Zain27z/Nba_DashBoard/blob/main/miscellaneous/3.png?raw=true" alt="game-image" height="600px"></a></p>
- Navigation (with a custom animated tooltip on hover)
<p align="center"><a href="https://nba-1-480a7.web.app/"><img src="https://github.com/Zain27z/Nba_DashBoard/blob/main/miscellaneous/4.png?raw=true" alt="game-image" height="300px"></a></p>
- Navigation on big screens
<p align="center"><a href="https://nba-1-480a7.web.app/"><img src="https://github.com/Zain27z/Nba_DashBoard/blob/main/miscellaneous/5.png?raw=true" alt="game-image" height="600px"></a></p>
- Navigation on mobile devices (toggled on)
<p align="center"><a href="https://nba-1-480a7.web.app/"><img src="https://github.com/Zain27z/Nba_DashBoard/blob/main/miscellaneous/6.png?raw=true" alt="game-image" height="600px"></a></p>
- Mobile View with navigation toggled off
<p align="center"><a href="https://nba-1-480a7.web.app/"><img src="https://github.com/Zain27z/Nba_DashBoard/blob/main/miscellaneous/7.png?raw=true" alt="game-image" height="600px"></a></p>
- Liked Team (already added to favorites)
<p align="center"><a href="https://nba-1-480a7.web.app/"><img src="https://github.com/Zain27z/Nba_DashBoard/blob/main/miscellaneous/8.png?raw=true" alt="game-image" height="100px"></a></p>
- Not liked (you can click on the star to add it to favorites). Also showcases the custom tooltip on hover telling you what happens if you click the star. The star also spins with an animation effect, but to see that you must try out the app. :)
<p align="center"><a href="https://nba-1-480a7.web.app/"><img src="https://github.com/Zain27z/Nba_DashBoard/blob/main/miscellaneous/9.png?raw=true" alt="game-image" height="200px"></a></p>


## A lot more awaits you on the app. Thank You! 
<a href="https://nba-1-480a7.web.app/" target="_blank"><img src="https://github.com/Zain27z/Nba_DashBoard/blob/main/miscellaneous/try-now-btn.png?raw=true" height="60px" /></a>
- BACKUP: [In case main hosting is down](https://nba-1-480a7.firebaseapp.com/)



<br />
<br />

# Technical Information

## Front End side 
### This SPA project was built using the Angular framework
- More information regarding Angular can be found in [this README](https://github.com/Zain27z/Nba_DashBoard/blob/main/client/README.md) and in the [Angular Docs](https://docs.angularjs.org/api).


## Back End side
### Back End is fully handled by Firebase
- Read the details of this project's back end handling and challenges. [Here](https://github.com/Zain27z/Nba_DashBoard/blob/main/server/README.md)

### NBA Data obtained via web scraping
- The lack of a free and feasible good API led to me learning web scraping and incorporating it for this project.
- It was a great way for me to learn more about the `puppeteer` library and web scraping as a whole.
- This of course made the Front End use of this data harder than using a regular API. 
- There were many challenges and the process was very involved. 
- Read more about it [Here](https://github.com/Zain27z/Nba_DashBoard/blob/main/web-scrapers/README.md)
