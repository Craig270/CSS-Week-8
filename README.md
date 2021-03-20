# CSS-Week-8

Finish FreeCodeCamp CSS work

\*\*Style the website you made last week using CSS. Below are the requirements:

--Use only external CSS file (no internal or inline styling)

--Every element must be styled

--Create style rules using class, id, and element selectors

What is CSS clearfix, how is it used, and why is it helpful?
CSS technique to solve the problem of floating elements when you have an element floating to the right and an element floating to the right and you want them to be inline, next to one another in the same div. This will make the div’s border containing the two elements shrink in size above them and not wrap around them as intended. Using the work around clear fix is an easy way to make sure the dev’s border is wrapped around both the left and right element. Making a class called .clearfix and adding the key value pair, overflow: auto;; seems to be the quickest fix I was able to find. Keep in mind you should have control over the margins and padding in that div or else it could result in scorebars. The other popular way and the way you should use if you can not control the margins and padding, is to make .clearfix contain the following three key value pairs: content: ""; clear: both;display: table;. Doing this will wrap the border of your div around the two floating elements, one to the left and one to the right.
What are SaSS and LESS?
SaSS basically allows you to do a lot more with CSS than you could normally do with CSS.
These are preprocessors for CSS. Gives the coder the ability to easily create reusable components. SaSS allows you to write CSS code but then it takes your CSS code and compiles it so that it’ll add all the vendor prefixes for the browsers that don’t necessarily support something like flex box or other CSS properties that may not work across browsers. SaSS also allows you to create a variable in your CSS code that could be used for something such as a color you want to add to all your buttons on your webpage you could add the value and only need to change it where the value is declared and not on every single button. You are also able to do nested values with it, allowing you to put header buttons class inside your header class. This is a great way of condensing everything in one area of your CSS code. SaSS also allows you to make what are called @mixin that is basically a function in CSS that could allow you to create arguments for your mixin that accepts different variables when called, just like a function in JS almost.
What is your favorite thing you learned this week?
I think my favorite thing this week was exploring some of the websites that teach you CSS and make life building a website easier. My favorite thing to find had to be the color generator https://coolors.co/ I found it so much easier to come up with cool colors using this website! https://codepen.io/trending Code Pen was also a very cool resource to find as it allows you to easily see your HTML, CSS, and JS all together in one page and the effect that has on your webpage when you make changes to one. The last very cool thing I found was CSS Battle https://cssbattle.dev/ that allows you to practice writing CSS to make all sorts of shapes and color schemes. This website was awesome to get an idea of the other potential things that can be done with CSS.

Sources:
https://youtu.be/Zz6eOVaaelI
https://www.w3schools.com/css/css_float_clear.asp
https://www.freecodecamp.org/
