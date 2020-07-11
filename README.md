# reading-notes

---

- [x] Chapter Read and Notes Taken

---

## Day 1 - Due 7/7/20 AM

- [ ] HTML CH1
- [ ] HTML CH8
- [ ] HTML CH17
- [ ] HTML CH18
- [ ] JS CH1

---

## Day 2 - Due 7/8/20 AM

- [ ] HTML CH2
- [ ] HTML CH10
- [ ] JS CH2
- [ ] JS CH4

---

## Day 3 - Due 7/9/20 AM

- [x] HTML CH3 Lists:<br>
      Lists can be numbered with ol, bulleted with ul, or definitions with dl. Definitions can be terms with dt or definitions with dd. I was surprised to find that lists can be nested in list items to indent further.
- [x] HTML CH13 Boxes:<br>
      Box sizes can be controled with width and height, and prepended with max- or min- can make them dynamic until the set size. Sizes can be set with em, px or %. Overflow hidden can cut off content beyond box boundaries, and scroll will add scroll bars.<br>
      The box model consists of the element with padding, border, and margins around it. Padding is the popcorn within the box giving white space between content and the border, the border is like the box that wraps the content and the margin is the space between it and the next box. Margins overlap, so only the largest margin will show.<br>
      Borders can be styled a few different ways including with a picture. Box shadow can give them a 3D look.<br>
      Boxes can be hidden 2 ways, display: none will remove it from the page flow, and visibility: hidden will hold its place. Either way the user can see the content in the page code.
- [x] JS CH4 Decisions and Loops:<br>
      Decisions can be made based with these statements: if else if..else. Comparisons can be made with a bang, triple equals, less or greater than. Logic can be applied with and, or, bang.<br>
      All data types break down into truthy or falsey values. Falsey values include 0, empty strings, NaN, not assigned, empty values, false. Truthy values are strings with characters, other numbers besides 0, true.<br>
      Functions are groups of related tasks that can take parameters. Objects represent some thing. Functions on objects are Methods and variables on objects are Properties. Objects get some default Methods and Properties. Arrays of objects can create complex data sets.

---

## Day 4 - Due 7/10/20 AM

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
      Objects represent real world things modeled by a set of variables and functions. Objects are made of key: value pairs. Objects can be created literally defined into a varaible, and they can be made with a constructor defined by declaring a function. The New keyword will instruct the function to create a new object based on the outcome of the function. Properties can be added, removed and accessed with dot notation if the path is static, or bracket notation if it will be dynamically determined. This can be used to reference the object that the function is created inside.<br>
      Arrays and Objects are used to store complex data. Arrays can be made up of objects, and objects can use arrays as values. <br>
      The Browser Object starts with the window and contains information on the browser. Within that is the Document Object which contains the document the current window or tab is referencing. Global variables are in the scope of anything at this level.<br>
      Data can also be strings and numbers and each have their own Methods. Custom Methods can also be built for objects.<br>
- [x] JS Article _6 Reasons for Pair Programming_
      Pair programming allows two people to team up to code. The driver types the code and navigates all the files and the navigator scans for typos, thinks about the big picture and looks up solutions.<br>
      Research indicates that writing the code takes slightly longer than two people working separately, but it produces a higher quality of code. This can make the code more efficient in the long run. Solutions are found faster and technical skills, communication and enjoyability were all increased when tested. It makes it easier for the two coders to stay on track, learn new solutions.

---

## Day 5 - Due 7/13/20 AM

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
