# sre-github-lab
Requirements documentation 
# Customer Service & Medical Equipment Maintenance Management System 
## Overview
ElectroMed Corporation deals with the sales, installation, repair, servicing, and maintenance 
of medical equipment. Its service operations involve customers, technicians, workshop staff, 
accounts, store staff, and management. Currently, information is maintained through physical 
records, Excel files, quotations, invoices, and other separate records. 
The proposed system will centralize customer service and medical equipment maintenance 
information to make service operations easier to manage and monitor.
## Scope
-  Customer Management 
-  Equipment Management 
-  Equipment Management 
-  Technician Management
-  Maintenance and Repair Management 
-  Service History
-  Follow-up and Monitoring
- Full accounting and financial management 
- Patient medical records 
- Medical diagnosis or treatment 
- Remote control of medical equipment 
- Online payment processing 
- External hospital-system integration 
## Stakeholders
- Management : Monitor service activities and performance
- Service Team: Manage and track customer complaints 
- Technicians : Access equipment details and record repairs
- Sales Team : Access customer and equipment information 
- Store Staff : Access relevant spare-parts information 
- Accounts : Access relevant invoice/payment information 
- Customers  : Receive timely and effective service 
- System Administrator : Manage users and system access 
## Functional requirements
FR-01: The system shall let an authorized employee create and maintain a customer record.
-	FR-02: The system shall let an authorized employee retrieve a customer's information.
-	FR-03: The system shall let an authorized employee create an equipment record linked to its customer.
-	FR-04: The system shall let an authorized employee retrieve equipment information.
-	FR-05: The system shall let the service team register a customer complaint/service request.
-	FR-06: The system shall display the current status of a service request.
-	FR-07: The system shall let the service team assign a service request to a technician.
-	FR-08: The system shall let a technician record diagnosis/fault details, repair and maintenance activities, and testing/completion of a service.
-	FR-09: The system shall keep each equipment's service history and let an authorized employee retrieve it.
-	FR-10: The system shall identify pending and completed service requests.
-   FR-11: The system shall provide management with a report of ongoing and completed service activities.
-   FR-12: The system shall let the System Administrator manage users and their access.
## Nonfunctional requirements
- NFR-01: For 100 stored service requests, the pending-requests list shall appear within 2 seconds in at least 95 of 100 trials on the agreed test device.
- NFR-02: Each user shall be able to open only the functions allowed for their role, verified by testing every stakeholder role against the documented permissions.
- NFR-03: A trained employee shall be able to register a service request (FR-05) within 3 minutes, verified by timed trials with at least 5 employees.
## Acceptance criteria
- Customer, equipment, and service information is maintained in a centralized system instead of being dependent on scattered records. 
- Service staff can locate the required customer and equipment information more easily than with the existing separate records.  
- Service requests can be monitored clearly so that pending and completed requests are identifiable.
- Technicians and service staff can access the service history required for equipment maintenance and repair activities.  
- Management can obtain a clear view of ongoing and completed service activities.
- The organization reduces its dependence on physical records and separate Excel files for routine customer service and equipment maintenance activities.
 status to Complete.
## Assumptions and open questions
- Currently the companies overall process is manual no system (CRM etc) is being used
- How is the work and related information currently recorded or managed?
- Which part of the process requires the most time or follow-up?
## Project status and viewing
Documentation only. Application implementation has not started.
Clone this repository and open README.md in a Markdown viewer,
or read the rendered file on GitHub.
## Author
- Hafsa Asim 
- Maryam Ali
## Contributing
Create a documentation branch, edit and review the README,
commit the change, push the branch, and open a pull request.