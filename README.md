# JobTrackr - JavaFX Job Application Tracker

JobTrackr is a desktop application built with Java, JavaFX and SQLite to help job seekers organize their job applications, recruiter contacts, follow-ups and interview progress.

## Problem

When applying to many jobs across LinkedIn, company websites, email and job boards, it becomes difficult to track where you applied, which CV version you used, who contacted you, when to follow up and what the current status is.

## Solution

JobTrackr centralizes all job applications in one place and helps users track applications, recruiters, follow-up dates, salary ranges, remote/hybrid preferences and notes.

## Features

- Add, edit and delete job applications
- Track application status
- Store recruiter/contact information
- Filter by status, work mode and platform
- Detect pending follow-ups
- Export applications to CSV
- Local SQLite database
- JavaFX desktop interface

## Technologies

- Java 21
- JavaFX
- SQLite
- JDBC
- Maven
- Git

## What I practiced

- Object-oriented programming
- CRUD operations
- SQL database integration
- JavaFX UI development
- Form validation
- Functional testing
- Clean Git workflow
- Technical documentation


src/main/java/com/pelayo/jobtrackr/

│

├── MainApp.java

├── controller/

│   ├── ApplicationController.java

│   └── DashboardController.java

│

├── model/

│   ├── JobApplication.java

│   ├── ApplicationStatus.java

│   ├── WorkMode.java

│   └── CvType.java

│

├── dao/

│   └── JobApplicationDAO.java

│

├── database/

│   └── DatabaseManager.java

│
├── service/

│   └── JobApplicationService.java

│

└── util/

    ├── CsvExporter.java
    
    └── DateUtils.java
