# Custom Google Form for Public File Upload
A Google Apps Script and associated HTML file, to generate a form which allows public uploading of file attachments.
It saves the attachment in a Google Drive folder.
It registers the answer in a Google Spreadsheet.
It sends a confirmation email to the submitter.
It shares the attachment with the submitter's email account.


Please note that I am a noob, and that some functions or variables have names in spanish.

## Notes
The GAS structure is based on this code https://ctrlq.org/code/19747-google-forms-upload-files.
I kept the handy validation function, which limits attachment file size and returns error information.

IMO, this code improves over the original in some ways:
The CSS and jQuery libraries have been updated, and list options styling from MaterializeCSS is used.
Validation works; pressing the submit button while leaving any invalid or blank field results in alerts.
The only thing I really would like to improve is the "uploading" part after submission. It does not seem to be very... robust.