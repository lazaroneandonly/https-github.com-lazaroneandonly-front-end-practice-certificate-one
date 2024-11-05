# FORM PROJECT FOR CERTIFICATE

## Summary: 
**This project is meant to be a submisison for the FREECODECAMP certificate for froint end development.While Many could say that the design represented here is an overkill, I found it compelling to go above and beyond the required standard, even for such a simple task as this. I find that in this way I am able to develop further my skills as a front end programmer and go into avenues and patterns of thought that I rarely went into before.** 

## Use:

## Relevant links:
- https://survey-form.freecodecamp.rocks
- Link to WCAG:  https://www.w3.org/TR/WCAG20/#intro-layers-guidance

## Basic divisions of the project: 
**This project has the following structure.** 

- A html file (webform.html)
- A css file (webform.css)
- A resource folder containing snapshots and pictures upon which the form should be based
- This README. 

## Summary: Objectvies: 
**The basic requiremnts are alrady stiplated in one of the picture sin the resources, but to summarise:**  

- [x] You should have a page title in an h1 element with an id of title.
- [x] You should have a short explanation in a p element with an id of description.
- [x] You should have a form element with an id of survey-form.
- [x] Inside the form element, you are required to enter your name in an input field that has an id of name and a type of text.
- [x] Inside the form element, you are required to enter your email in an input field that has an id of email.
- [x] If you enter an email that is not formatted correctly, you will see an HTML5 validation error.
- [x] Inside the form, you can enter a number in an input field that has an id of number.
- [x] The number input should not accept non-numbers, either by preventing you from typing them or by showing an HTML5 validation error (depending on your browser).
- [x] If you enter numbers outside the range of the number input, which are defined by the min and max attributes, you will see an HTML5 validation error.
- [x] For the name, email, and number input fields, you can see corresponding label elements in the form, that describe the purpose of each field with the following ids: id="name-label", id="email-label", and id="number-label".
- [x] For the name, email, and number input fields, you can see placeholder text that gives a description or instructions for each field.
- [x] Inside the form element, you should have a select dropdown element with an id of dropdown and at least two options to choose from.
- [x] Inside the form element, you can select an option from a group of at least two radio buttons that are grouped using the name attribute.
- [x] Inside the form element, you can select several fields from a series of checkboxes, each of which must have a value attribute.
- [x] Inside the form element, you are presented with a textarea for additional comments.
- [x] Inside the form element, you are presented with a button with id of submit to submit all the inputs.

## Additional changes: 
**I have decided to add some further aspects to the project here, as small as it is. Those are:**

- [x] More animative css styles that give a more fluid and relaxing user experience.
- [x] A darkmode option that is toggable.
- [ ] A "visual +" option whcih changes the text and css layout in a way that suits people with sight and visual imparements, in accordance with WCAG standard

## Additional concept:
**Another idea that I had for the standardisationa nd compartmentalisaiton of the code is to have a reusable function pattern design similar to the "Atomic Design" model**

## Noting a design improvement case:
**Another idea that I had for the standardisationa nd compartmentalisaiton of the code is to have a reusable function pattern design.I I have noticed that a lot of these patterns seem to follow the same structure of:**

- [x] Header
- [x] form button descritpion (optional)
- [x] The actual form buttons based on type and context. 

**This seems to me to be a classic case of...**