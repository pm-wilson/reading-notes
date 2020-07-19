# reading-notes

- [x] Chapter Read and Notes Taken

---

## Read 1 - Due 7/7/20 AM

- [x] HTML CH1 Structure:
      HTML describes structure. An HTML element is made up of the opening and closing tags. <br>
      They can have attributes that tell us more about the element in the opening tag (not all tags will have closing tags). Tags usually have a name and value. <br>
      The body element holds everything that is seen on the page. The head element holds information about the page, like the title.<br>
      HTML pages are text documents.
- [x] HTML CH8 Extra Markup:
      Every HTML page should start with a !DOCTYPE html tag to show what version of HTML is being used. <br>
      Comments can be added to leave a note to future developers, or to comment out code you do not want to run.<br>
      All HTML elements can have an id or class attribute. Ids typically work well when using JavaScript and Classes work well with css. The more unique the style, the easier it is to manipulate that particular element. <br>
      Block elements will always start on a new line (like a div) and inline elements will continue on if there is room (like a span). <br>
      An iframe will be a window with another page inside it. Attributes iframes use is src to source the page, height and width, scrolling, frameborder and seamless to turn off scroll bars.<br>
      The meta element goes in the head section and contains addtional information about the site. description, keywords, robots author, pragma, expires.<br>
      Escape characters can be used to show symbols HTML reserves. If a particular symbol isn't showing up, you might need a new font for the symbol.
- [x] HTML CH17 HTML 5 Layout:
      HTML 5 has more sematic tags like article, header, aside to help show what elements are for. Older browsers might need to be told which elements are block level. Extra javascript free from Google might be needed to make newer elements backwards compatable with IE8.
- [x] HTML CH18 Process and Design:
      When designing a website it is a good idea to ask yourself who the site is for. This helps you design a site that will be good for the most important part of your audience. Ask yourself why they are visiting the page, so you can keep the most important information easy to find. Asking what your visitors are trying to achieve will help you keep the most important tasks easy to access. Asking yourself how often people will access your site will help you decide how often to update the site. <br>
      It is useful to create a site map to organize all the infomration on a site. In the home page, you might have other groups of pages like about, articles, visit, shop, contac and each of these might lead to a few other pages that fit that category.<br>
      When organizing how the page will look it is good to sketch a wireframe with areas set aside showing what information they will have.<br>
      Using visual hierarchy like size, color, style or contrast like images can be used to attract attention. Grouping items with proximity, distance, continuance, color, borders and separated by white space can let a user know they are related.
- [x] JS CH1 The ABCs of Programming:
      A script is a series of instructions for the comupter. To write a script define a goal, design the script and code each step. Designing a script with a flowchart can help you decide what goes where. Scripts are made of Objects, Events and Methods. <br>
      Web Browsers are programs built using Objects. The window object is the tab or window in the browser, the document object is the current document that is being viewed. <br>
      HTML makes up the content, CSS handles the presentation, and Javascript manages the functionality of web pages. It is best to keep the JavaScript code in its own file.

---

## Read 2 - Due 7/8/20 AM

- [x] HTML CH2 Text:
      Html is made up of tags, otherwise known as markup. Structural markup is using the elements do describe headings and paragraphs. Semantic markup provides extra infomration such as where to place emphasis in a sentence and that something is a quote (and who said it).<br>
      HTML has 6 levels of headings, with 1 the largest, and 6 the smallest. paragraphs by default will be shown on the next line.<br>
      Text can either be bold with b or itallic with i tags. Sup and sub make super or subscript. <br>
      Browsers will show only one blank space for multiple spaces or a line break. The line break br tag adds a line brake and the hr tag adds 2 line breaks witha horizontal line between. <br>
      Semantic markup uses strong to indicate bold and em for itallic. Blockquote is used for multi line quotes and q is used for shorter quotes. Abbr can be used for abbreviations or acronynms. Cite can be used to show where a citation is from and dfn is for a definition. Address should be used for contact info for the author of the page. Ins can be used to underine to show content added and del can be used for strikethrough to show content removed from a site. S shows something no longer relevant, but also not deleted.
- [x] HTML CH10 CSS Intro:
      Every element is in a box. Css associates rules with html elements. A selector tells CSS what to select and the property tells it what to change about that element, and the value tells it by how much to change it.<br>
      Css can link externally with href, type, rel and src. Css can also link internally with style.<br>
      Css rules cascade and the latest, most accurate style will overwrite previous styles.
