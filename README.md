# 20H TALENT CODE EXERCISES UNIT 2 #

# *Reviews* #
1. **Intro to CSS Review**
2. **Adding CSS Review**
3. **Basic Selectors Review**
4. **Color Values Review**
5. **Fonts and Line Height Review**

---
---
# *Challenges* #
1. **Type Selectors**
    1. Create a type selector that targets the *body* element. Then, add the *text-align* property and set the value to *center*.
    2. Create a new type selector that targets the paragraph elements. Add a *color* property and set the value to *lightslategrey*.
    3. Next, create a new type selector that targets the *header* element. Set the background color to *orange* and the text color to *white*.
    4. Finally, create a new type selector that targets the *div* element. Add a *background-color* property and set the value to *lightblue*.
---
2. **ID and Class Selectors**
    1. Give the header element a class attribute. Then, set the class value to main-header.
    2. In the style sheet, target main-header with a class selector. Then, add a background-color property and set the value to orange.
    3. In the HTML file, give the h1 element the class main-heading.
    4. Next, target the class main-heading. Give the heading a font-size property and set the value to 72px.
    5. In the HTML file, give the div element an ID name of main-content.
    6. Finally, target main-content with an ID selector. Add a background-color property and set the value to lightsteelblue.
---
3. **Descendant Selectors**
    1. Create a descendant selector that targets the *span* inside the *header* element. Add a *font-size* property and set the value to *26px*.
    2. Next, target the paragraph that is a descendant of the *main-content* class. Add a *font-weight* property and set the value to *bold*.
    3. Finally, target the paragraph that is a descendant of the *footer* element. Add a *color* property and set the value to *slategrey*.
---
4. **Pseudo-Classes**
    1. Use the pseudo-class selector that targets default, unvisited links. Set their color value to *orange*.
    2. Next, create a pseudo-class selector that targets all visited links. Add a *color* property and set the value to *steelblue*.
    3. Finally, add a new pseudo-class selector that targets all links on hover. Add a *color* property and set the value to *tomato*.
---
5. **Pixels and Percentages**
    1. Let's make the `<span>` element with the class "title" larger. Increase its font size to 26 pixels.
    2. Next, increase the font size of the *h2* element to 53 pixels.
    3. Finally, let's reduce the width of the *main-content* div. Give it a width value that takes up 75 percent of its container's width.
6. **Em and Rem Units**
    1. The em-based font-size values for *.title* and *h1* are relative to their parent header's font-size value. This causes a compounding issue that makes their font size values larger than the desired values.

    -   Replace the em units of *.title* and *h1* with a unit that is relative to the root element of the page.
    2. Create a new rule that targets the *h2*. The *h2*'s parent element has a *font-size* value of *16px*. Use an *em* unit to give the *h2* a *font-size* value equivalent to *53px*.
    3. Finally, create a new rule that targets the *h3*. Using the same parent font-size context, give the *h3* a *font-size* value in ems equivalent to *20px*.
7. **Styling the Intro Paragraph**
    1. Give the paragraph element on *line 14* the class *intro*.
    2. In the style sheet, select the *intro* class and add a *font-size* property. Using *16px* as the parent font-size context, give *intro* an *em* font-size value equivalent to *20px*.
    3. Next, give *intro* a unitless *line-height* that's 1.6 times larger than the *font-size* value.
    4. Create a new rule that targets the *span* element inside *.intro*. Give the *span* element a bold font weight and an italic font style.
    5. Finally, create a new rule that removes the underline from all unvisited links on the page.
---