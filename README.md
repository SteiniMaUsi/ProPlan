# DepartmentPlan

A simple department planner UI for resources and projects

# Dependencies

- Python 3.10
- Pyqt5

# Requirements


## File Format

- Excel is the most often used tool in companies. -> The file format shall be directly importable into Excel - Minimum Requirement is Excel 2010.
- The file format shall be directly user-readable and well-formatted <!---(weak requirement - further describe well formatted?)--->


## Resources view

- There shall be an overview page as per resources (people and/or hardware)
- This shall not be alterable - it shall be the outcome of the projects and peoples vacation


## Project Planning view

- There shall be a project planning page
- It shall be possible to have multiple projects (e.g. multiple project planning views)
- The project plan shall be divided into a side pane and a main pane.


### Project Planning Calendar pane

- The Calendar pane shall essentially be a calendar.
- The calendar shall have the following separation and in the following format
    - [CW], [M] [YYYY]
    - [D]
- Weekends shall be visible in a different colour


### Project Planning pane

- The Project Planning pane shall contain all necessary information to create the data to be displayed in the main pane
- The Project Planning pane shall be hideable.
- In a separated side view, in one row, there shall be the following information :

| Title (including Ticket Link if existing) | Effort estimation | Start Date | End Date
| --- | --- | --- | --- |
| [JIRA Ticket 1](http://justanexample.com) | 1w | 1.1.2021 | 20.1.2021


### Functionality

- Either the start date, the estimate or the end date shall be possible to calculate, based on the given information.
- If there is no information present, the possible missing information shall be identifiable (e.g write "input missing" into the field)
- The calculation of start date, estimate or end date shall include vacation, public holiday, absence and weekends

# Vacation planner
- It shall be possible to import or add vacation or absence of a resource
- Therefore a Vacation sheet (Tab) shall exist
- The Vacation Sheet shall look similar than the Project Planning Calendar pane
It shall look as follows:

| Vacation Plan |        |         |     |     |     | CW48 Nov 22  |     |     |     |     |     |     |
| ---       |        --- |     --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Last Name | First Name | Acronym | 20  | 21  |  22 | 23 | 24  | 25  | 26 | 27  |  28 |  29  |

- The cell width of the Day rows shall be as small as possible
- The Calendarweek, Month and year shall overlap other cells.
- The information of calendarweek, month and year shall be in a single cell
- The information of calendarweek, month and year shall be centered in the working week (Mo-Fr)
- The Information of Last Name, First Name and Acronym shall be coming from the Data pane

## Burn Down Chart

- Lets have a directly creatable burn down chart, based on the project plan and JIRA information
- No idea yet how to accomplish this!


## Data

- There shall be a page to set up resources (people/hardware)
- There shall be 