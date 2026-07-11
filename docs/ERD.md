# ERD

## Purpose
This document outlines the primary data entities expected in the EduSphere platform.

## Core Entities
- Users
- Roles
- Courses
- Modules
- Lessons
- Enrollments
- ProgressRecords
- Assessments
- AssessmentSubmissions
- AuditLogs

## Relationship Summary
- A user can have one or more roles
- A course contains modules
- A module contains lessons
- A user can enroll in many courses
- A course can have many enrollments
- Progress records track user activity against course content
- Assessments can be associated with courses or modules

## Design Notes
- Use stable identifiers for all entities
- Separate transactional data from reporting views where practical
- Keep audit data append-only when possible
