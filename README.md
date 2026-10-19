
# ShiftLedger
## VA Timesheet & Invoice Management System

### 1. Project Overview
ShiftLedger is a web-based timesheet and invoice management system designed specifically for Virtual Assistant (VA) agencies. It automates shift reporting, working-hour calculations, timesheet management, and monthly invoice preparation.

### 2. Problem Statement
Many VA agencies rely on manual Excel-based timesheets and invoice preparation. These processes can cause calculation errors, duplicate records, scheduling and reporting difficulties, and delays in invoice delivery.

### 3. Proposed Solution
ShiftLedger provides a centralized platform that receives daily shift reports through WhatsApp, uses an AI agent to convert messages into structured records, calculates working hours automatically, and generates draft invoices for administrative review and approval.

### 4. Main Features
- WhatsApp-based shift reporting.
- AI-powered message interpretation and confirmation.
- Timesheet and leave management.
- Automatic daily, weekly, and monthly working-hour calculations.
- Overtime and pending-hour calculations.
- Secure administrator dashboard.
- Virtual Assistant, client, assignment, and rate management.
- Monthly draft invoice generation.
- Invoice review, editing, and approval.
- PDF invoice generation and email delivery.
- Manual shift entry and correction.

### 5. User Roles
- Virtual Assistant (VA): Reports working hours through WhatsApp.
- Admin/Manager: Manages records, rates, timesheets, and invoices.
- Client: Receives approved PDF invoices through email.

### 6. Technology Stack
- Frontend: HTML, CSS, JavaScript.
- Database and Authentication: Supabase (PostgreSQL).
- Workflow Automation: n8n.
- Messaging: WhatsApp Business Cloud API.
- AI Message Parsing: OpenAI API.
- PDF Generation: html2canvas and jsPDF, or an equivalent solution.
- Email Delivery: Gmail API.
- Hosting: Vercel.
- Version Control: GitHub.

### 7. Project Scope
The system covers shift reporting, timesheet management, working-hour calculations, rate management, and invoice generation and delivery.

Payroll payments, online payment collection, tax filing, and a native mobile application are outside the initial project scope.

### 8. Security and Reliability
- Secure administrator authentication.
- Protection of client billing rates and VA pay rates.
- Role-based data access using Supabase Row-Level Security.
- Secure storage of API keys and credentials.
- Manual correction of shift records when automated services fail.

### 9. Development Methodology
The project follows an Agile, iterative development approach, with four planned sprints covering requirements and dashboard development, WhatsApp and AI integration, calculations and invoice workflows, and PDF delivery, testing, and deployment.

### 10. Project Status
Requirements analysis and SRS preparation.

### 11. Team Members
- Muhammad Fahad Zafar
- Sania Saif
- Musfirah Sheikh
- Muhammad Farhan Shahid
