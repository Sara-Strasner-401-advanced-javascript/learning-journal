# CSS

CSS properties affect how elements are displayed. CSS associates style rules with HTML elements. A CSS rule contains two parts: a selector and a declaration.
 - **Selectors** indicate which element the rule applies to. The same rule can apply to more than one element if you separate the names with commas. 
 - **Declarations** indicate how the element referred to in the selector should be styled. Declarations are split into two parts (a property and a value) and are separated by a colon. 

![CSS Diagram](https://upload.wikimedia.org/wikipedia/commons/5/53/CSSsyntax.JPG)

### How CSS Rules Cascade
If there are two or more rules that apply to the same element, it is important to understand which will take precedence. 
- If two selectors are identical, the latter of the two will take precedence. 
- If one selector is more specific than the others, the more specific rule will take precedence over more general ones. 
- You can add `!important` after any property value to indicate that it should be considered more important than the other rules that apply to the same element. 

### Why use external style sheets?
CSS rules usually appear in a separate document, although they may appear within an HTML page. By putting your CSS rules in a separate style sheet, all of your web pages can share the same style sheet. If you are just creating a single page, you might decide to put the rules in the same file to keep everything in one place. However, many authors would consider it better practice to keep the CSS in a separate file. 

For commonly used CSS selectors, see [MDN CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors).


## Color
Color not only brings your site to life, but also helps convey the mood and evokes reaction. There are three ways to specify color in CSS: RBG values, hex codes, and color names. 

Color pickers can help you find the color you want. [Adobe Color](https://color.adobe.com/create/color-wheel) is a great resource. 

It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content). 

CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as *RGBA.* CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA. 