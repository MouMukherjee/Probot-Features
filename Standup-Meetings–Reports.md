 # Standup Meetings – Reports

The main purpose of scrum reports is to collect and analyze data along the way to accomplishing the right project, at the right time using minimum iterations.

The actual process is initiated by typing this command- ‘scrum start’. As soon as a member writes this command in the channel, the daily stand-up meeting resumes. During a stand-up, Probot asks a set of questions to each active participant. The questions are:

• What did you do yesterday?

• What will you do today?

• Any roadblock?
 
 After the stand-up is concluded, Probot collects the data and sends reports to relevant recipients. There are various ways to retrieve scrum reports which we will learn today.
 
## Scrum Log
Scrum log helps to keep track of time. After every successful stand-up, Probot broadcasts the scrum log on the channel. Scrum log is the summary of the scrum duration. It calculates the time and duration of an entire session, compares with previous day’s log and broadcasts the same.

Ideally, daily stand-ups should not take more than 15 minutes and scrum log ensures the team is doing just that. In rare circumstances, if your team has taken more than the allotted time, it would track and trace time consumption both at an individual and team level, giving you a scope to improve time management and be more productive at work. 

## Retrieval of Reports
Details of the responses logged in during the stand-up are always visible on the channel so that every member stays on the same page. Additionally, Probot sends DM and digest emails to the members in the lead roles; as a result, the team leaders, managers, and product owners stay up-to-date. To view or edit privileges, please visit the settings tab.

**1.Scrum Digest DM**

Probot shares Scrum Digest DM (Direct Message) to authorized channel members. In this process, Probot combines the responses of all the stand-up attendees and triggers DM on Slack. 

**2.Scrum Digest Emails**

Other than DM, Probot also sends Scrum Digest Emails to designated people. Digest emails include individual entries and stats. To enable this service, the members need to have their preferred email IDs registered on Slack and should be authorized to receive digest emails from Probot.    

**3.View Report from Dashboard**

Want to view reports from an individual member? Probot has got you covered. In order to view entries from individual participants for a given date:

•	Go to dashboard and then to ‘Reports’. 

•	Type the name of a member in the ‘User’ section. 

•	Select the start and end date. 

•	Click on “Go”.

**4.Use Commands**

There are two commands to help you fetch scrum reports. 

If you want to retrieve a report of an individual member using the command prompt, follow the instructions: 

•	Write scrum start followed by the name of the user and channel name in this format- scrum report [@user] [Channel-Name]. 

•	To view a report of a member for a particular date, type scrum report, followed by a username, channel name, and the date in this given format- scrum report [@user] [Channel-Name] [date]. 



