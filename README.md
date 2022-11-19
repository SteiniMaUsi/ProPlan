# DepartmentPlan
A simple project plan UI for resources and projects

# Requirements
## File Format
- Excel is the most often used tool in companies. -> The file format shall be directly importable into Excel - Minimum Requirement is Excel 2010.
- The file format shall be directly user-readable and well-formatted <!---(weak requirement - further describe well formatted?)--->
## Resources view
- There shall be an overview page as per resources (people and/or hardware)
## Project Planning view
- There shall be a project planning page
- It shall be possible to have multiple projects
- It shall be possible to import or add vacation or absence of a resource
- The project plan shall be divided into a side pane and a main pane.

### Project Planning Main pane
- The main pane shall essentially be a calendar.
- The calendar shall have the following separation
    - Year
    - Month
    - Calendarweek
    - Numeric Day in the month
    - Weekday
### Project Planning Side pane
- The side pane shall contain all necessary information to create the data to be displayed in the main pane
- The side pane shall be hideable.
- In a separated side view, in one row, there shall be the following information :
    - Title
    - Effort estimation
    - Start or End Date
    - Link to the Ticket
- The side view

## Burn Down Chart
- Lets have a directly creatable burn down chart, based on the project plan and JIRA information
## Data
- There shall be a page to set up resources (people/hardware)
- There shall be 