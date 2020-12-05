# Accessibility

Accessible design lets people of all abilities interact with, understand, and navigate our website.

Web properties need to be accessible to everyone, including those with vision, hearing, cognitive, or motor impairments.

Accessible design is everyone's responsibility, from information and user experience design, through to development, and on into help and support. It is about understanding the users' journeys and proactively anticipating their needs.

To make sure products are accessible to everyone, follow the [four principles of the Web Content Accessibility Guidelines:](https://www.w3.org/TR/UNDERSTANDING-WCAG20/intro.html#introduction-fourprincs-head)

1. **Perceivable** - Information and user interface components must be presentable to users in ways they can perceive.
   * This means that users must be able to perceive the information being presented \(it can't be invisible to all of their senses\)
2. **Operable** - User interface components and navigation must be operable.
   * This means that users must be able to operate the interface \(the interface cannot require interaction that a user cannot perform\)
3. **Understandable** - Information and the operation of user interface must be understandable.
   * This means that users must be able to understand the information as well as the operation of the user interface \(the content or operation cannot be beyond their understanding\)
4. **Robust** - Content must be robust enough that it can be interpreted reliably by a wide variety of user agents, including assistive technologies.
   * This means that users must be able to access the content as technologies advance \(as technologies and user agents evolve, the content should remain accessible\)

## Keyboard navigation

Some people can't use a mouse and navigate through websites using tools such as a keyboard, mouth wand, or eye-tracking system. People should be able to navigate with a keyboard or screen reader. Make sure anything that can be seen by hovering with a mouse is also accessible to keyboard focus and screen readers.

When using the website, check if a keyboard can be used to:

* navigate
* perform the same tasks as people who use a mouse
* locate where you are on the page
* tell where the keyboard focus is

### Manage focus

Keyboard focus follows the page as the eye would scan it. Focus travels top to bottom, left to right, moving from most to least important item. People can navigate applications using alternative input methods \(D-pads, trackballs, keyboards, and navigation gestures\), and the focus flows in a logical order.

When assessing keyboard focus:

* Create Noticeable `:focus` Styles
* Use Non-Color Designators for Links
* Use Native Control Elements
* Indicate where focus is

### Validate forms inline

Validate forms inline so keyboard users don't have to navigate far to get feedback.

Ideally, design interactions to prevent errors happening in the first place and help people fix problems as they occur.

