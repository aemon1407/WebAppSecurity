Restaurant Booking Form
This repository contains files for a simple restaurant booking form, built using HTML, PHP, and JavaScript.

Files:
index.html: This file contains the HTML structure for the booking form. It includes form fields for name, phone number, total pax, and email. The form submission is handled by form.php, and client-side validation is done using form.js.

form.php: This PHP file receives the form data submitted from index.html. It validates the input data and returns appropriate error messages if any. Upon successful validation, it redirects the user to submit.html.

form.js: This JavaScript file contains client-side validation logic for the form fields. It checks if the input values meet certain criteria and displays error messages if validation fails.

form.css: This CSS file contains code that designs the appearance of the form.html page to make it look better visually.

submit.html: This file displays a confirmation message upon successful form submission. It is linked from form.php after successful validation.

