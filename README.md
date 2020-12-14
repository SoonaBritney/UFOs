# UFOs

Module 11 | Assignment - JavaScript and DOM Manipulation


1. Background
WAKE UP SHEEPLE! The extra-terrestrial menace has come to Earth and we here at ALIENS-R-REAL have collected all of the eye-witness reports we could to prove it! All we need to do now is put this information online for the world to see and then the matter will finally be put to rest.
There is just one tiny problem though... our collection is too large to search through manually. Even our most dedicated followers are complaining that they are having trouble locating specific reports in this mess.
That's why we are hiring you. We need you to write code that will create a table dynamically based upon a dataset we provide. We also need to allow our users to filter the table data for specific values. There's a catch though... we only use pure JavaScript, HTML, and CSS, and D3.js on our web pages. They are the only coding languages which can be trusted.


2. Results
Level 1: Automatic Table and Date Search
Create a basic HTML web page or use the index.html file provided (we recommend building your own custom page!).
Using the UFO dataset provided in the form of an array of JavaScript objects, write code that appends a table to your web page and then adds new rows of data for each UFO sighting.
Make sure you have a column for date/time, city, state, country, shape, and comment at the very least.
Use a date form in your HTML document and write JavaScript code that will listen for events and search through the date/time column to find rows that match user input.

(1) Dynamically Filtered UFO page: 
Search Criteria: datetime
Search Results Screenshot - https://github.com/SoonaBritney/UFOs/blob/main/Capture_dynamic_search.PNG
Index.html - https://github.com/SoonaBritney/UFOs/blob/main/index.html
app.js - https://github.com/SoonaBritney/UFOs/blob/main/static/js/app.js
data.js - https://github.com/SoonaBritney/UFOs/blob/main/static/js/data.js
style.css - https://github.com/SoonaBritney/UFOs/blob/main/static/css/style.css
image - https://github.com/SoonaBritney/UFOs/blob/main/static/images/nasa.jpg

(2)Search by Button (multi search criteria)
Search Criteria: datetime. city, state, county, shape
Search Results Screenshot - https://github.com/SoonaBritney/UFOs/blob/main/Capture_search_by_button.PNG
index_button html - https://github.com/SoonaBritney/UFOs/blob/main/index_button.html
app js - https://github.com/SoonaBritney/UFOs/blob/main/static/js/app_button.js
data.js - https://github.com/SoonaBritney/UFOs/blob/main/static/js/data.js
style.css - https://github.com/SoonaBritney/UFOs/blob/main/static/css/style.css
image - image - https://github.com/SoonaBritney/UFOs/blob/main/static/images/nasa.jpg


3. Conclsion:
We can create the UFO search page using D3, snd javascript without any other tools in 2 ways.
1) seslect search criteria, and the data is dynamically refreshed.
2) select search criteria, and then click button 
