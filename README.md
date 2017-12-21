# GoogleAPI-reader
This repository is meant for google api reader
The first step, towards reading this data, is to create a Google project account, at https://console.developers.google.com/permissions/serviceaccounts, using the menu at the top of the page. Use that project, to create a service account. It may be necessary to select a project, to view the required menu. Click on "create service account", and save the P12 file somewhere locally. Once you have created it - So, there is now a new project with a service account.

In a new tab, navigate to https://console.developers.google.com/apis/library and the library of APIs should be visible. Under the "Google Apps API", select Sheets API and enable it.

Give the service account read-only access to the Google Sheet, using the service account id for the email address. Using the Java client jars at https://developers.google.com/api-client-library/java/google-api-java-client/download


