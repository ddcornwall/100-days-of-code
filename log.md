# 100 Days Of Code - Log

<!--Template for log
### Day 70: December 21, 2017 - Time spent, 1 hour

**Today's Progress**:  

**Thoughts**: 


 

**Links that helped me get stuff done**


**Link(s) to work**


End Template for log-->

DISCLAIMER - This log will contain typos. For the nicely edited version of my progress, visit https://librarianfromalaska.wordpress.com/tag/100daysofcode/

### Day 77: December 28, 2017 - Time spent, 1 hour 15 minutes

**Today's Progress**:  Worked out sorting for National Archives Alaskana explorer, selected fields I needed to extract for project and verified I could pull them correctly via console logging. 

**Thoughts**: I really cannot find enough good things to say about the JSON Handle Chrome extension. It really helps to pin down the paths of fields you need from the nested arrays and objects provided by some APIs such as the US National Archives. 

I have plenty more to do on this project, even in the initial phase of trying to display the most recent Alaskana. I'll need loops within loops to display records and their associated digital items. I want to look into paging results so people can see more records. It might be good to offer people a choice about seeing all the digital objects associated with a record. Maybe I'd display the first digital object and then provide a link to the catalog.

This is also going to be my last #100DaysOfCode entry for a bit. I'm currently travelling and my family is taking a side trip from here to visit good friends they want me to meet. Given the number of people who will be crammed into one house, I want to let go of the idea that I'll have an uninterrupted hour of coding there. I'll restart my R1 of #100DaysOfCode after I get back from the side trip on 1/2/2018. Happy coding all!
 

**Links that helped me get stuff done**
JSON Handle Chrome Extension - https://chrome.google.com/webstore/detail/json-handle/iahnhfdhidomcpggpaimmmahffihkfnj
NARA Interactive API documentation - https://catalog.archives.gov/interactivedocumentation

**Link(s) to work**
https://github.com/ddcornwall/nara-alaskana


### Days 75 & 76: December 26 and 27, 2017 - Total Time spent, 2 hours 15 minutes

SPECIAL NOTE: Wonky home internet access kept me from blogging yesterday.

**Today's Progress**:  Continued examining US National Archives(NARA) API. Gained appreciation for how complicated NARA data is. 

**Thoughts**: NARA data is very complicated. My goal is to pull out the most recently digitized items related to Alaska. I can get data of the NARA API. I can even get only online objects. But NARA appears to store the metadata about the digital objects separate from the descriptions of the physical items. As a result, if I limit my query to digital objects only, I get a result list with no meaningful descriptions. But so far, if I include descriptions, I have to accept descriptions without corresponding digital objects. 

A possible further complication, at least for the user is that the data returned from NARA can include large amounts of text extracted from PDFs as well as user transcriptions. I'm guessing that will add to the download time for users. 

I might want to narrow the scope of this project to just photographs and see if that helps. To get a sense of how complex NARA data can be, check out https://catalog.archives.gov/api/v1/?description=alaska%20digitization%20project, one of my experiments to get data out of the National Archives Search API. "Alaska Digitzation Project" refers to a specific initiative to digitize materials formerly housed in Anchorage Alaska but which are now on file with the Seattle Field Office of NARA. It's a bit of a cheat as there may be more digitized items of Alaskana beyond the Alaska Digitization Project, but I wanted a set of files I could be sure had digital surrogates. 

On a personal note, I may have to restart 100 Days of Code soon because my family and I are taking a trip to a friend's house this weekend. My wife and I will be on a couch in the living the living room and people we're staying with have two small children. I don't see how I get a coding hour a day out of that. 


 

**Links that helped me get stuff done**
1. NARA search API interactive documentation - https://catalog.archives.gov/interactivedocumentation (This is where to find the searchable/sortable fields.

**Link(s) to work**
https://github.com/ddcornwall/nara-alaskana



### Day 74: December 25, 2017 - Time spent, 1 hour 10 minutes

**Today's Progress**:  Ported my Free Code Camp (FCC) Weather Explorer to CodePen. Started work on National Archives (NARA) Alaskana Explorer by examining the NARA Catalog API for search/export and examining a record for digitized Alaskana in detail. Made note of possibly sorting parameters. 

