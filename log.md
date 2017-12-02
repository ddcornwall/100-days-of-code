# 100 Days Of Code - Log

<!--Template for log
### Day 50: December 1, 2017 - Time spent, 1 hour

**Today's Progress**:  

**Thoughts**: 


 

**Links that helped me get stuff done**


**Link(s) to work**


End Template for log-->

DISCLAIMER - This log will contain typos. For the nicely edited version of my progress, visit https://librarianfromalaska.wordpress.com/tag/100daysofcode/

### Day 51: December 2, 2017 - Time spent, 1 hour 15 minutes

**Today's Progress**:  Completed Free Code Camp (FCC) Caesars Cipher challenge. Commited working code to GitHub Repo. Started JSON APIs and Ajax. Raised completed coding challenges to 257. 

**Thoughts**: Today was interesting and another reminder to watch your code punctuation. I wrote pseudocode for working out the Caesar Cipher challenge, translated that to JavaScript and ran my program. Only the first letter of each string was being translated correctly. The other letters weren't being touched. I fiddled with console.log in several places before realizing the best place for one was in my "decoding for loop" that showed me the loop was only executing once. That made me stare at my "if" and "if else" statements for awhile. The logic seem perfect. It worked out by hand. So what was wrong?

I had not closed my "for" loop with a "}", so it only executed once and moved on. Once I closed it, I was golden and moved on to JSON. Part of me thinks I should have picked up on the open loop much earlier. Another part of me reminds me I'm human and have only been coding an hour or so a day for the past seven weeks. Some things will come easier with experience. 

The JSON APIs and Ajax section is much shorter than I realized. Hadn't seen the "two hours" on it before now. After I get finished with that, I have some choices to make in my coding journey:

1. Do I focus on getting my front end developer certificate? 
2. Do I take what I learn from JSON APIs and AJAX and start working with APIs I care about (like US National Archives and NASA?)
3. Do I split the difference, working on a few of the Intermediate Front End Development projects to get a feel for putting everything together and then split off on my own API work, along with revisiting my portfolio?

Right now I'm leaning towards 3, but part of the answer probably depends on what I want from coding. If I want to do a career change, it would probably be best to keep working towards the certificate. It might be good to keep going that way because I have a brillant and talented web developer working for me. I'm her back-up on vacations and other absences. Continuting to work towards the certificate not only helps me understand her work and suggestions better, but would help me whenever she feels its time to move on. MPOW has frequent hiring freezes and I would not be surprised to be in the interim webmaster role for six months or so if my webmaster left. 

On the other hand, I think there is a lot that can be done with government APIs that is interesting to me personally and potentially helpful to my library community. It might be more meaningful to me than additional algorithm challenges. Though I do like the feeling that comes with the solves.

I will think about this some more. 

 

**Links that helped me get stuff done**
1. JavaScript String charCodeAt() Method - https://www.w3schools.com/jsref/jsref_charCodeAt.asp
2. JavaScript String fromCharCode() Method - https://www.w3schools.com/jsref/jsref_fromCharCode.asp
3. ROT13 - https://en.wikipedia.org/wiki/ROT13
4. ASCII Printable characters - http://www.theasciicode.com.ar/ascii-printable-characters/capital-letter-a-uppercase-ascii-code-65.html

**Link(s) to work**
1. Convert JSON Data to HTML - https://www.freecodecamp.org/challenges/convert-json-data-to-html


### Day 50: December 1, 2017 - Time spent, 1 hour 15 minutes.

**Today's Progress**:  Completed Free Code Camp (FCC) Seek and Destroy challenge to my satisfication. Also completed FCC Where do I belong Challenge. Committed solutions to my github repo. Only Caesars Cipher stands between me and JSON APIs and Ajax.

**Thoughts**: Wow! I've made it halfway through the #100DaysOfCode! And I was able to celebrate with two solves - even if one was only vaguely satisfying. 

Generally, when you hear me say something like "Solved it to my satisfication", it means the code works, but not as well as I want it to. It also reflects a decision not to allow the perfect be the enemy of the good. This was the case with the "Seek and Destroy" challenge. I feel like I have learned callback functions and can somewhat use the array.filter method. I also understand the basic logic of the "Seek and Destroy" challenge. If I'd used a set of loops instead of the callback/filter method, I'm confident that I code write code that would support any number of arguments. But because I was using callback with a filter, I wound up settling for hard coding three arguments. An attempt to pass an array and more than three arguments would break my code. But it met all the FCC tests so I'm calling it good. Someday I may know better.

One interesting learning from the "Seek and destroy" seek and destroy challenge was realizing that using "arguments" in JavaScript means that you're taking on EVERYTHING passed to the function. I'm not sure why I didn't realize this up front, but console.log quickly made me wise to it. 

"Where do I belong?" was solved without any reservations on my part. It took several iterations to get, but I'm comfortable with tinkering with something till it works. I'm also very grateful for the array.sort() method, because it means I don't have to code a bubble sort from scratch. Once that sorted my array, I tested the number that was passed along with the array and had the function return the index where it should be inserted. I hit a point where I passed all of the FCC tests except one -- and wasn't getting any output at all for that particular condition. I realized that the number should go at the end of the array, but the loop I set up would complete without taking action if a number was greater than all other numbers in the array. So I put another return statement outside the loop to catch that condition, and problem solved.

Overall, today was much more satisfying than yesterday.
 

**Links that helped me get stuff done**
1. Seek and Destroy - I don't understand at all - https://forum.freecodecamp.org/t/seek-and-destroy-i-dont-understand-at-all/89162/2
2. Array.prototype.sort - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort


**Link(s) to work**
1. FCC Caesar's Cipher - https://www.freecodecamp.org/challenges/caesars-cipher





### Day 49: November 30, 2017 - Time spent, 1 hour

**Today's Progress**: Successfully used deep breathing techniques to avoid throwing my laptop to the floor and stomping on it. Understood that I'm not the only coder who didn't immediately get the filter method. Really got to understand the beauty of Array.prototype.push. Gained new appreciation for the teaching methods of some Free Code Campers. Committed to stay on the Seek and Destroy challenge at least one more day. 

**Thoughts**: Today is the first day in weeks I felt like I made zero headway. I would have actually abandoned this challenge entirely and decided that the javascript filter method was something I could live without if it weren't for fellow Free Code Camp (FCC) Campers. First I found several people who were at least as frustrated as me with the Seek and Destroy challenge. They, like me, had read through documentations on Array.prototype.filter() and were none the wiser. So this told me it wasn't my incompetent self that was the problem. 

What really convinced me to stay on this problem instead of just tossing it to the side was PortableStick's answer to "Seek and Destroy - I don't understand at all!" - They really broke things down step by step, asking the respondent to do mini code writings to get closer and closer to what Array.prototype.filter() is meant to do. By the time I finished reading, I felt like I did understand what a callback function was and how it could be used. I would work on it more this morning, but I have to close up and get ready for work. 

We'll see what happens tomorrow and over the weekend. 
 

**Links that helped me get stuff done**
1. Arguments object - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/arguments
2. Seek and Destory - I don't understand at all! - https://forum.freecodecamp.org/t/seek-and-destroy-i-dont-understand-at-all/89162/2

**Link(s) to work**
https://www.freecodecamp.org/challenges/seek-and-destroy


### Day 48: November 29, 2017 - Time spent, 1 hour

**Today's Progress**:  Completed Mutations and falsy bouncer challenges on Free Code Camp (FCC). Committed working code to Github repo. 

**Thoughts**: While I continue to make mistakes, like reversing the strings in the str.indexOf commmand, I have growing confidence in my programming skills. And the more times I'm presented with an issue, the more I naturally use the correct syntax. I also feel that most of the time, I understand the underlying logic of the problem at hand. 

With Falsy Bouncer, I understood logically exactly what was required. But I couldn't get the Boolean function to play with the array.filter command. I diverted and tried a loop that only loaded true values into a new array. My first instance didn't quite work because it used the same index value ("i") as the original array. It did not contain any false values, but it did have empty items. Just as I was starting to write this log entry, I realized the solution was to create a separate index value for the new array ("j") and only increment J when a new value was loaded into the new array. That worked like a charm!

Now there are only three challenges to go before working with JSON and APIs.
 

**Links that helped me get stuff done**
1. Boolean - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean

**Link(s) to work**
FCC Seek and Destroy - https://www.freecodecamp.org/challenges/seek-and-destroy



### Day 47: November 28, 2017 - Time spent, 1 hour

**Today's Progress**:  Completed Free Code Camp (FCC) challenges of Chunky Monkey and Slasher Flick. Started to work on Mutations. Committed completed code to Github repo. 

**Thoughts**: It was nice to have another day of solving more than one coding challenge. I needed to work a few cycles of "chunky monkey" by hand before an algorithm occurred to me. Mutations will take a bit more work than I first supposed because it's asking about whether ALL the letters in one string are present in another, which is different from my first quick take of the project. Another reminder to understand business requirements clearly before jumping into a project. Fortunately I do think I know what needs to be done. 

Now there are Five challenges left before JSON APIs and Ajax. 


**Links that helped me get stuff done**
1. Array.prototype.slice() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice
2. Array.prototype.push() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push
3. Array.prototype.splice() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice
4. String.prototype.indexOf() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf

**Link(s) to work**
Mutations - https://www.freecodecamp.org/challenges/mutations

### Day 46: November 27, 2017 - Time spent, 1 hour 20 minutes

**Today's Progress**:  Completed the Free Code Camp (FCC) challenges of "Confirm the Ending", "Repeat a string repeat a string" and "Truncate a string", raising my completed code challenges to 247.

**Thoughts**: Testing is our friend. Intermediate print/console.log statements are our friend. It is much easier to tweak code when you run different bits of code and use print statements to make the computer show its work. This was particularly true with the "repeat a string" challenge, where testing show me that my initial approach was doubling strings rather than adding to them. The solution was to introduce a separate variable to track the sum of my strings. I could have also used the second variable to be the added value instead of the sum. 

I'm mostly enjoying the algorithm challenges so far. They're making me think more precisely and that's not a bad thing. Now if I could get out of the habit of starting my if statements with "If" instead of "if." Because as far as Javascript knows "If" is an undefined variable but "if" if the start of a condition statement. 

Seven challenges to go before JSON APIs and Ajax. I'm not going to claim I'm going to knock out three challenges tomorrow. We'll see how things go. 
 

**Links that helped me get stuff done**
1. Change directory in Node.js command prompt - https://stackoverflow.com/questions/31217771/change-directory-in-node-js-command-prompt
2. JavaScript String slice() method - https://www.w3schools.com/jsref/jsref_slice_string.asp

**Link(s) to work**
1. Chunky Monkey (Arrays) - https://www.freecodecamp.org/challenges/chunky-monkey



### Day 45: November 26, 2017 - Time spent, 1 hour

**Today's Progress**:  Completed Return Largest Numbers in Array Free Code Camp (FCC) challenge. Committed the solution to my Github repo. Began consideration of "Confirm the Ending", another string driven problem. 

**Thoughts**: The arrays problem was another coding problem where I was grateful I had node.js to work with. It helped me identify the need for an extra loop in my code. It helped me confirm my understanding of accessing array elements. While I've come to understand that console.log statements will show up in "developer tools" in chrome, many times it's just easier for me to have a standalone execution environment. Plus the ATOM editor. I've gotten better over the weeks at noticing how both ATOM and the FCC environment will help you understand where matching brackets are. That's becoming increasingly helpful in deciding whether I've put code in the right loops or if statements. 

