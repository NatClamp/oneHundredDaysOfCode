# 100 Days of code log

### Day 0: Log template

***Today's Progress***: 

***Thoughts***:

***Link to work***:

### Day 1: Thursday 27th August, 2020

***Today's Progress***: Flicked through some of freecodecamp's Responsive Web Design Certification tutorials and decided to zip through their CSS challenges. All basics, but I learned some new things too.
- Use `:root` pseudo-class to declare CSS variables in order to have access to them globally (because they're inherited). This sets them for the whole page. You can reset the variable within a selector.
- You can use media-queries to change a CSS variable. Set them globally within `:root`, and then reset them within a media query.
- browser fallbacks when using CSS variables for IE - just include an alternative declaration beforehand.

I also started to work through the Applied Visual Design challenge section. Similar to the above - some interesting learnings on colour theory. 
- Saturation is a measure of how much grey there is in a colour (I've worked a lot with saturation but never knew that)
- Repeating linear gradients are pretty nasty looking
- How to use the `background: url();` property to set a pattern as a background image - I think I've done this before through googling + copy/paste but it's nice to see it explained.
- Transformations have always been a bit of a mystery to me, so there's a few new things here:
    - Scale is useful if you have >1 element with a class and you want one item to be a different size. Just set id's and use scale(). Works with `:hover` - useful for buttons perhaps.
    - SkewX and skewY make funky shapes like parallelograms
    - `::before` and `::after` pseudo-elements have also stayed a mystery to me for too long - they must always have a `content:` property (usually used to add things like photo or text to an element). but when you use `::before` /`::after` to make shapes, you can assign the `content:` property an empty string.
- Animations! Another one I've only ever really copied/pasted. The animation properties control how the animation should behave and the `@keyframes` rule controls what happens during that animation.         
    - `animation-name` sets the name which can be used by the `@keyframes` later. 
    - `animation-duration` sets the length of time for the animation. 
    - If you need the property to remain after the animation duration has finished, you can use `animation-fill-mode: forwards`. 
    - To keep an animation running infinitely or for a certain number of times, you can use `animation-iteration-count`.
    - The `animation-timing-function` property determines how quickly an element changes. Predefined keywords :`ease`, `ease-in`, `ease-out`, `linear`.
    - Bezier curves can be used with the cubic-bezier function - this uses a 1 by 1 coordinate system where x is the duration of the animation and y is the change in the animation. There are 4 main points, p0, p1, p2 and p3 (p0 and p3 are pr-set as the beginning [0,0] and end [1,1]). You anchor points in the form (x1, y1, x2, y2). A bouncing movement can be simulation by setting the y2 coordinate to >1.

***Thoughts***: Definitely not a challenging day, mostly covering old ground, but practicing stuff you already know can be good, I think. Plus, I did learn quite a bit more about CSS variables, transform properties, generating complex shapes and animations. The last few exercises sparked a bit of interest for creating some CSS art, so maybe I'll try that later in the challenge as I've never attempted it before.

### Day 2: Friday 28th August, 2020

***Today's Progress***: Completed the Applied Accessibility and responsive design section on freecodecamp. I knew quite a lot of this stuff beforehand, but it was useful to see the reasons behind why we use some of the accessibility features e.g.
- To accessibly hide elements - using zero values for px sizes removes them from the document flow, so it's ignored by screen readers - that's why they have to be set to 1px width and height, plus shifted to the side with `position: absolute;`.
- Using the `accesskey` property on anchor links to improve keyboard navigation.
- Using the `tabindex="0` property on `div`, `span` and `p` elements as they don't automatically receive keyboard focus. A negative tabindex indicates that it's focusable but not reachable by keyboard. Assigning different numbers to `tabindex` means you can order them - but 1 comes first, and it cycles through, and those marked 0 are last.
I also completed the Flexbox and CSS Grid sections, both of which I've used before and am comfortable with, but it's good to do a bit of revision and the completionist in me is getting good vibes from all these tickboxes...
Made a start on one of the project exercises to try and get myself into the swing of actually building things.

***Thoughts***: Another day of not too much exciting stuff, but lots of reminders. I'm actually a bit scared about starting to build something properly, but hopefully I'll pluck up the courage soon. At least I made a start on one of the FCC projects on codepen - it meets all of the user story requirements and passes the tests but I haven't done a lot of the styling yet. Will finish when I'm back at my laptop after the weekend.

***Link to work***: https://codepen.io/ichbinclamp/pen/mdPmNxw 

### Day 3: Wednesday 2nd September, 2020

***Today's Progress***: Started the day by finishing off a bit of simple styling in the FCC tribute page exercise codepen. I then completed the form exercise too.

***Thoughts***: Had an unexpected few days off due to car issues meaning I was away from my laptop for 4 days. Back to the grindstone now, however. Unsure whether doing these exercises is worth it but it does seem like it's taking me a little longer than I would like, so maybe it's good practice. The repeating image background with the linear-gradient still confuses me a little so maybe I'll return to that lesson, or look it up again elsewhere.

***Link to work***: https://codepen.io/ichbinclamp/full/GRZMmPx 

### Day 4: Thursday 3rd September, 2020

***Today's Progress***: Completed the FCC technical docs exercise.

***Thoughts***: Thought this might be a good one to try as I've never made anything like this before with a fixed navbar. Was pretty simple and not that interesting to be fair...

***Link to work***: https://codepen.io/ichbinclamp/full/NWNaQdr

### Day 5: Friday 4th September, 2020

***Today's Progress***: Today I worked on a short, simple algorithm for work to access and transform some bank account data. I also read a chapter of Don't Make Me Think by Steve Krug.

***Thoughts***: Simple stuff. Code reviewed and off to merge into dev.

### Day 6: Monday 14th September, 2020

**_Today's Progress_**: Not much free time today so just a couple of chapters of Don't Make Me Think. Did some templating and set-up for translating content at work.

**_Thoughts_**: Not an exciting one! Gotta start prioritising learning some new stuff I think. Maybe I'll get a chance to organise that tomorrow.

### Day 7: Tuesday 15th September, 2020

**_Today's Progress_**: Did some work on content templating today ready for a new page for our service's accessibility statement.

### Day 8: Wednesday 16th September, 2020

**_Today's Progress_**: Read a chapter of Don't Make Me Think

### Day 9: Thursday 17th September, 2020

**_Today's Progress_**: Debugged an error in one of our apps at work where we use a dependency called govuk-frontend. It was out of date, and leading to missing underlining on some links in the footer - not great when you're deploying your accessibility statement...

### Day 10: Friday 18th September, 2020

**_Today's Progress_**: Worked on a couple of different tickets today at work. One was altering some SAML requests in a mocked service to do with previous addresses, the other adding an API key header to a call, and altering the linked mock service to throw a 401 error if the request is unauthorised.

**_Thoughts_**: Felt pretty productive today!

### Day 11: Saturday 19th September, 2020

**_Today's Progress_**: Read a chapter of Don't Make Me Think

### Day 12: Sunday 20th September, 2020

**_Today's Progress_**: Did a bit of investigation around Shopify and deciding whether or not it'll be useful for a client I'm working with.

### Day 13: Monday 21st September, 2020

**_Today's Progress_**: Not much to add here, bits and bobs for work on two repositories, a microservice and an API stub.

### Day 14: Tuesday 22nd September, 2020

**_Today's Progress_**: Had a call with a client(!!) about building a new site for them, involving a shop and blog section. Have drafted up some design ideas.

### Day 15: Wednesday 23rd September, 2020

**_Today's Progress_**: Got the keys to the Wordpress site today, which means I could have a look around! It's been absolutely ages since I've used a wordpress site - I think the last time was when I was the 'head of website' for a student society about 5 years ago. Now I need to figure out how I'm going to work on this project. My client says they're not tied to Wordpress - the site is a bit bare-bones at the minute - but they've got quite a history of blog posts which they'd like to keep. So I've been investigating different ways of dealing with this. I've thought about keeping WP and developing my own theme, or exporting the blog data and going with something like Shopify, or building a new static site entirely. I came across the idea of making WP headless and building a react frontend, which I quite like, but further investigation is required!

### Day 16: Thursday 24th September, 2020

**_Today's Progress_**: Have spent a couple of hours or so researching the wordpress REST API('s! There's multiple...). Then I investigated how to figure out the domain situation if I build a frontend/deploy separately and then use the domain name for that application rather than the wordpress site. I also played around with [Frontity](https://docs.frontity.org/), an open-source framework which lets you build a React frontend for a WP site. I'm pretty impressed so far, it spins up super quickly and pulled in all of my clients blog posts straight away. I've deployed what I have already using Vercel. Ready to read-up on how to make a theme, exciting stuff!

***Thoughts***: Got to say, Wordpress documentation is not easy to navigate - I think it's to do with the difference between wordpress.org and wordpress.com, but there's a lot of conflicting information out there and if you aren't exactly certain what you're looking for, it's a bit of a minefield. Turns out there was an API set up before it was a part of WordPress core, which is primarily used for wp.org, but is enabled on wp.com. But when you're working with wp.com, the URL structure is different and sometimes the structure of the endpoint/queries differ. It makes it a bit more confusing that they're pretty similar. 
For my own future reference, and maybe I might write some kind of blog about it later, what I've found out:
The _most recent version_ of the REST API is v1.1 (at least this is what it says in the docs), has documentation on [https://developer.wordpress.com/docs/api/](https://developer.wordpress.com/docs/api/) and their base URL is `https://public-api.wordpress.com/rest/v1.1`. 
However, you can also find a second API base URL - apparently this is a seperate REST API that shipped as a part of WP core v4.7. The base URL for this API is `https://public-api.wordpress.com/wp/v2/` and the documentation is at [https://developer.wordpress.org/rest-api/](https://developer.wordpress.org/rest-api/).
Not just me that finds that confusing, right? Anyway, after fiddling around with Frontity, I found that it uses the baked-in version i.e. the second option above. So I guess I'm using that API!
Things to figure out:
I want to use my clients custom domain (managed by wordpress) for the deployed react app instead of the wordpress site (which will be headless, I think). So I need to stop using it for the wordpress site before I can set up the react site properly, as the wordpress site URL is used in the API calls.

### Day 17: Friday 25th September, 2020

***Today's Progress***: Took a look at GitHub this morning and realised I had around 20 notifications about security issues with various repositories, so had to spend about an hour tidying those up. That'll teach me to not deal with them immediately... Spent the rest of the day learning more about Frontity and how to make a custom theme. 

***Thoughts***: Ending the day feeling quite frustrated due to lack of understanding. Setting up a new theme to begin with was fairly straightforward and the docs are great, but the configuration is a little confusing and it's not too familiar to the React apps I've built in the past because there's extra packages that don't have huge amounts of documentation. Basically, I had a bit of a struggly day and now I'm grumpy.