**Thoughts**: I was pleasantly surprised that my CodePen worked the first time. The Weather Viewer is still rough around the edges, but I'm eager to put my newly developed API coding skills to work on a task I've dreamed about for at least a year - providing better access to Alaska related materials digitized by the US National Archives. In particular, I would like to code an app that will display the most recently digitized materials from the Archives. While there is no clear way to do this from the public NARA catalog, there seems to be promising approaches within the NARA catalog API. I'd also like to provide a very limited subject browse to digitized Alaskana. I established a GitHub repo to track my notes and eventual code. If you'd like to join me, drop me a line. Or just fork the repo and go your own way. Plenty of room for all. 
 

**Links that helped me get stuff done**
1. National Archives Catalog Search and Export - https://github.com/usnationalarchives/Catalog-API/blob/master/search_and_export.md


**Link(s) to work**
1. nara-alaskana - https://github.com/ddcornwall/nara-alaskana/tree/master


### Day 73: December 24, 2017 - Time spent, 1 hour 20 minutes

**Today's Progress**:  Completed reformatting of weather data using "toFixed(n)" function to format numbers and a long "if / else if" statement to translate wind direction. 

**Thoughts**: Today was another day of steady progress. A lot of my time was looking up conversion formulas and coding them into my project. I worked on my task list for the Free Code Camp (FCC) "Show the local weather" project. Here's how it stood after yesterday:

1) Display tempetature in both C and F
2) Display wind speed in both mps and mph
3) Display pressure in inches and millibars
4) Migrate to CodePen, since that is what Free Code Camp (FCC) asks for the project.
5) Bonus - Show wind direction in terms of every day direction (i.e. North instead of 0 deg, etc)
6) Bonus - Put in a static Google map

I accomplished everything on my list except migrating to CodePen and putting in a static Google map. I've decided to forgo the Google Map because my page takes awhile to load. Adding one more API call will just slow it down more. 

I decided to NOT code a toggle button between C and F because it just doesn't make sense to me to code a button for that and not the other metric measurements. It also doesn't make sense to have three buttons. So I'm not going to do either. I think in a real life situation, I could convince my client not to insist on a C to F button. 

So tomorrow (or possibly boxing day) the goal will be to migrate my project to CodePen and submit it to FCC. Then I'll start studying the National Archives Catalog API to see if I have a chance of retrieving the most recently digitized photos with Alaska subjects. 

 

**Links that helped me get stuff done**
1. Conversion of Temperature - https://www.mathsisfun.com/temperature-conversion.html
2. Pressure Conversion (National Weather Service) - https://www.weather.gov/media/epz/wxcalc/pressureConversion.pdf
3. How do I convert m/s to mph? (Quora) - https://www.quora.com/How-do-I-convert-m-s-to-mph
4. JavaScript Number Methods (w3schools) - https://www.w3schools.com/js/js_number_methods.asp
5. Wind directions and degrees - http://snowfence.umn.edu/Components/winddirectionanddegreeswithouttable3.htm

**Link(s) to work**
1. Show the local weather - https://www.freecodecamp.org/challenges/show-the-local-weather


### Day 72: December 23, 2017 - Time spent, 1 hour 15 minutes

**Today's Progress**: Reformatted weather display using Bootstrap Grid layout. Reformatted Sunrise and Sunset display so only the parts I wanted to display showed up.   

**Thoughts**: I'm pleased with my programming progress so far, but my page is loading fairly slowly. I will need to see what I can do to optimize things after I'm done with my other tasks.

Speaking of tasks, here is my task list from yesterday:

1) Make display more attractive. Try to make icon pop out more. Remember to use accessible contrasts
2) Display tempetature in both C and F (Consider button)
3) Display wind speed in both mps and mph
4) Display pressure in inches and millibars
5) Display only the time part of sunrise and sunset. Bonus - display Date before showing either
6) Bonus - Show wind direction in terms of every day direction (i.e. North instead of 0 deg, etc)
7) Bonus - Put in a static Google map

