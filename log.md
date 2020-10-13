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

### Day 18: Saturday 26th September, 2020

***Today's Progress***: Read through more of the documentation to try and get my head around the issues I encountered yesterday - namely whether I could create custom pages in Wordpress.com (rather than wordpress.org) so that my client could update his own shop through the wordpress CMS. Turns out it's not possible without converting the site to wp.org. The other was figuring out the routing without having a custom page.

***Thoughts***: A lot of the issues I've been having are due to the fact the wordpress site is on wordpress.com rather than .org - I never knew they were two separate entities before this project, and that there were so many differences between them. I'll be sure to remember this for future projects and maybe consider transferring any .com sites to .org.

### Day 19: Monday 28th September, 2020

***Today's Progress***: Spent today trying to muscle the Frontity project into something more familiar. Styling should be straightforward - I've only used CSS-in-JS frameworks a little before but it's easy enough to get used to. I think the differences in how you manage state within a Frontity project will take a bit more getting used to, but we'll get to that when we need to. Started building out the header and footer.

***Thoughts***: I'm trying to power through my frustrations - I think this is mainly why I don't tend to have a lot of side projects - when I get stuck on something, I get super frustrated and either want to give up, or can't give up until it's sorted. Neither is incredibly healthy, I guess, but I have to figure out a way through it...

### Day 20: Tuesday 29th September, 2020

***Today's Progress***: Today I built out the subscription form in the footer for the mailchimp newsletter that my client has. I decided to go for a package that does it out of the box for now, but I know it's not a long term solution. It's not like a form is particularly difficult to manage but I need to figure out how to properly manage state in Frontity first I think. I'm marking it down as a technical debt, and will try and rebuild the form from scratch when the rest of the site is up and running.

***Thoughts***: Probably not the smartest move, the package isn't regularly updated. Hopefully I'll get a chance to come back to this soon and rebuild from scratch.

### Day 21: Wednesday 30th September, 2020

***Today's Progress***: Worked on tidying up the mobile/tablet responsiveness today. Took me a while to get it right, and involved a lot of tweaking breakpoints to make the footer neater especially. Also added the logo into the header and hero on the main page, which makes it look a lot better!

***Thoughts***: I find this process incredibly frustrating, especially when the site looks different when you've deployed it as it does when you're using inspect in the browser when running locally.

### Day 22: Thursday 1st October, 2020

***Today's Progress***: Today I worked on trying to get the Shopify CDK working on the site, and lets say it wasn't particularly successful. I've looked at a lot of examples and it doesn't seem too difficult - you just have to install the package, initiate the shopify client and then you should be able to use the functions. But despite initiating the client and it being available in my components, it doesn't seem to be able to access the functions - I keep getting the error `fetch is not defined at Client.fetcher`. Can't seem to work out what I'm doing wrong.

***Thoughts***: ARGHHH

### Day 23: Friday 2nd October, 2020

***Today's Progress***: Carried on trying to debug my issue from yesterday. No progress yet, urgh! Spent the rest of the day preparing for an interview.

***Thoughts***: Need to figure out where I can get some help with the shopify problem.

### Day 24: Monday 5th October, 2020

***Today's Progress***: I fixed the issue!! I don't feel so bad about it because apparently it's not explained very well in the documentation of the Shopify SDK. Apparently, you have to pass in some fetch implentation when you initiate the client. I found this out by re-reading a github issue I'd found earlier but actually paid attention to this time [here](https://github.com/Shopify/js-buy-sdk/issues/458).

***Thoughts***: Well that wasted some time. Never mind I guess, this kind of thing happens all the time.

### Day 25: Tuesday 6th October, 2020

***Today's Progress***: Carried on working on the ecommerce site. Nothing much exciting happened, just fiddled around with where I was calling the Shopify API and how the responses were being rendered.

### Day 26: Wednesday 7th October, 2020

***Today's Progress***: Ended up back at square one - I've decided that Frontity isn't the way to go with this project. Whilst it makes the blog aspect much easier by sorting out all the wordpress gubbins, it makes everything else so much harder, especially the shop, which is meant to be the main aspect of the site. I'll take this as a learning point. Going to just use straight react.

***Thoughts***: I'm frustrated. Very, very frustrated.

### Day 27: Thursday 8th October, 2020

***Today's Progress***: Started building the site in plain old react today, which I'm much more used to. I think I'll try and get the shop sorted out first this time, and everything else will hopefully fall in place later. Perhaps I can even deploy it in stages, with the wordpress blog integration coming later. I focussed on getting the routing sorted to begin with.


### Day 28: Friday 9th October, 2020

***Today's Progress***: Shopify is now integrated into the site. I've used a boilerplate with a cart etc for ease because I've not done this sort of this before, though I've been through it all and made sure I understand how it works. It uses React context which I haven't used previously but seems pretty cool, I'll be using it again in future.

### Day 29: Monday 12th October, 2020

***Today's Progress***: Started building out the rest of the site, starting with the header and navigation. Think I've sorted it all now. I decided to use a UI framework called atomize, which I wouldn't normally turn to in projects, but it's speeded things up a bit which is nice. Also started building out the footer again. Managed to salvage some of this from the last iteration, though I'm building the mailchimp subscription input myself this time instead of using an out-of-date package. That's tomorrows job.

<!-- ### Day 30: Tuesday 13th October, 2020

***Today's Progress***: 

***Thoughts***:  -->