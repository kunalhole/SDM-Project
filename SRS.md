# Online Assessment For CDAC Course 

## Document:
System Requirement Specification Document

## Title:
System Requirement Specification for online assessment for CDAC courses.

## Team:
Exam coordinator, Student(Examinee), Support Staff, System Administrator, Backend developer, Frontend developer, Database developer, Quality Assurance Team, System Analyst.

## Objective (Purpose):
The online assessment for CDAC course is intended to evaluate online assessment for examination taken by the candidate appaering for CDAC courses.

## Scope:
The system will allow CDAC course students to take online assessments, view results, and receive feedback.

## Functional Requirements:

### 1. User Registration and Profile
The system shall provide a registration interface for new candidates. Upon registration, an email containing an admission booklet shall be sent to the registered email of the candidate.
 Registered candidates can view the examination landing page.
 The system shall prevent anonymous users from accessing the examination.

### 2. Eligibility Criteria
 The system shall list detailed eligibility criteria for the candidates.
 During registration, the system will prompt candidates to provide relevant information to check eligibility.
 The system shall automatically verify the eligibility based on the criteria and provided information.

### 3. C-CAT Examination
Registered candidates can access details about the C-CAT examination.
 The system shall provide features like 'submit', 'opted', 'restart', and a 'counter' during the examination.
 Candidates shall receive notifications about MCQs during the examination.
 Announcements and instructions will be available before starting the examination.

### 4. C-CAT Syllabus
 The system shall display the detailed syllabus for the C-CAT examination.
 Registered candidates can download the syllabus in PDF format.

### 5. Examination Fee
 Details about the C-CAT examination fee will be provided.
  The system shall provide an integrated payment gateway for the candidates to pay the examination fee.
   Payment methods will include online payment and check (paper) options.
   Receipts for payment will be generated and sent to the registered email of the candidate.

### 6. Counseling & Seat Allocation
The system shall describe the counseling and seat allocation process.
  Registered candidates can provide their course and college preferences.
   Seat capacities for different training centers will be displayed.

### 7. Scheduling
The system shall show the schedule for the examination, counseling, and other relevant events.
BOD (Board of Directors) can view and modify the schedule with adequate permissions.

### 8. Support and Requests
 Candidates can raise specific requests or queries.
Support staff will receive and review these requests.
Support staff have the capability to approve or reject the requests.
BOD support will be available for high-priority issues or escalations.

### 9. Examination Details
Registered candidates can access specific details about the examination from CDAC.
The system shall maintain confidentiality and integrity, ensuring only authorized candidates can access the exam details.


##  NonFunctional Requirements:
1.Regarding windows switching
No exterenel websites not accessible
Security
Mic & webcam should be in good condition
Capability(Load balancing)

Availability:
uptime: 24* 7 

Performance
Maintainability:
Accessibility:
Scalability:
Safety:
