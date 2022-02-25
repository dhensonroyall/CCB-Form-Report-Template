# CCB-Form-Report-Template

This is a Google Sheets template with a Google Apps Scripts file
to get form details and responses from Church Community Builder (CCB) and populate into a Google Sheet, like a Google Form would.

Some form fields have been modified to meet the needs of our church.

The spreadsheet template can be viewed here: https://docs.google.com/spreadsheets/d/1otX5ypuX2YPT5SytTF2bsvObejFm5BXHBJ2V775hH3k/template/preview

The user would:
1. Paste in the form's URL into the setup sheet (any of the various URLs found in CCB)
2. From the "Update Form" menu, select "Update Form Responses Now"
3. If desired, set up a daily or weekly trigger or remove that trigger from the same menu

### Important ###
Note that the basic auth is hardcoded into the Apps Script file, so that will be accessible by anyone who has access to this file. You may want to create an API user with only a read form permission and/or add extra security measures.
