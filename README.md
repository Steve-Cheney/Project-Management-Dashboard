# Project-Management-Dashboard
### A Project Management and Timecard Dashboard built with Microsoft Power Suite

### Tools utilised:
    Microsoft Power Apps
    Microsoft Dataverse
    Microsoft PowerAutomate
    Microsoft Teams PowerBI Integration

#### Scope of Project
The Client wanted to move from Excel spreadsheets that tracked employee payroll to a more in-depth system where they could not only easily track payroll, but also track Project status, completion, and time-spent. This Dashboard provides the Client an easy way to have their employees enter time worked and view all relevant data from thoese punches. This dashboard offers a low-maintenance solution, low upkeep cost, and high customizability.


#### Work Flow
The MS PowerApps app connects to Microsoft Dataverse, a proprietary DBMS system that is integrated into the MS Power Suite. It is an SQL-like relational platform that allows for querrying, views, and security roles. The GUI run through PowerApps connects to custom relational tables hosted on Dataverse. Querries to Dataverse return dynamically updated results to the GUI in real-time and to any amount of users. This allows for multiple users to run the App through a seamless MS Teams interface, where Teams hosts the app run-time.

## Home Screen
![Home](https://user-images.githubusercontent.com/29099473/203427140-76321a1f-c7c2-4e75-a0ef-7c4195e95317.png)

###### The home screen displays a list of scrollable Open Projects [Click each project to get to more project info] and a quick display of all of the user's input hours for the current week. Automatically calculates up to date Regular Time, Overtime, PTO, and Holiday time input.

## Timesheet
![Timesheet 1](https://user-images.githubusercontent.com/29099473/203427177-151e6d07-345a-46f6-a38f-876ec679814f.png)

###### The timesheet page is where users can enter the timepunches for the week. You can change the week in the top left, but will automatically land on the current week when you visit the page. You add a row for each project, with a dropdown of all currently open projects and standard time types. Users can enter time in the boxes shown in the row as a placeholder for total time per project per day. Users will then click the "clock" icon for the project to break-down their hours as seen below.
![Timesheet 2](https://user-images.githubusercontent.com/29099473/203427206-8f07920c-ffad-4399-af11-bc4dfb4e7d8a.png)

###### These hour breakdowns are required to be filled out. These hours are what the timesheet/payroll/project hour tracker is calculated off of. This feature was a client requested feature.

## Reimbursement
![Reimbursement](https://user-images.githubusercontent.com/29099473/203427236-b128caa3-1d06-4dd5-b8bf-606199fa5f34.png)

###### Users can add in reimbursement requests for miles traveled, tolls paid, parking paid, and other work-related expenses. The total is calculated per month for the user, and the weekly totals per employee are displayed to the payroll manager on the payroll page. When the amount has been paid, the payroll manager can mark the reimbursement paid which will show up to the user in a read-only format.

## Summaries
![By Project](https://user-images.githubusercontent.com/29099473/203427283-7ae0be7e-bd88-429b-a46e-b18d3b902e50.png)

###### Users can pick a project and see their hourly history broken down by category.
![By Week](https://user-images.githubusercontent.com/29099473/203427312-eb848b60-b994-467e-a7c8-12ac998b0de5.png)

###### Users can review their weekly hours broken down by project, in the same manner the payroll manager would see their hours.

## Project Info
![Project](https://user-images.githubusercontent.com/29099473/203427331-75c888d9-5263-49ea-95ce-dab53660beb2.png)

###### This is the main project information page. Lists of all projects are seperated by various categories to the left, which can be further filtered by Project Stage in the dropdown selector. A CSV of the filtered project list can be downloaded and opened by clicking the export buttons. Project information will show up on the right. Different fields are able to have different edit access roles based on user role, defined by the client. By clicking "Project Management for .....", a button only visible to administrators, admins can view and edit further project information which includes budget information and market segment information.

## Project List
![Project List](https://user-images.githubusercontent.com/29099473/203427361-75b51298-d4a6-4b4f-8062-1e086b60452a.png)

###### A condensed list of all projects maintained on the dashboard. Clicking on a project in the list will navigate to that project's Project Info sceen (referenced above).

## Calendar
![Calendar](https://user-images.githubusercontent.com/29099473/203427389-17b7a499-eb83-46f3-b12b-4c24743189cc.png)

###### This dynamic calendar will show project dates based on the input dates on the project's Project Info. Clicking on a project in the calendar will navigate to that project's Project Info sceen.

## Admin Panel
![Admin panel](https://user-images.githubusercontent.com/29099473/203427402-6aa56850-de83-41a3-a616-a101c80334bc.png)

###### The admin panel is only accessible to administrators defined by the client. This page is where administrators enter a new project to be added to the dashboard, get to the Payroll section to view all employee's payroll (similar to a user's weekly summary but with the option to choose any user), and view project hour summaries. You can also adjust the hour breakdown types available to users from this panel.

## Project Totals
![Project Totals](https://user-images.githubusercontent.com/29099473/203427439-396887fd-0652-4898-8faf-77be97009f46.png)

###### The Project Totals page allows admins to view hour summaries for certain projects and compare the budget with employee rates. By selecting a project, you can choose an individual in the top middle section to see their hours in addition to the total hours broken down by work type in the top right. Budget information and employee rates are located at the bottom, along with the ability to filter all hours by a date range in the bottom left.
