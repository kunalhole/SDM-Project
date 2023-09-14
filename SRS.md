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

## 1. Performance
- *1.1* The system shall support concurrent access by multiple users without degradation in response times.
- *1.2* Load times for examination landing pages should not exceed 2 seconds under standard network conditions.

## 2. Security
- *2.1* User data, including personal details and examination scores, shall be encrypted both in transit and at rest.
- *2.2* The system shall implement a secure user authentication method to prevent unauthorized access.
- *2.3* All payment transactions should be secured using industry-standard encryption protocols.

## 3. Usability
- *3.1* The system shall offer a user-friendly interface, ensuring that users can navigate and understand functionalities without difficulty.
- *3.2* Features should be intuitively named and organized to promote a streamlined user experience.

## 4. Reliability
- *4.1* The system shall have an uptime of 99.9% during examination periods.
- *4.2* Regular data backups should be implemented to prevent data loss.

## 5. Scalability
- *5.1* The system should be scalable to accommodate an increasing number of users.
- *5.2* It should handle spikes in traffic, especially during registration and examination periods.

## 6. Accessibility
- *6.1* The system should be accessible from various devices, including desktops, laptops, tablets, and mobile phones.
- *6.2* The design should be responsive, adapting to different screen sizes and resolutions.

## 7. Interoperability
- *7.1* The system shall integrate seamlessly with other existing CDAC systems or databases if necessary.
- *7.2* There should be capabilities for API integrations for potential future expansions or third-party tools.

## 8. Maintainability
- *8.1* The codebase should be modular and well-documented, allowing for easy maintenance and updates.
- *8.2* Any changes or updates to the system should not cause extended downtimes.

## 9. Compliance
- *9.1* The system should comply with all relevant data protection regulations.
- *9.2* For payment functionalities, it must adhere to financial and banking standards and regulations.
