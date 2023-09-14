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

## 1. User Registration and Profile
- **1.1** The system shall provide a registration interface for new candidates.
- **1.2** Upon registration, an email containing an admission booklet shall be sent to the registered email of the candidate.
- **1.3** Registered candidates can view the examination landing page.
- **1.4** The system shall prevent anonymous users from accessing the examination.

## 2. Eligibility Criteria
- **2.1** The system shall list detailed eligibility criteria for the candidates.
- **2.2** During registration, the system will prompt candidates to provide relevant information to check eligibility.
- **2.3** The system shall automatically verify the eligibility based on the criteria and provided information.

## 3. C-CAT Examination
- **3.1** Registered candidates can access details about the C-CAT examination.
- **3.2** The system shall provide features like 'submit', 'opted', 'restart', and a 'counter' during the examination.
- **3.3** Candidates shall receive notifications about MCQs during the examination.
- **3.4** Announcements and instructions will be available before starting the examination.

## 4. C-CAT Syllabus
- **4.1** The system shall display the detailed syllabus for the C-CAT examination.
- **4.2** Registered candidates can download the syllabus in PDF format.

## 5. Examination Fee
- **5.1** Details about the C-CAT examination fee will be provided.
- **5.2** The system shall provide an integrated payment gateway for the candidates to pay the examination fee.
- **5.3** Payment methods will include online payment and check (paper) options.
- **5.4** Receipts for payment will be generated and sent to the registered email of the candidate.

## 6. Counseling & Seat Allocation
- **6.1** The system shall describe the counseling and seat allocation process.
- **6.2** Registered candidates can provide their course and college preferences.
- **6.3** Seat capacities for different training centers will be displayed.

## 7. Scheduling
- **7.1** The system shall show the schedule for the examination, counseling, and other relevant events.
- **7.2** BOD (Board of Directors) can view and modify the schedule with adequate permissions.

## 8. Support and Requests
- **8.1** Candidates can raise specific requests or queries.
- **8.2** Support staff will receive and review these requests.
- **8.3** Support staff have the capability to approve or reject the requests.
- **8.4** BOD support will be available for high-priority issues or escalations.

## 9. Examination Details
- **9.1** Registered candidates can access specific details about the examination from CDAC.
- **9.2** The system shall maintain confidentiality and integrity, ensuring only authorized candidates can access the exam details.


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
