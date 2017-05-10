# QR attendance on Google Sheets

This webpage contains a form to submit data into a Google Spreadsheet
based on [a 2014 blog post][mha14] and its [2011 predecessor][mha11].

## Prerequisites

For a webserver, I've used Python's SimpleHTTPServer, as I'm familiar
with it. Run the server on port 5000 within this directory:

    $ python -m SimpleHTTPServer 5000

To test this with your own Google Spreadsheet, you need access to the
Sheets API so that you can get a client ID from the Developer Console.
This value needs to be updated in `js/submitform.js`.

Make sure the correct port is allowed for API access.

I also used `jquery 3.2.1`.

[mha14]:https://mashe.hawksey.info/2014/07/google-sheets-as-a-database-insert-with-apps-script-using-postget-methods-with-ajax-example/
[mha11]:https://mashe.hawksey.info/2011/10/google-spreadsheets-as-a-database-insert-with-apps-script-form-postget-submit-method/
