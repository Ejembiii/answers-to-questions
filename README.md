1.	The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.

2.	Advantages of CSS:
•	Better website speed.
•	Easier to maintain.
•	Consistent design.
•	Time saving.
•	Better device compatibility.
•	Better device compatibility.

3.	Limitations:
•	CSS cannot perform any logical operations like if/else or for/while or +/-.
•	We cannot read any files using CSS.
•	It cannot interact with databases. 4.CSS cannot request a web page.

4.	The 3 ways to include CSS in webpage are:
•	Linking the external file with your web page.
•	By creating a CSS block i.e., inserting within the <head> and </head> tags.
•	By inserting the CSS code right on the tag, itself i.e., in-line CSS.

5.	Selectors:
•	CSS Element Selector.
•	CSS Id Selector.
•	CSS Class Selector.
•	CSS Universal Selector.
•	CSS Group Selector.

6.	A CSS preprocessor is a program that lets you generate CSS from the preprocessor's own unique syntax. Most CSS preprocessors will add some features that don't exist in pure CSS, such as mixin, nesting selector, inheritance selector, and so on. These features make the CSS structure more readable and easier to maintain.
I.	Sass - is the most mature, stable, and powerful professional grade CSS extension language in the world. It is compatible with all versions of CSS and has a large community.
II.	Less - (which stands for Leaner Style Sheets) is a backwards-compatible language extension for CSS. It is a CSS pre-processor that enables customizable, manageable and reusable style sheet for website.
III.	Stylus - is a dynamic stylesheet preprocessor language that is compiled into CSS. It aims to add functionality to CSS without breaking compatibility across web browsers. It does this using variables, nesting, mixins, functions and more. Stylus syntax is very flexible.

7.	Viewport Height (vh) - This unit is based on height of the viewport. A value of 1vh is equal to 1% of the viewport height. Viewport Width (vw) – This unit is based on the width of the viewport. A value pf 1w is equal to 1% of the viewport width.

8.	Resetting CSS: A CSS reset is a set of styles that you load before your other styles to remove built-in browser styles. Every browser has its own user agent stylesheet, which it employs to make unstyled websites more readable. Most browsers, for example, make links blue and visited links purple by default, add a border and padding to tables, apply various font sizes to H1, H2, H3, and practically everything, and apply a specific amount of padding to almost everything.
Normalizing CSS: Normalizing CSS improves cross-browser consistency in HTML element default styling of the browser’s user agent. It’s an HTML5-friendly replacement for the standard CSS Reset.

9.	CSS Display:
•	An inline element has no line break before or after it, and it tolerates HTML elements.
•	An inline-block element is placed as an inline element (on the same line as adjacent content), but it behaves as a block element.
•	A block element has some whitespace above and below it and does not tolerate any HTML elements next to it.

10.	Yes, it is. Testing of webpage on different browser helps to deliver consistency and accuracy. In modern times web users use different web browsers and devices and so making sure the webpage serves each of those, no matter which browser or device they’re using is necessary.

11.	Pseudo-classes select regular elements but under certain conditions, like when their position relative to siblings or when they’re under a particular state.
Pseudo-elements effectively create new elements that are not specified in the markup of the document and can be manipulated much like a regular element. This introduces huge benefits for creating cool effects with minimal markup, also aiding significantly in keeping the presentation of the document out of the HTML and in CSS where it belongs.

12.	CSS has several different units for expressing a length. Many CSS properties take "length" values, such as width, margin, padding, font-size, etc. Length is a number followed by a length unit, such as 10px, 2em, etc. The absolute length units are fixed and a length expressed in any of these will appear as exactly that size. Relative length units specify a length relative to another length property. Relative length units scale better between different rendering medium.


13.	Top and bottom margins do not affect inline elements because inline elements flow with content on the page. You can set left and right margins/padding on an inline element but not top or bottom because it would disrupt the flow of the content.

14.	The property used in changing the font face is the font-family property.

15.	The adaptive design display different fixed layouts that are created to adapt to the user’s screen size while the responsive design will reconfigure all design elements whether it’s viewed on a desktop, laptop, tablet, or a mobile phone. 

16.	The browser determines what styles to show on an element depending on the specificity of CSS rules. It also matches the selectors from right to left to find the children and then check their parents to see if they match the rest of the parts of the rule.

17.	Content-box: The width & height of the element only include the content. In other words, the border, padding and margin aren’t part of the width or height. Now the border-box: The padding and border are included in the width and height.

18.	To set the opacity of a background, image, text, or other element, you can use the CSS opacity property. Values for this property range from 0 to 1. If you set the property to 0, the styled element will be completely transparent (i.e., invisible).

19.	We should because it is necessary for controlling the positioning and format of the content on the page. However, float property can also be used to wrap any inline elements around a defined HTML element, including lists, paragraphs, divs, spans, tables, iframes, and blockquotes.

20.	Z index (z-index) is a CSS property that defines the order of overlapping HTML elements. The z-index property specifies the stack order of an element (which element should be placed in front of, or behind, the others).

21.	Flexbox properties
•	Display.
•	Flex-direction.
•	Justify-content.
•	Align-items.
•	Flex-wrap etc.

22.	The cascade is an algorithm that defines how to combine property values originating from different sources. It lies at the core of CSS, as emphasized by the name: Cascading Style Sheets.

23.	To move the inner div container to the center of the parent div we must use the margin property of style attribute. We can adjust the space around any HTML element by this margin property just by providing desired values to it. The div tag is used to construct a division or section of an HTML document in which other elements of HTML is placed and that division/section works like a container whose CSS styling can be done as a single unit or JavaScript can be used to perform various tasks on that container. 
<div>
 <h3>'This is a div of the web page.>/h3>
 <p>This is some text in a div element.</p>
               </div>

24.	Properties
•	All (default. Used for all media type devices)
•	Print (used for printers)
•	Screen (used for computer screens, tablets, smart phones etc.
•	Speech (used for screenreaders that “reads” the page out loud).

25.	CSS Grid is a two-dimensional grid system used to work on the layout of UI elements and segments of a webpage. The Grid comprises horizontal and vertical lines to form rows and columns, much like a table.

26.	Different ways to hide elements using CSS: Absolute position, Color, Clip-path, Display, filter, Measurements, Opacity, Transform, Visibility.

27.	The :root pseudo-class represents an element that is the root of the document. In HTML, this is always the HTML element. 
Syntax
selector: root{ properties }

               example
               [style.css]
                   :root{
                      background-color: #ccc;
                    }

                 [index.html]
                 <body>
                         <p>This is a paragraph.</p>
                 </body>

28.	The basic difference between CSS Grid Layout and CSS Flexbox Layout is that flexbox was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time.

29.	The !important rule in CSS is used to add more importance to a property/value than normal.
In fact, if you use the !important rule, it will override ALL previous styling rules for that specific property on that element!
example
#myid {
  background-color: blue;
}

.myclass {
  background-color: gray;
}

p {
  background-color: red !important;

30.	What's the difference between margin and padding in CSS? In CSS, a margin is the space around an element's border, while padding is the space between an element's border and the element's content.


