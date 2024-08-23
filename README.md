C-ALPHA Project Management Software
Overview
C-ALPHA is a comprehensive project management software tailored for the construction industry. It is designed to address common challenges in managing construction projects, such as dependencies, deadlines, and resource allocation. The software integrates with other popular tools like Primavera P6 and offers a range of features to streamline project management tasks.

Features
Task Management: Efficiently manage tasks and their dependencies within your projects.
Time Scheduling: Create detailed schedules, including Gantt charts, critical paths, and lags.
Resource Allocation: Allocate resources effectively and monitor their usage with resource profiles.
Budget Tracking: Track planned budgets and compare them against actual expenditures.
Reporting: Generate detailed reports on project duration, critical activities, and resource consumption.
File Exporting: Export data to Excel (XLS), Primavera (XML), and PDF formats.
Calendar Integration: Assign events and meetings, and manage them through an integrated calendar.
Cash Flow Management: Monitor cash flows on a monthly and daily basis.
File Attachments: Attach and manage project-related files in PDF, JPG, and Excel formats.
Technologies Used
Front-End:

HTML
CSS
JavaScript, jQuery, Bootstrap
Back-End:

ASP.NET Core
ASP.NET MVC
LINQ
Database:

Local SQL Server Database
Entity Framework (EF)
Third-Party Libraries:

DHTMLX for Main Gantt Chart
Fusion Charts for Cash Flow and Resource Profile
AnyChart Library for Critical Path Gantt Chart
ClosedXml for Excel Operations

Installation
Clone the repository:
git clone <repository_url>

Restore dependencies:
dotnet restore

Update database connection:
Update the connection string in appsettings.json to point to your local SQL Server instance.

Build and run the application:
dotnet build
dotnet run

Usage
Task Management: Create tasks, define dependencies, and assign resources.
Scheduling: Use the Gantt chart to visualize and adjust your project timelines.
Resource Management: Allocate resources and monitor their usage throughout the project lifecycle.
Budgeting: Track and compare planned vs. actual budgets.
Reporting: Generate and export detailed reports on various aspects of the project.
Future Enhancements
Resource Leveling: Automatically adjust time schedules to fit specific resource limits.
Schedule Updates: Update schedules with actual work rates from executed activities.
Risk Analysis: Perform time and cost risk analysis with uncertainty calculations.
Mobile Application: Develop a mobile version of the application for on-the-go management and notifications.
Task Assignment: Assign tasks to users based on roles and restrict access accordingly.

License
C-ALPHA is free and open-source software. Feel free to contribute or modify it to fit your needs.

Acknowledgments
Ahmed Owis
Aya Tharwat
Fatma Alaa
Wesam Khaled
Thank you for using C-ALPHA!
