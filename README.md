Whether Weather 
This is Whether Weather, a weather forecasting website I built for my web development project. The idea is just to have a site that shows the weather for different cities, using hardcoded data.
What It Does
Shows current weather for a city
Displays a 7-day forecast.
Lets you mark favourite cities and set preferences like Celsius/Fahrenheit, km/h or mph, Dark Mode, and live updates/. (These don’t save currently as not hardcoded).
Uses weather emojis and icons.
Everything is hardcoded, no backend/saved data.


How I made it. 
Used HTML and Nunjucks templates with Eleventy for multiple pages.
Bulma handled the layout and responsive design.
Created reusable components for weather cards, dashboard cards, and toggle switches.
Styled everything with CSS, sticking to a sky-blue background and sunny yellow text for visibility, mimicking a sunny day.
Added hover effects on cards and the logo for some interactivity.


Features I’m Happy With
Custom toggle switches on the settings page instead of standard checkboxes.
Responsive navbar with a logo that scales on hover.
Dashboard and forecast cards that slightly grow on hover to make things feel dynamic.
Colour scheme and text shadows so everything is readable on the background.

Features that need improving
Logo sizes needs to be increased - changing this in the CSS didn’t work and I was having issues with this.
Some of the HMTL felt “patchy” more pieced together than I would like to see. 


Sources
Weather emojis: Unicode standard emojis
FontAwesome: for extra icons
Bulma: layout and basic styling
See reflection for other sources

How to Run 

Clone the project
Install Node.js if you don’t have it
Install Eleventy:


npm install @11ty/eleventy --save-dev

Start the server:


npx eleventy --serve or npm star

Go to http://localhost:8080 in your browser

