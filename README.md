# My-Daily-Summary-Power-Automate

My Daily Summary is daily digest sent to your inbox with a summary of your meetings for that day.  The Power Automate is scheduled to run once a day, every weekday.

Example of the digest

![image](https://user-images.githubusercontent.com/18420048/234805873-88ffea13-830a-4d59-8d90-4c5e1f22773f.png)

## Installation

1. Download the zip file
2. Go to [Power Automate](https://make.powerautomate.com/) in [Office.com ](https://www.office.com/)
3. Import the Power Automate from My Flow, Import Legacy
![image](https://user-images.githubusercontent.com/18420048/234807160-8063cd6d-37b0-43cb-9cea-8f3832f92ce9.png)
4. Browse for the zip file and click upload
![image](https://user-images.githubusercontent.com/18420048/234807475-ae4f39cf-a77f-4d46-9e0c-0c4fae67a07d.png)
5. Once imported you will see this screen
![image](https://user-images.githubusercontent.com/18420048/234807988-6d9afed6-3611-4103-b07f-a93434d319cf.png)
6. Click Select During Import to create the neccesary connections for the Power Automate to function.
7. If this is your first time using Power Automate then you may need to create the connection.  If this isn't your first rodeo then you can re-use previous connections.  The below is an example screen of connection selection.
![image](https://user-images.githubusercontent.com/18420048/234809324-5ce30966-8e5a-436c-96a2-a7f8abd6022b.png)
8. Once the connections have been configure then you can import the Power Automate
![image](https://user-images.githubusercontent.com/18420048/234809574-a43e0a4b-6c83-47df-9d17-f4b971bf2c75.png)
9. Once imported successfully, you will need to config it to:
* What time of day you want the digest
* Which calendar to read
* Which email account to send from
10. To change the frequency of the digest click Recurrance
11. Click on the Get calendar view of events (V3) to expand the connector to select the calendar to read.  When you first open it, it will look like the below.  Click on the X to clear out the string of letters and numbers.  After doing so, you should see a list
![image](https://user-images.githubusercontent.com/18420048/234811329-b56a7739-5196-45d3-a5e5-d370904aa79d.png)
![image](https://user-images.githubusercontent.com/18420048/234811527-bb39c9fb-1b5f-4612-87b5-6bbfd4470149.png)
12. The final stage is configure the email account to send you the digest.  In my example I have used a shared mailbox.  If you don't have access to a shared mailbox, you can change the connector to either send an email or send an email (Outlook).
![image](https://user-images.githubusercontent.com/18420048/234816790-5c0fb6cb-a0c3-4c9e-b1b1-07980ec3eeb8.png)

If you want to customise what information is in the digest, simply add the relevant fields into the HTML table.



