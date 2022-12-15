# GMail_OTP


First Go To ==> https://console.cloud.google.com/  Then
Create A New Project  ==>


      Click on Select A Project
      Click on New Project
      Give A Project Name 
      Leave Location to No Organization
      CLICK ON CREATE BUTTON

Now Select The Created Project and Search GMAIL API in Search Box
and Select the Gmail API from Marketplace

Click On Enable API (Wait For API to Enable)

Setup Credentials ==>

      Click on Credentials Tab from Left Menu
      Click On Create Credentials 
      Select Help Me Choose
      Select Gmail API in Select API Box
      Click On Add or Remove Scopes and search GMAIL API
      
and select the options -> https://mail.google.com/
 				  ./auth/gmail.modify
  				  /auth/gmail.compose
                          /auth/gmail.readonly
                          /auth/gmail.metadata
                          /auth/gmail.insert
                          /auth/gmail.send
                          /auth/gmail.labels
            after selecting all above options click on update

Now Click On Save And Continue

Now Select Desktop App In Application Type
Assign Desktop Project Name

Now Download the File 

Process Done For API SetUp

go to ==> https://developers.google.com/gmail/api/quickstart/java
 and use the code

 **In Java ==> Set Application Name to Your Application Name

Change The Subject Name in below Line To Get Email By Using it's Subject -->
            
            Change 'Gmail Api Test' To Subject Name That You Want To Get

            HashMap<String, String> hm = getGmailData("subject:Gmail Api Test");
      
 