Looking at the FCC challenges map, it looks like I have ten more challenges until I start the JSON API and AJax section. I'm really looking forward to this and if I keep solving problems at my current rate, I hope to start in on JSON before Christmas. 

 
**Link(s) to work**
1. Confirm the Ending - https://www.freecodecamp.org/challenges/confirm-the-ending




### Day 44: November 25, 2017 - Time spent, 1 hour

**Today's Progress**:  Completed Free Code Camp (FCC) Title Case a Sentence challenge. Commited solution to my FCC-Algorithm-Challenges repo on GitHub. 

**Thoughts**: This cannot be said often enough, "Comb through every line of your code!" I probably could have done this challenge in half the time if I would have realized early on I had typos in a variable name and had not added "()" to the end of a string function. 

One typo I don't feel guilty about is that regular expressions always have to have a concluding "/" after them even if you don't use extra flags. For example, if you wanted to search for every occurance of a lowercase letter in a string, you'd use the expression ```/[a-z]/g``` The g stands for "global", i.e. the whole string. But I only wanted to check the first letter in a string so I used ```/[a-z]```. That gave me a syntax error with an obscure message. I finally found something on the web that showed that the concluding "/" was mandatory, flag or no flag. 

I take comfort from the fact that I seem to understand the logic of these puzzles reasonably well. But while I accept I'll never catch 100% of my maddening typos - especially when they're only a letter off from what I intended - I wish I did a better job at catching them. 

Tomorrow I will start on FCC's "Return Largest Numbers in Arrays" - At first blush the logic seems simple:

1. Test each array for the largest number (I did something similar in "Find the longest word in a string")
2. Load the largest number in an array into an array of largest numbers
3. Return the largest array

We'll see if it's as straightforward as it sounds. 1 & 2 above need to be broken down into smaller steps. It is nice how my prior FCC experience gives me ideas to solve the new challenges.
 

**Links that helped me get stuff done**
1. unclosed-regex.md - https://github.com/jamesallardice/jslint-error-explanations/blob/master/message-articles/unclosed-regex.md

**Link(s) to work**
Return Largest Numbers in Arrays - https://www.freecodecamp.org/challenges/return-largest-numbers-in-arrays



### Day 43: November 24, 2017 - Time spent, 1 hour

**Today's Progress**:  Completed Free Code Camp "Longest Word Challenge", moved on to "Title Case a Sentence."

**Thoughts**: Overthinking can be a danger in programming. I was messing around with trying to compare each element of my array to each other. Once I realized that I only needed to compare them to the current longest length, this challenge was very easy with a for loop. Node.js was helpful in console logging my array string so I could make sure my for loop was getting the whole string and nothing more.

The most straightfoward approach to my current problem, "Title Case a Sentence" did not work as individual characters in a string cannot be simply assigned new values. I've looked over two of three hints for this project. I had already completed hint 1 before looking (spilt sentence into an array of words) and have enough to get started tomorrow. 

If you're curious about my particular coding solutions for the challenges, you can check out my repo for the algorithm challenges at https://github.com/ddcornwall/fcc-algorithm-challenges. 
 

**Links that helped me get stuff done**
1. FCC Understand String Immutability - https://www.freecodecamp.org/challenges/understand-string-immutability
2. freeCodeCamp Algorithm Challenge Guide: Title Case a Sentence - https://forum.freecodecamp.org/t/freecodecamp-algorithm-challenge-guide-title-case-a-sentence/16088

**Link(s) to work**
Title Case a Sentence - https://www.freecodecamp.org/challenges/title-case-a-sentence



### Day 42: November 23, 2017 - Time spent, 1 hour

**Today's Progress**:  Completed Free Code Camp (FCC) Palindrome challenge. Started on "Find Longest Word" challenge. 

**Thoughts**: The Palindrome challenge went as expected. I will confess to temporalily confusing alphanumeric with alphabetical. It is important to be as detail oriented as you possibly can in these challenges. It was a fun exercise and, I as suspected, my previous work in reversing a string made it easier.

The Longest word challenge is interesting. I'm working with for loops and it seems to be a challenge to go just to the end of an array and no farther. I might change my idea into a while loop. 

I'm also starting to think that these algorithm challenges will likely eat up the rest of my 100 days. I am learning new and interesting things and that's a good thing. I also know that I want to tackle the JSON and API section because there are a lot of APIs out there I would like to start working with. I'm tempted to jump ahead but then I think the the algorithm challenges may come in handy with the next set of projects. So maybe I'll flow into a R2 right away. We'll see. 
 

**Links that helped me get stuff done**
1. javascript regex to return letters only - https://stackoverflow.com/questions/23136947/javascript-regex-to-return-letters-only

2. JavaScript String replace() Method - https://www.w3schools.com/jsref/jsref_replace.asp

3. String.prototype.toLowerCase() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toLowerCase

4. String.prototype.split() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/split

**Link(s) to work**
https://www.freecodecamp.org/challenges/find-the-longest-word-in-a-string




### Day 41: November 22, 2017 - Time spent, 1 hour

**Today's Progress**:  Solved the Factorialize A Number challenge to the satisifaction of Free Code Camp (FCC). Began planning the Check for Palindromes challenge.

**Thoughts**: It's good that there is more than one way to solve a coding challenge. I tweaked my recursion based solution some more in hopes of it being accepted by FCC (remember it does work in node.js), but no dice. Then I remembered a few people online mention that they work working on solutions involving while loops. I refreshed my memory on the structure of while loops and then quickly coded a solution that yielded the answer after a few trials. FCC granted me an "Escape Velocity Reached" and I moved on to the palindrome challenge. 

A palindrome is a set of letters that read the same backwards or forwards, not counting spaces of special characters. In psuedocode this looks simple:

```
Accept the string
Strip out non-letter characters
copy the reverse of the stripped string into a variable, say "revstring"
compare revstring to stripped string and report whether match or not
```

I'm guessing my previous work on the "reverse a string" will be helpful here provided I figure out how to strip out non-letter values. 

 

**Links that helped me get stuff done**
1. Javascript while loops - https://www.w3schools.com/js/js_loop_while.asp

2. String.prototype.replace() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replace

3. String.prototype.toLowerCase() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toLowerCase

4. JavaScript RegExp Reference - https://www.w3schools.com/jsref/jsref_obj_regexp.asp 

**Link(s) to work**
1. Check for palindromes - https://www.freecodecamp.org/challenges/check-for-palindromes



### Day 40: November 21, 2017 - Time spent, 1 hour 15 minutes

**Today's Progress**:  Successfully transitioned my CodePen portfolio page to standalone. Tested on MS Edge, Chrome, Firefox and on Chrome mobile in Pixel. Tested against WAVE Evaluation tool and issues noted. 

**Thoughts**:  Last night was a misery of coughing and sneezing, but I was determined to code anyway. Despite my illness, I was able to transition my portfolio from CodePen to a standalone site. I commented out my contact form until such time that I connect it up with a mail server. 

In moving the page over, I feel like I've got a good start on a checklist for porting a page or application between platforms:

- Check for dependencies: bootstrap, your own CSS, JQuery, JavaScript, etc.
- Put page code into HTML wrapper if needed.
- Check for unmatched brackets and parenthesis
- Post to new platform
- Test in at least two browsers and your phone
- Test against WAVE Evaluation tool

About WAVE - It dinged me to duplicate links. At first it's because I truly had duplicate links, one for my page image and one for my caption. WAVE opened my eyes to the fact that I could wrap one ```a href``` tag around both. But after that it still dinged me. I've checked my code a few times and I can't see the problem. It also pointed out contrast errors in the link color of my navbar. This is an issue that plagued me before I had my eyes opened about accessibility. I'm still mostly lost on how to change that. So it will go into my enhancements list for the page.

My enhancements list for my portfolio page include:
- Fixing the link contrast issues in my navbar.
- Having the ```active``` attribute in my navbar light up when you're in that section of the page. 
- Having a functional contact form.
- Seeing if there are ways to make my page prettier but accessible. I won't be using background images for accessibility reasons but there are probably other approaches. 

Now that my page is up in a mostly usable form and some of the enhancements depend on my learning more, I'm going to leave it as it is for now till I get more insight. Tomorrow, if I'm not feeling too bad to code will be to return to the Factorialize A Number at Free Code Camp (FCC). I have the basic idea down, I believe, but I will tear down my code to the bottom and rebuild it parts till I get it returning some kind of number in FCC. 

My closing thought before I go back to bed is that now that I've been at this for 40 days, my first reaction to a problem isn't "Huh? What?" but "I think it might be X. Let's try X and see what happens. If X doesn't fix it, I have the vocabulary to search for a solution." It's a nice place to be at. 


 

**Links that helped me get stuff done**
1. Wave Evaluation tool - http://wave.webaim.org/extension/

**Link(s) to work**
1. Portfolio page - https://ddcornwall.github.io/portfolio
2. Factorialize a Number - https://www.freecodecamp.org/challenges/factorialize-a-number



### Day 39: November 20, 2017 - Time spent, 1 hour

**Today's Progress**:  Completed transition of Free Code Camp (FCC) Tribute page from CodePen to standalone web page. Fixed mobile display and found colors that suited me AND passed the WAVE evaluation tool. Put my portfolio page CodePen Code into an HTML wrapper. 

**Thoughts**: This was a productive day and made me think about what might be lurking in the background of the various tools we use. For example, my CodePen portfolio page had acceptable text size in my mobile view, but my standalone page did not. I fixed my text display by using a responsive meta tag (see below). That makes me think that the CodePen site has responsive meta tags as well that my "bundled" CodePen was getting the benefit of. 

I didn't notice the responsive meta tag in my review of "Responsive Design with Bootstrap" at FCC. My searches for "text not resizing in Bootstrap" gave me results on media queries that might have been helpful but I couldn't quite wrap my brain around yet. I'm trying to avoid simply copying and pasting code snippets whose function I don't really understand. So I went back to my CodePen and checked all the behind the scenes settings to make sure I hadn't left something behind. I hadn't, BUT - under HTML settings right underneath the "Stuff for head" window was a button that said "Insert the most common viewport meta tag." So I pressed the button and got:

```<meta name="viewport" content="width=device-width, initial-scale=1">```

I copied and pasted that line into Google and got back the page below. I already knew that "viewport" was basically a device screen size. The "Responsive Meta tag" page explained that the other two values instructed the device to show all of the content within its screen at its default font size setting. These concepts I easily understood and dropped the tag into my standalone page. That took care of text sizes on different screens. I tested my pixel phone with chrome as well as desktop versions of Microsoft Edge, Firefox and Chrome. 

The next step was to reconsider my color scheme. While my purplish background and link colors satisifed the WAVE Evaluation tool, it didn't satisfy ME. So I said goodbye to the Jumbotron, reverted to the original link color and put a border with a 5% margin around my text by inline css in the container-fluid div. I liked the look and the WAVE Evaluator liked the colors. 

Unless I get some major "please fix this" feedback on this page, I'm done for now. At some point, I should double check with a screenreader to back up WAVE's claims and I need to learn more about keyboard navigation. 

My next stop is posting my portfolio page as a standalone web page that looks good in mobile and passes the WAVE Evaluation tool. Then it will be a rebuild of the FCC Factorial exercise. 
 

**Links that helped me get stuff done**
1. Responsive meta tag - https://css-tricks.com/snippets/html/responsive-meta-tag/
2. WAVE Evaluation tool - http://wave.webaim.org/extension/