Today I felt like I accomplished #1 (nicer display) by using a grid display. I used the img height and width attributes to pump up the size of the icon. Some of the spacing could be better, but it's a big improvement over my previous versions.

Thanks to the functions toLocaleTimeString, getMonth, getDate and getFullYear, I was able to resolve #5, displaying the date just once, and only showing the time part of sunrise and sunset. Quick note about getMonth() - it is a zero index function, so December shows up as 11. So I created a variable called month and set it to getMonth(sunrise)+1.

With these items taken care of, my revised task list looks like this:

1) Display tempetature in both C and F
2) Display wind speed in both mps and mph
3) Display pressure in inches and millibars
4) Migrate to CodePen, since that is what Free Code Camp (FCC) asks for the project. 
5) Bonus - Show wind direction in terms of every day direction (i.e. North instead of 0 deg, etc)
6) Bonus - Put in a static Google map


**Links that helped me get stuff done**
1. HTML <img> Tag (w3schools) - https://www.w3schools.com/tags/tag_img.asp
2. extract time from datetime using javascript - https://stackoverflow.com/questions/15546292/extract-time-from-datetime-using-javascript
3. Extract date and time from string using Javascript - https://stackoverflow.com/questions/14787271/extract-date-and-time-from-string-using-javascript
4. JavaScript getMonth() Method (w3schools) - https://www.w3schools.com/jsref/jsref_getmonth.asp


**Link(s) to work**
1. Show the Local Weather - https://www.freecodecamp.org/challenges/show-the-local-weather



### Day 71: December 22, 2017 - Time spent, 1 hour

**Today's Progress**:  Completed display of data for Free Code Camp (FCC) Show the Local Weather. Committed my index.html, style.css and script.js files to GitHub. Use JavaScript Date function to convert Unix timecodes into usable sunrise/sunset dates and times. 

**Thoughts**: Another day of good progress without odd glitches. I'm a little grumbly that the FCC Weather API didn't come with an explanation of fields and units. But by comparing what I got from my FCC weather station to what's available on weather.gov (with a bit of an assist from Wolfram Alpha for speed calculations), I determined the units for different conditions are as follows:

Tempetature: Celsius
Pressure: Millibars (mb)
Wind Speed: Meters per second

While FCC only seems to care about converting tempetature, I'm planning on displaying all three of these metric measures both ways. 

After reviewing what I have so far and comparing it to the user stories on the FCC challenge, plus some of my own desires, I came up with this list of tasks:

1) Make display more attractive. Try to make icon pop out more. Remember to use accessible contrasts
2) Display tempetature in both C and F (Consider button)
3) Display wind speed in both mps and mph
4) Display pressure in inches and millibars
5) Display only the time part of sunrise and sunset. Bonus - display Date before showing either
6) Bonus - Show wind direction in terms of every day direction (i.e. North instead of 0 deg, etc)
7) Bonus - Put in a static Google map

I'm not crazy about offering a button to toggle the tempetature, but it is a business requirement.  

**Links that helped me get stuff done**
1. Sunrise and sunset calculations for api weather machine - 
https://forum.freecodecamp.org/t/sunrise-and-sunset-calculations-for-api-weather-machine/151949/3

**Link(s) to work**
1. Show the Local Weather - https://www.freecodecamp.org/challenges/show-the-local-weather



### Day 70: December 21, 2017 - Time spent, 1 hour

**Today's Progress**:  Began writing weather data to my weather viewer. Learned about unix time.

**Thoughts**: I felt like I made good progress today. I identified the fields I wished to display in my weather viewer and started coding their display. I have more fields and more formatting to do, but I'm confident I can get it done. 

A trip to the Free Code Camp (FCC) Forum helped me decipher the odd sunrise and sunset times provided by the FCC weather API. For example for today 12/21/17 it provided:

*Sunrise: 1513806493
*Sunset: 1513841781

It turns out these values are "unix time", or the number of seconds since midnight, 1/1/1970. Javascript has a "date" function that might turn these values into something human usuable. 
 

**Links that helped me get stuff done**
1. Sunrise and sunset calculations for api weather machine - 
https://forum.freecodecamp.org/t/sunrise-and-sunset-calculations-for-api-weather-machine/151949/3

