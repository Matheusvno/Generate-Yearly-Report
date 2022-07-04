# Calculate-Client-Security-Hash

Generate Yearly Report Dispacher and Performer for UiPath Course.

Steps performed by the Robot:

<ol>
<li>
Open the ACME System 1 Web Application.
</li>
<li>
Log in to System 1. Required input data: email and password.<br>
</li>
<li>
Access the Dashboard - the central location, where the user can pick a specific menu item.<br>
</li>
<li>
Access the Work Items listing to view all the available tasks to be performed (Output data: list of tasks).<br>
</li>
<li>
For each activity of type WI4, perform the following steps:
</li>
</ol>
  <ul>
  <li>
  Open the Details page of the selected activity to retrieve the Vendor Tax ID (Output data: Tax ID).
  </li>
  <li>
  Go back to the Dashboard and access the Download Monthly Report section in the Reports menu.
  </li>
  <li>
  Fill in the Vendor Tax ID and download all the monthly reports for previous year.
  </li>
  <li>
  Group the downloaded monthly reports into a single Excel file with the naming convention
  “Yearly-Report-[Year]-[Tax ID].xlsx”.
  </li>
  <li>
  Upload the resulting yearly report file in the “Upload Yearly Report” section in the Reports menu.
  </li>
  <li>
  Fill in the Vendor Tax ID, set the year, and select the file on your hard drive. This will return a unique upload ID.
  Output: Upload ID.
  </li>
  <li>
  Go back to the Work Item Details page and select Update Work Item.
  </li>
  <li>
  Set the status to “Completed”. Add the following comment: “Uploaded with ID [Upload ID]”.
  </li><br>
  </ul>
 <ol>
