Project Overview

The E-Seva Application is a digital service platform built on Pega Constellation 24.2, designed to provide multiple citizen services online in a single unified portal.

The system enables users to apply for various government certificates and utility services, while ensuring secure processing, role-based approvals, and automated notifications.

Developed as part of a team project involving Aadhar Update, Bill Payment, Income Certificate, and Caste Certificate modules — with end-to-end case management and automation.

Features Implemented

1. Multi-Service Portal

Users can apply for multiple services such as Aadhar Update, Bill Payment, Income Certificate, and Caste Certificate.

Each service is designed as a separate case type, integrated under one portal for ease of access.

2. User Authentication & Dashboard

Users can register and log in using secure credentials.

Personalized dashboard displays active, completed, and pending service requests.

3. Dynamic Case Creation

Each selected service dynamically launches its own case type with unique workflows and approvals.

All case data is stored and retrieved using Data Pages and Data Objects for reusability.

4. Terms & Conditions & Form Validation

Users must agree to the service terms before form submission.

Mandatory field validations ensure data accuracy and completeness.

5. Automated Approval Workflow

Auto-approval configured for minor requests or low-risk services.

Manual approval routing for critical cases based on request type and service category.

6. Document Upload & Verification

Users can upload required identity and address proofs.

Uploaded files are validated for type, size, and completeness before submission.

7. Status Tracking & Notifications

Real-time status tracking for every case (e.g., Submitted → Under Review → Approved → Completed).

Email notifications sent automatically at every stage for transparency.

8. Admin & Officer Portal

Officers review and approve/reject applications based on eligibility rules.

Admin dashboard allows monitoring of all service cases, delegation, and performance tracking.

Roles Implemented

Citizen: Submit service applications, upload documents, and track status.

Verification Officer: Validate document accuracy and approve/reject cases.

Manager/Admin: Handle escalations, monitor SLAs, and manage configurations.

Key Concepts Covered

Case Management for Multiple Services

Data Modeling & Integration using Data Pages

Decision Tables for Approval Routing

SLA and Escalation Handling

Correspondence (Email Notifications)

Optional Actions (Withdraw, Resubmit, Feedback)

Role-Based Access and UI Control

Workflow Summary

Login/Register → Select Service → Fill Application → Upload Documents → Submit → Verification → Approval → Service Completion → Notification

Users receive automatic email updates at each milestone.

Rejected cases can be resubmitted or withdrawn based on system configuration.

DigiSeva Application Zip File Link - https://drive.google.com/file/d/1UMpdupUc15lloGL4ir4ip9EYBzON4tG-/view?usp=sharing