**Link(s) to work**
1. Show the Local Weather - https://www.freecodecamp.org/challenges/show-the-local-weather


### Day 69: December 20, 2017 - Time spent, 1 hour

**Today's Progress**:  Successfully retrieved and addressed data from the Free Code Camp (FCC) weather API. Got it to work on the geolocation of my laptop. 

**Thoughts**: The first part of the day was frustrating and reminded me of the need to track and triple check all punctuation. I also had to relearn that for the most part, what happens in the function stays in the function. Once I got these two truths out of the way, it was a simple matter to use geolocation to generate latitude and longitude to use in retrieving weather data via a $getJSON request. I've satisfied myself that I can reliable address sub-items within the weather data "blob" I get. Now I can move on to which data I want to use and how to display it. Because its an FCC project that directs us to CodePen, I'll probably be setting one up in the next day or two. 

While I'm definitely finding some of the details frustrating, my confidence level in working with APIs is increasing, for which I am grateful. 

**Link(s) to work**
1. Show the Local Weather - https://www.freecodecamp.org/challenges/show-the-local-weather




### Day 68: December 19, 2017 - Time spent, 1 hour

**Today's Progress**:  Kept my patience as I tried different things. 

**Thoughts**: Not much done today. Sort of like a rat in a maze. But better to explore the maze than lie down and give up, right? 

First I tried separating out the javascript and css bits into their own files. I kept a copy of my original HTML file that had both elements in that. Then I constructed new files index.html, style.css and script.js. The separated Javascript file did not work, though I was prepared for that as Google called a script within a script.  But I couldn't make that call work within script.js and after Googling the possibilities, I settled on keeping the javascript inside my index.html file. What stumped me more is that although I triple checked my stylesheet link AND could apparently see it working in developer tools, the map would not unless the styles were inside index.html. I'm sure I'm missing something, but for the life of me can't figure what.

Next I turned my attention to the Free Code Camp (FCC) weather API. It seemed straightforward, but my efforts to use Get JSON seem to break the map. Without the weather API code, it's fine. Drop in the weather API code and all of a suddent "InitMap()" is no longer a function. 

It may be that I bit off more than I can chew. So tomorrow I think I will go back to basics and drop the Google Map for now, even though I'd like to bring it back later. 


**Link(s) to work**
1. Show the Local Weather - https://www.freecodecamp.org/challenges/show-the-local-weather



### Day 67: December 18, 2017 - Time spent, 1 hour

**Today's Progress**:  Figured out how to get geolocation and Google Maps to work together. Started studying the Free Code Camp (FCC) weather API. 

**Thoughts**: Today was mostly tweaking and poking once I found an example of getting Google to take my laptop's location. Worked at getting the right sized map. Looking at the FCC weather API it looks like it's got a lot of good fields to play with. I figure I'm going to try and use the sunrise and sunset data in addition to weather conditions. It would be nice to know what their original source is just because I like vetted resources for applications, but this will do for the exercise.  

I also have some work to do because the examples I used to generate the Google Map based on geolocation ran script and style tags inside the HTML. I think it would be good practice to transfer these out to their own separate script.js and style.css 


**Link(s) to work**
1. Show the Local Weather - https://www.freecodecamp.org/challenges/show-the-local-weather

### Day 66: December 17, 2017 - Time spent, 1 hour

**Today's Progress**:  Completed Free Code Camp (FCC) Wikipedia Viewer. Started planning for Show Local Weather. Obtained a developer key for the Google Maps API.

**Thoughts**: I spent about half my time this morning trying to wrap my brain around using autocomplete and how that would affect the code in my working project. I came to the conclusion that this is a "nice to have", I don't need it right now. So I submitted my Wikipedia Viewer as a completed project to FCC. I figured that the local weather viewer would be a nice way to continue working with different APIs. 

As part of my customization of "Show your local weather", I intend to display an embedded Google Map so people can tell at a glance if their geolocation has gone wonky. For example, while I live in Juneau Alaska, it is not uncommon for geolocation apps to put me in either Anchorage Alaska or even Seattle Washington. So far I have a basic Google Map, but I haven't worked out how to pass the latitude and longitude I get from my laptop into Google's script. But I'm guessing that just means I need a tutorial in HTML5 geolocation. 
 

