# 100 Days Of Code - Log

### Day 10: October 22, 2017 - Time spent, 1 hour

**Today's Progress**: I figured out how to make my image and caption look like they belong together. With that last problem solved to my satisfaction, I submitted it as completed to Free Code Camp (FCC)  

**Thoughts**: My last significant coding issue was:

"How they get their caption seemingly inside the image? Mine definitely looks tacked on to the bottom. It works but isn't elegant."

As I mentioned yesterday, I thought the solution might involve putting a bootstrap panel within my panel. After some more of read/search, I tried out that solution. It worked decently well, but then I had a problem with text from below the image flowing around the image in a way that looked ugly. My first thought was to try a brute force approach involving over a dozen break tags:

<pre>
<br/><br/><br/>
<br/><br/><br/>
<br/><br/><br/>
<br/><br/><br/>
<br/><br/><br/>
<br/><br/><br/>
<br/><br/><br/>
</pre>

This actually looked ok on the desktop, though I wasn't at all proud of the coding. BUT it looked very odd on my Android smartphone. Way too much space between the image and the next paragraph. So I eliminated the panel for the figure. Then I tried styling the "figure" tag with background color white and a huge margin. That gave me my frame that had the caption looking like it belonged inside the block. I would have liked to make the white spaces on either side of the image go away completely, but the large margin shrinks the image on mobile. 

The end product is not perfect. But it does look functionally similar to the Borlaug tribute and it does meet the two required user stories. I have a personal philosophy of "Don't let the perfect be the enemy of the good." In coding this can be expressed as "It's better to put out a "good enough" product in a few weeks than a perfect product eight months from now." I also figure that if it had been mission critical for me to have the exact look and feel of the Borlaug tribute, I would have looked at the code.

While I did not look at the Borlaug code during the creation of this page, I do intend to look at it in a day or two. I'd like to see how things were done and perhaps make another version of my tribute page with it. But I think I'll at least start on the coding for the Portfolio page before I do so. 


**Link(s) to work**
1. [Dr. Norman Borlaug Tribute Example that end product should look like  (https://codepen.io/ddcornwall/full/YrdRLa/)]
2. [Mahatma Gandhi Tribute Page (https://codepen.io/ddcornwall/full/YrdRLa/)]


### Day 9: October 21, 2017 - Time spent, 1 hour

**Today's Progress**: I boosted my title size by using a style tag in my h1 header. It now looks close to the size of the Borlaug tribute. I completed the content part of my tribute page and I may have gotten a lead on my captioning issue.  

**Thoughts**: In terms of coding issues without any kind of solution, I'm down to just one:

- How they get their caption seemingly inside the image. Mine definitely looks tacked on to the bottom. It works but isn't elegant.

After some more read/search, I THINK the solution might be a nested panel. That is, turn the image and caption into a panel that is in the panel containing the majority of my content. I hope to test that out tomorrow, when I also hope to have more than an hour to code. 

I consider the title problem solved since I didn't put the style tag in a separate CSS window. This is more or less a Ben Kenobi solution of "It's true ... from a certain point of view."

My plan for this project is to test out one or two more ways of getting the caption in my tribute photo to look more like the one in the FCC example. Then I will call this project done and offer it for feedback. After that, I will look at the code for the Borlaug page and document where its solutions differ from my own. 


**Link(s) to work**
1. [Dr. Norman Borlaug Tribute Example that end product should look like  (https://codepen.io/ddcornwall/full/YrdRLa/)]
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
1. [Dr. Norman Borlaug Tribute Example that end product should look like  (https://codepen.io/ddcornwall/full/YrdRLa/)]
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
1. [Dr. Norman Borlaug Tribute Example that end product should look like  (https://codepen.io/ddcornwall/full/YrdRLa/)]
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
1. [Dr. Norman Borlaug Tribute Example that end product should look like  (https://codepen.io/ddcornwall/full/YrdRLa/)]
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


