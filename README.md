# Udacity-Full-Stack Development Track
 
## Milestone 1 -
<details>
  <summary> Intro to HTML: </summary>

  ### 1.1- Intoduction
  - The web is a collection of documents written in html.
  - **Hypertext**: is a form of text in which documents can refer(link) to other documents and resources.
  - The web is a hypertext system.
  ### 1.2- Web pages and servers
  - Web pages are usually stored on servers.
  - A server is a special computer that isn't fundamentally different from your personal computer, but they have a programs on them that answers the browser's requests.
  - All of the resources you see on a web page stored on the same server or from other web servers.
  - Usually, to load a web page, your browser sends a request for that page to a server.
  - Hypertext transfer protocol(HTTP): The rules of how the requests and responses are work.
  - The difference between addresses with http: and https: is whether the browser uses encryption to keep your data private (the S stands for Secure).
  - A web browser is an application, like Chrome, Firefox, Edge, or Safari, that is designed for displaying web pages.
  - HTML: Hypertext Markup language, is the language that provides the structure and the text of web page.
  ### 1.3- HTML and programming
  - Syntax: is a grammer rule of a language(Rules for how could you put your code together).
  - Formalism: Computers are stupid :"D. Computer take code literally, word for word letter for letter.
  - Nesting: Some bits of code is inside other bits of code in an orderly way.
  - Ther's a lot of Help and alot of people learing code and there is a lot of resources to help.
  - One of the most important resouces is documentations.
  - [MDN](https://developer.mozilla.org/en-US/)
  ### 1.4- Text Edittor and files
  - make file and save it with .html to open inside the browser.
  ### 1.5- The Job of HTML
  - Html is made of:
    - Text that the user will actually read in the browser.
    - Markup which tells the browser what that text should look like, how it's arranged, and within markups there can be resources.
    - Resources to include other files and documents like images and videos.
  ### 1.6- Markup
  - Markup is a text wich has special meaning.
  - it calles Tags.
  - tags always open with < and ends with > wich is usally calles angle brackts.
  - An opening tag marks the beginning of an element.
  - An closing tag marks the ending of an element.
  - Technically, < em >Hello!</ em > is an element.
  ### 1.7- Breaks and empty elements
  - Browser Collapse all witespaces together, So we don't see the line breaks we put on it.
  - Whitespace includes spaces, tabs, and line breaks. When the browser displays an HTML file, it treats a run of whitespace as a single space character. In order to create a line break that will show up in the browser, use the < br > tag.
  ### 1.8- Paragraphs
  - we use Paragraphs to markup all of Paragraphs.
  - using paragraph tags instead line break to tell the browser about the structure of our text.
  ### 1.9- Lots of elements
  - sub and sup stand for "subscript" and "superscript". Originally, HTML started out as a tool for scientific and academic work; and these are really useful for science and math, like writing x2+3x+4 = 1 or chemical formulas like H2O.
  ### 1.10- Nested elements
  - Element can be inside other element.
  - Html can't be Overlap like this
  ```
  <em> Text <sup> Text </em> text </sup>
  ```
  ### 1.11- Block and inline
  - p is a block element, which means the browser creates a box around it. It also generates a margin around this box, to visually separate the paragraph from surrounding elements.
  - br is an inline element that just creates a line break. It doesn't have a box around it and doesn't create any margin.
  - [Block Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements#Elements).
  - [Inline Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements#Elements)
  ### 1.12- Practice — The div element
  - The div is short for division, because that's what this element is for—you can use it to divide up the page into different sections.
  - Like the paragraph p element, the division div element has an invisible box around it—and just like p, it can have a border, a margin, a width, a height, and so on.
  - But a p element is specifically meant to contain text. In contrast, the div element is a generic container for whatever other elements you might want to put inside. You can use the div element to organize the content and divide the page into sections.
  ### 1.13- Lists and implied close tags
  - The default display of an unordered list (ul) uses bullet points. The default display of an ordered list (ol) uses numbers.
  - li can be only occur inside ol or ul tags. so that li is an element for which the closing tag is optional.
  - when browser see li opening tag it knows that the previous li must be done, so the closing tag is optional.
  - But ul and ol tags must have closing tag.
  - if we leave off the closing </ ol > or </ ul >, then the browser will not know when our list ends! It will simply treat everything that comes after that point as part of the list
  - The p element is another example of an element for which the closing tag is optional.
  - when you leave off an optional closing tag, it is still implied—that is, the browser will figure out where the element should be closed, even though you didn't explicitly tell it.

  ### 1.14- Nested lists
  ```
  <ul>
    <li>Mammals
      <ol>
        <li>Raccoons
        <li>Gorillas
      </ol>
    <li>Reptiles
      <ol>
        <li>Iguanas
        <li>Cobras
      </ol>
    <li>Birds
      <ol>
        <li>Ostriches
        <li>Ravens
      </ol>
  </ul>
  ```
  ### 1.15- Practice — Indentation
  - Instead of writing like this:
  ```
  <p>
  Does indentation matter?
  </p>
  ```
  - Use Indentation
  ```
  <p>
      Does indentation matter?
  </p>
  ```
  ### 1.16- Practice — Implied close tags
  - Without the closing</p> tag, the browser will still close the element automatically—but not until it sees the next p element starting. So all of the text up until that point gets included in the contents of the blue p element.
  - With li and p, the browser can figure out where to close the element. But with an element like strong, there's no way for the browser to know where you want the emphasis to stop!
  - The br element is a void element— it doesn't have any contents (unlike p, which does have contents!).
  ### 1.17- Web addresses
  - URL: Uniform Resource Locator.
    - Uniform: Standerized
    - Resource: file or other data object
    - Locator: address for finding something.
  - A fully-qualified URL contains:
    - http, https, file -> protocols
    - :// -> separate protocol from the next part.
    - ex.com -> the domain name, which tells the browser what server to connect to.
    - file -> no domain followed it.
    - / -> file path.
    -  When you're linking to the top page (or home page) of a site, the URL does not need a file path after the domain name.
    - If we look at the URL for a file on your local system, we must give the file path instead of domain.
  ### 1.18- Links and the <a> tag
  - The web is based on the idea of hypertext.
  - <a href="http://example.net/stuff.html">Example Page</a>: anchor element
    - href="http://example.net": hypertext reference attribute
    - The Example Page: contents (what the user actually clicks on)
    - </a>: closing anchor tag
  ### 1.19- Adding images
  - ```<img src="https://fakeurl.example.net/fish.png" alt="Fish">:```
    - src -> url of the image file(it doesn't copy the file it just tell the browser where   to find it)
    - alt -> description of the image, (displayed if the file is missing or the user's network connection stops before the image is loaded or if the user can't see the image for instance if they are blind).
    - empty element -> No closes tag.
  - To create an image that is a link, put an img element between the open and close tags of an a element, for instance:

  ```<a href="https://google.com"><img src="glogo.png" alt="Google!"></a>```
  ### 1.20- Files and relative URLs
  - Relative URLs Is a url that has the path of the file in the local computer
  - a url without :// the browser will treat it as a relative url and look for it as s file inside the computer.
  ### 1.21- Practice — Images and relative URLs
  -  attributes always go inside the start tag of an HTML element.
  - [placekitten](https://placekitten.com/)
  - [placebear](https://placebear.com/)
  ### 1.22- Documents: The DOCTYPE tag
  ``` <!DOCTYPE html> ```
  - without this tag browser will go into quirks mode, which trying to be compatable with older versions of html.
  ### 1.23- Documents: Head and body
  ```
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <title>Title of your page</title>
    </head>
    <body>
      Content goes here! (Things like paragraphs, links, and images.)
    </body>
  </html>
  ```
  - **Are head and body required?**
  - In one sense, no, but in another sense, yes.
  - The grammar of HTML does not require that you literally write a <head> or <body> tag in your HTML code. Many web developers do write these. However, if you don't, the browser will attempt to place them into your code itself.
  - It needs to put the head element around certain elements that belong there, such as title; and to put the body element around the elements that form the document's body. This means that all the head elements must appear first, and the body elements after.
  ### 1.24- Validating HTML
  - Web browsers are very lenient about how they interpret HTML. They work around small errors and omissions.
  - [validator](https://validator.w3.org/)
  
</details>

 
<details>
  <summary>Intro to CSS</summary>

  ### 2.1- Starting with style
  - CSS -> cascading style sheet.
  - language fo descriping the visual appearance of the web pages, including properites such as layout, colors and fonts.
  ### 2.2- Developer tools
  - Developer Tools makes this representation look like HTML, because that's a convenient way for web developers to see what's going on in the page. But the view that you see in Elements is actually a picture of the way the browser thinks about the page internally — not just a copy of the original HTML file.
  - **Google Chrome**: Open the Chrome menu at the top right of the browser window (the three vertical dots), select and select Tools > Developer Tools, OR
  - Right-click on any page element and select Inspect.
  ### 2.3- Text to trees
  - Text edittor -> made of text.
  - Browser -> image made of pixels.
  - The Browser reads html and it turns the code into the editor into a map(tree), and then tutns it into screen.
  - This kind of data structure called tree structure because each element can have a branch.
  - DOM -> Document object model, the particular tree structue for html.
  - DOM has tree structure for each html element.
  ### 2.4- Tree structure
  - Tree structure: Not diagram, it's data structure, a way that information can be organized.
  - Rules for trees structure:
    - The tree starts with a single node, the root, which has no incoming branches(no parent).
    - Each node can have branches to new nodes(Childrens).
    - Each (non-root) node can have only one incoming branch(one parent).
  ### 2.5- Trees to boxes
  - Tree structure tuns into boxs.
  - Each element displayed into a box.
  ### 2.6- Styling HTML directly
  - The first way is to use the style attribute to apply style directly to an HTML element.
  - The second way is to use the style element along with a ruleset.
  - when styles are applied directly to an HTML element using the style attribute, these are called inline styles.
  - The idea is that the style is being applied directly in the same line as the HTML element that it is styling.
  ### 2.7- Practice — Multiple styles
  ```<p style="color: blue; text-align: center;">Hello world!</p>```
  ### 2.8- Practice — Quotes or no quotes?
  - The quotes indicate where an attribute value starts and stops, even if there are spaces inside it.
  - An attribute value: the part that comes after the = sign.
  ```<p style=color: blue; text-align: center;>Hello world!</p>```
  - When we remove Quotes, the browser thinks <code>text-align:center;</code> is an attribute name not value.
  ### 2.9- Practice — Styling HTML separately
  - CSS is a different language from HTML. That means that it has its own syntax (or grammar), which is different from the syntax for HTML.
  ### 2.10- CSS syntax
  - There are two rulesets here. Each one has a selector and a block of rules.
  - The selector occurs at the start of each ruleset, and describes what elements the ruleset will be applied to.
  ```
  li {
      color: green;
      margin:20px;
  }
  ```
  - li -> selector
  - color: green; -> declaration / rule 
  - {color: green;margin:20px;} -> declaration block
  - color: -> property
  - green; -> value
  ### 2.11- Selectors: Type
  - Type selectors are written using just the type name.
  ### 2.12- Selectors: Class and ID
  - class: is a group of things with the same characteristic.
  - Whenever you see a CSS selector starting with a dot, you know you're looking at a selector that applies to the class of elements.
  ### 2.13- Selectors: Combining
  - [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors)
  ### 2.14- What's so "cascading" about CSS?
  - The term "cascading" in Cascading Style Sheets refers to the way that style properties "cascade" down the DOM tree, starting at the top. A style applied to the body element will affect the entire document. A style applied to a lower-level element will affect that element and all its descendants.
  - A style applied at a lower level can override a style at a higher level. For instance, if the body has color: red but a paragraph within the body has color: blue, the blue will apply to that paragraph and to any elements inside it:
  ```
  <style>
      body { color: red; }
      p { color: blue; }
  </style>
  <body>
      <p> This will be blue, not red. <br>
          <em> Same with this. </em> </p>
  </body>
  ```
  ### 2.15- Units
  - CSS allows you to specify heights (and other distances) using inches or centimeters, but a yard (36 inches) is a much larger unit than we usually use on the web.
  - The CSS unit em is named for the size of the letter "M", and comes from print typography. The HTML element < em > is short for "emphasis". They're spelled the same, and often pronounced the same, but they have no other relation between them at all.

  ### 2.16- Boxs
  - Each element is inside a box.
  ```
  <style>
    .blue_box {
      border: 10px solid blue;
      padding: 0.5em;
      width: 150px;
      height: 100px;
    }
  </style>

  <div class="blue_box">Hooray, a box!</div>
  ```
  ### 2.17- Percentages
  - The width property only changes the width of the contents. The padding, border, and margin are not included in the width (so they add extra width around the sides of the box!).
  ### 2.18- Learning more CSS
  - Use Reference and search engine.
  - [Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference).
  ### 2.19- Separating style
  - Linking stylesheets: To link to a stylesheet in your HTML file, add a link element to the head of the HTML file. The syntax for the link element is just like this:
  ```
  <link rel="stylesheet" href="style.css">
  ```
  - If you are linking to a stylesheet located on another web server, you will use a full URL in the href attribute. If you're linking to one that's in the same directory as your HTML file, you can just use the filename as a relative URL.
  ### 2.20- Color
  - In browser each primary color(red, green, blue) can have 256 possible values.
  - Each primary color is stored in a single byte, a space in memory that can hold a number from 0 to 255.
  - In all cases, we need to give the amount (or you could say the intensity) of each of the three primary colors: red, green, and blue (RGB).
  - We've been using the words "amount" and "intensity". What we really mean by this is the brightness of the light. Higher values indicate brighter (more intense) light, and lower values indicate darker (less intense) light.
  - By mixing different levels of red, green, and blue, we can get different colors, at different levels of brightness.
  - To make gray, use equal amounts of red, green, and blue. But if all three colors are equal to zero, you'll get black; and if all three are the maximum value (255, FF, or 100%) you'll get white.
  - what about hex values, like #00cc66 or #99ccff? These look strange, but they work the same way. Each pair of digits is a number that gives the intensity of red, green, or blue. The reason these values look strange is because they're in a different number system—instead of the decimal system that we are used to working with, these numbers are given in the hexadecimal system.
  - Hexadecimal is not as complex as it might appear. Instead of having 10 digits (0, 1, 2, 3, 4, 5, 6, 7, 8, 9), hexadecimal has 16. Since we don't have 16 number symbols, hexadecimal counts up to 9 and then starts using letters.
  ### 2.21- Practice — Searching for properties
  - Even experienced developers don't have every single property memorized. Fortunately, it's usually easy to find what you need by looking it up in the documentation or using your favorite search engine.
  - Most of the time, you can simply type in "CSS", followed by some words related to the property. For example, if you want to know how to set the background color, searching for "css background color" will turn up the results you're looking for.
  ### 2.22- fonts
  - use font-family property.
  - [Get Started with the Google Fonts API](https://developers.google.com/fonts/docs/getting_started)
  - [Google fonts](https://fonts.google.com/).
  ### 2.23- Practice — Fonts
  - We can style fonts using a bunch of separate declarations, like this:
  ```
  font-weight: bold;
  font-style: italic;
  font-size: 14pt;
  text-decoration: underline;
  ```
  - Or we can combine all of this styling info into one declaration, by using the short-hand font property. This can be very convenient!
  - What's not so convenient is that the values for the font property have to be in a certain specific order or they won't work. This is a great example of why it's important to get comfortable looking things up in the documentation.
  - [Font Shorthand Gotchas](https://css-tricks.com/almanac/properties/f/font/)
  - what's a "gotcha"? In computer science, a gotcha is some feature of the code that is likely to trip you up and cause a mistake—in this case, the CSS language makes it easy to write a font declaration that seems like it should work, but that is really in the wrong order.
  ### 2.24- Practice — Meaning vs. style
  - Something you may have wondered is why we have both <strong></strong> and font-weight: bold;. If you want to bold some text, it seems like you could use either of these—and they would have the same results.
  - And the same seems to be true of <em></em> and font-style: italic;.
  - Why would we need CSS style properties like font-weight and font-style, when we already have HTML elements like em and strong?
  - There are a couple of reasons for this.
  - The historical reason is that HTML was created before CSS, but the engineers who designed CSS wanted it to provide more customization than HTML alone did. The default way to show emphasis is by styling it as italic. But we don't have to do it that way — we can use CSS to override the default styles. For example, we could say that we want emphasized text to be red, or in a larger font size.
  - But the differences go deeper than that. HTML code isn't only used by browsers that display on the screen. It's also used by search engines, smart speaker apps, and other programs. Those programs can't see "boldface" or "italics", but they still need to know which text on a page is more important.
  - The em and strong elements specify the meaning of their contents. In contrast, the CSS style properties are just specifying the visual appearance.
  - To repeat this in more general terms: the HTML indicates what the contents mean, while the CSS indicates how the contents should look. Web programmers refer to this as semantic markup — using markup to indicate meaning, not just appearance.
  - For example, if we place some text inside an em element, this is our way of indicating that this text should be emphasized in some way. But to a program that's reading the page aloud to the user, it won't use italics; it will use tone of voice. And even in a page that _is_ displayed to the user, you might want it to be emphasized using color or another property, instead of with italics.
  ### 2.25- Practice — Containers
  ```
  <style>
  .box{
    width: 100px;
    height: 100px;
    text-align: center;
    font-size: 30px;
    font-weight: bold;
    font-family: sans-serif;
    float: right;
  }
  </style>
  <div class="box red">red</div>
  <div class="box green">green</div>
  <div class="box yellow">yellow</div>
  ```
  - Each box gets floated individually, which causes them to line up in a horizontal row rather than staying in a vertical stack.
  - behavior changes if we first put the three boxes inside a container div.
  ```
  <style>
  .box{
    width: 100px;
    height: 100px;
    text-align: center;
    font-size: 30px;
    font-weight: bold;
    font-family: sans-serif;
  }
  .container{
      float: right;
  }
  </style>
      <div class="container">
        <div class="box red">red</div>
        <div class="box green">green</div>
        <div class="box yellow">yellow</div>
      </div>
  ```
  ### 2.26- flexbox
  - [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
  ### 2.27- Practice — Flexbox
  - When using flexbox, it's important to understand how the size of the container element affects the layout of the boxes that are inside of it.
  ### 2.28- Replicating a design
  ```
  /* CSS  */
  ul{
    display: flex;
    flex-wrap: wrap;
    width: 335px;
    padding: 5px;
  }

  li{
    width: 95px;
    height: 95px;
    list-style: none;
    text-align: center;
    background-color: #89c9ff;
    margin: 5px;
    font: bold 80px sans-serif;
    border: 1px solid #000
  }
  ```

  ```
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <title>Tic Tac Toes</title>
      <link rel="stylesheet" href="tictactoe.css">
  </head>
  <body>
      <ul>
          <li>X
          <li>
          <li>O

          <li>
          <li>X
          <li>O

          <li>X
          <li>O
          <li>
      </ul>
  </body>
  </html>
  ```

</details>


## Milestone 2 - Intro to Python
<details>
	<summary>Lesson 1: Turtles and Code</summary>

  ### 3.1- Starting out
  - **A program**: is a set of instructions for a computer. A program is made up of lines of code. Each line tells the computer a particular detail of those instructions.
  ### 3.2- Drawing with turtles 
  - turtles: A data object that knows how to draw lines on the screen.
  ```
  import turtle
  fred = turtle.Turtle()
  fred.color("red")
  fred.forward(100)
  fred.right(135)
  fred.forward(140)
  fred.right(135)
  fred.forward(100)
  ```
  ### 3.3- Variables
  - variable: A connection between a name in the code and some data in the computer’s memory.
  - assignment statement: fred = turtle.Turtle()
  - fred: gives the name of the variable
  - =: takes the thing on the right and assigns it to the name on the left
  - turtle.Turtle(): creates a new turtle data object in memory
  ### 3.4- Changing colors
  - colors in turtle code is a string.
  - Strings in Python code always appear in quotes. The string "123" is different from the number 123.
  - right(deg): When we want the turtle to turn right, we have to tell it how far to turn, and we use degrees of angle to do it.
  ### 3.5- Changing shapes
  - An integer: is a whole number with no fraction or decimal part. Integers can be positive, zero, or negative (like -5).
  - In Python, a list is written with square brackets around it, and commas separating the items.
  ### 3.6- Finding errors
  - python run code from top to the bottom.
  - The purpose of an error message is to tell you what might be wrong, and to point to the part of your code (usually, the line number) where the problem was detected.
  ### 3.7- Modules and methods
  - Python is a case-sensitive programming language: the case or capitalization of the letters matters.
  - A module: is a file with some useful code, which we can import into our program.
  - A method: is a named block of code that can be called to get the module to do something.
  - The import turtle statement: tells Python that you want to use the turtle module in your code.
  - amy.forward(100): We're calling the <code>forward</code> method on a <code>Turtle</code> object named <code>amy</code>, and giving it the input <code>100</code>.
  ### 3.8- Comments
  - a comment is a message for human readers. The computer ignores comments when running the code. In Python, a comment line begins with #.
  - Comments can help make your program a lot easier to understand. 
  - Comments can also be a handy tool for experimenting with your code. If you want to temporarily "turn off" some code so that it doesn't run.
  - <code>amy.penup()</code> : Deactivate the pen so that the turtle stops drawing when moving.
  - <code>amy.pendown()</code> : Activate the pen so that the turtle starts drawing when moving.
  It's probably surprising that <code>amy.speed(0)</code> is the fastest speed. A speed of 0 means that no animation takes place to show the turtle moving—instead, the turtle jumps instantly from one spot to the next.
  ### 3.9- Practice — Order matters
  - by default, Python will run each line of code in order, from top to bottom. That means that the order in which you put the lines of code in your program can make a big difference.
  ### 3.10- Using variables
  Being able to assign a value to a variable <code>favorite_color = "cyan" </code>
  ... and then use this variable to do stuff elsewhere in your code ...
  <code>
  mary.color(favorite_color)
  </code>... is an important skill to have as a programmer! So let's get some practice with the syntax.
  - <code>blah = "purple"</code>: is a bad name because it makes the program harder for human beings to understand.
  - you can assign all sorts of other things to variables too, like lists and integers.
  ### 3.11- Looping
  ```
  for side in [1, 2, 3, 4, 5]:
      amy.forward(100)
      amy.right(72)
  ```
  - In this loop, what matters is the number of things there are in the list. For now, it doesn't matter what those things are — it just matters how many of them are in the list.
  - <em>Indentation</em> is how we indicate that a line of code is <em>inside</em> the loop.
  - In Python, indentation is important!
  - we can use whatever word we want in place of side.
  ### 3.12- Lists and loops
  - In Python, a list of items is written with square brackets around it, and commas separating the items.
  ```
  for side in [1, 2, 3, 4]:
      george.forward(100)
      george.right(90)
  ```
  -  Lists and for loops work closely together. But in the above example, we're not actually using the numbers in the list — we're just using the fact that there are four of them.
  -  we can use the numbers in the list, in the code that's inside the for loop.
  ```
  import turtle

  lengths = [10, 20, 30, 40, 50, 60, 70, 80]

  dizzy = turtle.Turtle()
  dizzy.color("blue")
  dizzy.width(5)

  for length in lengths:
      dizzy.forward(length)
      dizzy.right(90)
  ```
  - The lengths variable refers to a section of the computer's memory that contains the list [10, 20, 30, 40, 50, 60, 70, 80, 90, 100].
  - Each time the loop runs, the <code>length</code> variable gets assigned a single item from the<code>lengths</code> list.
  - The key idea behind all of this is that a for loop has a special variable built into the first line of the loop. In these examples, the variable is called length.
  ### 3.13- Practice — Loop variables
  ```
  for length in [10, 20, 30, 40, 50, 60]:
      length = 100
      dizzy.forward(length)
      dizzy.right(90)
  ```
  - The first line of the loop will assign a new value to length each time the loop runs. But then, the second line (length = 100) will re-assign length to the value 100. Thus, dizzy moves forward by 100 pixels every time.
  ```
  for length in [10, 20, 30, 40, 50, 60]:
      dizzy.forward(length)
      length = 100
      dizzy.forward(length)
  ```
  - dizzy goes forward by a length of 10, and then again by a length of 100 (for a total of 110).
  ### 3.14- Mystery shape
  - angles can be used in the for loop with different values.
  ### 3.15- Loops within loops
  - Nested loops.
  ```
  import turtle
  anna = turtle.Turtle()
  for path in [1, 2, 3, 4]:
      for step in [1, 2, 3]:
          anna.forward(10)
  ```
  - The inner loop runs three times for each pass through the outer loop, and the outer loop runs four times.
  - The turtle goes forward 10 pixels each time <code>anna.forward(10)</code> is called, and this happens 12 times total, because 4 × 3 = 12. So it goes 120 pixels forward in total.
  ### 3.16- Practice — Turtle methods
  - <code>anna.width(10)</code> : Change how thick the line is.
  - <code>anna.speed(0)</code> : Draw as fast as possible.
  - <code>anna.penup()</code> : Stop drawing.
  - <code>anna.pendown()</code> : Start drawing.
  - [Turtle Documentation](https://docs.python.org/3/library/turtle.html)

  ### 3.17- Practice — More loop variables
  - Remember, the first line of a for loop comes with a special sort of variable. We say it's a "special" variable because of the fact that each time the loop runs, the variable gets assigned the next value from the list. You don't see any assignment statements, but that's how for loops work.
  ### 3.18- Thinking about errors
  - There are really three major kinds of errors that come up in programming: syntax errors, usage errors, and logic errors.
  - Syntax errors are like spelling errors. When you're learning a new language, you'll probably make a lot of them. But once you're used to the language, you'll make very few.
  - Usage errors, This is when you ask the computer to do something that doesn't make sense. Ex: <code>alison.forward("orange")</code>
  - logic errors: The program runs fine — it doesn't crash — but it doesn't do what you wanted it to do, because what you wrote isn't what you meant. These are what people mean when they say, "The computer doesn't do what you want it to; it only does what you tell it to do."
  - **Indentation**: 
  ```
  for a in [1, 2, 3]:
      # code here will run 3 times.
      for b in [4, 5, 6]:
          # code in here will run 9 times
      # but code here will run only 3 times!
  ```
  ### 3.19- Rainbow turtles
  ```
  import turtle
  mai = turtle.Turtle()
  rainbow = ["red", "orange", "yellow", "green", "blue", "purple"]


  # Write whatever code you want here!
  mai.width(5)
  mai.speed(0)

  for color in rainbow:
      mai.color(color)
      for inner in [1,2,3,4,5]:
          mai.forward(50)
          mai.right(144)
      mai.right(60)
      mai.penup()
      mai.forward(50)
      mai.pendown()
      mai.hideturtle()
  ```
  ### 3.20- Review
  - A method call asks an object, such as a turtle, to perform some action, such as moving forward. A method call can take additional inputs, such as the number 90 here.
  - Quotes are how we indicate a string value in Python.
  - NameError is a really common error message from Python, and it means that the code tried to use a variable before defining it. For instance, matthew.right(45) will give a NameError if you don't have a turtle named matthew yet.

</details>

<details>
	<summary>Lesson 2: functions, part One</summary>


</details>


















