# Project-Management-Dashboard
### A Project Management and Timecard Dashboard built with Microsoft Power Suite

### Tools utilised:
  Microsoft Power Apps
  Microsoft Dataverse
  Microsoft PowerAutomate
  Microsoft Teams PowerBI Integration

## Home Screen
(home.png)
###### The home screen displays a list of scrollable Open Projects [Click each project to get to more project info] and a quick display of all of the user's input hours for the current week. Automatically calculates up to date Regular Time, Overtime, PTO, and Holiday time input.

## Timesheet
(timesheet1.png)
###### The timesheet page is where users can enter the timepunches for the week. You can change the week in the top left, but will automatically land on the current week when you visit the page. You add a row for each project, with a dropdown of all currently open projects and standard time types. Users can enter time in the boxes shown in the row as a placeholder for total time per project per day. Users will then click the "clock" icon for the project to break-down their hours as seen below.
(timesheet2.png)
###### These hour breakdowns are required to be filled out. These hours are what the timesheet/payroll/project hour tracker is calculated off of. This feature was a client requested feature.

## Reimbursement
(Reimbursement.png)
###### Users can add in reimbursement requests for miles traveled, tolls paid, parking paid, and other work-related expenses. The total is calculated per month for the user, and the weekly totals per employee are displayed to the payroll manager on the payroll page. When the amount has been paid, the payroll manager can mark the reimbursement paid which will show up to the user in a read-only format.

## Summaries
(By Project.png)
###### Users can pick a project and see their hourly history broken down by category.
(By Week.png)
###### Users can review their weekly hours broken down by project, in the same manner the payroll manager would see their hours.

## Project Info
(project.png)
###### This is the main project information page. Lists of all projects are seperated by various categories to the left, which can be further filtered by Project Stage in the dropdown selector. A CSV of the filtered project list can be downloaded and opened by clicking the export buttons. Project information will show up on the right. Different fields are able to have different edit access roles based on user role, defined by the client. By clicking "Project Management for .....", a button only visible to administrators, admins can view and edit further project information which includes budget information and market segment information.

## Project List
(project list.png)
###### A condensed list of all projects maintained on the dashboard. Clicking on a project in the list will navigate to that project's Project Info sceen (referenced above).

## Calendar
(calendar.png)
###### This dynamic calendar will show project dates based on the input dates on the project's Project Info. Clicking on a project in the calendar will navigate to that project's Project Info sceen.

## Admin Panel
(admin panel.png)
###### The admin panel is only accessible to administrators defined by the client. This page is where administrators enter a new project to be added to the dashboard, get to the Payroll section to view all employee's payroll (similar to a user's weekly summary but with the option to choose any user), and view project hour summaries. You can also adjust the hour breakdown types available to users from this panel.

## Project Totals
(project totals.png)
###### The Project Totals page allows admins to view hour summaries for certain projects and compare the budget with employee rates. By selecting a project, you can choose an individual in the top middle section to see their hours in addition to the total hours broken down by work type in the top right. Budget information and employee rates are located at the bottom, along with the ability to filter all hours by a date range in the bottom left.
