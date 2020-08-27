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