**Links that helped me get stuff done**
1. Adding a Google Map with a Marker to Your Website - https://developers.google.com/maps/documentation/javascript/adding-a-google-map

**Link(s) to work**
1. FCC Show the Local Weather - https://www.freecodecamp.org/challenges/show-the-local-weather


### Day 65: December 16, 2017 - Time spent, 1 hour

**Today's Progress**:  Made Wikipedia viewer more presentable. Researched ways to implement autocomplete. 

**Thoughts**: 
Today was pretty fun. Mostly tweaking my Wikipedia Viewer that I put into a CodePen because that was the preferred format of Free Code Camp (FCC). I spend the last part of my coding time on reading how to get my search form to autocomplete with wikipedia titles. I feel close but not quite. This partly because finding alone focused time is harder to do at my families place than at home. 

**Links that helped me get stuff done**
1. usa.gov design components: Colors - https://standards.usa.gov/components/colors/
2. Getting started with jQuery and jQuery UI – Back to Basics - http://www.dotnetcurry.com/jquery/1089/jquery-jqueryui-basic-beginner-tutorial
3. jQuery UI TextBox AutoComplete with Remote Data Source (Back to Basics) - http://www.dotnetcurry.com/jquery/1129/jqueryui-autocomplete-using-remote-data

**Link(s) to work**
1. FCC Wikipedia viewer - https://codepen.io/ddcornwall/pen/aEOwjj



### Day 64: December 15, 2017 - Time spent, 1 hour

**Today's Progress**:  Built an unaesthetic working version of the Free Code Camp (FCC) Wikipedia Viewer. 

**Thoughts**: After considering my coding options and how I'm still stuck on the random quotes machine, I decided to apply my new Wikipedia API skills I picked up on Udacity to the FCC's Wikipedia Project. Thankfully the skills are transferrable and I have a very basic CodePen that meets the basic use cases. You can search for wikipedia articles, see a list and get a random article if you want.

Call this version 0.9. It could look better. I'd also like to bring up suggested search terms. So tomorrow will be focused on aesthetics. Once done, improve the functionality a bit more. 

**Link(s) to work**
https://codepen.io/ddcornwall/pen/aEOwjj


### Day 63: December 14, 2017 - Time spent, 1 hour

**Today's Progress**:  Learned ways Ajax requests can go wrong. 

**Thoughts**: Ok, so lessons learned in one API aren't necessarily applicable to others. I'm still stumped on the random quote machine. I can load wikipedia data into CodePen, but it doesn't like the https version of forismatic I found. Trying to use a callback function just got me mime type errors. Though only with forismatic. Wikipedia grooves with callbacks. 

Will try more read/search tomorrow. Perhaps look for other code sources. Or maybe I'll try playing with the national archives API instead. 

**Link(s) to work**
1. https://www.freecodecamp.org/challenges/build-a-random-quote-machine

### Day 62: December 13, 2017 - Time spent, 1 hour

**Today's Progress**:  Completed Udacity Intro to Ajax class. Tweaked Move Companion App in preparation for future hosting. Fixed Wikipedia error handling. Learned that the WAVE Evaluation tool doesn't seem to work on local files.

**Thoughts**: I took the Udacity Intro to Ajax class because several people at Free Code Camp (FCC) and on Twitter recommended it. So do I if you're interested in getting hands on experience with APIs. I definitely need more practice but I feel comfortable with the basics. 

I had a problem with error handling Wikipedia content. It turned out that JSONP doesn't allow you to just tack on an "error" or "fail" function. So the Udacity instructor included a neat trick involving setting a timeout that ended in an error message AND a line that canceled the timeout if wikipedia content returned. It worked great! 

The app itself is ok. I can see several ways to make it better and once I get it web posted, I ought to check it for mobile access. Maybe also put the photo, NYT articles and Wikipedia entries into Bootstrap containers. 

Also, I want to give it a go over for accessibility, but the web-based WAVE Evaluation tool doesn't work on local files. So that will have to wait till I get it web hosted.

