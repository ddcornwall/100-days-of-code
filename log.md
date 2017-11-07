# 100 Days Of Code - Log

<!--Template for log
### Day 20: November 1, 2017 - Time spent, 1 hour

**Today's Progress**:  

**Thoughts**: 


 

**Links that helped me get stuff done**


**Link(s) to work**
1. My Porfolio page - https://codepen.io/ddcornwall/full/zEQELW/
2. Free Code Camp (FCC) Portfolio example - https://codepen.io/freeCodeCamp/full/YqLyXB - Seemed to be working as of 11/2/2017.

End Template for log-->

DISCLAIMER - This log will contain typos. For the nicely edited version of my progress, visit https://librarianfromalaska.wordpress.com/tag/100daysofcode/

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


