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
    2. **HTML Forms Review**
    3. **Attribute Selectors and Combinators Review**
    4. **Structural and Element States Pseudo-Classes Review**
    5. **Advanced Selectors Review**
    6. **Flexbox Basics Review**
    7. **Flexbox Properties Review**
    8. **Building a Layout with Flexbox**

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
    6. **Create a Form Element**
        1. Create a form element. Don't add any attributes yet.
        2. Add an *action* attribute to the form element with the value *index.html*.
        3. Add a *method* attribute to the form element with the value *post*.
    ---
    7. **Create a Text Input**
        1. Create a form element with an *action* attribute set to *index.html* and the *method* attribute set to *post*.
        2. Inside the form element, add an input with the *type* attribute set to the value *text*. Don't add any other attributes yet.
        3. On the input created in the last step, add an *id* attribute with the value *name*.
        4. Now, add a *name* attribute to the input. Set its value to *user_name*.
    ---
    8. **Create a Textarea**
        1. Create a form element with an *action* attribute set to *index.html* and the *method* attribute set to *post*.
        2. Add a text input with the *id* attribute set to *name* and the *name* attribute set to *user_name*.
        3. After the input element, add a *textarea* element. Don't add any attributes yet.
        4. On the *textarea* element, add an *id* attribute and set the value to *comment*.
        5. On the *textarea* element, add a *name* attribute and set the value to *user_comment*.
    ---
    9. **Create a Submit Button**
        1. Create a form element with an *action* attribute set to *index.html* and the *method* attribute set to *post*.
        2. Add a text input with the *id* attribute set to *name* and the *name* attribute set to *user_name*.
        3. After the input, add a *textarea* with the *id* attribute set to *comment* and the *name* attribute set to *user_comment*.
        4. After the *textarea*, create a button element. Between the button tags, write the text *Submit Comment*. Don't add any attributes yet.
        5. On the button element created in the last step, add a *type* attribute with the value *submit*.
    ---
    10. **Add Labels**
        1. Create a label with a *for* attribute that matches the input element's ID. Between the label tags, write the text *Name:*.
        2. Now create a label for the *textarea* element, and give it the text *Comment:*.
        3. After the name field, add another input for email addresses. Set the *type* attribute to *email*, the *id* attribute to *email*, and the name to *user_email*.
        4. Create a label for the email field with the text *Email:*.
    ---
    11. **Add Fieldsets and Legends**
        1. Create a *fieldset* element that wraps the name and email fields.
        2. Create another *fieldset* element that wraps the comment field.
        3. Add a *legend* element to the first *fieldset* and give it the text *Tell us about yourself.*
        4. Add another *legend* element to the second *fieldset* and give it the text *What's on your mind?*
    ---
    12. **Create a Select Menu**
        1. Below the `<h1>` element, create a *select* element with the ID of "color" and the name "shirt_color". Don't add any options yet.
        2. Add the following options to the select menu: *Red, Yellow, Purple, Blue, Green, and Orange*. Each option should have a *value* attribute. Set each *value* attribute to the same color name, but in all lowercase. Example: `value="blue"`
        3. Add a label element to the select menu with the text `"Shirt Color:"`.
        4. Add a submit button with the text "Place Order".
    ---
    13. **Create Radio Buttons**
        1. After the select menu, create a radio button with the ID *small*, the value *small*, and the name *shirt_size*. Don't add a label or line breaks yet.
        2. In the same radio button group, add two more radio buttons for medium and large shirt sizes. Don't add a label or line breaks yet.
        3. Add a label above the radio button group that says *Shirt Size:*. Don't associate it with any specific element.
        4. Create and associate a label with each of the 3 shirt size radio buttons. Give them the text *Small*, *Medium*, and *Large*.
        5. Add a line break element after each shirt size label.
    ---
    14.  **Create Checkboxes**
        1. After the radio button group, create a checkbox with the ID *shipping* and the value *fast_shipping*. Don't add any labels or line breaks yet.
        2. Create another checkbox with the ID *newsletter* and the value *subscribe*. Don't add any labels or line breaks yet.
        3. Add labels for the two checkboxes that say *Fast Shipping* and *Subscribe to Newsletter*. Then add line breaks after the labels.
    ---
    15. **Attribute Selectors Challenge**
        1. Create an attribute selector that targets *img* elements with a *title* attribute value of 'avatar'. Give the elements a border radius of 50%.
        2. Next, create a new attribute selector that targets *input* elements with a *type* attribute value of *password*. Then, set the color to `#ccc`.
        3. Finally, write a new attribute selector that targets *input* elements with a *type* attribute value of *submit*. Then, set the background color to `#52bab3`.
    ---
    16. **Combinators Challenge**
        1. Create a child selector that targets *li* elements that are direct children of .*main-nav*. Set the display to *inline-block* and the left margin to *20px*.
        2. It looks like we need to decrease the space between *h2* elements and the paragraph that immediately follows. Create a new selector that targets *p* elements that are adjacent siblings of an *h2*. Then, set the top margin to .*5em*.
    ---
    17. __:first-child and :last-child Challenge__
        1. Create a pseudo-class selector that targets the first-child *li* in .*main-nav*. Remove all border styles by setting *border* to *none*. Then, set the top-left and bottom-left *border-radius* to *5px*. 
        2. Next, create a new pseudo-class selector that targets the last-child *li* in .*main-nav*. Give it a top-right and bottom-right *border-radius* of *5px*.
    ---
    18. **Substring Matching Attribute Selectors Challenge**
        1. Create a selector that targets an *img* element if its *title* value begins with 'product-'. Set the border color to *lightblue*.
        2. Next, create a new selector that targets an *a* element if its *href* value ends with '.html'. Set its *text-decoration* to *none*.
        3. Finally, create a new selector that targets an *img* element if its *src* value contains the word 'preview'. Then, set its *width* to *100%*.
    ---
    19. __:nth Pseudo-Class Challenge__
        1. Inside the media query, create a new rule that targets *img* elements. Then, float the images *left*.
        2. We want three floated images per row. In the media query, create a pseudo-class selector that targets the fourth *img* child element first, then every third *img* that follows. Then, add a *clear* property that clears the left float.
        3. Hey, nice job! To see which combination of images we selected, give them a different *border-color* value –– any color you want. Don't forget to preview before you click 'check work'.
    ---
    20. __:nth Pseudo-Class Challenge - Pt. 2__
        1. It looks like an `<h1>` made its way inside the parent *body*. Now our :*nth-child* selector no longer targets the desired combination of *img* child elements. Replace :*nth-child* with the pseudo-class that only targets a specific type of child element.
    ---
    21. **Pseudo-Elements Challenge**
        1. Let's use pseudo-elements to create a progress bar from a single element. First, in the top .*progbar* selector, add the pseudo-element that will insert content after the element.
        2. In the same rule, add the property that lets us insert content into an element. The value should be an empty set of quotes.
        3. Next, in the second .*progbar* selector, add the pseudo-element that will insert content *before* the element. Don't forget to write the *content* declaration on *line 13*.
        4. Finally, create a new rule that will insert a pseudo-element *after* an *a* element. As the *content* value, define a CSS function that will insert an *href* attribute's value as content.
    ---
    22. **Flex Container Challenge**
        1. The first step to using flexbox is creating a flex container. Target .*main-nav* and make it a flex container.
    ---
    23. **Wrapping Items and Distributing Space**
        1. First, make .*row* a flex container.
        2. Next, give .*row* the flexbox property and value that will make it a multi-line flex container.
        3. Finally, let's distribute the available space inside .*row*. Give .*row* the flexbox property and value that will place the first and last items along its edges, then equally distribute the space between the other items.
    ---
    24. **Growing and Aligning Flex Items**
        1. Select the class .*column* and use the flex item property and value that will expand the columns to fill the space of the row.
        2. Next, target .*primary* and assign it twice as much free space as the other flex items.
        3. Finally, align the columns to the vertical center of .*row*. Use the flex container property that controls alignment on the cross axis.
    ---
    25. **Flexbox Columns Challenge**
        1. Let's display equal -- but flexible -- widths for the columns. Create a new rule that targets the columns. Then, set the columns to evenly expand and display on one line, with an initial width of *300px*.
        2. The columns should break to multiple lines when they're narrower than 300px. Give .*row* the flexbox property and value that will make it a multi-line flex container.
    