Looking back on my list from yesterday:

1. finish the Udacity course, which still has a few sections.
2. Edit my app so that the street view does not fill the background.
3. Look for other accessibility issues with WAVE Evaluation tool (if that can be done with local files)
4. Fix error handling for the wikipedia articles. 
5. Get this project hosted on Github Pages and work out the inevitable posting glitiches

It looks like I knocked out 1,2 and 4. Not bad for working on this project in the Seattle-Tacoma airport after waking up at 2:30am. 

From here, I'm thinking I'll go back to the FCC Random Quote Machine so I can use my knowledge of APIs outside of the fairly careful guidance of Udacity. 
 

**Links that helped me get stuff done**
https://classroom.udacity.com/courses/ud110/

**Link(s) to work**
1. Move companion app (URL coming soon!)
2. Free Code Camp Build a random quote machine - https://www.freecodecamp.org/challenges/build-a-random-quote-machine

### Day 61: December 12, 2017 - Time spent, 1 hour 30 minutes

**Today's Progress**:  Figured out how to get wikipedia data of my choosing, then formatted and inserted that data into my moving companion app for my Udacity Intro to Ajax class. Committed working code to GitHub.

**Thoughts**: It's a joy to figure something out. It always is. To get to that point, I had to review searching in the Wikimedia/Wikipedia API, use a great tool called JSON-Handle to better see how wikipedia data was structured, and spend some time figuring out how loops were going to help me out. 

JSON-Handle was particularly helpful because it not only presents JSON data in a nice outline, but it shows you the exact bracket notation of an element when you click on it. I really needed that functionality today because unlike the New York Times, Wikipedia does not name the arrays it passes back to you. It also packages titles, snippets and URLs into completely separate (objects? Arrays?) instead of the New York Times approach of passing you a single object of muliple arrays for each article. 

Next steps are:

1. finish the Udacity course, which still has a few sections.
2. Edit my app so that the street view does not fill the background.
3. Look for other accessibility issues with WAVE Evaluation tool (if that can be done with local files)
4. Fix error handling for the wikipedia articles. 
5. Get this project hosted on Github Pages and work out the inevitable posting glitiches

Tomorrow is a travel day for me. I've got long enough layovers that I'm hopeful of getting at least an hour's coding in. Then I'm with family for the holidays. We'll have to see how that affects. Wish me well in finding an appropriate coding/family balance for the rest of the month. 
 

**Links that helped me get stuff done**
1. Wikipedia API Search - https://www.mediawiki.org/wiki/API:Opensearch
2. Extension JSON-handle -  https://chrome.google.com/webstore/detail/json-handle/iahnhfdhidomcpggpaimmmahffihkfnj

**Link(s) to work**
https://classroom.udacity.com/courses/ud110/


### Day 60: December 1, 2017 - Time spent, 1 hour 15 minutes

**Today's Progress**:  Figured out how to get some data from Wikipedia API. Learned anew importance of callbacks

**Thoughts**: Wikipedia API. Harder than it looks. I went through the Undacity tutorial, read through Ajax documentation and the Wikimedia/Wikipedia API documentation and tried several variants of Ajax requests. Not only did they not work, but they erased my other APIs display. eventually I found a tutorial on Wikipedia/Ajax tutorial that showed me what I was doing wrong. I needed to add ```&callback=?``` to the end of my calling URL. I knew that I was passing JSONP through a function and saw the term callbacks in documentation, but handn't thought that it needed to go into the URL. Call me n00b. 

Stil some more work to do with my function, but I feel like I'm on the right track. And my page isn't broken. I suppose another takeaway is that every API is different. 
 

**Links that helped me get stuff done**
1. Getting Data From the Wikipedia API Using jQuery - http://www.9bitstudios.com/2014/03/getting-data-from-the-wikipedia-api-using-jquery/

**Link(s) to work**
https://classroom.udacity.com/courses/ud110/



### Day 59: December 10, 2017 - Time spent, 1 hour

**Today's Progress**:  Completed successful display of New York Times API data within moving app. Successfuly "failed" application gracefully. 

