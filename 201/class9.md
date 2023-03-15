## Class 9 Notes

## Why are forms so important in web development?

- Web forms are a very powerful tool for interacting with users — most commonly they are used for collecting data from users, or allowing them to control a user interface

## When designing a form, what are some key things to keep in mind when it comes to user experience?

1. Less is more (i.e. remove form fields).
2. Single-column beats multi-column forms.
3. Communicate errors clearly.
4. Use inline form-field validation.
5. Order fields from easiest to hardest to fill out.
6. Make typing easy.
7. Indicate if each field is required or optional (unless they’re all required).
8. Name and phone number fields should be one field.
9. Offer radio buttons instead of drop-down boxes.
10. Don’t make coupon code fields prominent.
11. Avoid the “clear fields” button.
12. Offer field focus.
13. Don’t mask passwords.

## List 5 form elements and explain their importance.

- The label element defines a label for several form elements.
The label element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.
The label element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the label element, it toggles the radio button/checkbox.

- The select element defines a drop-down list

- The option elements defines an option that can be selected.
By default, the first item in the drop-down list is selected.

- Use the size attribute to specify the number of visible values

- Use the multiple attribute to allow the user to select more than one value

## How would you describe events to a non-technical friend?

- An event refers to an action or occurrence that happens in the system you are programming. The system then notifies you about the event so that you can respond to it in some way if necessary.

## When using the addEventListener() method, what 2 arguments will you need to provide?

- A function or object

## Describe the event object. Why is the target within the event object useful?

- Sometimes, inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. This is called the event object, and it is automatically passed to event handlers to provide extra features and information.

## What is the difference between event bubbling and event capturing?

- Capturing phase : the event moves down towards the element. Target phase: the event reaches the target element. Bubbling phase: the event bubbles up from the element.