**Link(s) to work**
1. FCC Portfolio page - https://ddcornwall.github.io/portfolio (coming soon!)
2. FCC Tribute page (completed standalone) - https://ddcornwall.github.io/fcc-tribute/


### Day 38: November 19, 2017 - Time spent, 1 hour

**Today's Progress**:  Solved my link color problem. Manipulated link and background color on tribute page until I got a combination that passed the WebAim WAVE evaluation tool. Cloned my portfolio page Github repo in preparation for posting on Github pages. 

**Thoughts**: 
The first breakthrough was once again paying attention to details. I somehow had missed that I did not put a "#" in front of my color changes. ```{color:23297C;}``` iis worthless but ```{color:#23297C;}``` will actually work. 

Next it took me some time to realize that the contrast tool that came with WAVE wasn't making recommendations on the basis of what my colors actually were. It was just a pallete to play with. Not realizing this I had several go rounds of changing my code to what I thought what WAVE wanted but that didn't affect my scoring. 

I gave some thought to just tossing the issue aside, but I have a friend and coworker who is a strong advocate for accessibility and I could hear their voice in my ear, along with Laura Kalbag, author of "Accessibility for Everyone" telling me accessiblity is not a nice to have, but something that should be built in from the beginning. So I soldiered on and found what was advertised as a WCAG contrast checker (see below) that had you enter values for your background and foreground colors. If you're not comfortable with hex values, it has color pickers. As you vary the colors, buttons below offer pass fails on several contrast scores, including color difference, used in determining suitability for color blindness.

I had to give up on my gray background, because I could not find anything with a gray background that could pass a color difference test. so I have the purplish background. I might fiddle a bit more later. Also while the link color looks good against the purplish background, I think it gets lost on the white background my contact links are on. 

Just now I thought to look up the mobile view of the tribute page. And it looks completely unresponsive. CodePen must have been doing me some behind the scenes favors because I got the mobile view looking ok on that. So improving the mobile look now becomes job one. Sometimes coding feels lack whack-a-mole. 

 

**Links that helped me get stuff done**
1.  Changing color of my links in Bootstrap Navbar - https://stackoverflow.com/questions/30633635/changing-the-color-of-the-links-in-my-bootstrap-navbar
2. Contrast checker - https://contrastchecker.com/

**Link(s) to work**
1. FCC Tribute page - https://ddcornwall.github.io/fcc-tribute/

### Day 37: November 18, 2017 - Time spent, 1 hour

**Today's Progress**:  Successfully migrated my Free Code Camp Tribute page to Github pages. Learned how to sync my local Github repositories to my online account. Tested tribute page with WAVE accessibility checker and began efforts to increase my link contrast. 

**Thoughts**: It was great to have a productive day. I like having a stand alone tribute page. As I suspected, once my code was by itself instead of a CodePen wrapper, WAVE was able to actually analyze my page. I got passing marks for everything except the low contrast of my links. I tried fixing them in a ```<style>``` block that followed my loading of Bootstrap but that didn't change my my link colors. Here's my full "head" code:

```
<head>
  <meta charset="utf-8">

  <title>Mahatma Gandhi - FCC Tribute page</title>
  <meta name="description" content="Celebration of the life of Mahatma Gandhi, composed as a Free Code Camp (FCC) project. ">
  <meta name="author" content="Daniel Cornwall">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/css/bootstrap.min.css">
<style>
<--!To increase link contrast to meet WCAG AA standards.-->
a {color: 1d1dff;}
</style>

</head>
```

I would have thought that the ```<style``` for a would have overridden the previously loaded Bootstrap, but not so much. The next time I'm coding I'll do more read/search and see what I can come up with. Perhaps for this page I'll abandon Bootstrap since I only need it for the Jumbotron and I've learned some new ways to code background colors easily. But I do want to try first. 

After I resolve the contrast issue, I think my next step is creating a portfolio page on Github pages. Then I'll go back to Factorializing and see if I can get my working algorithm into something that FCC will accept. 


 

**Links that helped me get stuff done**
1. Github pages - http://pages.github.com
2. WAVE Accessibility checker - http://wave.webaim.org/extension/

**Link(s) to work**
FCC Tribute Page - https://ddcornwall.github.io/fcc-tribute/ (Working to increase link contrast) 



### Day 36: November 17, 2017 - Time spent, 1 hour 20 min

**Today's Progress**:  Installed GitHub Desktop and ATOM editor. Syncronized two of my repos on my desktop. Put Free Code Camp (FCC) tribute page into an HTML wrapper. 

**Thoughts**: I didn't get any more responses to my FCC Forum ask on my factorial project and still hadn't noodled out why, despite functional code console.log doesn't work in FCC and "return", while apparently breaking correctly, doesn't work in node.js. Further mystery - why this version of factorial.js won't at least return wrong value in FCC. 

So I decided to let my unconscious work on that problem and set myself the task of setting up an environment where I can publish full web pages instead of codepens. I've done most of the spade work to get started on Github Pages and I've set up github deskstop so I can just push changes to files instead of manually uploading files. It was a bit confusing to figure out how to start working with my pages until I saw a suggestion in Github Desktop to start using the ATOM editor. I did that and started off by putting my tribute page code into an HTML 5 wrapper. Tomorrow I will look up the link to add Bootstrap to it and then try my hand at publishing it as a project page. Then I can test it for accessibility using the WAVE evaluation tool. 
 

**Links that helped me get stuff done**
1. Github pages - https://pages.github.com/

**Link(s) to work**
https://pages.github.com/ to set up pages. 


### Day 35: November 16, 2017 - Time spent, 1 hour 30 minutes

**Today's Progress**:  Got a working Factorialize a Number program in node.js, but cannot get Free Code Camp (FCC) to accept it. Did various troubleshooting and read documentation for Javascript return statement and node.js. Submitted a help question to the FCC forum. 

**Thoughts**: So now I have working code in node.js, but not in FCC. I've added the working version to my Github repo for the algorithm projects. There was a lot of read/search this morning. Since I started my log entry, I got one response to my forum question. It is helpful in understanding part of why FCC isn't accepting my code, but doesn't get me further along. The respondent pointed out I had declared a global variable, therefore, FCC was storing the previous value of my function calls. This does make sense, but doesn't explain why nothing at all is being returned to the console. 

Speaking of "no returns", I can't get node.js to display ANYTHING in a return statement, not even ```return("Hello World");``` I had to use console.log statements to verify my code is working. So far my node.js research has not turned up an answer to this problem. 

**Links that helped me get stuff done**
1. Installing Node.js Tutorial: Windows - http://nodesource.com/blog/installing-nodejs-tutorial-windows/

2. Getting started in developing Node.js in Windows by AJ Bubb - http://www.altifysoftware.com/developing-node-js-in-windows/

3. Recursion (Fun Fun Function) - https://youtu.be/k7-N8R0-KY4

4. Return statement in javascript - https://docs.microsoft.com/en-us/scripting/javascript/reference/return-statement-javascript

5. Markdown formatting cheatsheet (for displaying code in FCC and other forums) - https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code

**Link(s) to work**
1. https://www.freecodecamp.org/challenges/factorialize-a-number



### Day 34: November 15, 2017 - Time spent, 1 hour

**Today's Progress**:  Figured out all but one case of the Free Code Camp (FCC) Factorialize a Number challenge. Installed Node js on my laptop. Committed the "all but 0" version of my solution to my Github repository. 

**Thoughts**: Recursion was definitely the ticket for this challenge. It's so weird to have a function call itself, but it works. Unless you ask it to factorialize 0. Then it returns "undefined" even though I have a return statement that should take care of that.

I decided that the developer console was too clunky for me, so after a bit of research I settled on node js. I had to review the documentation a little before I got actual output from my code, but it is nice to be able to write in notepad and see the full execution of my scripts instead of just the last line. At some point, I will need to move from console.log in progress to actual return statements so that FCC will accept my work. 

**Links that helped me get stuff done**
1. Installing Node.js Tutorial: Windows - http://nodesource.com/blog/installing-nodejs-tutorial-windows/

2. Getting started in developing Node.js in Windows by AJ Bubb - http://www.altifysoftware.com/developing-node-js-in-windows/

3. Recursion (Fun Fun Function) - https://youtu.be/k7-N8R0-KY4

**Link(s) to work**
1. https://www.freecodecamp.org/challenges/factorialize-a-number



### Day 33: November 14, 2017 - Time spent, 1 hour 15 minutes

**Today's Progress**:  Completed Free Code Camp (FCC) the "Reverse a String" challenge.  Started a Github repository for my code solutons at https://github.com/ddcornwall/fcc-algorithm-challenges/tree/master. Began Factoralize A Number challenge, much harder than it looks. Started looking at recursion. 

**Thoughts**: Definitely feeling challenged and learning new things. I went through several iterations of loops that gave results either much below target or many orders of magnitude above target. Looked at hints and started wrapping my brain around recursion. I HIGHLY recommend the YouTube video listed below. The instructor is both clear and funny. I feel like I now understand the concept, but my implementation is going to take a lot more work. 

The factorialization problem is a great example of something that can be explained to a human being quite quickly but difficult to get across to a computer. 

Now, off to work for me. 

**Links that helped me get stuff done**
1. Array.prototype.join() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/join - Knowing about inserted separators was important. 

2. freeCodeCamp Algorithm Challenge Guide: Factorialize A Number - https://forum.freecodecamp.org/t/freecodecamp-algorithm-challenge-guide-factorialize-a-number/16013

3. Recursion (Fun Fun Function) - https://youtu.be/k7-N8R0-KY4

**Link(s) to work**
1. https://www.freecodecamp.org/challenges/reverse-a-string




### Day 32: November 13, 2017 - Time spent, 1 hour

**Today's Progress**:  Raised completed Free Code Camp Challenges up to 238. Hit the first of the Algorithm Challenges. Started solving the "Reverse a String" challenge. Along the way learned more about JavaScript arrays. Though I'm not sure why anyone would want to reduce an array.

**Thoughts**: Happy that I'm still coding away. Grateful for FCC's explanation of the algorithm challenges and how they expected them to be frustrating. Reverse a String was easy enough to put into pseudocode and I thought FCC's "helpful links" were generous. It took me a bit to figure out how to get the string into an array. My first guess was to try and using the str.split function with a regular expression for a non-space character but that gave me error messages. I decided I was overthinking things and used a for loop with string and array index values to get the string into an array. 

I have to get ready for work soon, so I didn't finish the challenge. But I feel pretty clear on how to reverse the array, convert it back to a string and return the reversed string. 

I have a feeling that I'll be writing a lot of pseudocode over the next few weeks. 

**Links that helped me get stuff done**
1. String -https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String 

**Link(s) to work**
1. https://www.freecodecamp.org/challenges/reverse-a-string



### Day 31: November 12, 2017 - Time spent, 1 hour

**Today's Progress**:  Solved the Profile Lookup exercise on Free Code Camp (FCC), raised my completed coding challenges to 227 and learned about general expressions and the beginnings of object oriented programming. Possibly learned how word processors do word counts - using some form of a general expression to find non-whitespace groups of characters. In JavaScript this would be \S+.

**Thoughts**: My problem with the loop in the Profile Lookup exercise is that I had originally tried to combine "no such contact" and "no such property" in my loop. Looking back it should have been obvious that only the first name in the profiles list weould ever return a result about property. So I moved (I thought) the "no such contact" statement outside the loop. The only way the program should get to that statment is if the loop fully executed without finding a name. 