**Thoughts**: It was easy enough to find the proper way to deal with quote marks. After that it was a simple matter of creating the list item string to display my articles. I wound up with:

```
//Put articles into HTML
$(".article-list").append("<li> <a href=\"" + items[i].web_url + "\"" + "target=\"_blank\" >" + items[i].headline.main + "</a>" + "</br>" + items[i].byline.original + "</br>" + "Snippet: " + items[i].snippet + "</br>" + "Word count: " + items[i].word_count + "</li>");
```
Ok. Not totally simple and I did need to read it over a few times. But it works beautifully. Between this and the getJSON method I learned, I feel reasonably confident in extracting and displaying API data from those APIs that support JSON and JSON-P. Which is all I wanted from the Free Code Camp (FCC) JSON APIs and Ajax but didn't get. 

My plans are to finish the Udacity course, go back to FCC and buld the random quote machine, and then probably noodle around with the National Archives Catalog API. From reading https://github.com/usnationalarchives/Catalog-API/blob/master/search_and_export.md I see it supports JSON. 

For now, the next immediate step is to work with the Wikipedia API. Then I'll finalize the "move companion" to change the image from backgound to loading at the top because I do not like the readability of text against the photo backgrounds.

One final thought on this day is that at some point I'm going to set to set up a special file of developer keys outside of GitHub. Or upgrade my subscription.
 

**Links that helped me get stuff done**
1. JavaScript Strings - https://www.w3schools.com/js/js_strings.asp (Scroll down to "special characters")
2. Deferred.fail() - https://api.jquery.com/deferred.fail/

**Link(s) to work**
1. Intro to Ajax - https://classroom.udacity.com/courses/ud110




### Day 58: December 9, 2017 - Time spent, 1 hour 40 minutes

**Today's Progress**:  Successfully picked out just the fields I needed from my New York Times API/JSON query. Used jQuery append method to get headlines on my "moving companion app" page. 

**Thoughts**: Now that I can find the data I want using APIs with JSON, now the challenge is to display it in my web page. I looked through several different ways of displaying items before settling on JQuery's append method as the one I found most comprehensible and which did not totally replace text with every loop iteration. So now I have a list of headlines that display on my page in list item format. I tried to get them web linked, but I'm having issues getting append() to handle quote marks. I don't think I'm escaping the quote marks correctly. I want to get that part figured out because one of my future projects will be displaying images gathered with APIs and I'll definitely need ```<img src="some image url">``` then. Once I get quote mark handling sorted, it SEEMS like a simple matter of formatting my other fields into a list item. Then I can check off that part of the Udacity "Intro to Ajax" course and move on to the Wikipedia part, which I assume will also help me with the Free Code Camp (FCC) Wikipedia Viewer challenge.  


**Links that helped me get stuff done**
1. jQuery append() Method - https://www.w3schools.com/jquery/html_append.asp

**Link(s) to work**
1. Intro to Ajax - https://classroom.udacity.com/courses/ud110




### Day 57: December 8, 2017 - Time spent, 1 hour 15 minutes

**Today's Progress**:  Worked more with New York Times API. Learned to retrieve just the fields I wanted. Found a great video on addressing specific chucks of data within the big data blob "response." 

**Thoughts**: I was really flailing around trying to extract particular bits of New York Times articles from the big "response" blob containing objects, arrays, etc: 

```
[object Object]: {copyright: "Copyright (c) 2017 The New York Times Company. All Rights Reserved.", response: Object, status: "OK"}
copyright: "Copyright (c) 2017 The New York Times Company. All Rights Reserved."
       response: Object
           docs: Array
               0: Object

                    byline: Object

                    headline: Object
                      content_kicker: null
                      kicker: null
                      main: "A $40 Toll to Drive 10 Miles? It Happened on Virginia’s I-66"
                      name: null
                      print_headline: "Tolls Rise In Virginia With Flow Of Traffic"
                      seo: null
                      sub: null

                    __proto__: Object
                   score: 1
                   web_url: "https://www.nytimes.com/2017/12/05/us/i66-toll-virginia-washington.html"
                   word_count: 789
```
Then I found a YouTube video by The Coding Train. He showed the process of getting API data, which I already knew, but then he worked through the structure of the response. The keys are 1) To address an item, you chain the hierarchy through dot notation and 2) array objects in JSON can be addressed through array notation. So finding the first "main" headline becomes:

