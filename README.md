# Supernova-test
To run this script please do the following steps:

Go to the Google Cloud Console (https://console.cloud.google.com/).

Create a new project or select an existing project.

Go to the "APIs & Services" -> "Credentials" section.

Click on "Create credentials" and select "Service account".

Follow the prompts to create a service account. You will be asked to provide a name, role, and other details.

After creating the service account, click on the newly created service account in the "Credentials" page.

Click on "Create key" and select "JSON" as the key type. This will download a JSON file containing the service account credentials.

Save the downloaded JSON file as "credentials.json" in the same directory as your Python script.

You need to replace "your_spreadsheet_id_here" with the actual ID of your Google Sheet. 

Make sure you have shared the Google Sheet with the service account email address. The service account email can be found in the credentials.json file under the key "client_email". Share the Google Sheet with this email address and grant it the necessary permissions (Editor in this scenario). 
