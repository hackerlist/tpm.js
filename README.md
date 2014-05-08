tpm.js
======

Towards better Time & Project Management.

## Design Considerations

Zero clicking.
- hjkl, arrows, and wasd navigates between elements and contexts

ubiquitous components CRUD
- create/update components from any view

## Data Visualizations

The initial 0.1.0 release will include three d3 based visualizations:

* Productivity Burndown Chart
* Gantt Chart - show one's target progress, actual progress, and projected deadline
* Network: Priority, Density / Volume

Each visualization should be zoomable within the context and
granularity of each component: i.e missions, phases, milestones,
tasks, issues

### Burndown

### Gantt

### Network

## Components Heirarchy

Missions - A campaign towards a goal or objective key result

Phases - A continuous commitment which occurs during an alotted period of time

Milestones - A collection of work representing quantifiable progress / discrete OKRs towards the completion of a phase

Tasks - Comprehensive encodings of discrete units of work

Issues - A Qualifier/Modifier which documents problems within, and specifies necessary (unplanned) adjustments to, Tasks

### Missions

### Phases

### Milestones

### Tasks

### Issues, Tests

An issue is always associated with (quantifies) a task, otherwise it is a task.
