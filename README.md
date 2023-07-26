# SJVN Ltd Grievance Redressal Portal

## Project Description

The SJVN Ltd Grievance Redressal Portal is a web-based application built to handle employee grievances efficiently and securely. The portal is accessible only through the company's private LAN connection, ensuring confidentiality. This platform streamlines the process of submitting, tracking, and resolving grievances for employees.

## Features

### User Side

1. **Grievance Submission:**
   - Users can select the type of grievance from a dropdown menu.
   - They can provide a detailed description of their grievance in a text box.
   - Users have the option to attach relevant documents or files to support their grievance.

2. **Request ID Generation:**
   - After submission, a unique Request ID is generated, acting as the primary key for tracking the grievance.

3. **Data Upload to SAP S4/HANA Database:**
   - Upon submission, the grievance data is securely uploaded to the company's SAP S4/HANA database for further processing.

4. **Grievance Status Tracking:**
   - Users can check the current status of their grievance using the Request ID.
   - The portal displays the current stage of the grievance redressal process.
  
   ![User side](https://github.com/karanthakur13/Grievance-Redressal/blob/main/User.png)

### Admin Side

1. **Date-Based Grievance Filtering:**
   - Admins can filter and view grievances based on the range of dates in which they were submitted.

2. **Grievance Listing:**
   - Admins can see a list of grievances along with their respective Request IDs.

3. **Grievance Details and Attachments:**
   - By clicking on a specific grievance, admins can view the description provided by the user and access any attached files.

4. **Comment and File Attachment:**
   - Admins have the authority to add comments to the grievance.
   - They can also attach relevant files while responding to the grievance.

5. **Grievance Resolution History:**
   - The admin can view the history of the last three resolutions for a better understanding of the grievance's background.

6. **Grievance Reply:**
   - After careful consideration, the admin can reply to the grievance, initiating the redressal process.

7. **User Notified of Grievance Status Update:**
   - Once the admin responds to the grievance, the user is notified of the updated status.

## Technology Stack

- Programming Language: SAP's ABAP (Advanced Business Application Programming).
- Integrated Development Environment: SAP Web IDE.

## Confidentiality

Due to confidentiality reasons, the source code of the SJVN Ltd Grievance Redressal Portal cannot be published on public repositories like GitHub. However, the project's description and functionality have been outlined in this document to give a clear understanding of its features and implementation.

Please note that the project adheres to the necessary security measures to safeguard user data and maintain the integrity of the grievance redressal process.


