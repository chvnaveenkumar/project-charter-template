# Project Charter: Code Word (Team C)

This is the project charter for the Code Word.
This application will be delivered as a web application. (e.g. web, iOS, Android)

- [View Published Version](https://chvnaveenkumar.github.io/project-charter-template)
- [Source Code](https://github.com/chvnaveenkumar/project-charter-template)

Update the links above and add team name, year, semester, course, or other important project information

## Client

Clients include:

- Dr. Charles Hoot, hoot@nwmissouri.edu

## Mentor

Mentors include:

- Dr. Denise Case, dcase@nwmissouri.edu

## Collaborator

Collabrators include:

- Naveen Kumar Chandaluri, s530742@nwmissouri.edu
- Shivani Reddy Dodla,s531496@nwmissouri.edu
- Sreelekha Vijaya, s531382@nwmissouri.edu
- cherukuru Chaithanya,S531495@nwmissouri.edu

## Project Purpose

Creating Progressive Web Application for confidential codewords to each student in a course.

## Benefits

1. Instead of printing out a separate codeword and distributing it among the students, the process is automated which will generate the codewords for all the students in a particular course.
2. It is generating the new codeword each time a student enrolls the course.
3. It makes it easy for the student as they need not memorize the codeword.

## User Roles

This application is used by students.

1. Administrators
2. Professors
3. Students

## Stories by Role

**Administators**
1. Admin should be able to login the website.
2. Admin can grant access to student and instructor.
3. Admin can approve any changes made by the instructor.

**Students**
1. Student should be able to login the website.
2. Student can need to select the course to get the codeword.

**Instructor**
1. Instructor should be able to login the website.
2. Instructor can add new course and upload excel sheet with student details (student ID’s, names and course ID) for each course.
3. Instructor can delete the existing course for students if needed.

## Team Organization

This team is organized as follows.

|                        | Primary   | Secondary   | Content |
| ---------------------- | --------- | ----------- |---------|
| Team Lead              |    Naveen |  Shivani    | Repo, intro, budget, schedule, risk, coordination   |
| Architect              | Chaitanya |  Sreelekha  | E-R diagram |
| Data                   |  Sreelekha|    Naveen   | Sample data |
| UX                     | Shivani   |    Naveen   | Sketches  |
| Testing & Acceptance   |   Wendy   |   Sreelekh  | Stories, acceptance criteria |

## Scope

### Phase 1 - Conception and initiation (Module 1)

Phase 1 will include the development of a detailed Project Charter to be presented in Markdown with in-line images and tables (not Word). It will include at least the following sections.

* Overview
* Purpose
* Benefits
* Stories
* scope 
* User experience sketches
* E-R diagram
* Sample data
* Risks and assumptions

Deliverables:

- Project charter
- Supporting artifacts (as described in this document)
- Contract (link - the contract will reference this charter and supporting documents)

This phase includes the development of:

- Initial acceptance criteria (link)
- [E-R diagram](https://github.com/chvnaveenkumar/project-charter-template/blob/master/Documentation/Entity%20Relationship%20Diagram%20for%20CodeWord%20Project.pdf)
- [Sample Data](https://github.com/chvnaveenkumar/project-charter-template/blob/master/Documentation/Database%20Tables.xlsx)
- [Project Sketches](https://github.com/chvnaveenkumar/project-charter-template/blob/master/Documentation/Modified%20Sketches.pdf)
- For each phase, initial scope, schedule, budget (included in this document)
- [RFP Document](https://github.com/profcase/rfp-codewords/blob/master/index.md)

## sample table

Student Table

|Student ID	|Course ID	|Student Name   |Codeword         |
|-----------|----------|---------------|-----------------|
|S531482	   |CSE1023	  |WILLIAM	       |Whale_ Blue      |
|S531483	   |CSE1024	  |JOHN	          |Shark_ whale     |
|S531484	   |CSE1025	  |GEORGE	        |Elephant_ African|
|S531485	   |CSE1026	  |THOMAS	        |Elephant_ Indian |
|S531486	   |CSE1027	  |ARTHUR	        |Giraffe_ male    |
|S531487	   |CSE1028	  |JAMES	         |Mule             |

Login Table

|UserName	  |Password	|Status |
|-----------|---------|-------|
|WILLIAM	   |MARY	    |s      |
|DAVID	     |ANN	     |s      |
|BRIAN	     |JEAN	    |s      |
|DAVID	     |ANN	     |s      |
|JAMES	     |SUSAN	   |s      |

### Codewords
Africa 

Almond

Anger

America

Bravo

Bank

### Phase 2 - Definition and planning (Module 2 and 3)

During Phase 2, the best parts of each platform-specific charter will be used to create a single, 
consolidated charter that allows different platforms to share fundamental aspects such as the E-R diagram and 
sample data.

Deliverables:

- Combined project charter
- Integrated supporting artifacts (taking the best from Phase 1)

Include:

- Final stories by role (see above)
- Final acceptance criteria (see above)
- Final E-R diagram (link)
- Detailed project sketches by platform (link - images must be displayed)
- Architectural decisions, including platforms, languages, frameworks, libraries, cloud resources, data stores, releases, milestones, authentication, authorization, responsive supports, progressive supports, security, performance requirements, traditional or SPA, client-side rendering vs server-side rendering, REST vs GraphQL, web vs native vs hybrid, etc.
- List of projects with versions in JIRA
- Schedules for sprints, client presentations, milestones and acceptance criteria in JIRA
- Construction of product backlogs built from epics, stories, tasks, and subtasks in JIRA

### Phase 3 - Implementation of architectural prototypes (Module 4 and 5)

During Phase 3, new teams will be defined to work in parallel (again in friendly competition) to build platform-specific architectural prototypes to identify any major issues with the plan. 

Deliverables:

- Updated versions of all artifacts
- JIRA management system
- Working prototype deployed in each proposed platform
- Presentation of architectural prototype to client and extended team (include pros & cons of these choices).
- Together with the client decide what platform(s) will be selected for implementation.
- Client acceptance of the plan

### Phase 4 - System requirement specification (Module 6)

Based on the results and lessons learned during the architectural prototypes, finalize the requirements to be used during the coming implementation phase.

Finalize implementation plan (including all remaining phases along with scope, schedule, and budget by phase).

Deliverables:

- Complete implementation plan for next semester.
- Suggested project organization for next semester.
- Signed acceptance by the client with comments.

## Out of scope

The following items are specifically not included in this scope of work:

- We can access the application offline once the webpage is loaded in the browser.
- If we have the appropriate resources and time, we will deploy it into the canvas.

## Schedule

The following general schedule will be followed:

Phase1:

Following are the tasks completed in week 1:
- Created repository and collaborated with the team members.
- Analyzed Scope of the project
- Designed ER diagram
- Populated Sample data
- Benefits of the project
- Added project related documents into the cloud repository

Following are the tasks need to be completed in week 2:

- Reviewing and modifying the documents if needed.
- Meeting the client to know the requirements of the project.


- Phase 2 completed and presented at the end of week 7.
- Client feedback and updates completed at the end of week 8.
- Phase 3 completed and presented at the end of week 12.
- Client feedback and updates completed at the end of week 13.
- Phase 4 finalized and published at the end of week 14.
- Client feedback and updates completed at the end of week 15.
- Project reflections and discussions completed during week 16.

You will develop the schedule for next semester as part of this work. 

The complete schedule is shown in the following Gantt chart:
- Display or link to the current project Gantt chart 
- Schedule by work tasks by phase
- Include through final implementation (next semester)
- Include durations, dependencies, and key milestones

## Budget

Bill estimation of phase1 for two weeks:

 1. For the first week:
     - Number of hours worked - 16
     - Wage rate per hour- $70
     - Total bill for the first week = $ 1,120

2. For the second week:
    - Number of hours worked- 15
    - Wage rate per hour - $70
    - Total bill for the second week = $ 1,050

## Risk

- Inadequate funding from the client.
- Conflicts between the team members.
- Delay of project completion due to unavailability of resources.

## Acceptance criteria

- For each story, enumerate and clearly describe the acceptance criteria. 
- Be specific - your client may have a very different definition of vague words. 

<<<<<<< HEAD
## sample table

### Student Table
|Student ID	|Course ID	|Student Name   |Codeword
|-----------|-----------|---------------|--------|
|S531482	|CSE1023	|WILLIAM	    |Whale_ Blue
|S531483	|CSE1024	|JOHN	        |Shark_ whale
|S531484	|CSE1025	|GEORGE	        |Elephant_ African
|S531485	|CSE1026	|THOMAS	        |Elephant_ Indian
|S531486	|CSE1027	|ARTHUR	        |Giraffe_ male
|S531487	|CSE1028	|JAMES	        |Mule

### Login Table
|UserName	|Password	|Status
|---------- |---------- |------|
|WILLIAM	|MARY	    |s
|DAVID	    |ANN	    |s
|BRIAN	    |JEAN	    |s
|DAVID	    |ANN	    |s
|JAMES	    |SUSAN	    |s

### Codewords
Africa 

Almond

Anger

America

Bravo

Bank
=======

>>>>>>> 719357db391da2a50204b48f68b33df204c549a7
