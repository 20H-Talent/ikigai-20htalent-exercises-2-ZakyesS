# 20H TALENT CODE EXERCISES UNIT 2 & UNIT 3

* # UNIT 2

    # _Reviews_

    1.  **Intro to CSS Review**
    2.  **Adding CSS Review**
    3.  **Basic Selectors Review**
    4.  **Color Values Review**
    5.  **Fonts and Line Height Review**
    6.  **The Box Model Review**
    7.  **Basic Layout Review**
    8.  **Multiple Backgrounds and Web Fonts Review**
    9.  **Fundamental Concepts Review**
    10. **Getting Started with CSS Layout Review**
    11. **CSS Display Modes**
    12. **Float Property Review**
    13. **CSS Layout Review**
    14. **Positioning Page Content**
    15. **Delivering Responsive Images and Image Formats**
    16. **Srcset with Picturefill**
    17. **Adding Sizes**
    18. **Art Direction**
    ---

    ---

    # _Challenges_

    1.  **Type Selectors**
        1.  Create a type selector that targets the _body_ element. Then, add the _text-align_ property and set the value to _center_.
        2.  Create a new type selector that targets the paragraph elements. Add a _color_ property and set the value to _lightslategrey_.
        3.  Next, create a new type selector that targets the _header_ element. Set the background color to _orange_ and the text color to _white_.
        4.  Finally, create a new type selector that targets the _div_ element. Add a _background-color_ property and set the value to _lightblue_.

    ---

    2.  **ID and Class Selectors**
        1.  Give the header element a class attribute. Then, set the class value to main-header.
        2.  In the style sheet, target main-header with a class selector. Then, add a background-color property and set the value to orange.y
        3.  In the HTML file, give the h1 element the class main-heading.
        4.  Next, target the class main-heading. Give the heading a font-size property and set the value to 72px.
        5.  In the HTML file, give the div element an ID name of main-content.
        6.  Finally, target main-content with an ID selector. Add a background-color property and set the value to lightsteelblue.

    ---

    3.  **Descendant Selectors**
        1.  Create a descendant selector that targets the _span_ inside the _header_ element. Add a _font-size_ property and set the value to _26px_.
        2.  Next, target the paragraph that is a descendant of the _main-content_ class. Add a _font-weight_ property and set the value to _bold_.
        3.  Finally, target the paragraph that is a descendant of the _footer_ element. Add a _color_ property and set the value to _slategrey_.

    ---

    4.  **Pseudo-Classes**
        1.  Use the pseudo-class selector that targets default, unvisited links. Set their color value to _orange_.
        2.  Next, create a pseudo-class selector that targets all visited links. Add a _color_ property and set the value to _steelblue_.
        3.  Finally, add a new pseudo-class selector that targets all links on hover. Add a _color_ property and set the value to _tomato_.

    ---

    5.  **Pixels and Percentages**
        1.  Let's make the `<span>` element with the class "title" larger. Increase its font size to 26 pixels.
        2.  Next, increase the font size of the _h2_ element to 53 pixels.
        3.  Finally, let's reduce the width of the _main-content_ div. Give it a width value that takes up 75 percent of its container's width.
    6.  **Em and Rem Units**

        1.  The em-based font-size values for _.title_ and _h1_ are relative to their parent header's font-size value. This causes a compounding issue that makes their font size values larger than the desired values.

        - Replace the em units of _.title_ and _h1_ with a unit that is relative to the root element of the page.

        2.  Create a new rule that targets the _h2_. The _h2_'s parent element has a _font-size_ value of _16px_. Use an _em_ unit to give the _h2_ a _font-size_ value equivalent to _53px_.
        3.  Finally, create a new rule that targets the _h3_. Using the same parent font-size context, give the _h3_ a _font-size_ value in ems equivalent to _20px_.

    7.  **Styling the Intro Paragraph**
        1.  Give the paragraph element on _line 14_ the class _intro_.
        2.  In the style sheet, select the _intro_ class and add a _font-size_ property. Using _16px_ as the parent font-size context, give _intro_ an _em_ font-size value equivalent to _20px_.
        3.  Next, give _intro_ a unitless _line-height_ that's 1.6 times larger than the _font-size_ value.
        4.  Create a new rule that targets the _span_ element inside _.intro_. Give the _span_ element a bold font weight and an italic font style.
        5.  Finally, create a new rule that removes the underline from all unvisited links on the page.

    ---

    8.  **Padding, Borders, and Margins**
        1.  Let's style parts of the Lake Tahoe website using padding, borders, and margins. First, target the class _primary-content_. Set the top padding to 25 pixels and the bottom padding to 95 pixels.
        2.  Next, give the _.wildlife_ div a _solid_, _orange_ top border that's _10px_ wide.
        3.  Target the _.secondary-content_ div. Set the top padding to 80 pixels and the bottom padding to 70 pixels.
        4.  Let's separate the _.wildlife_ container from the content above it. Give _.wildlife_ a top margin of 105 pixels.
        5.  Finally, give the _.secondary-content_ element a dotted, _lightgrey_ bottom border that's _2px_ wide.

    ---

    9.  **Styling the "Wildlife" div with Background Properties**
        1.  Create a new rule that targets the class 'wildlife'. Set the _bear.jpg_ image, located in the _img_ folder, as the background image.
        2.  Next, define the background property and value that prevents a background image from repeating in any direction.
        3.  Next, position the background image in the center of the '.wildlife' element.
        4.  Add a _background-size_ property. Set a value that fills the entire background of the container while maintaining the width and height proportions.
        5.  Finally, give _.wildlife_ the _box-sizing_ property and value that forces any padding and border widths into its total width and height.

    ---

    10. **Floats**
        1.  Create a new rule that targets the _.content-lodging_ div. Add the property and value that takes _.content-lodging_ out of the normal page flow and places it along the right side of its container.
        2.  Next, create a new rule that targets _.content-traveling_. Add the property and value that takes _.content-traveling_ out of the normal page flow and places it along the left side of its container.
        3.  In the preview, notice how the floats made the parent container's height collapse. In the HTML file, give the _.secondary-content_ div the specified class for clearing floats.

    ---

    11. **Text Shadows and Box Shadows**

        1.  Create a new rule that targets _.main-heading_. Give the heading a text shadow by setting the horizontal and vertical offsets to _0_, the blur radius to _5px_, and the color to the hex value _be7b31_.
        2.  Next, create a new rule that targets _.title_. Let's also give _.title_ a text shadow by setting the horizontal offset to _1px_, the vertical offset to _3px_, the blur radius to _0_, and the color to _#e59740_.
        3.  Create a rule that targets _.main-header_. This time, we'll give _.main-header_ a box shadow. Set the box shadow's horizontal offset to _0_, the vertical offset to _2px_, the blur radius to _15px_, and the color to _#aaa_.
        4.  Just like the _text-shadow_ property the _box-shadow_ can take multiple comma-seperated values to add additional shadows to the same element.

            - Let's give _.main-header_ an inner-shadow with a second set of _box-shadow_ values. Set the new shadow's horizontal and vertical offsets to _0_, the blur radius to _60px_, the spread radius to _5px_, and the color to _firebrick_. Don't forget to include the keyword value that creates an inner box shadow.

    ---

    12. **Border Radius**
        1.  Let's give the _.wildlife_ div rounded corners! Add the shorthand property for setting rounded corners. Set the top-left border radius to 20px, the top-right radius to _5px_, the bottom-right radius to _20px_, and the bottom-left radius to _5px_.

    ---

    13. **Gradients**
        1.  Create a new rule that targets _.main-header_.
        2.  Next, add a _background-image_ property and define a linear gradient function as the value.
        3.  Set the gradient's first color stop to _steelblue_ and the second color stop to _darkslateblue_.
        4.  Set the second color stop's position to 90%. Then, add the value that sets the gradient direction from bottom to top.

    ---

    14. **Media Queries**
        1.  Create a media query that targets all devices when the viewport width is _1020px_ or less. Inside the media query, select the _.main-header_ element. Set the background color to _tomato_ and the text color to _white_.
        2.  Next, create a new media query that targets all devices when the viewport width is _768px_ or narrower. Inside the media query, target the _.title_ element and set the font-size to _1.4rem_. Finally, target the _h1_ element and set its font-size to _5rem_.

    ---

    15. **Layout Wrapper Challenge**
        1.  Add a wrapper `<div>` around the content inside `<body>`. Give it the class 'container'.
        2.  Set the wrapper's width to _80%_ of the browser width. Then use margins to center the wrapper in the browser.

    ---

    16. **CSS Display Modes Challenge**

        1.  Display the list items inside _.main-nav_ side by side. Use the _display_ value that generates a block element that flows with surrounding content.
        2.  The `<ul>` with the class _main-nav_ is a block-level element by default, so it takes up the full width of its container. Let's set ._main-nav_ to be as wide as the content inside it.

            - Change the display of ._main-nav_ to the *display* value that generates a block element that doesn't take up a full line.

        3.  The logo is an _<img>_, so it displays inline with surrounding content by default. The logo displays on the same line as ._main-nav_ and the auto margins have no effect on it. Place the ._logo_ on a separate line by changing its _display_ mode.

    ---

    17. **Footer Layout with Floats**
        1.  Float ._footer-nav_ to the left edge of the footer and ._logo_ to the right edge.
        2.  Next, display the list items inside ._footer-nav_ side by side with a float.
        3.  The floats inside the `<footer>` caused its height to collapse. Give the `<footer>` element the class that will clear all floats inside it.
        4.  The _copyright_ text in the footer needs to be moved down below the floated elements. Select .copyright and apply the property and value that clears both the left and right floats.

    ---

    18. **CSS Positioning Challenge**
        1.  Select the class _logo_ and give it absolute positioning.
        2.  Next, give ._logo_ a top offset of -_45px_ and a left offset of _125px_.
        3.  The logo's absolute position is relative to the browser viewport. Make ._card_ the new positioning context for ._logo_.
    ---

    19. **Using Srcset**
        1. The `<img>` element inside `<div class="profile-image">`, has a @1x image inside the *srcset* attribute. Modify the srcset attribute so that the @2x image *photo-@2x.jpg* comes first, and the @1x image that's already present comes second.
    ---
    20. **The Picture Element**
        1. The `<picture>` element has two child `<source>` elements. In the first `<source>` element, add a *media* attribute with a value that will only use the source when in landscape orientation. The second `<source>` element should not be modified.

---

* # UNIT 3

    # _Reviews_
    1. **HTML Tables Review**
    2. 

    ---
    ---
    
    # _Challenges_

    1.  **Create a Table**
        1. Create a table element. Don't add any other elements yet.
        2. Create four table rows. Don't fill them with table cells yet.
        3. Add two table cells inside each table row. Don't fill the table cells with any data yet.
        4. In the first row, fill the first table cell with the word "Name" and fill the second table cell with the word "Job". Then, fill in the rest of the table cells with any information that you'd like.
    ---
    2. **Add Table Cell Headers**
        1. Convert the cells containing "Name" and "Job" into table header cells. For both, add the *scope* attribute with the value "*col*".
    ---
    3. **Add the Table Head and Body Elements**
        1. Add the table head and table body elements in the appropriate places.
    ---
    4. **Add the Table Footer Element**
        1. Add a table footer element with one row and one table cell. Don't add any attributes or content yet.
        2. Inside the table footer, fill the table cell with the text, "Data is updated every 15 minutes."
        3. Inside the table footer, add a *colspan* attribute to the table cell so that it spans the width of the table.
    ---
    5. **Add a Table Caption Element**
        1. Add a caption element that says "Employee Data".
    ---
    6. 