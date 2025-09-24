# Challenge: Feedback-form

## Project brief
We'd like you to imagine that you have just been to stay at a hotel called the little house in the woods (well, at least you thought it was a hotel). We want you to help us create a fictional feedback form for the hotel. As well as marking up the required features and structuring the form, there are a few additional HTML features we want you to implement.

### Implementing form controls
1. In the "Facilities" section, we want you to turn the first two sets of lines into sets of radio buttons plus a label to describe each one and a legend describing the whole group. Add an attribute to make the first radio button in each case selected by default.
2. In the "Facilities" section, turn the third set of lines into a set of checkboxes, with a label to describe each one and a legend describing the whole group.
3. In the "About your hosts" section, turn both sets of lines into a drop-down menu of options, with a label to describe each one.
4. In the "Any other feedback?" section, add a multi-line text entry box and turn the existing line into its descriptive label.
5. In the "Your details" section, add a suitable type of text input to collect each of the three listed values. Turn the existing lines into their labels.
6. Turn "Submit" into a submit button for the form.
   
### Structuring the form
1. Wrap the form in a suitable wrapper element to specify the whole thing as a form.
2. Add repeating structural elements inside the form, to wrap each form section. Give each form section element a class of form-section. To make things easier, each form section is surrounded by two sets of double-hyphens (--). You can remove the double-hyphens when you've added your structural elements.
3. You'll need to include additional structural elements around some of the control/label pairs to make them sit on their own separate lines. Add these now, giving each one a class of separator.
4. Add a line break element between the multi-line text entry box and its label to make the two sit on separate lines.

### Additional HTML features
1. There are several headings in the text that need marking up with suitable elements:

    1. The top level-heading: "We want your feedback!".
    2. Second level headings: "Facilities", "About your hosts", "Any other feedback?", and "Your details".
2. The opening paragraph below the top-level heading needs to be marked up appropriately.
3. Also in the opening paragraph, turn the text "little house in the woods" and "prize draw" into links. We don't have pages to link to yet, so for now, just set the target URL as # for a placeholder.
4. We want you to place a wide, flat image below the opening paragraph as a decoration. The image path is [this](https://mdn.github.io/shared-assets/images/examples/learn/woodland-strip.jpg), and we'd like you to set the alternative text for it to an empty value, given that it is decorative only.
5. Following on from the previous point, as a stretch goal, research a better way to include the decorative image on the page, and have a go at doing so (this involves a different technology to HTML, which we haven't touched on in this module).
   
### Hints and tips
Use the W3C HTML validator to catch unintended mistakes in your HTML — so that you can fix them.


### Example
The following screenshot shows an example of what the form might look like after being marked up. 
![Final-view](/assets/final-view.png)


> This activity is based on the Forms Challenge from [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Forms_challenge), used here for educational purposes.