But it still didn't work. Not until I carefully counted all my curly brackets and noted where my (return "no such contact") statement was. As far as the computer was concerned, that was still in the loop, breaking it whenever the first contact wasn't an input. So I moved my curly bracket and the program worked. 

After that, most of the challenges went easy even though many of them covered new-to-me stuff. I've already gotten a health respect for "regular expressions" that can search strings and I'm looking forward to getting in deeper into Object Oriented Programming.

Lastly, I'd like to thank several people on Twitter who let me know that there is a free simple javascript console in most modern browsers. See the links below for details. Learning programming has so much more support these days than when I was in college. 


 

**Links that helped me get stuff done**
1. How To Use the JavaScript Developer Console - https://www.digitalocean.com/community/tutorials/how-to-use-the-javascript-developer-console
2. How can I run JavaScript programs in my computer offline?! - https://www.codecademy.com/en/forum_questions/55edac31d3292f78cc000080 (This covered "control-enter" to get yourself new lines to write multline Javascript in the command line console. )



### Day 30: November 11, 2017 - Time spent, 1 hour 30 minutes

**Today's Progress**: Raised the number of completed coding challenges to 216. Learned how to insert "troubleshooting printouts" into Free Code Camp (FCC) code challenges. Worked on FCC Profile lookup. 

**Thoughts**: The FCC Profile Lookup is a challenge that looked straightforward but wasn't. I wound up looking at the hints page BUT NOT THE CODE. I had originally thought that the look up was going to be along the lines of "Using Objects for Lookups" at https://www.freecodecamp.org/challenges/using-objects-for-lookups but I wasn't sure how to go through a compound list like the dating profiles using that. The hint, not so shocking, was to use for loops and equality checks. 

That's where I'm at now, but my code seems to be breaking its loop too early. I figured this out by adding some items to my return statements, including where my loop iteration was. Along the way I also forced the FCC console to accept input of my choosing by reassigning the function's parameters within my function - something that should not should be done in production.

Forcing the parameters to ones of my choosing did demonstrate that I have the equality test and property tests formatted correctly. But my logic in combining them with my loop isn't sound. 

I'm not ready to give up yet. Though I do think I need somewhere to run and display javascript outside of Free Code Camp. I also need to get ready for a still life photography opportunity as there is more to life than coding. If the weather holds I'm also looking forward to seeing the new Thor movie with a few friends of mine. 
 

**Links that helped me get stuff done**
1. freeCodeCamp Challenge Guide: Profile Lookup - https://forum.freecodecamp.org/t/freecodecamp-challenge-guide-profile-lookup/18259

**Link(s) to work**
1. FCC Profile Lookup - https://www.freecodecamp.org/challenges/profile-lookup

### Day 29: November 10, 2017 - Time spent, 1 hour 30 minutes

**Today's Progress**: Successfully completed the card sorting challenge. Worked though other Free Code Camp (FCC) coding challenges to raise my completion total to 214. Learned new stuff about JavaScript objects and reviewed loops which is pretty much them same idea in many coding languages. 

**Thoughts**: Typos matter. If you write a letter or e-mail to another human being and there are typos, you will likely be understood. The reader may or may not be judgemental towards you but they will usually understand you. Not so with computers, not so!

Let's start with the card counting challenge. The first thing I did this morning was to take a notebook and some test data and run the algorithm by hand. It worked. Got the results I was supposed to get - really. But my code wasn't running that way. In the FCC environment it is a little hard to tell how your intermediate steps run as they just give you the final line of output. After some additional noodling around, I decided to look at the hint page. Results:

Hint 1 - Yep I did that.
Hint 2 - Previously done.
Hint 3 - Yes, I fingured that's how it was done. But my code produces different results.

After that was "spolier alert - here's the solved code." I only looked at it because I felt I had followed all three hints.

Surprise! To my mind, the code solution matched my code exactly! I had already written this and yet it didn't give the same result. For a moment I indulged a fantasy of FCC not running code correctly. But I realized the problem was most likely coder error. Even though I THOUGHT my solution looked like theirs, there must be a typo if I just look hard enough. 

Sure enough. Fixing a missing curly bracket in my switch and realizing that my "copy-paste-edit" approach had left me with two Jacks and no Aces was enough for my output to match the what the challenge asked for. 

Feel free to judge me if you want because I did see the final code and maybe I should have kept just staring at my code after reading through the hints and knowing I had to be on the right track. I'm counting it as a win because I chose the correct elements,the pseudo code of the algorithm was exactly right and the fixes amounted to clerical changes and not a change in approach. But I will spend more time reviewing code for typos in the future. 

Some of the other challenges this morning took longer due to typos of some sort of another. But all (mostly case sensitivity) were resolved without references to hints or code. 

I'm human. I will make mistakes. But on some level it is nice knowing that so far, I'm getting the thinking straight and mostly need to honor punctuation and case sensitivity. 


**Links that helped me get stuff done**
1. FCC Challenge Guide: Counting Cards - https://forum.freecodecamp.org/t/freecodecamp-challenge-guide-counting-cards/16809

**Link(s) to work**
1. FCC Counting Cards challenge - https://www.freecodecamp.org/challenges/counting-cards


### Day 28: November 9, 2017 - Time spent, 1 hour 20 minutes

**Today's Progress**:  Brought my Free Code Camp (FCC) completed code challenge count up to to 197. Learned new JavaScript tools like "switch." Figured out one way to partially solve card counting challenge. 

**Thoughts**: On the card counting challenge I haven't run out of ideas, but I have run out of time. I find that I'm most consistent about coding when I do it first thing in the morning. On the plus side, for 28 days I've been consistently coding an hour or so day. Since I have a day job, the downside is that I only code for about an hour or so a day. But I'm happy for the coding time. 

I did figure out part of the card counting challenge. Since 7,8,9 don't affect the card count, I pulled them out of the function proper. Now those work. Tomorrow I'll probably change my code from being switch based to if then based in case I don't understand the new to me switch logic. If that doesn't work, I'll probably spend some pen and paper time working with the algorithm and seeing if I can generate pseudocode for it. 

I'm not discouraged. Actually, after racing though a lot of JavaScript review, when I got to this challenge and didn't get it right off, I thought "FINALLY! A challenge!" For some reason I picture Chris Hemsworth's Thor saying this. Although certainly not in response to a coding challenge. Loki strikes me more as the hacker type. He'd definitely pick up coding if he thought it was a shortcut to global domination. 

Tomorrow is a holiday for me. So I might get in more coding time. It does seem like I will need it!
 

**Link(s) to work**
https://www.freecodecamp.org/challenges/counting-cards


### Day 27: November 8, 2017 - Time spent, 1 hour

**Today's Progress**: Worked up to 185 completed Free Code Camp (FCC) code challenges. Learned more about manipulating arrays in JavaScript and reviewed if-then statements and value comparisons.

**Thoughts**: Some of the Java array stuff really gave me a workout. I'm going to have to work at remembering what shift and unshift to. Pop and push made more sense to me. I might be naive, but it could be I actually do know more JavaScript than I thought I did. At least much seems familiar. Or it's just the product of having a nodding accquaintance with several coding languages. 

**Links that helped me get stuff done**
1. Free Code Camp - https://www.freecodecamp.org/

### Day 26: November 7, 2017 - Time spent, 1 hour

**Today's Progress**: Committed Free Code Camp (FCC) Portfolio page code to GitHub. Worked on FCC Javascript code challenges. Have now completed 157 coding challenges so far.  

**Thoughts**: This has been a nice break. I've been exposed to javascript before. Just not proficient enough to claim it as a skill. Yet. Focused mostly on variable assignment, arithmetic and basic string functions that are common to a lot of programming languages. So far a good review. Expect more new learning soon. 

**Links that helped me get stuff done**
https://www.freecodecamp.org/



### Day 25: November 6, 2017 - Time spent, 1 hour 15 minutes

**Today's Progress**:  Fulfilled all of the user stories for the Free Code Camp (FCC) assignment, made my social media buttons a little prettier by making them ovals and submitted the Portfolio page. 

**Thoughts**: In my worklife I have worked with coders (mostly webdev, but also few database people). I give them a list of business requirements (at my best) and negociate a rough timeline to get it done. It's usually fine for them to offer refinements in their work but not if it unduly delays project completion. As long as the project meets the basic business requirements, it can be launched and enhancements added later.

In that spirit, I went back to the FCC Portfolio assignment and reminded myself of the user stories that needed to be fulfilled:

1) User Story: I can access all of the portfolio webpage's content just by scrolling.
2) User Story: I can click different buttons that will take me to the portfolio creator's different social media pages.
3) User Story: I can see thumbnail images of different projects the portfolio creator has built (if you haven't built any websites before, use placeholders.)
4) User Story: I navigate to different sections of the webpage by clicking buttons in the navigation.

My project does meet all four conditions. I included a few actual thumbnails to give the page a more finished look. Before submitting, I looked over my remaining items from  my to-do list from yesterday :

1) Make top menu items highlight on mouseover. Bonus - get them to light up as you scroll through the page. 
2) Revisit social media button issue - can we make it pretty(ish) on desktop and still have workable mobile display?

The issue of not being able to change :hover behavior turned out to occur in my buttons as well as the navbar. I did more research into the this question before letting it go again. I also ditched my external style sheet since it was not producing the effects I wanted. I also realized that with the world going mobile, hover effects are becoming less of a big deal. After all, how do you deal with hover on touch screens? If you have ideas, send them my way. 

I used the border radius command to make my social media buttons ovals. 

Learned something fun about the interaction of the bootstrap grid and the "text-center" attribute. I had originally centered my thumbnail captions, but I noticed that it did not look centered correctly on the full laptop screen. Was fine on phones, was fine in the quasi-tablet size of the editor view, but just odd in the full page view. Then I realized that in every case the text was completely centered in it's col-xs-6 column. Rather than fiddle with the images (which I think I tried before), I took away the centering and now the thumbnails plus captions look acceptable.

I deliberately used small file sizes for the images to help with page loading speed. I'd love feedback and whether there's unacceptable pixilation on larger screens. 

After these changes I submitted my page. I think it's decent and meets the business requirements but I'm looking forward to revising it as I learn more. Now on the FCC Javascript coding challenges. 


**Links that helped me get stuff done**
CSS Buttons - https://www.w3schools.com/css/css3_buttons.asp

**Link(s) to work**
1. My Porfolio page - https://codepen.io/ddcornwall/full/zEQELW/
2. Free Code Camp (FCC) Portfolio example - https://codepen.io/freeCodeCamp/full/YqLyXB - Seemed to be working as of 11/2/2017.
3. FCC Portfolio Assignment - https://www.freecodecamp.org/challenges/build-a-personal-portfolio-webpage




### Day 24: November 5, 2017 - Time spent, 1 hour 20 minutes

**Today's Progress**:  Prettied up the "does not work" notice on my contact form. Added textual content to introduction and work examples. Learned more ways not to do things. 

**Thoughts**: Here's my current to-do list for the portfolio page as of yesterday:

1) Make top menu items highlight on mouseover. Bonus - get them to light up as you scroll through the page. 
2) Go back to e-mail form, this time finding a way to link the form to an e-mail server so no mail client needed.
3) Revisit social media button issue - can we make it pretty(ish) on desktop and still have workable mobile display?
4) After look and feel issues dealt with, update page with content instead of placeholders.