- [x] JS CH2 Basic JavaScript Instructions:
      Statements are instructions and should start on a new line. Comments can be added to keep track of what the code is doing, or removing code from the script. Variables hold on to information as long as they are in scope. Simple data types are stings, numbers and boolean. <br>
      Variable names must start with a dollar sign underscore or letter, dash and period is not allowed, special javascript key words are not allowed and the variable should be named carefully so later developers will be able to tell it apart from other variables. Variables should be written in camelCase.<br>
      Variables can also be an array notated within brackets and separated with commas [1,2,3]. Values can be accessed by the index, starting with 0.
- [x] JS CH4 Decisions and Loops (to switch):
      Decisions can be made based with these statements: if else if..else. Comparisons can be made with a bang, triple equals, less or greater than. Logic can be applied with and, or, bang.<br>
      All data types break down into truthy or falsey values. Falsey values include 0, empty strings, NaN, not assigned, empty values, false. Truthy values are strings with characters, other numbers besides 0, true.<br>

---

## Read 3 - Due 7/9/20 AM

- [x] HTML CH3 Lists:<br>
      Lists can be numbered with ol, bulleted with ul, or definitions with dl. Definitions can be terms with dt or definitions with dd. I was surprised to find that lists can be nested in list items to indent further.
- [x] HTML CH13 Boxes:<br>
      Box sizes can be controled with width and height, and prepended with max- or min- can make them dynamic until the set size. Sizes can be set with em, px or %. Overflow hidden can cut off content beyond box boundaries, and scroll will add scroll bars.<br>
      The box model consists of the element with padding, border, and margins around it. Padding is the popcorn within the box giving white space between content and the border, the border is like the box that wraps the content and the margin is the space between it and the next box. Margins overlap, so only the largest margin will show.<br>
      Borders can be styled a few different ways including with a picture. Box shadow can give them a 3D look.<br>
      Boxes can be hidden 2 ways, display: none will remove it from the page flow, and visibility: hidden will hold its place. Either way the user can see the content in the page code.
- [x] JS CH4 Decisions and Loops (after switch):<br>
      Functions are groups of related tasks that can take parameters. Objects represent some thing. Functions on objects are Methods and variables on objects are Properties. Objects get some default Methods and Properties. Arrays of objects can create complex data sets.

---

## Read 4 - Due 7/10/20 AM

- [x] HTML CH4 Links:<br>
      Links allow you to move to another target page (or specific place within), file or email. A link target is href and the text is between the a tags. If linking on the same site you do not need to include the domain.<br>
      On larger sites code can be organized into separate folders called Directories.
- [x] HTML CH15 Layout:<br>
      Block elements start on a new line. Inline elements stay on the same line.<br>
      Parent elements are elements with another element within it, that element is a child.<br>
      In normal flow they stack below and next to the preceding element (sibling). Relative positioning moves it relative to where it would be in normal flow. Absolute moves it within its containing element. Fixed fixes the element on the screen and ignores scrolling. Floating elements can float within their parent and the other elements will flow around it. If boxes overlap by using different positioning, z-index can change the way they overlap.<br>
      Different users will have different screen sizes. Fixed width layouts will make the design static to control the layout, but might not look the best with users of large or small screens. Liquid layouts are more dynamic, but might not look good if a user is using a screen size not accounted for in design.<br>
      The top 570px or so is considered above the fold and it is good to engage the user to scroll with the information there. Designers like to keep pages about 1000px wide.<br>
      Grid makes for an easy overall layout of a page to give elements their own area.<br>
      Multiple style sheets can be used to break down the styles in a more organized way.
- [x] JS CH3 Functions, Methods, Objects:<br>
      Functions group instructions for a series of tasks. Before being called, functions must be declared. Parameters can be passed to a function from the previous scope and return can send infomration back to that original scope. Functions can only return a single value, but that value can be an array or object with multiple values within.<br>
      Methods are functions that live on an Object.<br>
      Arrays and Objects are used to store complex data. Arrays can be made up of objects, and objects can use arrays as values. <br>
      The Browser Object starts with the window and contains information on the browser. Within that is the Document Object which contains the document the current window or tab is referencing. Global variables are in the scope of anything at this level.<br>
      Data can also be strings and numbers and each have their own Methods. Custom Methods can also be built for objects.<br>
- [x] JS Article _6 Reasons for Pair Programming_
      Pair programming allows two people to team up to code. The driver types the code and navigates all the files and the navigator scans for typos, thinks about the big picture and looks up solutions.<br>
      Research indicates that writing the code takes slightly longer than two people working separately, but it produces a higher quality of code. This can make the code more efficient in the long run. Solutions are found faster and technical skills, communication and enjoyability were all increased when tested. It makes it easier for the two coders to stay on track, learn new solutions.

