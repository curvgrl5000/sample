Quick Takeaways
Mor Ben David is brand spanking new to this
field, with many questions and concerns.
He's coming from a totally different background,
but has expressed interest in the career.
This is a student that will undoubetedly take
longer due to the fact that he is completely
new to programming.  Anyhow, we're going to
focus on the basics vs. rush through to make
sure he's got a solid understanding.

+++++++++++++++++++++++++++++++++++++++++
Tuesday, Dec 6th, 2016

Mor's Background...
Israel, has a  H.S. Diploma,
spent 3.999% in the Israeli Military.
Worked in Security + Managed a Small Business.

Mor's Short Term Goal...
Is this a right fit?

Mor's Long Term Goal...
Choose a particular niche in software developement:
• UX && UI
• Product Manager
• Front End Development
• BackEnd Development
• IOS & MOBIILE
• Native Development
• DevOps

+++++++++++++++++++++++++++++++++++++++++

We started out the session with the following links that
will help any developer discover the current offerings of CSS  + HTML. 
Then worked on Cascading StyleSheets and how to nest folders
and link them in the HEAD of a document.

+++++++++++++++++++++++++++++++++++++++++
I recommend that you start working with these reference tools
- Codedrops CSS REF and the Dash Library.

The best part of this library is that it's written by an inspirational female, 
Sara Soueidan who was Named Developer of the Year in the 2015 net awards. Her story can be viewed here: https://sarasoueidan.com/about/

The reference CSS library can be viewed here:
http://tympanus.net/codrops/css_reference/

DASH LIBRARY at: 
https://kapeli.com/dash

Another great place for those CSS TRICKS  is here:
https://css-tricks.com/

One of the best places to get inspiration is at the Comm Arts website:
Communication Arts is where the latest and best examples of 
creativity for many disciplines:
http://www.commarts.com/

Another great place is DRIBBLE, where designers upload 
examples of work that they share with other designers:
https://dribbble.com/

+++++++++++++++++++++++++++++++++++++++++++++++++++

HTML5 CHEATSHEET
http://makeawebsitehub.com/the-html-5-mega-cheat-sheet/

+++++++++++++++++++++++++++++++++++++++++++++++++++

Get faster writing HTML with EMMET!!!
Emmet
http://emmet.io/

Emmet CheatSheet
http://docs.emmet.io/cheat-sheet/

+++++++++++++++++++++++++++++++++++++++++++++++++++

When you want to read an inspiring story of a developer's path,
let's have you checkout the MIT LABS media blog. There is where
you can read about a Developer's Work, what the industry is thinking 
about a topic and how the marketplace is integrating the product offering.

http://www.media.mit.edu/people/students

+++++++++++++++++++++++++++++++++++++++++++++++++++

Another great resource that's coming to market is the KITE.COM 
platform. It's going to be the automated pair programming tool, 
that takes off where DASH might have left off. It IS the pair programming wave of the future. It's in Beta right now, but will soon be previewed into the marketplace! Sign up!

http://techcrunch.com/2016/04/14/kite-wants-to-be-every-developers-pair-programming-buddy/
https://kite.com/

+++++++++++++++++++++++++++++++++++++++++++++++++++

A way to research a stack:
http://stackshare.io/

+++++++++++++++++++++++++++++++++++++++++++++++++++

What is cascading Stylesheets...

Remember that CSS is called Cascading for a reason.
When you have styles that start at the top of a document,
they will be over-ridden by the styles at the bottom of the document.

AND where the styles actually live inside of that structure makes
a huge difference. For instance in your HTML code:

<p>
	<a href="#">Something</a>
	<h1>I'm a black and love it!</h1>
	<h1 class="pink">pink</h1>
	<h1 class="red">red</h1>
	<h1 class="green"></h1>
</p>

Your h1 element is not going to render inside your p element in
the browser? WHY? Because there are certain kinds of 'tags' or
elements that cannot be rendered inside of NESTED ELEMENTS.

The anchor tag is a child element of the 'p' tag.
The 'p' tag is nested element of the 'body' tag.
BUT the 'h1' tag does not render efficiently in the 'p' tag as the
structure is not allowed and will not render properly.

Hence, it is important to neatly write your code within the documents,
and if you have a problem with how elements might render inside of 
other elements, double-check the structure.

BACK TO H1.
Isn't interesting that the H1 tag's color is black?
That's the USER AGENT STYLESHEET at work.
It means that we are INHERITING the style sheet from the BROWSER.
And only when we over-ride this property in the style sheet with a CLASS
does this change.

So the following properties defined in your CSS stylesheet will OVER RIDE the 
styles provided by the User Agent Stylesheet of the browser you're using.
All browsers these days have default styling, that you have to over-ride.

EX:
.pink {
	color: pink;
}
.red {
	color: red;
}
.green {
	color: green;
}

Cascading works when you add a property to a class  like '.green' and
the last property and value will load when the browser loads.

EX:
.green {
	color: green;
	color: blue;
	color: aqua;
	color: pink;
}

TADA!
UNCHECK the items one by one and you'll see the 
cascading effects in action!!!
Keep coding and trying and you'll most likely get it!

+++++++++++++++++++++++++++++++++++++++++++++++++++

A few Good Reads:
How to Change Your Career from Web Design to UX Design
https://www.interaction-design.org/literature/article/how-to-change-your-career-from-web-design-to-ux-design

Making the Transition from Development to Design—My Experience and Advice
http://somerandomdude.com/2012/01/10/transition-from-development-to-design/
** A bit backwards, but here you see where you can pitch your value on both sides

Designers And Developers: No Longer A House Divided
https://www.smashingmagazine.com/2015/05/designers-and-developers-no-longer-a-house-divided/

Also to get a reading list going join medium.
https://medium.com/

Khan Academy - https://www.khanacademy.org/
EDX -  https://www.edx.org/

+++++++++++++++++++++++++++++++++++++++++++++++++++
  SEE YOU NEXT TIME!
  Best,
  ANNA