As I mentioned yesterday, I hit a wall with my navbar. Something is overriding my efforts to style my navbar links based on :hover. I can affect the base elements just fine, so I know it's not an issue with selecting the right item. Just something in the background that decided it knows best how to treat hover and click behavior. So I decided to let that rest and move on to my contact form.

I don't have a way within CodePen to make the form work. But, it seems that for this particular challenge, the contact form doesn't actually have to WORK. A close reading of the project rules at https://www.freecodecamp.org/challenges/build-a-personal-portfolio-webpage implies this, but it took the "formspree" discussion listed below to make that clear for me. So I will mark that as done FOR NOW. I will revisit it when I work more on backend development modules and find myself a cheap place to host PHP and Python that provides a production environment. 

Another reason I could use a production environment is for accessibility testing. I actually started this morning's coding session by downloading and installing the WAVE Accessiblity Evaluation tool into Chrome and testing my Free Code Camp (FCC) tribute page. Unfortunately, the tool told me more about CodePen's accessibility issues than my actual page. The report was clearly presented by since a Pen is basically wrapped in CodePen, WAVE didn't see the underlying content. So if I want MY code evaluated, I need to host it elsewhere. As long as I only use HTML/CSS/BootStrap and Javascript, I could use pages.github.com, but I think I want a more general solution. 

Now back to my checklist. After concluding that for THIS exercise, my form is acceptable, I moved back to my social media buttons. Now new ideas there. Maybe I could make them rounded. Still committed to words over icons as an accesssibility and kind to newebies choice. Though I don't know how many newbies would be looking at a developer page. 

So, having looked and not improved items 1-3, I replaced some of my placeholder text with real text. Today I'll probably create real images outside of coding time and upload and link them in my next coding session. I'll also tweak my buttons and do more read/search/ask on my navbar. 



**Links that helped me get stuff done**
1) Can JavaScript email a form? - 
http://javascript-coder.com/javascript-form/javascript-email-form.phtml

2) Formspree - a free working contact form for your portfolio - 
https://forum.freecodecamp.org/t/formspree-a-free-working-contact-form-for-your-portfolio/32442

3) How can I run my PHP content on GitHub pages? (Spoiler Alert - You Can't) - https://www.quora.com/How-can-I-run-my-PHP-content-on-GitHub-pages

4) WAVE Accessibility Evaluation Tool - http://wave.webaim.org/extension/

**Link(s) to work**
1. My Porfolio page - https://codepen.io/ddcornwall/full/zEQELW/
2. Free Code Camp (FCC) Portfolio example - https://codepen.io/freeCodeCamp/full/YqLyXB - Seemed to be working as of 11/2/2017.



### Day 23: November 4, 2017 - Time spent, 1 hour 20 Minutes

**Today's Progress**:  For learning, it was great! I refreshed my JQuery, used it to select almost any element I wanted outside of the navbar. I learned two ways to implement an external style sheet on Codepen to override most of bootstrap. (I chose to use a special codepen. It refreshes immediately.) I refreshed myself on css link selectors. I can make any link outside of my navbar do whatever I want. 

Oh! You meant coding progress! Yeah, not so much. 

**Thoughts**: 

"I have not failed 700 times. I have not failed once. I have succeeded in proving that those 700 ways will not work. When I have
eliminated the ways that will not work, I will find the way that will work." - Attributed to Thomas Edison on his efforts to create an incandescant light bulb. Likely not original quote. See http://answers.google.com/answers/threadview?id=747226 for context. 

Instead of giving you a blow by blow of trial and effort, let me summmarize:

- Outside of the navbar, I have found several ways to make links do what I want to do.
- Inside the navbar, I can target "a" elements through both JQuery and CSS, but efforts to change styling based on behavior like a:hover fail. 

On the second point, I read that definitions of a:hover won't take unless it comes after a:link and a:visited. Just to be on the safe side I added definitions to a:link and a:visited above my a:hover just in case. Didn't matter. Didn't think it would since a:hover had worked fine on a link outside the navbar.

I know I can select links inside the navbar because ".nav > li > a" works like a charm. But ".nav > li > a:hover" does not. And yes, my custom style sheet does load after Bootstrap. 

Unless I great crazy inspired or someone drops a hint out of the blue, I'm going to shift to my contact form for awhile, locating a mail server I trust I can connect it to. 
 

**Links that helped me get stuff done**
1. CSS :link Selector - https://www.w3schools.com/cssref/sel_link.asp
2. Targent HTML elements with selectors using JQuery - https://www.freecodecamp.org/challenges/target-html-elements-with-selectors-using-jquery


**Link(s) to work**
1. My Porfolio page - https://codepen.io/ddcornwall/full/zEQELW/
2. Free Code Camp (FCC) Portfolio example - https://codepen.io/freeCodeCamp/full/YqLyXB - Seemed to be working as of 11/2/2017.


### Day 22: November 3, 2017 - Time spent, 1 hour.

**Today's Progress**:  Fixed Work Examples formatting on Free Code Camp (FCC) portfolio project. Discovered borders to insert a green line into my intro. Found a number of ways how NOT to change my nav menu so hover is more obvious. Joined Stack Overflow even though I think I all have to offer is upvotes for solutions that worked for me. 

**Thoughts**:  Here is my portfolio project to-do list from yesterday:

     1) Resolve margin display issues, especially for work examples. 
     2) Make top menu items highlight on mouseover. Bonus - get them to light up as you scroll through the page. 
     3) Go back to e-mail form, this time finding a way to link the form to an e-mail server so no mail client needed.
     4) Revisit social media button issue - can we make it pretty(ish) on desktop and still have workable mobile display?
     5) After look and feel issues dealt with, update page with content instead of placeholders. 
 
I got problem #1 (Margin display) knocked out pretty quickly. It was a matter of inspecting my work examples code closely and realizing that I had extra /div tags in my second and third rows. Once I took those out, the page formatted correctly.  I suspect my problem arose from writing the first row from scratch and then copying and pasting to create the remaining rows. I must have picked up a /div tag further down my code. 

Then I moved on to getting my menu items to highlight better when moused over, with the secondary aim of getting the top buttons to light when you scrolled down to that section. I picked up and tried several solutions that should have worked but did not. Eventually I figured out that the bootstrap nav/navbar styling was overriding my css efforts. A few Stack Overflow threads stressed the importance of loading the customizing CSS AFTER Bootstrap which makes perfect sense to me. But I'm not sure how to make that work in codepen if your CSS window isn't loading after Bootstrap.

One possibility I thought of after writing that paragraph is to write some custom css on Github and then add it through CodePen's external CSS - after Bootstrap! I have to go to work now, but it's worth trying tomorrow. Not that I want to override Bootstrap too much. But if there's another way to get what I want within Bootstrap, I'm not seeing it. 

Another way I could override Bootstrap is with some JQuery, since you can use it to select items and add classes. That's another thing to think about more later. Enough thinking out loud for now!
 
 
**Links that helped me get stuff done**
1. CSS Borders - https://www.w3schools.com/css/css_border.asp
2. Highlight Menu Item when Scrolling Down to Section -https://stackoverflow.com/questions/32395988/highlight-menu-item-when-scrolling-down-to-section
3. How to become a better Stack Overflow user in five simple steps - https://medium.freecodecamp.org/5-steps-to-become-a-better-stack-overflow-user-4ce85711c0f9



**Link(s) to work**
1. My Porfolio page - https://codepen.io/ddcornwall/full/zEQELW/
2. Free Code Camp (FCC) Portfolio example - https://codepen.io/freeCodeCamp/full/YqLyXB - Seemed to be working as of 11/2/2017.
3. FCC Portfolio Exercise - https://www.freecodecamp.org/challenges/build-a-personal-portfolio-webpage




### Day 21: November 2, 2017 - Time spent, 1 hour 15 min.

**Today's Progress**:  Fixed alt text of images. Redid social media buttons and moved them to bottom of page. Moved picture of me out of "about" and into jumbotron. Resolved a problem with Jumbotron display in mobile. Changed portfolio rows for web pages and research guides from three to two to allow for larger thumbnails.

**Thoughts**: Can hardly believe I'm three weeks into this learning experience! And I'm definitely more comfortable coding than when I started. I feel like I've really improved at using the bootstrap grid system to arrange items on my page and within sections. I've also gotten more comfortable working with "div" and understanding its power. I've also learned to check the mobile presentation of my work at least once a coding session. 

There are several formatting issues I need to look into. I suspect I might not be using containers correctly. I especially need to look more closely at the "work examples" section. Another issue is how my buttons look. I don't like them as small as they are on the desktop, but when I used padding to make them larger on the desktop, it really messed up the text of the buttons on mobile. 

I wouldn't use buttons at all except that is a "user story" in the FCC exercise. Left to my own devices, I would make them links in my top menu bar. I do like that I ditched icons for words. I think this will be better for the newbie and sight challenged. 

Challenges for the coming days:
- Resolve margin display issues, especially for work examples. 
- Make top menu items highlight on mouseover. Bonus - get them to light up as you scroll through the page. 
- Go back to e-mail form, this time finding a way to link the form to an e-mail server so no mail client needed.
- Revisit social media button issue - can we make it pretty(ish) on desktop and still have workable mobile display?
- After look and feel issues dealt with, update page with content instead of placeholders. 
 
**Links that helped me get stuff done**
1. Very helpful article on Alt-Text - https://axesslab.com/alt-texts/
2. CSS Buttons - https://www.w3schools.com/css/css3_buttons.asp

**Link(s) to work**
1. My Porfolio page - https://codepen.io/ddcornwall/full/zEQELW/
2. Free Code Camp (FCC) Portfolio example - https://codepen.io/freeCodeCamp/full/YqLyXB - Seemed to be working as of 11/2/2017.
3. FCC Portfolio Exercise - https://www.freecodecamp.org/challenges/build-a-personal-portfolio-webpage



### Day 20: November 1, 2017 - Time spent, 1 hour 

**Today's Progress**: Rebuilt Navbar to collapse and be a bit more accessible. Removed background image from Jumbotron because not optimal for accessibility. Also learned that order of loading components matters. 

**Thoughts**: Some of my most important work came yesterday when a friend and coworker forwarded me a newsletter on web accessibility. I've listed the two articles in the "Links that helped me get stuff done" section below. There might be a problem with their server this morning as images were not displaying. The alt-text article is going to be VERY helpful to me in future efforts. It was written by a person with vision impairments who uses a screenreader. He had lots of suggestions that made total sense once I heard them but wouldn't have occurred to me as a sighted person. 

The second article "Trends that Exclude" talked about a number of popular web design ideas that really make life difficult for people with disabilities. I STRONGLY urge you to read it. One of the biggest was having text over photographs and another was icon only buttons. So I've eliminated these two features from my portfolio page. Right now I have a hybrid of text over icon. Not sure if I like it. I may convert them to regular links or text only buttons. 

As I mentioned yesterday that major work of today was to get a menu bar to collapse in the mobile view. After adding Javascript and JQuery to my codepen, plus some more read/search, I got that to work. I chose to have it collapse to a button labeled "Menu" instead of the traditional "hamburger menu" which I know know is made of three icon bars. This is another effort at accessibility, not just for screenreaders but for internet newbies. I have had to point out hamburger menus to so many people. It's not intuitive until you have been on the internet for awhile. I realize that "Menu" priveleges English readers but 1) Most of the pages I create will be in English and 2) They can use Google to translate the page and get the word "menu" in their own language.