---

## Read 5 - Due 7/13/20 AM

- [x] HTML CH5 Images:
      As the site grows, organize images into folders. <br>
      User src to tell the browser the image source, use alt for an alternate text description if it is not able to be seen, use a title to give additional information that can be shown in a tooltip. Use height and width to specify the size (but usually done in css). Img is an inline element.<br>
      It is best to format your images to the correct size before using them on the site. JPEG format works best for images with many colors, GIF or PNG formats work best when there are few color variations. SVG format is scalable, but their use is not widespread yet. Animated Gifs are good for simple animations. Transparent GIFs are better for straight edges 100% transparent, PNGs work better for diagonal or partially transparent images.Figcaption can be used to give the image a caption.
- [x] HTML CH11 Color:
      You can change for foreground and background colors of elements. Be sure to use colors that have enough contrast to easily see.<br>
      Colors can be specified by RGB, Hex, names, HSL. RGBA and HSLA can be used for opacity.
- [x] HTML CH12 Text:
      Text can change the type face using refular, bold, italic or size.<br>
      Serifs are the decorations at the ends of the letters, and sans-serif is without them. Monospace is also used for letters that all take up the same space. Browsers can only display a given typeface when installed on that computer. It is possible to get around this, but fonts are subject to copyright and uploading fonts to a user might slow the site. <br>
      Typical font size is usually about 16px. EMS can be used to set the given font to a percentage of the default font size.<br>
      Font-weight can be used to set bold and font-style can be used for italic(based on calligraphy) or oblique(angled). Text-transform can be used for upperase, lowercase and capitalize. Text decoration can be used to underline, overline line-through or blink. Line-height can be used to change the height of the line the letters are on. Letter/word-spacing changes the distance between letters and words. text-align aligns the text to the left, right, center or justify. Vertical-align aligns vertically. Text-indent indents the first line of text in the element. Text-shadow gives each letter a shadow.<br>
      First-letter/line can specify a style for the first letter or line with a style. Links can be styled with :link(not yet clicked) and :visited(already clicked). Styles can be set to :hover for when the mouse is over the element, :active for when the element i being activated, or :focus for while the element is in focus.
      Text can also change more generally with color, spacing.

## Read 6 - Due 7/15/20 AM

- [x] JS CH3 Object Literals (pp100-105):
      Objects represent real world things modeled by a set of variables and functions. Objects are made of key: value pairs. Objects can be created literally defined into a varaible, and they can be made with a constructor defined by declaring a function. The New keyword will instruct the function to create a new object based on the outcome of the function. Properties can be added, removed and accessed with dot notation if the path is static, or bracket notation if it will be dynamically determined. This can be used to reference the object that the function is created inside.<br>
- [x] JS CH5 Document Object Model (pp183-242):
      The DOM tells the browser how it should model the HTML and how the JavaScript can access and update the web page. It is not part of HTML or JavaScript.<br>
      The DOM is the model the browser builds based off the HTML and JS. The 4 types of node types are the document, element, attribute, and text nodes.<br>
      The Document Node corresponds to the document object and is the entire page. The Element nodes are the elements described in the html. The Attribute nodes are the attributes assigned to the opening html tags. The text nodes are the text within elements, and can not have any nodes within them.<br>
      The DOM tree can be accessed by getting the node you want to work with and using its text, child elements, and attributes.<br>
      DOM queries are methods that find DOM elements (like getElementById, querySelector, GetElementsByClassName, getElementsByTagName, QuerySelectorAll). If the selector returns multiple nodes, they will be in an array. Looping through these arrays can be a good way to apply code to each node.<br>
      Traversing the DOM can be done with Parent Node to get the parent, previous/nextSibling to get the corresponding sibling, first/lastChild to get the corresponding child in the element. Some browsers treat the whitespace in the html as text nodes so might cause unforseen issues unless all the whitespace is removed.<br>
      Text content can be accessed from the parent node. textContent is the best way to change text, innerText should generally be avoided, and innerHTML can add other nodes but has security risks. Users can potentially add scripts if their data is added with innerHTML. To protect against this validate data going to server and double check on the server side. Escape all potentially dangerous characters like amp, greater than, less than, quote, etc. Limit where user content goes.<br>
      Nodes can be created with createElement() and appended to another node with append(). removeChild() can be used to remove an element. Once you have a node saved in a variable, you can modify its attributes.<br>
      The DOM can be inspected in Chrome with the Developer Tools. Many browsers have similar tools.
