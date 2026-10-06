# -WGU-ClickUp-Employee-Onboarding-Workflow-Build
Employee onboarding workflow and supervisor dashboard built in ClickUp (WGU project)
# Employee Onboarding Workflow – ClickUp

**WGU Project – Business Productivity Software**
Designed and built by Daimmaire Rashadd

## 📌 Project Summary
This project demonstrates the design and implementation of an employee onboarding workflow in ClickUp, an all-in-one productivity platform that centralizes tasks, documents, goals, and team communication. The goal was to replace scattered email threads and static spreadsheets with a single, structured workspace that gives new hires clarity and gives supervisors real-time visibility.

> **Note:** All employee names and records shown in this project are sample data created for demonstration purposes.

## 🏗️ Architectural Overview
Each new hire is tracked as a parent task, with nested subtasks for each onboarding phase. Supervisors monitor progress from a dashboard.

- **Space:** Employee Onboarding
- **Project:** New Hire Onboarding Process
- **Phase lists (checkpoints):**
  - Pre-Start Checklist
  - Onboarding Tasks (Days 2–3)
  - IT & Systems (Days 2–3)
  - Department Onboarding
  - Role-Specific Training
  - Completion and/or Follow-Up
- **Views:** List, Board, and Supervisor Dashboard
- **Task statuses:** Not Started, In Progress, Pending Approval, Approved
- **Custom fields:** Employee Name, Supervisor, Assigned To, Assigned Role, Onboarding Phase, Completion Percentage, Priority, Due Date, Supervisor Reviewed

## 🚀 Key Milestones & Solutions

### 1. Structured Workspace Hierarchy
- **Challenge:** Onboarding was fragmented across email and spreadsheets, with no single source of truth.
- **Solution:** Built a Space → Project → phase-list structure. Each employee is a parent task with nested subtasks for sequential phases, and standardized task templates generate the same checklist for every role.

### 2. Checkpoint Tasks with Approval Gates
- **Challenge:** Compliance steps needed to be explicit and verifiable, not assumed complete.
- **Solution:** Created milestone subtasks such as Non-Disclosure Agreement signing, tax paperwork, and employment agreement signing. Each carries a status tag (Pending Approval or Approved) so new hires and supervisors can see exactly what is done.

### 3. IT & Systems Provisioning Checkpoints
- **Challenge:** Access and equipment setup needed clear ownership and tracking.
- **Solution:** Defined checklist-style subtasks for confirming equipment, confirming active login credentials, confirming building and badge access, and submitting the badge and credential requests. Automations route provisioning items to the assigned department group.

### 4. Custom Fields for Consistency
- **Challenge:** Supervisors could not compare progress across multiple new hires.
- **Solution:** Configured project-level custom fields that carry identity, supervisor, progress, and priority data on every task. These fields also feed the dashboard.

### 5. Supervisor Dashboard
- **Challenge:** Supervisors relied on manual status check-ins.
- **Solution:** Built a dashboard with four widgets: Active New Hires, Onboarding Progress by Phase, Overdue Tasks, and Upcoming Milestones. Color-coded status badges and red past-due indicators show stuck steps at a glance.

### 6. Communication & Accountability
- **Challenge:** Questions and feedback were getting lost in separate threads.
- **Solution:** Used task-level comments and @mentions so guidance stays attached to the work. Priority and assignee flags show who owns each delayed item, and supervisors can reassign tasks to IT, HR, or Security teams.

### 7. Process Documentation
- Wrote step-by-step procedures for adding a new hire and for checking a hire's status, so the workflow can be handed to another team member.

## 📋 How It Works

**Adding a new hire**
1. From the home screen, open the **Spaces** section.
2. Open the **Employee Onboarding** space, then the **New Hire Onboarding Process** project.
3. Open the **Pre-Start Checklist** and click **Add Task**.
4. Enter the new hire's name as the task name.
5. Set the assignee, then complete the **Employee Name** and **Supervisor** custom fields.
6. Click **Create Task**.

**Checking a new hire's status**
1. Open **List view** and scroll to the relevant phase (for example, IT & Systems_Days 2-3).
2. Expand the new hire's task to see required subtasks and their statuses.

## 🖼️ Screenshots
| Workspace structure | Supervisor dashboard |
|---|---|
| ![Workspace structure](screenshots/workspace-structure.png) | ![Supervisor dashboard](screenshots/supervisor-dashboard.png) |

| Checkpoint tasks | Custom fields |
|---|---|
| ![Checkpoint tasks](screenshots/checkpoint-tasks.png) | ![Custom fields](screenshots/custom-fields.png) |

## 🛠️ Skills Demonstrated
- Workflow & Process Design (onboarding lifecycle, phase-based checkpoints)
- ClickUp Administration (Spaces, custom fields, list views, automations, dashboards)
- Dashboard & Status Reporting (progress tracking, overdue and milestone monitoring)
- Access Provisioning Coordination (credential, equipment, and badge access requests)
- Compliance Workflow Tracking (NDA, tax, and agreement approvals)
- Technical Documentation & Stakeholder Communication
