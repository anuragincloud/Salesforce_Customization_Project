# Salesforce_Customization_Project

# Project Overview
This project demonstrates the creation and customization of various Salesforce objects and automations to enhance data management and business workflows. The project includes object and field creation, validation rules, workflow rules, and a flow for case creation to streamline operations in an educational environment.

# Features
Custom Objects:

Course: Tracks details about various courses, including course name, duration, instructor, etc.

Subjects: Manages subject-specific information such as subject name, number of modules, and instructor.

Course Leads: Stores details about leads interested in courses, including contact information and lead rating.

Technology: Tracks technology used in courses, including instructor availability and rating.

Custom Fields:

Added a variety of fields to each object, such as course duration, priority, lead amount, instructor contact details, etc.

Validation Rules:

Ensured data integrity by enforcing non-empty fields for all required attributes in each object, preventing incomplete data entries.

Workflow Automation:

Created workflow rules to automatically update records:

If a course's priority is marked as "High", the course name is updated to include "High Priority".

If a lead's amount exceeds $1000, the lead's name is updated to include "Top Priority Customer".

Flow for Case Creation:

Developed a flow allowing users to easily create support cases by entering essential information like name, course enrolled, subject, and query description.

# Installation and Setup

1.Salesforce Org Setup:

Ensure you have a Salesforce Developer or Sandbox Org.

Clone the repository or download the code.

2.Deploying Objects:

Use Salesforce Setup to create custom objects: Course, Subjects, Course Leads, and Technology.

Add the specified fields to each object.

3.Creating Validation Rules:

In Salesforce Setup, create validation rules for each object to ensure required fields are not left blank.

4.Setting up Workflow Rules:

Implement workflow rules for automatically updating course names and lead priorities based on specified conditions.

5.Building the Flow:

Use Flow Builder to create a case generation flow, allowing users to input case details and streamline support processes.

