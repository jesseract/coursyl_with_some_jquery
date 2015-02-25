For this assignment, you will continue to modify Coursyl, an existing open source application. This application has a course detail page which lists (among other things) all the assignments for the course. Each assignment has two dates: starts_on and ends_on. Although the application has a page for editing an assignment, dates shift like crazy due to snow days. The users would like a quick way to edit just the start and end dates on an assignment.

You must add the following JQuery functionality to this page:

-Refactor all of your existing Javascript code to use JQuery.
-Add a link (which looks like an icon) to each row of the assignments table. -Choose an icon which seems reasonable for changing dates.
-When the user clicks on that link, they should NOT leave the page. They should see a modal popup appear hovering over the page, and it should have two fields: starts_on and ends_on.
-There should also be a button for submitting this modal form. On submit, it is fine if the page loads. Feel free to submit this form to assignments/update.
-The date fields should not be simple text fields. Instead, when you place the cursor in the box, it should display a visual calendar nearby and allow you to pick a date from it.
-Note that this application currently uses Bootstrap 2. Bootstrap has modal functionality built into it, so you should use those components to create this modal. Also note that Bootstrap 2 has Fontawesome built into it, so you should use that font set to pick out an icon for the link to the modal.