Getting the menu to collapse was tedious but straightforward. Then it wouldn't open. Checked my code a few times. No dice. I commented out my navbar and inserted what was promised to be a working code example from W3Schools. No dice. It collapsed but could not expand. After some more read/search, I found the last item on my "Links that helped me get stuff done" list. The first answer on the page wasn't relevant to my code, but the second was:

"Then I changed the order so that bootstrap.min.js came after jquery.min.js, and this solved the problem. I don't know enough about javascript to explain why this caused the problem (or fixed it), but that is what worked for me."

I don't know enough about it either, but I made the switch and the menu worked. It collapses to a button called "menu" on small displays and the buttons work. 

First task for tomorrow revisit the "alt" text on all may images and make sure they're descriptive and don't start off with "image of." Then I need to think about how to lay out the page so that it is both accessible and reasonably nice to look at. I'll probably looking for examples of accessible portfolio pages. If you have any you like, let me know!
 

**Links that helped me get stuff done**
1. Very helpful article on Alt-Text - https://axesslab.com/alt-texts/
2. Trends That Exclude - https://axesslab.com/trends/
3. bootstrap 3 navbar collapse button not working -
 https://stackoverflow.com/questions/20719607/bootstrap-3-navbar-collapse-button-not-working

**Link(s) to work**
1. My Porfolio page - https://codepen.io/ddcornwall/full/zEQELW/


### Day 19: October 31, 2017 - Time spent, 1 hour

**Today's Progress**: Figured out background image for Jumbotron. Identified problem with navbar display in mobile.   

**Thoughts**: I'm setting aside my form work for now because so far I haven't found anything helpful through read/search/ask. 

Having put aside further work on the contact form, I started out looking at ways to get hover effects for my project thumbnails and I found some promising material. Along the way though I found the command to add a background image to any HTML element. So I browsed though my pictures, picked one with a lot of sky, did some editing, uploaded it to Github and added to my Jumbotron element. 

I do my development on a laptop and I decided to see how my portfolio page displayed on mobile. I run Android on a Google Pixel and the default browser is Chrome. My navbar covers three quarters of the screen. Tonight or tomorrow I need to work on fixing that. 

I learned new things today. That makes me happy. 
 

**Links that helped me get stuff done**
1. CSS Image Overlay - https://www.w3schools.com/howto/howto_css_image_overlay.asp
2. CSS Hero Image - https://www.w3schools.com/howto/howto_css_hero_image.asp
3. CSS image hover effects - http://www.corelangs.com/css/box/hover.html (ironically, helped me with background image on jumbotron section).
4. CSS Background Size - https://www.w3schools.com/cssref/css3_pr_background-size.asp


**Link(s) to work**
1. My Porfolio page - https://codepen.io/ddcornwall/full/zEQELW/
2. Itamar Rosenblum Portfolio page - https://codepen.io/ItamarRosenblum/full/eGozMa/ - I'm using this for my example, but will have a different color scheme. 


### Day 18: October 30, 2017 - Time spent, 1hr

**Today's Progress**: Made my own placeholder images, added them to work examples template, styled form better and figured out how to post code to Free Code Camp (FCC) forum. Posted my first FCC forum question.   

**Thoughts**:  It's a constant struggle to not get fixated on content during my coding time. I was going to take screenshots of what I intended to link to on my portfolio page. I realized that placeholder images would be a better use of my time, then promptly got hung up on finding the "right kind" of placeholder images from "reputable sites." Fortunately I didn't stay in that rabbit hole too long. I realized that I had several image creation tools at my disposal. Two minutes later, I had a 400x200 placeholder image which I dropped into my code, then copy and pasted as needed. 

It's important to be careful with your copy and paste or you may wind up with a div tag too many or too few. This WILL change the look of your page. 

With my basic gallery in place, I once again considered my contact form and its styling. It was relatively easy once I remembered that "height" and "width" are attributes you can give to nearly any HTML element and now I'm mostly happy with the look of the form. My one remaining concern with the LOOK of the form is that while the message area is a satisfying box text input begins in the middle of the box and does not wrap when it hits the end. Ideally I'd like text entry to begin at the top of my box and for the text to move to the next line when it hits the end of the box. 

What's more important is that my form does not do anything real at this point. You can fill it out and when you hit the submit button your default e-mail program is launched with my e-mail address. But that's all that appears in the e-mail. The e-mail SHOULD have all the fields you filled out. I've compared my code to working examples on the web, but can't find a problem. It's like Dr. McCoy on Star Trek - "Jim according to my tricorder, this dead man should be perfectly healthy." 

That led me to my last accomplishment, asking a question on the Free Code Camp (FCC) forum. I learned to use three dots together (...) before and after my code to make it display to others. I hope someone has some ideas. 


**Link(s) to work**
1. My Porfolio page - https://codepen.io/ddcornwall/full/zEQELW/
2. Itamar Rosenblum Portfolio page - https://codepen.io/ItamarRosenblum/full/eGozMa/ - I'm using this for my example, but will have a different color scheme. 



### Day 17: October 29, 2017 - Time spent, 1 hour 20 minutes

**Today's Progress**: Defined bootstrap rows for work examples. Added photography work examples with links back to github. Added styled photo to "About" section and defined columns so that text would be next to photograph. 

**Thoughts**: I feel accomplished today now that I'm in coding mode as opposed to troubleshooting mode. I knew my next step was to lay out the grid for my work examples, even if I didn't have all the images and links ready. I started off by looking for portfolio grids and found a few examples. I almost did cut and paste from one of those, but remembered it is often more rewarding to build as much from scratch as possible. So I stepped back and reviewed bootstrap grids. I'm still getting the hang of rows and columns and making everything in a row to add up to twelve columns, but that clearly was the way to go. 

After the grid was lined up, I figured I'd try inserting my photography examples first partly because I had them handy. Along the way I learned the power of img-thumbnail to tame images that wanted to display across columns. For the next two sets of work, I need to take and edit some screenshots, I think. 

Taking a few moments to look at the Rosenblum portfolio listed below, I was impressed with how his screenshots changed as you mouseover. That's an effect I think I might want to have. I also need to get back to my form and get it to actually do something. It would also be nice if the boxes did not go clear across the screen. 
 

**Links that helped me get stuff done**
1. Bootstrap Grid Video (YouTube) - https://www.youtube.com/watch?v=GDwWmrpCa30
2. Bootstrap images - https://www.w3schools.com/bootstrap/bootstrap_images.asp


**Link(s) to work**
1. My Porfolio page - https://codepen.io/ddcornwall/full/zEQELW/
2. Itamar Rosenblum Portfolio page - https://codepen.io/ItamarRosenblum/full/eGozMa/ - I'm using this for my example, but will have a different color scheme. 


### Day 16: October 28, 2017 - Time spent, 1 hour

**Today's Progress**: Figured out my formatting issues. Can make better progress tomorrow. 

**Thoughts**:  Through what's best described as iterative fiddling around, I solved both of my formatting issues:

Problem 1 - All content is glued to left margin. Solution, put it into a fluid container element. 
Problem 2 - Why doesn't the $##%#$@@ ul tag work like it's supposed to? Solution, realized I may have accidently added the "materialize css" behind the scenes. I say "may have accidentally" because I can't find anything in my notes telling me I needed it. Once I removed it, the formatting problem went away. Also my social media buttons changed color. But an acceptable trade for now. 

Also, I'm noticing that my links here in the github log, and presumably in Wordpress are malformed because github tagged a closing brack as the last character of the URL. So I'm dropping the parens for URLs. 

**Link(s) to work**
1. My Porfolio page - https://codepen.io/ddcornwall/full/zEQELW/
2. Itamar Rosenblum Portfolio page - https://codepen.io/ItamarRosenblum/full/eGozMa/ - I'm using this for my example, but will have a different color scheme. 


### Day 15: October 27, 2017 - Time spent, 1 hour

**Today's Progress**: Added content to portfolio page, spent unproductive time troubleshooting a very odd formatting error. 

**Thoughts**:  Head, meet wall. Something I've done on my portfolio page caused my left margin to disappear and the page to overwrite how the ul tag normally works. I tried my usual search/read approach but I'm not finding the right vocabulary. I know the list code itself is sound because it works when copied into a blank pen. It still kept working when I added bootstrap and my css into the new pen. In my portfolio page, the list item style works if I take off the ul tag.

Very odd and I don't have more time this morning to deal with it. Unless I have a brillent idea, I may start the portfolio page over, adding elements bit by bit until I find what breaks my margins and list style. 

