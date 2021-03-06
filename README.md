# Udacity-Full-Stack Development Track
 
## Milestone 1 - HTML, CSS
<details>
  <summary>Intro to HTML </summary>

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
  - Whitespace includes spaces, tabs, and line breaks. When the browser displays an HTML file, it treats a run of whitespace as a single space character. In order to create a line break that will show up in the browser, use the <code> br </code> tag.
  ### 1.8- Paragraphs
  - we use Paragraphs to markup all of Paragraphs.
  - using paragraph tags instead line break to tell the browser about the structure of our text.
  ### 1.9- Lots of elements
  - <code>sub</code>  and <code>sup</code> stand for "subscript" and "superscript". Originally, HTML started out as a tool for scientific and academic work; and these are really useful for science and math, like writing x2+3x+4 = 1 or chemical formulas like H2O.
  ### 1.10- Nested elements
  - Element can be inside other element.
  - Html can't be Overlap like this:
  ```
  <em> Text <sup> Text </em> text </sup>
  ```
  ### 1.11- Block and inline
  - <code>p</code> is a block element, which means the browser creates a box around it. It also generates a margin around this box, to visually separate the paragraph from surrounding elements.
  - <code>br</code> is an inline element that just creates a line break. It doesn't have a box around it and doesn't create any margin.
  - [Block Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements#Elements).
  - [Inline Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements#Elements)
  ### 1.12- Practice — The div element
  - The <code>div</code> is short for division, because that's what this element is for—you can use it to divide up the page into different sections.
  - Like the paragraph <code>p</code> element, the division <code>div</code> element has an invisible box around it—and just like <code>p</code>, it can have a border, a margin, a width, a height, and so on.
  - But a <code>p</code> element is specifically meant to contain text. In contrast, the <code>div</code> element is a generic container for whatever other elements you might want to put inside. You can use the div element to organize the content and divide the page into sections.
  ### 1.13- Lists and implied close tags
  - The default display of an unordered list (ul) uses bullet points. The default display of an ordered list (ol) uses numbers.
  - <code>li</code> can be only occur inside <code>ol</code> or <code>ul</code> tags. so that li is an element for which the closing tag is optional.
  - when browser see <code>li</code> opening tag it knows that the previous <code>li</code> must be done, so the closing tag is optional.
  - But <code>ul</code> and <code>ol</code> tags must have closing tag.
  - if we leave off the closing <code>ol</code> or <code> ul </code>, then the browser will not know when our list ends! It will simply treat everything that comes after that point as part of the list
  - The <code>p</code> element is another example of an element for which the closing tag is optional.
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
  - Without the closing <code>p</code> tag, the browser will still close the element automatically—but not until it sees the next <code>p</code> element starting. So all of the text up until that point gets included in the contents of the blue p element.
  - With <code>li</code> and <code>p</code>, the browser can figure out where to close the element. But with an element like strong, there's no way for the browser to know where you want the emphasis to stop!
  - The <code>br</code> element is a void element— it doesn't have any contents (unlike <code>p</code>, which does have contents!).
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
  ### 1.18- Links and the <code>a</code> tag
  - The web is based on the idea of hypertext.
  - ```<a href="http://example.net/stuff.html">Example Page</a>```: anchor element
    - href="http://example.net": hypertext reference attribute
    - The Example Page: contents (what the user actually clicks on)
    - </ a >: closing anchor tag
  ### 1.19- Adding images
  - ```<img src="https://fakeurl.example.net/fish.png" alt="Fish">```:
    - <code>src</code> -> url of the image file(it doesn't copy the file it just tell the browser where   to find it)
    - <code>alt</code> -> description of the image, (displayed if the file is missing or the user's network connection stops before the image is loaded or if the user can't see the image for instance if they are blind).
    - empty element -> No closes tag.
  - To create an image that is a link, put an img element between the open and close tags of an <code>a</code> element.
  - for instance:
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
  - language for descriping the visual appearance of the web pages, including properites such as layout, colors and fonts.
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
  - <code>li</code> -> selector
  - <code>color: green;</code> -> declaration / rule 
  - <code>{color: green;margin:20px;}</code> -> declaration block
  - <code>color:</code> -> property
  - <code>green;</code> -> value
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
  - The <code>em</code> and <code>strong</code> elements specify the meaning of their contents. In contrast, the CSS style properties are just specifying the visual appearance.
  - To repeat this in more general terms: the HTML indicates what the contents mean, while the CSS indicates how the contents should look. Web programmers refer to this as semantic markup — using markup to indicate meaning, not just appearance.
  - For example, if we place some text inside an <code>em</code> element, this is our way of indicating that this text should be emphasized in some way. But to a program that's reading the page aloud to the user, it won't use italics; it will use tone of voice. And even in a page that _is_ displayed to the user, you might want it to be emphasized using color or another property, instead of with italics.
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
  - behavior changes if we first put the three boxes inside a container <code>div</code>.
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


## Milestone 2 - Python
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
  - assignment statement: <code>fred = turtle.Turtle()</code>
  - <code>fred</code>: gives the name of the variable
  - <code>=</code>: takes the thing on the right and assigns it to the name on the left
  - <code>turtle.Turtle()</code>: creates a new turtle data object in memory
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
  - <code>amy.forward(100)</code>: We're calling the <code>forward</code> method on a <code>Turtle</code> object named <code>amy</code>, and giving it the input <code>100</code>.
  ### 3.8- Comments
  - a comment is a message for human readers. The computer ignores comments when running the code. In Python, a comment line begins with <code>#</code>.
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
  <code>mary.color(favorite_color)</code>... is an important skill to have as a programmer!.
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
  - A method call asks an object, such as a turtle, to perform some action, such as moving forward. A method call can take additional inputs.
  - Quotes are how we indicate a string value in Python.
  - NameError is a really common error message from Python, and it means that the code tried to use a variable before defining it. For instance, <code>matthew.right(45)</code> will give a NameError if you don't have a turtle named matthew yet.

</details>

<details>
	<summary>Lesson 2: functions, part One</summary>
  
  ### 4.1- Statements
  - There are two kinds of Statements:
    - Simple Statements
    - compound Statements
  - Simple Statements:
    - <code>sides = 12</code>: Assignment Statement.
    - <code>import turtle</code>: import Statement.
    - <code>mary.color("purple")</code>: Method call Statement.
  - Compound Statements Controls:
    - **Whether** the code runs.
    - **When** the code runs.
    - **How many** times the code runs.
  - **Control Flow**: is the order in which statements are executed in a piece of code.
  - The default control flow is from the top to the bottom.
  - Compound Statements change the default control flow.
  ### 4.2- The range function
  - The best programmers write fewer lines of code rather than more.
  - The list <code>[0, 1, 2, 3, 4, 5, 6]</code> has seven items, so we'll write <code>range(7)</code> instead.
  ### 4.3- Crunching numbers (1/2)
  - Expression: Is a piece of code that resolves to some values.
  - <code>5 + 9 * 2</code> -> Expression.
  - <code>+, * </code> -> Operators.
  - <code>5, 9, 2</code> -> Operands.
  - Some Usage for Expressions:
  ```
    howard = turtle.Turtle()
    for side in [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]:
      howard.forward(side * 10)
      howard.right(90 - side)
  ```
  - Dividing 360 by <code>sides</code> will give the correct turning angle for any number of sides.
  ```
    sides = 5
    length = 100
    t = turtle.Turtle()
    t.color("orange")
    for side in range(sides):
        t.forward(length)
        t.right(360 / sides)
  ```
  ### 4.4- Crunching numbers (2/2)
  - To drow This shape:
  
  <p><img src="https://video.udacity-data.com/topher/2018/March/5ab5dd13_spirangle/spirangle.png"/></p>
  
  ```
  import turtle
  t = turtle.Turtle()
  t.color("cyan")

  for side in range(19):
      t.forward(side*10)
      t.right(120)
  ```
  ### 4.5- What's a function?
  - A function is a block of code that has a name, but that doesn't run until we tell it to.
  - We can tell a function to run by <em>calling</em> that function.
  - To <em>call</em> a function, use the name of the function, followed by parentheses.
  - **Callable code**: is the code that will only run when a call statement is used.
  -  A function call like <code>range(100)</code> do:
    - Runs the code in the function.
    - Passes <em>input</em> to the function.
    - Gets back some <em>output</em> from the function.
		
  - A **method** is a function that's associated with an object. It is a special kind of functions.
  - Every method is a function but not Every function is a method.
  - <code>edna.home()</code> is a call to the method named home on an object named <code>edna</code>.
  - <code>max(23, 17)</code> is a call to the function named <code>max</code>.
  - **Argument**: is a value that we can pass to a function when we call that function.
	
  ### 4.6- Defining functions

  ```

  def spiral():
      t = turtle.Turtle()
      t.color("cyan")
      for n in range(100):
          t.forward(n)
          t.right(20)

  spiral()

  ```
  ### 4.7- Parameters and arguments
  - When we define a function, we specify its parameters: <code>def spiral(sides, turn, color, width): </code>
  - When we call a function, we specify its arguments: <code>spiral(150, -30, "blue", 10) </code>
  - Parameters are just variables: Because the variable, is given as part of the function definition, we call it a parameter.
  - Arguments are just inputs: it's just some input that we pass to a function.
  - When we say that it "passes" this argument, all we mean is that it assigns this number to the corresponding parameter.
  - "passing an argument to a function" is really just another way that we can assign a value to a variable.
  <p> <img src="https://video.udacity-data.com/topher/2018/September/5ba5c286_arguments-to-parameters/arguments-to-parameters.png"/> </p>
  
  ### 4.8- Defining a <code>draw_square</code> function
  - function has to be defined before we can call it — otherwise, we'll get an error.
  - we only have to define the function one time in our program.
  ```
  import turtle
  jack = turtle.Turtle()
  jack.color("yellow")

  def draw_square():
    for side in range(4):
      jack.forward(100)
      jack.right(90)

  draw_square()

  for square in range(80):
    draw_square()
    jack.speed(0)
    jack.forward(5)
    jack.left(5)
  ```
  
  ### 4.9- Adding a parameter to <code>draw_square</code>
  - By putting a parameter in the function definition, we make it possible to pass that function some input when we call it.
  ```
  def draw_square(length):
    for side in range(4):
      jack.forward(length)
      jack.right(90)
  ```
  ### 4.10- Make your own function
  - Apply this pattern:
  <p> <img src="https://video.udacity-data.com/topher/2017/December/5a37d29c_screen-shot-2017-12-18-at-6.36.52-am/screen-shot-2017-12-18-at-6.36.52-am.png"/> </p>
  
  ```
  # Write a function here that creates a
  # turtle and draws a shape with it.
  def tringles(color, start):
    t = turtle.Turtle()
    t.color(color)
    t.width(3)
    t.speed(0)
    t.right(start)
    for n in range(6):
      for side in range(3):
        t.forward(100)
        t.right(120)
        t.hideturtle()
      t.right(15)

  # Call the function multiple times.

  tringles('orange', 0)
  tringles('red', 120)
  tringles('yellow', 240)
  ```
  ### 4.11- Variable scope
  - **scope**: the part of the code for which a variable is defined
  - **Local scope**: Defined inside a function. can only be used inside that function. It isn't defined outside.
  - **global variable**: Defined outside of a function. It is defined everywhere in the code.
  ### 4.12- Indent with care!
  - Some indentation mistakes will cause Python to give an error message. Others (like having a line outside of a loop when you meant for it to be inside of a loop) won't throw an error—instead, they'll simply cause the code to do something you didn't expect!
  
  ### 4.13- If this equals that
  - <code>==</code> ->To check for conditions:
  ```
  import turtle

  romeo = turtle.Turtle()
  juliet = turtle.Turtle()

  juliet.color("misty rose")
  juliet.width(3)

  romeo.color("violet")
  romeo.width(3)

  romeo_last_name = "montague"

  romeo.left(40)
  romeo.forward(100)
  for side in range(185):
      romeo.forward(1)
      romeo.left(1)
  romeo.hideturtle()

  if romeo_last_name == "montague":
      juliet.left(140)
      juliet.forward(100)
      for side in range(185):
          juliet.forward(1)
          juliet.right(1)
      juliet.hideturtle()
  ```
  ### 4.14- if / else
  - It's a variation on the if statement. The way it works is that the condition is checked, and if it's true, then the code under the if line will run; but if the condition is false, the code under the else line will run instead.
  
  ### 4.15- Modulo (1/3)
  - Modulo operator, %, divides one number by another—and then gives the remainder of that division.
  - [great video](https://www.khanacademy.org/math/arithmetic/arith-review-multiply-divide/arith-review-remainders/v/introduction-to-remainders).
  - [practice problems you can try out.](https://www.khanacademy.org/math/arithmetic/arith-review-multiply-divide/arith-review-remainders/e/division-with-remainders-1).
  - The most important concept here is not the math itself. The key idea is that **we need a way to create a repeating pattern**—and the modulo operator gives us a way to do that.
  -  If we have <code>a % b</code> and <code>b</code> is bigger, then the remainder will simply be <code>a</code>.
  - For example:
    - <code>7 % 10</code> gives the result <code>7</code>
    - <code>7 % 100</code> gives the result <code>7</code>
    - <code>7 % 1000</code> gives the result <code>7</code>
  - A common thing to do with the modulo operator is to use it with an **increasing sequence** of numbers. For example, we can do <code>1 % 5</code>, then <code>2 % 5</code>, then <code>3 % 5</code>, and so on.
  ### 4.16- Modulo (2/3)
  ```
  import turtle

  t = turtle.Turtle()
  t.width(3)
  t.color("yellow")
  t.penup()
  t.back(200)
  t.pendown()
  for n in range(10):
      t.forward(50)
      t.left(90)
      t.forward(50)
      t.right(90)

  t.hideturtle()
  ```
  - Make staircase pattern. But do it with only one use of the <code>forward</code> method in your code. 
  ```
  for n in range(10):
      t.forward(50)
      if n % 2 == 0:
          t.left(90)
      else:
          t.right(90)

  t.hideturtle()
  ```
</details>


<details>
	<summary>Lesson 3: functions, part Two</summary>
  
  ### 5.1- Returning a value
  ```
  def simple_function():
    return 10

  distance = simple_function() # is equivalent to: distance = 10
  ```
  - When we say that it "returns the number <code>10</code>" what we mean is this: This code works the same as if the function call, <code>simple_function()</code>, were replaced by the number <code>10</code>.
  - So a return statement takes a value and returns it back to the place from which the function was called.
  
  ### 5.2- Returning a value (3/3)
  - Function ca have more than one <code>return</code> statements.
  - Only the first <code>return</code> statement will run and the program will get out of the function.
  ```
  def simple_function():
    return 10 # will execute this line
    # These all will be dead code
    return 12
    return 14
    return 16
  ```
  - **Dead code**: Code that can be in a program but never do anything.
  - The only way to Use multiple <code>return</code> statements with <code>if</code>:
  ```
  def bead_color(num):
      if num % 3 == 0:
          return "red"
      if num % 3 == 1:
          return "green"
      if num % 3 == 2:
          return "blue"
  ```
  ### 5.3- Passing arguments in loops (1/3)
  - When we call a function from inside a loop, we can use the loop variable as input for that function. This allows us to call the same function repeatedly, but pass it a different input each time.
  ```
  for angle in [180, 135, 90, 45, 0]:
    star("red", 5, 50, angle, 100)
  ```
  - Each time through the loop, the <code>angle</code> variable will get a new number assigned to it (from the list), and we can then pass this to the <code>star</code> function when we call it.
  ### 5.4- Passing arguments in loops (3/3)
  - Drow this pattern:
  <p><img src="https://video.udacity-data.com/topher/2018/September/5baec871_passing-polygons/passing-polygons.png" /> </p>
  
  - The smallest polygon has 3 sides and the largest has 14!
  
  ```
  import turtle

  def polygon(sides, length):
    t = turtle.Turtle()
    t.color("lime")
    t.speed(0)
    angle = 360 / sides
    for side in range(sides):
      t.forward(length)
      t.right(angle)
    t.hideturtle()

  for side in [3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14]:
      polygon(side, 35)
  ```
  ### 5.5- Fizz Buzz, turtle style
  - The idea of the game is: 
    - If the number is evenly divisible by 3, you say "Fizz"
    - If the number is evenly divisible by 5, you say "Buzz"
    - If the number is evenly divisible by both 3 and 5, you say "FizzBuzz"
  - When we say "evenly divisible", we just mean that we can divide the one number by the other and not get any remainder.
  - This is one way we can check for a number that is divisible by both <code>3</code> and <code>5</code>:
  ```
  if x % 3 == 0:
    # Fizz
    if x % 5 == 0:
        # Buzz
  ```
  - First, we check if the number is divisible by <code>3</code>. If it's not, then the whole structure gets skipped over (none of the code inside gets run!). But if the number is divisible by <code>3</code>, then it will also check whether the number is divisible by <code>5</code>.
  ```
  import turtle

  def fizz(tur):
      # A red square bead.
      tur.color("red")
      tur.left(90)
      for side in [10, 20, 20, 20, 10]:
          tur.forward(side)
          tur.right(90)

  def buzz(tur):
      # A green hexagonal bead.
      # Fits inside the red bead.
      tur.color("green")
      tur.left(60)
      for side in range(6):
          tur.forward(10)
          tur.right(60)
      tur.right(60)

  def plain(tur):
      # A gray octagonal bead.
      tur.color("gray")
      tur.left(90)
      for side in [4, 8, 8, 8, 8, 8, 8, 8, 4]:
          tur.forward(side)
          tur.right(45)
      tur.right(45)

  # Set up the turtle to draw beads.
  t = turtle.Turtle()
  t.speed(0)
  t.width(2)
  t.penup()
  t.back(180)  # Back up to make room!
  t.pendown()

  for num in range(16):
      # Change this code:

      if num % 3 == 0:
          fizz(t)
          if num % 5 == 0:
              buzz(t)
      else:
          if num % 5 == 0:
              buzz(t)
          else:
              plain(t)
      # Advance to the next bead spot.
      t.color("gray")
      t.forward(22)
  t.hideturtle()
  ```
  ### 5.6- The random module
  - **Deterministic program**: a program that always produces the same output for a given input.
  - When we want to change this Deterministic behavior, we use random module.
    - <code>random.choice([items])</code> -> To use the function, we simply call it and pass it a list. The function then returns a random item from the list.
    
    ```
    cards = ["ace", 2, 3, 4, 5, 6, 7, 8, 9, "jack", "queen", "king"]
    my_card = random.choice(cards)
    ```
    
    - <code>random.randint(lower, upper)</code> -> randint stands for "random integer", because that's exactly what it does—it returns a random integer.
    
    ```
    die_roll = random.randint(1, 6)
    ```
  - To make random shape:
  
  ```
  import turtle
  import random


  colors = ["red", "orange", "yellow", "green", "blue", "purple"]

  t = turtle.Turtle()
  t.width(20)

  for step in range(100):
      # Change this to use a random number.
      angle = random.randint(-90,90)

      # Change this to use a random color.
      color = random.choice(colors)

      t.color(color)
      t.right(angle)
      t.forward(10)
  ```
  
  ### 5.7- Comparison operators
  - Python has several other comparison operators:
  
  | Operation           | What it means   |
  | ------|:-----:|
  | <code>a == b</code> | Is <code>a</code> equal to <code>b</code>?  |
  | <code>a < b</code> | Is <code>a</code> less than <code>b</code>? |
  | <code>a > b</code> | Is <code>a</code> greater than <code>b</code>? |
  | <code>a <= b</code> | Is <code>a</code> less than or equal <code>b</code>? |
  | <code>a > b</code> | Is <code>a</code> greater than or equal <code>b</code>? |
  | <code>a != b</code> | Is <code>a</code> not equal to <code>b</code>?  |
  
  ### 5.8- if and elif
  
  ```
  mood = "happy"
  if mood == "happy":
      riley.color("yellow")
  if mood == "sad":
      riley.color("blue")
  else:
      riley.color("gray")
  ```
  - This code makes color gray, instead yellow, because it treats the second <code>if</code> statement as a separate statement, that its result overrides the first <code>if</code> statement result.
  - To fix that we can use nesting:
  ```
  if mood == "happy":
      riley.color("yellow")
  else:
      if mood == "sad":
          riley.color("blue")
      else:
          riley.color("gray")
  ```
  - Sometimes nesting is very useful, or even necessary, but ... it kind of makes my brain hurt! And in this case, it's avoidable if we use <code>elif</code>
  - We can also fix that with <code>elif</code>, wich makes all <code>if</code> statements one compound:
  ```
  if mood == "happy":
    riley.color("yellow")
  elif mood == "sad":
      riley.color("blue")
  else:
      riley.color("gray")
  # The result will be yellow
  ```
  - we can use random module To pick a random mood:
  ```
  import turtle
  import random

  riley = turtle.Turtle()
  riley.width(5)

  # Add your code here.
  moods = ["happy", "sad", "bored", "depressed"]
  mood = random.choice(moods)
  if mood == "happy":
      riley.color("yellow")
  elif mood == "sad":
      riley.color("red")
  elif mood == "bored":
      riley.color('orange')
  elif mood == "depressed":
      riley.color('black')
  else:
      riley.color("gray")

  for side in range(5):
      riley.forward(100)
      riley.right(144)
  ```
  
  ### 5.9- Staying in bounds
  - <code>t.xcor()</code> -> returns the x coordinate of turtle object.
  - <code>t.ycor()</code> -> returns the y coordinate of turtle object.
  - If the turtle's canvas is 400 by 400 pixels in size:
    - If the turtle is off to the left, their x-coordinate will be less than -200 (for example, -201).
    - If the turtle is off to the right, their x-coordinate will be more than 200 (for example, 201).
  ```
  for step in range(2000):
      t.forward(1)
      # Add your code here
      if t.xcor() > 190 or t.xcor() < -190:
          t.left(180)
          t.forward(1)
  ```


</details>


## Milestone 2 - More Python

<details>
  <summary>Lesson 1: Strings & Lists</summary>

### 6.1- Variables vs. literals
- Interactive mode, also known as the REPL provides us with a quick way of running blocks or a single line of Python code. The code executes via the Python shell, which comes with Python installation. Interactive mode is handy when you just want to execute basic Python commands or you are new to Python programming and just want to get your hands dirty with this beautiful language.
- To access the Python shell, open the terminal of your operating system and then type "python". Press the enter key and the Python shell will appear. This is the same Python executable you use to execute scripts, which comes installed by default on Mac and Unix-based operating systems.
-	variable names (identifiers) -> can assign to all sorts of different data in the computer's memory using assignment `distance = sortOfData`.
- literals: represents the same fixed value every time like `10`, `"yummy"`.

### 6.2- Length
- `>>> len(variable or literal)` -> Returns the length of the variable or the literal.
- There is a Python module called `unicodedata` that lets you look up characters by name, including emoji:

```
>>> import unicodedata
>>> unicodedata.lookup("snake")
'🐍'
>>> unicodedata.lookup("cat")
'🐈'
```
- Emoji are usually wider on screen than letters or numbers; in a monospaced font they usually take up the space of two characters. They also take up more computer memory. But the length of a Python string depends only on the number of characters in it, not on what kind of characters they are:
```
>>> len("🐍")
1
>>> len("🐍🐍🐍")
3
>>> len("蛇 = 🐍")
5
```

### 6.3- Indexing
- We've seen that lists and strings have some things in common. Strings and lists both:
	-	Have a length.
	-	Are sequences.
	-	Can be looped over.
- The underlying idea of indexing is simple: It's just a way to give a number to each item in a sequence, so that you can tell Python which item you're referring to.
- Note that indexes start at `0`, not `1`. So the first item in a sequence would have an index of `0`, while the second would have an index of `1`, the third an index of `2`, and so on.
- You can also use negative numbers as indexes. If `word` is a string, then `word[-1]` is the last character of that string, and `word[-2]` is the second-last, and so forth.
- `word = "Fish"` -> The letter "s" is both `word[2]` counting from the left, and `word[-2]` counting from the right, if word is the string "Fish".

### 6.4- IndexError
- Assume that you just started Python and no new variables have been defined
	- `2 + "bears"` -> TypeError
	- `print(donkey)` -> NameError
	- `import explosion` -> ModuleNotFoundError
-	A string with no characters in it is an empty string: `word = ""`.
-	The IndexError message happens when you're trying to use an index to access a particular item, but there is no item with that index.
```
no_words = ""
print(no_words[0])
```
- You can avoid IndexError by writing loops that don't go past the end of the string. There are multiple ways to accomplish this:
`for char in word:` Or `for n in range(len(word)):`.

### 6.5- Slicing (1/2)
- `>>> "python"[0:2]` -> 'py'
- `>>> "python"[1:5]` -> 'ytho'
- `>>> "python"[0:5]` -> 'pytho'
- `>>> "python"[0:6]` -> 'python'
- `>>> "python"[:]` -> 'python'
- Now we have a string stored in the `word` variable, and we have the `length` of that string stored in the length variable. In this case, the length is `10`.

```
>>> word = "definitely"
>>> length = len(word)
```
- `>>> word[:length]` -> 'definitely'

- `>>> word[:length - 2]` ->  'definite'

- `>>> word[length - 8:]` -> 'finitely'

- `>>> word[length - 8:length - 2]` ->  'finite'

### 6.6- Concatenation (1/2)
- The `+` operator will perform arithmetic addition on two numbers, merge two lists, or concatenate two strings.
- `>>> 1 + 1` -> 2
- `>>> '1'+ ' ' + '1'` ->'1 1'
- `>>> '1' + 1 ` -> TypeError
-  A function called `adverbly` that takes a string as input and returns that string with "ly" appended to it:
```
def adverbly(str):
    return str + 'ly'
print(adverbly("quick")) #Prints quickly
```
### 6.7- Strings to numbers to strings

```
>>> n = input("Please enter a number: ")
Please enter a number: 2
>>> n * 2
```
- The result is `'22'`

```
>>> n = input("Please enter a number: ")
Please enter a number: 2
>>> int(n) + 2
```
- The result is `4`.

- In this next exercise, your goal is to write a program that asks the user for three numbers, adds those numbers up, and then prints a message saying what the sum is. Like this:

```
Enter a number: 2
Enter another number: 1
Enter a third number: 3
2 + 1 + 3 = 6
```
- Solution:
```
n1 = input("Enter a number: ")
n2 = input("Enter another number: ")
n3 = input("Enter a third  number: ")

result = int(n1) + int(n2) + int(n3)

f"{n1} + {n2} + {n3} = {result}"
```

### 6.8- Methods on strings
- `startswith` method is  simply a function that checking if one string starts with another. It is associated with a specific object.
- String predicates -> which means that they return `True` or `False` to indicate something about the string.
- [ list of string methods](https://docs.python.org/3/library/stdtypes.html#string-methods)

### 6.9- Boolean values
- `and` operation:
	- `>>> True and True` -> `True`
	- `>>> True and False` -> `False`
	- `>>> False and False` -> `False`

- `or` Operation:
	- `>>> True or True` -> `True`

	- `>>> True or False` -> `True`

	- `>>> False or False` -> `False`
- The function should return <code>True</code> if the string is between <code>8</code> and <code>64</code> characters long, and <code>False</code> otherwise.
```
def good_length(s):
    return len(s) > 8 and len(s) < 64
```
- There is a third boolean operation called `not`:
	- not x is true if x is false.
	- not x is false if x is true.
- An interesting consequence of these rules is that `not (x and y)` is the same as `(not x) or (not y)`. Similarly, `not (x or y)` is the same as `(not x) and (not y)`.

### 6.10- Operations on lists
-	Strings and lists have something important in common: They are both sequence types. That is, they're both data types that represent a sequence of values, not just a single value.
-	With a string, the values are the individual characters; with a list, they can be just about anything. But in both cases, there's a set of items, and the items have index numbers to identify the sequence in which they're ordered.
-	First, define the following list: `>>> my_list = ["a", "b", "c", "d"]`
	- `>>> my_list[1]` -> 'b'

	- `>>> my_list[0:2]` ->  ['a', 'b']

	- `>>> len(my_list)` -> 4 

	- `>>> my_list[3] == "d"` -> True

- Write a function total_length that takes a list of strings and returns the sum of the lengths of all the strings in that list:
```
def total_length(list_of_strings):
    total = 0
    for string in list_of_strings:
        total += len(string)
    return total
```

### 6.11- Methods on lists
- create a list in your Python interpreter: `>>> words = ["echidna", "dingo", "crocodile", "bunyip"]`.
- `words.append("platypus")`-> Add one item to the end of a list.
- `words.extend("abc")`-> Add possibly several items to the end of a list.
- `words.sort()`-> Change a list so it is in alphabetical (and numerical) order.
- `words.reverse()`-> Change a list so it is in the opposite order from how it was before.
- These methods all works on a list , Modify it, but don't returns any value.
- `append()` -> Adds its argument as a single item to the end of the list. It only ever adds one item to a list.
- `extend()` -> Treats its argument as a sequence and adds each item in the sequence to the end of the list. In other words, it adds a sequence of items to a list.
- `extend()` similar to `append()` with for loop:
```
>>> first_list = [1, 2, 3]
>>> second_list = [4, 5, 6]
>>> for item in second_list:
...     first_list.append(item)
... 
>>> first_list
```

### 6.12- Mutable vs. immutable
- lists are **mutable**. That means you can change the items in a list after it has been created.
- In addition to adding new items with methods like `append` and `extend`, you can also replace current items with new ones. You do this using the index operator `[]`.
- So lists are **mutable** (they can be changed), but strings are **immutable** (they cannot be changed).

```
>>> breakfast = 'waffles'
>>> new_breakfast = breakfast + ' and strawberries'
>>> new_breakfast
'waffles and strawberries'
```
- It may seem like we're modifying a string here, but what's actually happening in the computer's memory is that we are creating a new string. The old string is still exactly where it was, and hasn't been changed:
```
>>> breakfast
'waffles'
```

- Try this example with lists:
```
>>> first_list = [1, 2, 3]
>>> second_list = first_list
>>> second_list
>>> 
```
- You just saw that when you changed the items in `first_list`, this also affected `second_list`.
- Because <code>first_list</code> and <code>second_list</code> don't actually refer to two separate lists. It's the same <em>one</em> list, with two different names.

### 6.13- Augmented assignments
- The effect of `n = n + 1` and `n += 1` is the same. The latter is called an **augmented assignment** statement, because it's an assignment statement but it augments the existing value rather than replacing it.

- What do you think the new value of dog will be?
```
>>> dog = "woof"
>>> dog *= 2
```
- Solution is: 'woofwoof'.

### 6.14- while loops (1/5)
- A `while` loop will run while some condition is True. As soon as the condition is False, the loop will stop.

```
>>> password = ''
>>> while password != 'fizzbuzz':
...     password = input('Please enter the password: ')
```

- To make Count Down:
```
import time

n = 10
while n > 0:
    print(n)
    n -= 1
    time.sleep(1)
print("Blastoff!")
```

### 6.15- Infinite loops and breaking out
- It's possible to write code that gets stuck in an **infinite loop**! This happens when the condition you set up can only ever be True.

```
while 2 == 2:
    # Do something forever and ever without stopping
```
- If this happens while you're experimenting in the interpreter, you may have to stop the program. You can do this by pressing Ctrl + C (or in the absolute worst case, you can quit and re-open your terminal).

- There's another way to exit from an infinite loop. Inside a while or for loop, you can use the `break` statement to immediately exit the loop.
```
def no_repeating():
    words = []
    while True:
        word = input("Tell me a word: ")
        if word in words:
            print("You told me that word already!")
            break
        words.append(word)
    return words
```
- A `break` statement will always skip to the end of the innermost while or for loop. If you have a loop inside another loop, it will only exit the inside loop.

### 6.16- Finding substrings (1/4)
- When we search a string for substrings, we'll use index numbers to describe where the substring is found. For instance, if we search for 'ook' in 'cookbook', we'll say that it's found at positions 1 and 5. This means that if we take a slice of length 3 starting from one of these positions, we'll see that substring:
```
>>> location = 5
>>> size = 3
>>> word[location : location+size]
ook
```

### 6.17- Finding substrings (2/4)
- Our first goal will be to write a function, is_substring, that simply checks whether one string is a substring of another. If the first string is a substring of the other, it should return True; otherwise, it should return False.
```
def is_substring(substring, string):
    index = 0
    while index < len(string):
        if string[index : index + len(substring)] == substring:
            return True
        index += 1
    return False
```

### 6.18- Finding substrings (3/4)
- Change `count_character` to `count_substring`:
```
def count_character(string, target):
    index = 0
    total = 0
    while index < len(string):
        if string[index] == target:
            total += 1
        index += 1
    return total
```

```
def count_substring(string, target):
    total = 0
    index = 0
    while index < len(string):
        if string[index : index + len(target)] == target:
            total += 1
        index += 1 
    return total
		
# Here's a call you can test it with. This should print 4:
print(count_substring('love, love, love, all you need is love', 'love'))
```
- Overlapping matches: With the solution above, the function counts **overlapping matches**:

```
>>> count_substring('AAAA', 'AA')
```

There's one sense in which the answer is `2`, and another sense in which it's `3`. It depends on whether matches are allowed to overlap!

- We can solve the problem by making some modifications inside the function's while loop:

```
if string[index : index + len(target)] == target:
    total += 1
    index += len(target)
else:
    index += 1
```
- So here's the new version of the function:

```
def count_substring(string, target):
    total = 0
    index = 0
    while index < len(string):
        if string[index : index + len(target)] == target:
            total += 1
            index += len(target)   # <- This is the key line
        else:
            index += 1
    return total
```

The new code is saying that if we count a substring, we'll advance the index position forward by len(target) so that we skip over the rest of the characters in the substring.

### 6.19- Finding substrings (4/4)
- Here's one way to write the `locate_first` function. We've only had to change a few things from the `count_substring` function: instead of returning a total, we return the index on a successful match, or the value `-1` on no match:

```
def locate_first(string, sub): 
    index = 0
    while index < len(string):
        if string[index : index + len(sub)] == sub:
            return index
        else:
            index += 1
    return -1
```
- let's take it one step further and see if we can make a function that locates all instance of a substring:

```
def locate_all(string, sub):
    matches = []
    index = 0
    while index < len(string):
        if string[index : index + len(sub)] == sub:
            matches.append(index)
            index += len(sub)
        else:
            index += 1
    return matches
		
>>> locate_all('cookbook', 'ook')
[1, 5]
>>> locate_all('yesyesyes', 'yes')
[0, 3, 6]
>>> locate_all('the upside down', 'barb')
[]
```

### 6.20- More methods on strings
- Assume that we've got the entire text of the novel A Tale of Two Cities in a string variable called tale:
- How many times does the word "chocolate" occur in the novel? -> `tale.count("chocolate")`.
-	Yes or no: Does the word "chocolate" occur in the novel? -> `"chocolate" in tale`.
-	How far into the novel is the first occurrence of the word "chocolate"? -> `tale.find("chocolate")`.

### 6.21- Joining
- `"joiner".join("str")` -> sepatates the str with the joiner.
- Write a function breakify that takes a list of strings, and returns a single string with <br> inserted between each two strings in the list:
```
def breakify(strings):
    return "<br>".join(strings)
```

### 6.22- Silly sentences
- Make silly Random sentense choosen from `words` module :"D :

```
nouns = ['apple', 'ball', 'cat', 'dog', 'elephant',
         'fish', 'goat', 'house', 'iceberg', 'jackal',
         'king', 'llama', 'monkey', 'nurse', 'octopus',
         'pie', 'queen', 'robot', 'snake', 'tofu',
         'unicorn', 'vampire', 'wumpus', 'x-ray', 'yak',
         'zebra']

verbs = ['ate', 'bit', 'caught', 'dropped', 'explained',
         'fed', 'grabbed', 'hacked', 'inked', 'jumped',
         'knitted', 'loved', 'made', 'nosed', 'oiled',
         'puffed', 'quit', 'rushed', 'stung', 'trapped',
         'uplifted', 'valued', 'wanted']

templates = [
        'Waiter! I found a {{noun}} in my {{noun}}!',
        'The {{noun}} {{verb}} the {{noun}}.',
        'If you {{verb}} the {{noun}}, '
        'the {{noun}} will get you.',
        "Let's go: the {{noun}} is {{verb}}.",
        'Colorless green {{noun}}s {{verb}} furiously.'
]
```

- Generate Sentense:

```
import random
import words


def silly_string(nouns, verbs, templates):
    # Choose a random template.
    template = random.choice(templates)

    # We'll append strings into this list for output.
    output = []

    # Keep track of where in the template string we are.
    index = 0

    while index < len(template):
        if template[index:index+8] == '{{noun}}':
            # Add a random noun to the output.
            output.append(random.choice(nouns))
            index += 8
        elif template[index:index+8] == '{{verb}}':
            # Add a random verb to the output.
            output.append(random.choice(verbs))
            index += 8
        else:
            # Copy a character to the output.
            output.append(template[index])
            index += 1

    # Join the output into a single string.
    output = ''.join(output)

    return output


if __name__ == '__main__':
    print(silly_string(words.nouns, words.verbs,
        words.templates))
```


</details>















