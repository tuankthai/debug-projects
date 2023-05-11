## Bugs to fix:

HTML Bug: The closing `</h1>` tag is missing in the HTML code. Add the closing tag `</h1>` before the `<div>` tag to fix the bug.

CSS Bug: The background color of the body is set to "lightblue" in the CSS, but it should be "white". Change background-color: lightblue; to background-color: white; to fix the bug.

JavaScript Bug: The JavaScript function changeColor() is trying to access the content element using getElementById('content'), but the HTML code doesn't have an element with the id "content". Add the id attribute to the `<div>` tag as follows: `<div id="content">` to fix the bug.

After fixing these bugs, the app should display a heading, a paragraph, and a button. Clicking the button should change the color of the paragraph text to green.
