# 20H TALENT CODE EXERCISES UNIT 2 #

# *Reviews* #
1. **Intro to CSS Review**
2. **Adding CSS Review**
3. **Basic Selectors Review**
4. **Color Values Review**
5. **Fonts and Line Height Review**
6. **The Box Model Review**
7. **Basic Layout Review**

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
8. **Padding, Borders, and Margins**
    1. Let's style parts of the Lake Tahoe website using padding, borders, and margins. First, target the class *primary-content*. Set the top padding to 25 pixels and the bottom padding to 95 pixels.
    2. Next, give the *.wildlife* div a *solid*, *orange* top border that's *10px* wide.
    3. Target the *.secondary-content* div. Set the top padding to 80 pixels and the bottom padding to 70 pixels.
    4. Let's separate the *.wildlife* container from the content above it. Give *.wildlife* a top margin of 105 pixels.
    5. Finally, give the *.secondary-content* element a dotted, *lightgrey* bottom border that's *2px* wide.
---
9. **Styling the "Wildlife" div with Background Properties**
    1. Create a new rule that targets the class 'wildlife'. Set the *bear.jpg* image, located in the *img* folder, as the background image.
    2. Next, define the background property and value that prevents a background image from repeating in any direction.
    3. Next, position the background image in the center of the '.wildlife' element.
    4. Add a *background-size* property. Set a value that fills the entire background of the container while maintaining the width and height proportions.
    5. Finally, give *.wildlife* the *box-sizing* property and value that forces any padding and border widths into its total width and height.
---
10. **Floats**
    1. Create a new rule that targets the *.content-lodging* div. Add the property and value that takes *.content-lodging* out of the normal page flow and places it along the right side of its container.
    2. Next, create a new rule that targets *.content-traveling*. Add the property and value that takes *.content-traveling* out of the normal page flow and places it along the left side of its container. 
    3. In the preview, notice how the floats made the parent container's height collapse. In the HTML file, give the *.secondary-content* div the specified class for clearing floats.
---
11. **Text Shadows and Box Shadows**
    1. Create a new rule that targets *.main-heading*. Give the heading a text shadow by setting the horizontal and vertical offsets to *0*, the blur radius to *5px*, and the color to the hex value *be7b31*. 
    2. Next, create a new rule that targets *.title*. Let's also give *.title* a text shadow by setting the horizontal offset to *1px*, the vertical offset to *3px*, the blur radius to *0*, and the color to *#e59740*. 
    3. Create a rule that targets *.main-header*. This time, we'll give *.main-header* a box shadow. Set the box shadow's horizontal offset to *0*, the vertical offset to *2px*, the blur radius to *15px*, and the color to *#aaa*. 
    4. Just like the *text-shadow* property the *box-shadow* can take multiple comma-seperated values to add additional shadows to the same element.

        - Let's give *.main-header* an inner-shadow with a second set of *box-shadow* values. Set the new shadow's horizontal and vertical offsets to *0*, the blur radius to *60px*, the spread radius to *5px*, and the color to *firebrick*. Don't forget to include the keyword value that creates an inner box shadow.
---
12. **Border Radius**
    1. Let's give the *.wildlife* div rounded corners! Add the shorthand property for setting rounded corners. Set the top-left border radius to 20px, the top-right radius to *5px*, the bottom-right radius to *20px*, and the bottom-left radius to *5px*.
---

