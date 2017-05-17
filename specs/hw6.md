# Homework 6: Processing Form Input

It's time to handle your form input using the techniques discussed in class. You
should already have your forms on your site, but they aren't being used. In this
assignment, you will process user input and sanitize the data to prevent XSS
attacks. Then, you will store the data into your database in the next
assignment.

## Learning Objectives

* Process form input.
* Validate user input.
* Sanitize data to prevent XSS.

### Requirements

You should already have at least some of your forms on your page. You must have
at least registration and log in forms and any other forms from your mock-up.

- [ ] Usability. If you didn't already, add labels to all of your form input elements.
This makes it easier to bring focus to the form element because the user can
click on the label or the field to gain focus.

- [ ] Form submission. Decide whether to use `GET` or `POST` for each form submission.

- [ ] Post/Redirect/Get. Avoid form re-submission by directing the form action to a
separate PHP handler. When you are done processing the data, redirect the user
as necessary.

- [ ] Process form data. Use the global `$_GET` and `$_POST` arrays to retrieve form data
in PHP.

- [ ] Sanitize data. Sanitize all input. If you’re going to display data in HTML, make
sure it’s properly escaped.

- [ ] Validate data. Validate any email addresses, dates, etc. Use at least one
regular expression to validate one of the form inputs. Validate data even if
options are restricted (i.e. select, radio, etc. need validation too).
Presets. If any form data is incorrect when the user submits the form, DO NOT
let the form fields clear when re-directing the user back to the original page.
Use a session for persisting the input across pages. Fill out the form with
previously entered data and give the user a chance to fix their input.

- [ ] Error messages. Display a proper error statement to the user to indicate any
incorrect fields. Use a session for persisting the error messages across pages.
Make it obvious to the user if they missed anything required. Optionally, for a
better user experience, change the color of the input element with the bad data
using CSS.