**Link(s) to work**
1. [My Porfolio page  (https://codepen.io/ddcornwall/full/zEQELW/]
2. [Itamar Rosenblum Portfolio page (https://codepen.io/ItamarRosenblum/full/eGozMa/)] - I'm using this for my example, but will have a different color scheme. 


### Day 14: October 26, 2017 - Time spent, 1 hour

**Today's Progress**: Added anchors to sections in my portfolio form. Added non-working contact form at bottom of page.  

**Thoughts**:  After a short examination of the Borlaug code to see if I could improve the mobile display of my tribute page, I shelved that issue in favor of working on my portfolio page. This decision was easier knowing that a friend say a centered image in her mobile browser. I'll definitely keep an eye open to alternative ideas about my tribute image issue.

Portfolio page was mostly straightforward, adjusted for bootstrap. I am grateful for all the blog and forum posts around the net. They do make it much easier to track down the source of errors and their solutions. 

Tomorrow I plan to work more on my contact form. I ALMOST have it submitting as a mailto link, but not quite. Then I will look into styling my sections and creating placeholders for my work. 
 

**Links that helped me get stuff done**
1. [Portfolio Challenge: //#sourceURL:pen.js message  (https://forum.freecodecamp.org/t/portfolio-challenge-sourceurl-pen-js-message/154462)]
2. [Fix bootstrap anchor tags position using fixed nav bars   (https://www.servermule.com.au/help/bootstrap-anchors-fixed-nav/)]
3. [Bootstrap Forms (https://www.w3schools.com/bootstrap/bootstrap_forms.asp)]
4. [HTML Input Types (https://www.w3schools.com/tags/att_input_type.asp)]
5. [HTML Input Size (https://www.w3schools.com/tags/att_input_size.asp)]
6. [HTML Form Try It (https://www.w3schools.com/html/tryit.asp?filename=tryhtml_form_mail)]

**Link(s) to work**
1. [My Porfolio page  (https://codepen.io/ddcornwall/full/zEQELW/)]
2. [Itamar Rosenblum Portfolio page (https://codepen.io/ItamarRosenblum/full/eGozMa/)] - I'm using this for my example, but will have a different color scheme. 
3. [FCC provided example that had broken images as of 10/23/2017 (https://codepen.io/freeCodeCamp/full/YqLyXB)]


### Day 13: October 25, 2017 - Time spent, 1 hour

**Today's Progress**: Rebuilt my Gandhi tribute page with Jumbotron. Used more "read/search" to find ways to tweak the jumbotron and figure elements into looking more like Borlaug tribute. 

**Thoughts**:  There is a joy when you find the right tool for the job and you can eliminate all of the creaky workarounds you had been using. The display looks cleaner and the code looks cleaner. And I got this far without looking at the Borlaug code. I discovered Jumbotron on my own while looking for ideas on the Portfolio project. 

There is only one oddity left that the Borlaug tribute does not share. When I look at my tribute page on my Google Pixel phone in Chrome in portrait mode, the image of Gandhi is not center. BUT if you turn the phone to landscape mode, the image is centered. The image is centered on the desktop versions of Microsoft Edge, Firefox and Chrome.

Since the Borlaug tribute page DOES center in the mobile version of Chrome, I assume that I have missed one last trick. Not sure if I'm going to work that tomorrow, but probably should. If I were a professional developer, having an uncentered image on a common mobile center is something that should not be tolerated. 
 

**Links that helped me get stuff done**
1. [Jumbotron  (https://getbootstrap.com/docs/3.3/components/#jumbotron)]
2. [The Anti-hero of CSS Layout - "display:table" (https://colintoh.com/blog/display-table-anti-hero)]

**Link(s) to work** 
1. [My "post-submission" tribute page (https://codepen.io/ddcornwall/full/jGgOGm/)]
2. [Dr. Norman Borlaug Tribute Example that end product should look like  (https://codepen.io/freeCodeCamp/full/NNvBQW)]


### Day 12: October 24, 2017 - Time spent, 1 hour

**Today's Progress**: Worked on making my icon buttons accessible. Will need to get a screenreader to test. Turned icons into buttons as part of accessibility and that also made rollover colors more obvious. Added first draft of first page section. Realized that Jumbotron was EXACTLY what my portfolio page needed, so will likely work on that tomorrow. 

**Thoughts**: For those wondering, today was a much better experience than yesterday. I also got some feedback from my wise webdev coworker on the need for building in accessibility. So I spent most of today's coding time making the icons accessible. At least I think they're more accessible now. I need to get some screenreader software and get re-briefed on how to use the keyboard for navigation. 

My task list from yesterday, aside from making my icon buttons accessible to screenreaders:
 
1) Make the icons larger
2) Make them change color on mouse over
3) Have some roll over text for screenreaders
 
 For problem #1, I found that Font Awesome had classes to enlarge the icons, so I set them to 2x.
 For problem #2, I initially stuck in css to make the li element blue on mouseover, but I didn't need to do that after I made them button class.
 For problem #3, I put in tooltips. But that probably won't help screenreaders. Fortunately I found that I could combine a "visuallyhidden" class with some helptext. That ought to be accessible to screenreaders.
 
 Having dispatched (mostly) the button problems, I moved on to thinking about putting actual content on my portfolio. Searching around for "portfolio tips" I found the bootstrap jumbotron class. After adding a draft section to my portfolio page I realized that this was the EXACT background and typography of the Borlaug tribute page (https://codepen.io/freeCodeCamp/full/NNvBQW). Gray background, larger text than I could get with my h1 header, etc. This is so much more elegant than mucking around with panels that I will likely spend tomorrow's coding time in part redoing my tribute page. I don't expect it to take too long. 
 
After redoing the tribute page, I'll focus on deciding what sections I want for my portfolio, using the Rosenblum page for ideas. 
 

**Links that helped me get stuff done**
1. [Accessible Icon Buttons - video  (https://egghead.io/lessons/css-accessible-icon-buttons)]
2. [Places where it's tempting to use display:none but don't  (https://css-tricks.com/places-its-tempting-to-use-display-none-but-dont/)]
3. [What's the difference between HTML 'hidden' and 'aria-hidden' attributes?
  (https://stackoverflow.com/questions/31107040/whats-the-difference-between-html-hidden-and-aria-hidden-attributes)]
4. [How to set the size of the button in HTML  (https://stackoverflow.com/questions/25014849/how-to-set-the-size-of-button-in-html)]
5. [Jumbotron  (https://getbootstrap.com/docs/3.3/components/#jumbotron)]
6. [Font Awesome Examples (http://fontawesome.io/examples/)]
7. [Bootstrap tooltip (https://www.w3schools.com/bootstrap/bootstrap_tooltip.asp)]

**Link(s) to work**
1. [My Porfolio page  (https://codepen.io/ddcornwall/full/zEQELW/)]
2. [Itamar Rosenblum Portfolio page (https://codepen.io/ItamarRosenblum/full/eGozMa/)] - I'm using this for my example, but will have a different color scheme. 
3. [FCC provided example that had broken images as of 10/23/2017 (https://codepen.io/freeCodeCamp/full/YqLyXB)]





### Day 11: October 23, 2017 - Time spent, 2 hours 5 minutes

UPDATE 4pm Alaska Time: Did actually spend time after grocery shopping coding. My icons are now larger and have rollover descriptions. I couldn't get the icons to simply change color, so for now their background turns blue on mouseover. My total coding time today was 2 hours. 

SPECIAL NOTE: I see that since Day 5 I gave the wrong URL for the Borlaug tribute. It should be https://codepen.io/freeCodeCamp/full/NNvBQW. I have fixed this in the github log. 

**Today's Progress**: I learned a few ways how not to report a bug with Free Code Camp (FCC). I learned how to open an FCC issue on GitHub (the right way to report a bug). After a frustrated start, I began my web portfolio. So far all I have is a navigation bar with links to my professional social media - but I started! I also figured out how to host my page images on github, thought there are no hosted images on my portfolio page yet. 

**Thoughts**: A friend and coworker told me that a lot of web development is getting your environment right and to expect frustration in that. She is wise. 

When I started today, a day off for me, I was expecting the process to go something like this:
 
 - Review the Portfolio page assignement
 - Test out the functionality of the Portfolio page example
 - Make some kind of features list to work through
 - Make some sort of progress on the features
 - Be proud of my hours of productive coding.
 
 Um. No. When I opened the portfolio example, there were no images. I knew there should be images because text clearly drawn from alt tags was displaying. No example web pages were dispalying under portfolio, which is kind of the point of this exercise. Thinking it could be a browser issue, I switched from Chrome, to Microsoft Edge to Firefox, no luck.
 
 My next step was to search the forums to see if this issue had been mentioned. It had been mentioned in 2016 as an intermittent problem and at least four people had expressed frustration with it. I then went on a search for an example I could use. It took me awhile to find one that seemed fully suitable. Then I figured I'd report the problem. Eventually I was pointed to Github to open an issue after two other ways did not seem to work. So I opened an issue. [As I write this, I realize that while I searched OPEN issues on this topic, I probably should have searched CLOSED issues first.] 
 
 I was deeply frustrated by this point, but didn't want to throw up my hands before I'd finished an hour. So I went back to the example I'm using and decided to just focus on the navbar. I'm off to a decent start and now have icons that link to my public social media.
 
 I need to run some errands but hope to code more later. I'm going to keep my focus on the navbar. In particular I want to:
 
 - Make the icons larger
 - Make them change color on mouse over
 - Have some roll over text for screenreaders
 
 After that I'll do some planning for the other sections of my page. 
 

**Links that helped me get progress done**
1. [FCC Forum: Portfolio… JS? Where to start? (https://forum.freecodecamp.org/t/portfolio-js-where-to-start/22039)]
2. [W3Schools Bootstrap NavBar (https://www.w3schools.com/bootstrap/bootstrap_navbar.asp)]
3. [W3Schools Font Awesome (https://www.w3schools.com/icons/fontawesome_icons_brand.asp)]
4. [W3Schools Bootstrap Tootips   (https://www.w3schools.com/bootstrap/bootstrap_tooltip.asp)]
5. [Font Awesome examples (http://fontawesome.io/examples/)] - Helped to enlarge icons.

**Link(s) to work**
1. [My Porfolio page  (https://codepen.io/ddcornwall/full/zEQELW/)]
2. [Itamar Rosenblum Portfolio page (https://codepen.io/ItamarRosenblum/full/eGozMa/)] - I'm using this for my example, but will have a different color scheme. 
3. [FCC provided example that had broken images as of 10/23/2017 (https://codepen.io/freeCodeCamp/full/YqLyXB)]


### Day 10: October 22, 2017 - Time spent, 1 hour

**Today's Progress**: I figured out how to make my image and caption look like they belong together. With that last problem solved to my satisfaction, I submitted it as completed to Free Code Camp (FCC)  

**Thoughts**: My last significant coding issue was:

"How they get their caption seemingly inside the image? Mine definitely looks tacked on to the bottom. It works but isn't elegant."

As I mentioned yesterday, I thought the solution might involve putting a bootstrap panel within my panel. After some more of read/search, I tried out that solution. It worked decently well, but then I had a problem with text from below the image flowing around the image in a way that looked ugly. My first thought was to try a brute force approach involving over a dozen break (br) tags

This actually looked ok on the desktop, though I wasn't at all proud of the coding. BUT it looked very odd on my Android smartphone. Way too much space between the image and the next paragraph. So I eliminated the panel for the figure. Then I tried styling the "figure" tag with background color white and a huge margin. That gave me my frame that had the caption looking like it belonged inside the block. I would have liked to make the white spaces on either side of the image go away completely, but the large margin shrinks the image on mobile. 

The end product is not perfect. But it does look functionally similar to the Borlaug tribute and it does meet the two required user stories. I have a personal philosophy of "Don't let the perfect be the enemy of the good." In coding this can be expressed as "It's better to put out a "good enough" product in a few weeks than a perfect product eight months from now." I also figure that if it had been mission critical for me to have the exact look and feel of the Borlaug tribute, I would have looked at the code.

While I did not look at the Borlaug code during the creation of this page, I do intend to look at it in a day or two. I'd like to see how things were done and perhaps make another version of my tribute page with it. But I think I'll at least start on the coding for the Portfolio page before I do so. 


**Link(s) to work**
1. [Dr. Norman Borlaug Tribute Example that end product should look like  (https://codepen.io/freeCodeCamp/full/NNvBQW)]
2. [Mahatma Gandhi Tribute Page (https://codepen.io/ddcornwall/full/YrdRLa/)]


### Day 9: October 21, 2017 - Time spent, 1 hour

**Today's Progress**: I boosted my title size by using a style tag in my h1 header. It now looks close to the size of the Borlaug tribute. I completed the content part of my tribute page and I may have gotten a lead on my captioning issue.  

**Thoughts**: In terms of coding issues without any kind of solution, I'm down to just one:

- How they get their caption seemingly inside the image. Mine definitely looks tacked on to the bottom. It works but isn't elegant.

After some more read/search, I THINK the solution might be a nested panel. That is, turn the image and caption into a panel that is in the panel containing the majority of my content. I hope to test that out tomorrow, when I also hope to have more than an hour to code. 

I consider the title problem solved since I didn't put the style tag in a separate CSS window. This is more or less a Ben Kenobi solution of "It's true ... from a certain point of view."

My plan for this project is to test out one or two more ways of getting the caption in my tribute photo to look more like the one in the FCC example. Then I will call this project done and offer it for feedback. After that, I will look at the code for the Borlaug page and document where its solutions differ from my own. 


**Link(s) to work**
1. [Dr. Norman Borlaug Tribute Example that end product should look like  (https://codepen.io/freeCodeCamp/full/NNvBQW)]
2. [Mahatma Gandhi Tribute Page (https://codepen.io/ddcornwall/full/YrdRLa/)]

### Day 8: October 20, 2017 - Time spent, 1 hour

**Today's Progress**: I created vertical spacing on my page without violating the rules of the tribute challenge. I increased the margins of my panel box using the bootstrap grid system. I also filled in some content since I'd solved a few of the code challenges. Will replace final "placeholder text" after I solve code challenges to my satisfaction. 

**Thoughts**: Here's my updated "I don't get how he did it list":

1) How their title seems larger than my H1 tag
2) How they get their caption seemingly inside the image. Mine definitely looks tacked on to the bottom. It works but isn't elegant.
3) How he gets the vertical spacing between sections of his page. I doubt it's a set of <br> tags, but my searches for "bootstrap vertical spacing" haven't gotten me very far yet. 

Yesterday I wrote how I wound up using some custom CSS to control my vertical spacing, although that violated the rules of the challenge. Today I realized I was simply overthinking things. I simply stuck in three br tags where I wanted to space sections. Problem 3 solved, at least to my satisfaction.

I can't match the exact margins of the Borlaug tribute. Also, given some white gutter space on my panel header box, I'm thinking maybe FCC didn't use panels after all. Or used them with controls I haven't found yet. But after a lot of read/search, I'm going to call it good for the time being because it looks decent. I will revisit it once I've either gotten solutions for 1 and 2 above or decide they're ok too. Sometimes we just have to go for good enough. I'm not at that point - yet.

As far as problem 1, where the Borlaug title is bigger than I can get with a H1 tag, I found intriguing hints that you can increase the base size of text in Bootstrap. I couldn't explore that with the time I had this morning before work, but intend to follow up that hint. 

I'm definitely getting a better feel for just how iterative and research intensive coding can be. 


**Link(s) to work**
1. [Dr. Norman Borlaug Tribute Example that end product should look like  (https://codepen.io/freeCodeCamp/full/NNvBQW)]
2. [Mahatma Gandhi Tribute Page (https://codepen.io/ddcornwall/full/YrdRLa/)]



### Day 7: October 19, 2017 - Time spent, 1 hour

**Today's Progress**: I got my gray box on my tribute page. I've matched the color of the Borlaug tribute but the margins are different. I spaced out some of my elements better, though I did resort to CSS to make that happen. Because I wanted some feel of progress. 

**Thoughts**: Here's my "I don't get how he did it list from yesterday":

1) How their title seems larger than my H1 tag
2) How they generate the gray box. I feel like I've eliminated panels as a solution. I would say it's an add on to the <body> tag, but codepen doesn't seem to give you access to the <body> tag in pens.
3) How they get their caption seemingly inside the image. Mine definitely looks tacked on to the bottom. It works but isn't elegant.
4) How he gets the vertical spacing between sections of his page. I doubt it's a set of <br> tags, but my searches for "bootstrap vertical spacing" haven't gotten me very far yet. 

I feel like I've honestly solved #2. It seems I rejected panels too early. It turns out the exact color and the basic look of the box I wanted was a bootstrap panel header. I learned this from reading w3schools bootstrap panels tutorial at https://www.w3schools.com/bootstrap/bootstrap_panels.asp. The margins aren't quite right and I haven't figured out how to change them either by adding margin commands to the bootstrap elements or hacking it through CSS. Also, At one point I was considering cards rather than panels. I was starting to get confused, but then found https://ux.stackexchange.com/questions/78798/whats-the-difference-between-cards-panels-and-tiles which really helped me decide what tool to use. 

I "solved" #4 by using CSS to change my H2 and figure elements. I added a margin-bottom to each. For reasons I don't understand, simply adding them to the element in HTML did not work. While it gives me a look I like, I'm disappointed I couldn't get the spacing without going outside unmodified bootstrap. But I figure I can revisit that later after I've got other stuff out of the way. 
 

**Link(s) to work**
1. [Dr. Norman Borlaug Tribute Example that end product should look like  (https://codepen.io/freeCodeCamp/full/NNvBQW)]
2. [Mahatma Gandhi Tribute Page (https://codepen.io/ddcornwall/pen/YrdRLa)]



### Day 6: October 18, 2017 - Time spent, 1 hour

**Today's Progress**: Not huge progress so far. I'm getting lots of practice in read/search/ask. My tribute page has a bit more information and I've figured out one way to caption my image. 

**Thoughts**: I had to avoid my librarian tendency to make this "coding" time a chance to gather all the information I am going to use about Gandhi. Because this tribute page is a coding project, I contented myself with putting in some placeholders and just a few key resources and then focused on coding. 

This project is harder than it looks - no surprise. Partly because coding is work in general, but I feel especially constrained by the project instructions to not use CSS and rely on out of the box bootstrap. Comparing my page to FCC's Boralug tribute, I've generated this list of things I'm not clear yet on:

- How their title seems larger than my H1 tag
- How they generate the gray box. I feel like I've eliminated panels as a solution. I would say it's an add on to the <body> tag, but codepen doesn't seem to give you access to the <body> tag in pens.
- How they get their caption seemingly inside the image. Mine definitely looks tacked on to the bottom. It works but isn't elegant.
- How he gets the vertical spacing between sections of his page. I doubt it's a set of <br> tags, but my searches for "bootstrap vertical spacing" haven't gotten me very far yet. 

I'm not giving up. That would be silly. Also, I am confident I could closely duplicate this page if I was allowed to use CSS. I know how to code grey boxes. But I am interested in doing it the bootstrap way. Knowing that something can be done keeps my will alive. 

**Link(s) to work**
1. [Dr. Norman Borlaug Tribute Example that end product should look like  (https://codepen.io/freeCodeCamp/full/NNvBQW)]
2. [Mahatma Gandhi Tribute Page (https://codepen.io/ddcornwall/pen/OxaqdK)]


### Day 5: October 17, 2017 - Time spent, 1 hour

**Today's Progress**: I completed the 118 code challenges in Free Code Camp (FCC) Front End Developer and now am working on the first Front End Developer Project, the tribute page. I've started setting up the page and have my heading and graphics. I need to get my images to line up in the same row, add a timeline or other thoughts. 

**Thoughts** This will definitely be a challenge despite the fact that 1) I should have everything I need and 2) I've been using the "Read/Search/Ask" methodology for years in many areas. If I weren't contrained by the requirement to only use bootstrap, I think I could duplicate the gray box on the Borlaug page. I've started off by using a Bootstrap panel, but that doesn't look right. I started using a bootstrap row and columns to get the photos in the same row but that isn't working yet. Next time I have coding time, I will review my FCC Cat Photo App work because one of the exercises did put two pictures together.  

Finally, I write these entries in the morning to make sure they get done. I may do more coding tonight. If I do, I'll probably just tweet the progress. If you've done or are doing #100DaysOfCode, I'd be interested in hearing how you handle documenting (if you do) any "post log" coding. 

**Link(s) to work**
1. [Dr. Norman Borlaug Tribute Example that end product should look like  (https://codepen.io/freeCodeCamp/full/NNvBQW)]
2. [Mahatma Gandhi Tribute Page (https://codepen.io/ddcornwall/pen/OxaqdK)]


### Day 4: October 16, 2017 - Time spent, 1.25 hours coding, plus about an additional hour of attempting VM setup in Cloud9

**Today's Progress**: I have completed 114 coding challenges on Free Code Camp (FCC) and refreshing myself on the use of jQuery to change HTML. I have also learned a few ways of how not to set up a virtual machine in [Cloud9 (https://c9.io)]. I've also become a bit more comfortable in installing Python packages from a command line, even if they're not working as intended. 

**Thoughts** Today was actually pretty frustrating as opposed to the first three days. I had hoped to get more accomplished because I have the morning off. Instead, it wound up being less productive. It started when I got 504 errors from FCC. It still hadn't cleared up after ten minutes so I decided to set up a python box on Cloud9 so I could start working on my data analysis program. In retrospect, I wish I had played with my HTML5 box on Cloud 9 instead, consolidating what I'd been learning. But I went for python setup.

This was a problem because the basic Python setup in Cloud9 lacks some data specific modules I need. Specifically matplotlib and pandas. My efforts to install them on top of the basic C9 instance didn't work for me, so I followed a recipe for installing miniconda on a blank c9 box. That seemed to work, but now my program still can't find the modules it needs. I think it's probably a path environment error, but I couldn't find how to access that. So I threw up my hands and tried FCC again, which was working. 

Tonight I may spend some time trying to get my Python box to work, but I won't count that as coding time. Whether or not I get it working, I think tomorrow I'll be back on FCC code camp and go to my HTML5 Cloud9 box when I hit a good stopping point. 

It's always good to learn troubleshooting and work arounds, but I'd really like to be able to focus on the actual coding in the days ahead. 

**Link(s) to work**
1. [FCC Map (https://www.freecodecamp.org/map)]
2. [Using Conda on Cloud9 (https://kaiserho.wordpress.com/2016/07/21/using-conda-on-c9-io/)]


### Day 3: October 15, 2017 - Time spent, 2 hours

**Today's Progress**: I've now completed 104 coding challenges on the Front End Developer track at Free Code Camp (FCC). I learned more about colors in HTML, learned some basic Bootstrap layout for buttons and form fields and have begun to refresh myself on jQuery

**Thoughts** My favorite thing I learned today is something most readers here will know. The six digit hexadecimal codes for web colors aren't arbitrary. They are explicit color mixes. The first two digits are Red intensity, the second two are Green intensity and the last
two digits are for blue intensity. #000000 stands for black because RGB are all at zero. #FFFFFF is white because red, green and blue are at their highest and equal intensity. The hexadecimal numbers have gone from mystery to fun color mixing. 

Granted, I should be more excited about learning Bootstrap and some basic responsive design, and I do intend to play with that in coming days. It's just the FCC environment doesn't allow for much screen resizing - so harder to get excited within the Free Code Camp environment. 

Finally, I've started adding on "Time spent" for each day. I use Kanban flow (www.kanbanflow.com) for reminders prompts of things I want to get done through out the week. I have a recurring daily item for 100 days of code. Kanban flow includes timer features, so I'm using it to track my coding time. 
 
**Link(s) to work**
1. [FCC Map (https://www.freecodecamp.org/map)]



### Day 2: October 14, 2017 - Time spent, 1 hour

**Today's Progress**: I've now completed 56 coding challenges on the Front End Developer track at Free Code Camp (FCC). I learned about creating HTML forms and styling elements with colors. I used this knowledge to create my own simple form on my new Cloud9 account.

**Thoughts** I'm definitely starting to fill gaps in my self-education. While I feel like I've got the basics of HTML, I haven't refreshed my skills in awhile. So the creating forms with simple tags, while something I heard about, wasn't something I had done. It's great to see how easy it is put it together. I still need to learn how to pass the results of a form elsewhere and if I could figure out how to send it an e-mail address this might have direct relavance to a nonprofit I volunteer for. 

Eventually, I'll need to figure out how to get Cloud9 to host my content in a non-preview way, unless that's not something they do. 

**Link(s) to work**
1. [A simple form on Github (https://github.com/ddcornwall/CatPhotoApp/blob/master/asimpleform)]
2. [Live "preview" form, click button to see actual form (https://sandbox-ddcornwall.c9users.io/asimpleform.html)]


### Day 1: October 13, 2017 - Time spent, 1 hour

**Today's Progress**: I've gone through many exercises on FreeCodeCamp. Learned new border features in CSS

**Thoughts** One challege, putting an image into code gave me fits, not because the code didn't work, but a glitch in FCC check tests didn't work. But going to FCC forum at https://forum.freecodecamp.org/t/freecodecamp-challenge-guide-add-images-to-your-website/16640/7 helped me realize the issue wasn't me. Forums are your friend!

**Link(s) to work**
1. [CatPhotoApp GitHub Repository (https://github.com/ddcornwall/CatPhotoApp)
2. [Circular Images with a border radius (https://www.freecodecamp.org/challenges/make-circular-images-with-a-border-radius)



<!--- 
### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link to work:** [Calculator App](http://www.example.com)

### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)
--->

### Day 0: October 12, 2017

**Today's Progress**: Created Github account, renewed Free Code Camp account.

**Thoughts:** It was interesting to see how the Github repository process worked. Also how you can use the "forget password" functionality on websites to see if you had dabbled in them before. 

**Link to work:** - None