- [x] Understanding the Problem Domain:
      By creating something that is easily understood, the focus can be on learning the technology itself, rather than what it is you are trying to make. Coding is much easier if the design is well done, or if you already understand what the program needs to do from start to finish. Making the problem domain easier or getting better at understanding them are two ways to make this part of coding easier. Discussing what the program will do with users or designers is a great way to do this.

## Read 8 - Due 7/16/20 AM

- [x] Local Storage:
      Historically web applications didn't have options for easy local storage, unlike programs installed on a computer. Cookies were used, but had disadvantages like slowing the page, unencrypted, and only include about 4kb of data. Before HTML5, there were a few hacks that were used.<br>
      All the hacks worked only for certain browsers, or needed various software installed until HTML5 Storage. HTML5 storage saves data in key, value pairs and the data doesnt leave the client machine until it is requested by the page. <br>
      The drawback to HTML5 Storage is 5mb of space for each origin and not all browsers let this change. <br>
      The future of web storage and there are a few competing ideas. SQL would be able to store all the data on a remote database. IndexDB is another idea that some companies support.

## Read 9 - Due 7/17/20 AM

- [x] HTML CH7 Forms (pp144-175):
      Forms offer a good way to collect data from users. Form inputs come in many different types like text, password, radio buttons, checkboxes and drop down boxes. <br>
      Every form needs an action attribute to specify the server address the information will go. They also need an id to identify the data. The form inputs can be different depending on their type and each one should have a name to reference the data.
- [x] HTML CH14 Lists, Tables & Forms (pp330-357):
      Lists can be styled with the list-style css property. Unordered lists can be disc, circle, square. Ordered lists can be decimal, decimal-leading-zero, upper/lower-alpha, upper/lower-roman. Pictures can also be used. <br>
      Forms can be styled different ways and the better the form looks, the more willing people will be to fill them out. Even the cursor can be styled.
- [x] JS CH6 Events (pp243-292):
      When using the internet you can set up events that will trigger when certain things happen, once triggered code can run. To do this, first get the DOM node that you want the script to respond to, then indicate which event will run the response, then state the code you want to run.<br>
      The event handlers can be in the HTML, but mixes the javascript with the HTML so dont use this. The DOM event handler holds the event handler in the script but cannot use paramaters. Event Listeners are the newest way to trigger events and can trigger multiple functions, but isnt supported in some older browsers. Fallback code can be written to make this supportable in older versions of IE.<br>
      The Event Flow controls how events are handled by nested ancestors. Event Bubbling means the event starts at the most specific node and out to the least specific node. Event Capturing means the event starts at the least specific node and moves in to the most specific.<br>
      Event Delegation is to have fewer events, and let the events reference your target so you can have fewer event handlers that might slow down the page. The event's object's target can determine the target.<br>
      User Interface events occur as a result of interaction with the browser window rather than the HTML page.

## Read 10 - Due 7/20/20 AM

- [ ] HTML CH15 Layout (re-read):
      Each HTML element is treated as if it is in its own box, and each box is either inline or block level. Inline will display next to and block will display below the previous element.<br>
      Fixed width layouts have a fixed width and makes it easy to control size and positioning. Image and text sizes are easy to control. Liquid layouts change as the users screen size change and is tolerant of different sized screens. <br>
      Separate style sheets can be used to manage different parts of the style on your site.
- [ ] JS CH10 Error Handling & Debugging:
      Order of execution is important to understand when searching for a bug in the program. Most functions are either in global scope or function scope and the scope is the information the function has access to. The interpreter goes throgh the code line by line and follows the commands, called the stack. As the script enters a new execution context there are two phases, prepare and execute. Variable declarations (not values) and function declarations are hoisted to the top to be interpreted first then the code is ran. Scope is determined by the information that gets prepared in the prepare context along with any parent variables that are available (like global variables). If JavaScript generates an error it throws an exception, the interpreter stops and looks for handling code. The error code can show several types of errors and will likely give you a line in the code that caused it. Console logs can show you the information available at a specific time in the code and debugger statements can pause the code and show you what is going on in dev tools. Break points can be set within the console to add debugger statements that way. <br>
      Try, catch and finally can be used if you know you are goign to get an error to gather more information.

## Read 12 - Due 7/22/20 AM

- [ ] Charts.js API:
- [ ] Canvas API Basic Usage:
- [ ] Canvas API Drawing Shapes with Canvas:
- [ ] Canvas Applying Styles and Colors:
- [ ] Drawing Text:

## Read 10 - Due 7/24/20 AM

- [ ] HTML CH16 Images (pp406-427):
- [ ] HTML CH19 Practical Information (pp476-492):
- [ ] JS CH9 Flash (pp201-206):