---
* # UNIT 4

    # _Reviews_
    1. **JavaScript is Everywhere Review**
    2. **How JavaScript Runs Review**
    3. **Build Tools and Workflows Review**
    4. **Welcome to Web Programming**
    5. **What have you learned about programming?**
    6. **Review Your Progress**
    7. **Introduction to Sass Review**
    8. **Compiling Sass Review**
    9. **Sass Workflow Review**
    10. **Partials and Media Queries Review**
    11. **Functions Review**
    12. **Maps and Loops Review**
    13. **Debugging Review**
    ---
    ---
    
    # _Challenges_

    1. **Modifying Values** 
        1. Modify the *platforms.create* command on line 24 to move the platform 100 pixels down, making the new coordinates (300, 200).
        2. Let's change one of the platforms to a be different type. Modify the *platforms.create* command on line 25 to use the string 'platform2' instead of 'platform'.
    ---
    2. **Final Code Challenge**
        1. Click the preview button to view the game. Currently, there are 3 stars on screen. Click the Editor button and add two more stars, bringing the total number of stars to 5. Make sure none of the stars overlap with any other stars.
        2. There are bottles of poison on screen. The player's life goes up when the player touches a bottle of poison. Change the game so the player's life count decreases by one when a bottle of poison is touched. Hint: the code to change is between lines 71 and 78.
    ---
    3. **Declare and Use Variables**
        1. Declare a variable called "color-brand" and assign it the value #*6a5acd*.
        2. Use the 'color-brand' variable to set the color of *h1* elements.
        3. Declare another variable called 'gutter' and set its value to *20px*.
        4. Target the class .*col* and apply a left margin using the *gutter* variable.
        5. Finally, target .*row* and set its bottom margin to the *gutter* variable.
    ---
    4. **Write Nested Selectors**
        1. Nest a .*button* selector inside the .*banner* rule. Set the font-size of .*button* to *1.5em*.
        2. Below the .*banner* rule (at the root level), create a new rule that targets .*icn* and set a font-size of *1.25em*.
        3. Next, use the *&* symbol to create the selector .*icn-success*. Set the color of .*icn-success* to *green*.
        4. Use the *&* symbol to create the selector .*icn*-warning*. Set the color of .*icn-warning* to **red*.
    ---
    5. **Write a Mixin**
        1. Create a mixin called 'button' that sets *font-size* to *1.25em* and *background-color* to the variable $*btn-background*.
        2. Next, create a new rule to specify that all `<a>` tags should include the styles defined inside the *button* mixin.
        3. Inside the *button* mixin, write the directive that lets you pass content blocks to mixins.
        4. Finally, pass the color value #*f0f8ff* to the *button* include.
    ---
    6. **Practice Extending a Selector**
        1. Create a rule using the class .*roundy*. Give .*roundy* a width of *150px* and a border-radius of *50%*. Then, create a rule that targets .*img-author* and allow it to extend the properties of .*roundy*. 
        2. Next, create a placeholder called *warning*. Set its *font-weight* to *bold* and *color* to *red*.
        3. Finally, create a new rule that targets the class .*message-box*. Make sure all `<p>` tags nested inside .*message-box* extend the properties of %*warning*.
    ---
    7. **Write a Sass Function**
        1. Write a function, called *px-to-rem*, that accepts the parameters $*target* and $*context*. Set the default value of $*context* to the $*base-font-size* variable
        2. In the @*return* statement, divide $*target* by $context, and multiply it by *1rem*. This will return a *rem* value.
        3. Finally, create a rule that targets an *h1*. Use the *px-to-rem* function to convert a *font-size* value of *60px* to a value in *rem* units.
    ---
    8. **Advanced Mixins Challenge**
        1. Create a mixin called *square* that takes two arguments: one called "size" that will set the height and width, and another called "color" that will set the color of a *1px solid border*.
        2. Make the $*color* argument optional by setting it to *black* by default.
        3. Create a rule that targets the class *box*. Use the *square* mixin to set the height and width of .*box* to *50px* and the border color to *red*.
        4. Switch the order of the *square* arguments. Be sure to specify the variable for each argument.
    ---
    9. 