# Smart India Hackathon Workshop
# Date: 18/09/2026
## Register Number: 212224040260  
## Name: R RAIHAAN AHMED 
## Problem Title
Online Monitoring of Unauthorized Construction Across the City

SIH Problem Statement No.: SIH1618

Category: Software / Robotics & Drones
Problem Creator: Government of NCT of Delhi
Implementing Organization: Municipal Corporation of Delhi (MCD)

## Problem Description

Problem Description

MCD is working on monitoring unauthorized construction across the city and requires a viable and low-cost technological solution for effective monitoring.

Unauthorized construction can be difficult to identify and monitor continuously across a large urban area using conventional inspection methods. A web-based monitoring platform can help authorities collect reports, record construction locations, upload photographic evidence, monitor complaints, and track the status of verification and action.

The proposed solution provides a centralized web portal through which citizens and field officers can report suspected unauthorized construction using images, descriptions, and location information. The system provides an interactive map for visualizing reported locations and an administrative dashboard for authorities to verify, assign, monitor, and resolve cases.

The platform can also maintain historical records and generate analytics to identify areas with repeated unauthorized construction reports.

## Problem Creater's Organization
Government of NCT of Delhi

Implementing Authority

Municipal Corporation of Delhi (MCD)
## Idea
1. Citizen Complaint & Reporting Module

Citizens can report suspected unauthorized construction through the website.

Users can:

Register/Login
Upload construction images
Enter a description
Select the construction location
Submit a complaint
Receive a unique complaint ID
Track complaint status
2. Live Location & Interactive Map

The system uses location services to identify where the suspected construction is taking place.

An interactive map can display:

Reported construction sites
Pending complaints
Verified cases
Resolved cases
High-report areas

This allows authorities to understand the geographical distribution of complaints.

3. Image Upload & Evidence Management

Citizens and field officers can upload photographs of suspected unauthorized construction.

Each image can be stored together with:

Complaint ID
Date and time
Location
User information
Description
Verification status

This creates a digital evidence record for each reported case.

4. AI-Assisted Image Analysis

An optional AI module can analyze uploaded images to identify visible construction-related indicators.

For example, the system can assist in identifying:

Construction activity
Building structures
Construction materials
Changes between uploaded images

Important: The AI should act as an assistance tool, not as the final legal authority. Final verification should be performed by authorized officials.

5. Authority Monitoring Dashboard

Municipal authorities receive a centralized dashboard showing:

Total reported cases
New complaints
Pending verification
Verified cases
Resolved cases
Location-wise complaints
Department/zone-wise cases
Complaint trends

Authorities can open individual complaints and review the submitted evidence.

6. Complaint Verification & Status Tracking

Each complaint can follow a structured workflow:

Submitted → Under Verification → Verified → Assigned → Action Taken → Resolved

Authorities can update the status and add remarks.

Citizens can track the progress using their complaint ID.

7. Analytics & Reporting

The system generates reports based on collected data.

Examples:

Number of complaints per area
Monthly complaint trends
Pending cases
Average resolution time
Repeated complaint locations
Zone-wise statistics

This can help authorities identify areas requiring greater monitoring.

## Proposed Solution / Architecture Diagram
<img width="1288" height="440" alt="image" src="https://github.com/user-attachments/assets/f27f61b8-ac35-43da-acff-e06cbf7eda8b" />


## Use Cases
<img width="1289" height="398" alt="image" src="https://github.com/user-attachments/assets/7d72f551-9c67-4060-bc86-54f2ad2b03f3" />


## Technology Stack

Frontend

React.js

User interface
Complaint submission
Dashboard
Interactive map
Status tracking
Backend

Node.js + Express.js

REST APIs
Complaint processing
Authentication
Status management
Communication between frontend and database
Database

PostgreSQL

Stores:

User information
Complaint details
Location data
Complaint status
Officer details
Reports
Timestamps
Maps

Google Maps API / OpenStreetMap

Used for:

Location selection
Map visualization
Complaint mapping
Area-based monitoring
Authentication

Firebase Authentication / JWT

Used for secure:

Citizen login
Officer login
Administrator login
Image Storage

Cloudinary / Firebase Storage

Used to store construction photographs and supporting evidence.

AI / Image Processing

Python + OpenCV / TensorFlow

Used for optional image analysis and comparison.

Development Tools
Git
GitHub
VS Code
Postman

## Dependencies
| Dependency                  | Estimated Time |
| --------------------------- | -------------: |
| Requirement analysis        |         3 days |
| UI/UX design                |         4 days |
| Frontend development        |         8 days |
| Backend/API development     |         8 days |
| Database development        |         4 days |
| Maps integration            |         3 days |
| Image upload & storage      |         3 days |
| AI/image analysis prototype |         7 days |
| Admin dashboard             |         5 days |
| Testing & debugging         |         5 days |
| Deployment                  |         2 days |
