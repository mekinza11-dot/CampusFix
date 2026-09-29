CampusFix — Project Overview

About the Project

CampusFix is an AI-powered campus complaint management system designed to help students report everyday campus problems and route them to the appropriate department.

The project was built using n8n for workflow automation and AI processing, with Supabase used for storing complaint information.

 How It Works

1. A student submits a campus complaint through the CampusFix interface.
2. The AI agent analyzes the student's message.
3. The complaint is classified into relevant information such as:

   * Request Type
   * Issue
   * Category
   * Location
   * Impact
   * Priority
   * Department
   * Status
4. The workflow checks the complaint information and processes the request.
5. The complaint data is stored in Supabase.
6. CampusFix provides a response to the student.

 Example

**Student:**
My mouse is broken in Lab 3.

**CampusFix:**
The issue has been reported to the IT Support department. They will send a technician to Lab 3 to repair or replace the broken mouse.

Technologies Used

* n8n
* AI / LLM
* Supabase
* JSON
* Workflow Automation

Project Features

* AI-based complaint processing
* Automatic complaint categorization
* Department routing
* Priority identification
* Complaint status handling
* Database storage
* Automated responses

Project Structure

```text
CampusFix/
├── README.md
├── workflow/
│   └── CampusFix-n8n-workflow.json
├── screenshots/
│   ├── campusfix-workflow.png
│   ├── supabase-database-1.png
│   └── supabase-database-2.png
└── docs/
    └── project-overview.md
```

 Purpose

The purpose of CampusFix is to demonstrate how AI, workflow automation, and database technologies can be combined to create a practical solution for campus problem management.

 Learning Outcomes

Through this project, I practiced:

* Building AI-powered workflows
* Working with n8n nodes and connections
* Designing conditional workflow logic
* Connecting AI processing with databases
* Structuring and storing complaint data
* Debugging workflow execution
* Integrating multiple technologies into one practical application