```data.response.docs[0].headline.main```

I confirmed this works and know I think I'm in a position to complete the New York Times portion of "My Moving Companion" the next time I code. This will also help me with the Free Code Camp (FCC) Random Quote Machine once I go back to it. 


**Links that helped me get stuff done**
1. 10.9: New York Times API and JavaScript - p5.js Tutorial by The Coding Train - https://www.youtube.com/watch?v=IMne3LY4bks 
2. New York Times Article Search API - http://developer.nytimes.com/article_search_v2.json

**Link(s) to work**
1. Intro to Ajax - https://classroom.udacity.com/courses/ud110


### Day 56: December 7, 2017 - Time spent, 1 hour

**Today's Progress**:  Got a New York Times developer key, successfully retrieved data from Article Search API. Got a feel for just how complex JSON data could be. Figured out the data elements I want to bring into the "moving companion app."

**Thoughts**: I am really like this Udacity "Intro to Ajax" course. It is really coding heavy so I don't feel like it's a cheat to be using it for my #100DaysOfCode. The instructor gives brief overviews, points you to helpful documentation and then tells you to come back when you have the code working. There's a link to the class forum if that doesn't go well.

I'm impressed with the New York Times API. Aside from decent documentation, it actually has a form to help you build your Ajax requests. It took a little bit of looking at that and my class materials to translate the Times' Ajax query into the $.getJSON I was supposed to use, but I got it. Also got it to accept my city input. 

My next step is to parse the tsumani of data that comes with every record. Their JSON results are rather like a set of nested boxes. You get an object with an array of stories and there are some sub arrays within each story. It's a considerably more complex structure than the ones listed in the JSON.parse() function examples I've seen so far. I'm not discouraged though. Three days ago I could not figure out how to draw ANYTHING out of an API. So having too much data is actually a nice problem to have. 


**Links that helped me get stuff done**
1. jQuery.getJSON() - http://api.jquery.com/jquery.getjson/
2. New York Times Article Search API - http://developer.nytimes.com/article_search_v2.json
3. New York Times Developers FAQ - http://developer.nytimes.com/faq

**Link(s) to work**
1. Intro to Ajax - https://classroom.udacity.com/courses/ud110




### Day 55: December 6, 2017 - Time spent, 1 hour 15 minutes

**Today's Progress**:  Learned how to gather information from a form and put them in variables. Got Google Streetview requests working on my "moving information app" for the Intro to Ajax course on Udacity.

**Thoughts**: This was a good day, even though progress was slow. I now have the skill of getting user input to make something happen and I've used that in the Google StreetView API. While not an Ajax request, it's a start with APIs. Part of why it took me so long is that while the project calls for street and city, Google doesn't always show a photo when the state isn't entered as well. So my own address failed. Quietly. I was using my own address because I couldn't remember how to spell Pennsylvania. After seeing several forum posts that used variations of my solution, I broke down and put in the White House address. And the street view part worked! So I went back and put in my address WITH the state after my city and that worked too!

The course is having me work on my laptop, but once I'm done, I hope to put the app on GitHub pages. I say "hope" because I don't know yet if the New York Times or Wikipedia APIs are https. If they're not, then they won't work on Github pages or CodePen. 

**Link(s) to work**
1. Intro to Ajax - https://classroom.udacity.com/courses/ud110


### Day 54: December 5, 2017 - Time spent, 1 hour

**Today's Progress**:  Solved my internet woes. Learned a bit more about making Ajax requests and how to use my Chrome Developer Tools better. Started Intro to Ajax class on Udacity. 

**Thoughts**: Last night I figured my intermittant internet issues were linked to Google BackUp and Sync trying to sync ALL. THE. THINGS in my photos folders at once. Putting it on pause gave me steady internet. Turning it back on freaks out my router lights. So problem solved for now.

On the coding front. I played around a bit more with what I had yesterday, but still couldn't get a quotes API to return data. So I'm going to build up my Ajax knowledge with a course 
