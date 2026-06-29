# 🌐 Automated Network Request Management
## 📌 Project Overview

**Automated Network Request Management** is a ServiceNow application that eliminates manual processing of enterprise network service requests. Built using **Service Catalog**, **Flow Designer**, **Approval Engine**, **Business Rules**, and **Email Notifications**, it delivers a fully automated, auditable, and scalable workflow — ensuring faster fulfillment and a better experience for both users and network teams.

---

## 🎯 Problem Statement

Traditional network request management relies on manual approvals, email chains, and delayed task assignments, causing:

| Problem | Impact |
|---------|--------|
| Slow request processing | Delays in network provisioning |
| Heavy manual effort | Engineer time wasted on coordination |
| Poor status visibility | Users unaware of request progress |
| Human error risk | Missed steps and inconsistent handling |
| Limited audit tracking | Compliance and reporting gaps |

---

## 💡 Solution

Once a user submits a network request through the Service Catalog:

- Request details are validated by client scripts
- Approval workflow is automatically triggered
- Approver receives an email notification
- On approval — a network task is created and assigned
- Network engineer completes the task
- Request status auto-updates
- Completion email is sent to the requester
- Full audit trail is maintained throughout

---

## 🚀 Key Features

| Feature | Description |
|---------|-------------|
| Service Catalog Form | Dynamic catalog variables for structured user input |
| Client-Side Validation | Ensures clean, validated submissions |
| Automated Approval Workflow | Routes approvals and handles responses automatically |
| Flow Designer Automation | End-to-end process orchestration |
| Auto Task Creation | Network tasks generated and assigned on approval |
| Email Notifications | Alerts sent at every key stage of the workflow |
| Role-Based Access Control | RBAC enforced at catalog, task, and record level |
| Real-Time Status Tracking | Request state updates automatically throughout |
| SLA Monitoring | Tracks resolution time against defined SLAs |
| Audit-Ready Records | Complete, tamper-evident history for compliance |

---

## ⚙️ Technologies Used

| Technology | Purpose |
|------------|---------|
| ServiceNow Zurich | Development platform |
| Service Catalog | User request submission interface |
| Flow Designer | Visual process automation |
| Business Rules | Server-side backend logic |
| Client Scripts | Dynamic form behavior and validation |
| Approval Engine | Approval routing and response handling |
| Notifications | Email alerts throughout the workflow |
| Task Management | Network fulfillment and tracking |
| JavaScript (ES6) | Custom scripting |
| ACL | Role-based security and access control |

---

## 🔄 Workflow

Below is the end-to-end automation flow that powers the system:

> **Step 1** — User submits a network request via the Service Catalog
>
> **Step 2** — Request is validated using Client Scripts
>
> **Step 3** — Approval request is generated and email is sent to the approver
>
> **Step 4** — Approval decision is made:
> - **If Approved** → User record is updated, a network task is created, assigned to the team, and an email is sent
> - **If Rejected** → The requester is notified that the request was rejected
>
> **Step 5** — Network engineer completes the assigned task
>
> **Step 6** — Request status is automatically updated
>
> **Step 7** — Completion email is sent to the requester
>
> ✅ **Done** — Full audit trail maintained throughout the process

---

## 🛠️ Implementation

### Administrator Tasks
- Configured User Groups and Roles
- Set up Access Control Lists (ACLs)
- Created and published the Catalog Item
- Designed Notification Templates

### Developer Tasks
- Built Client Scripts for form validation
- Designed Flow Designer automation flows
- Implemented Approval Logic and conditions
- Automated Task creation and assignment
- Configured Email Notifications
- Scripted automatic Record Updates

---

## 📸 Flow Designer Screenshot

![Flow Designer](images/flow-designer.png)

**The automation flow includes:**
- Catalog Variable triggers
- Database record creation
- Approval activity with conditional branching
- Network task creation and assignment
- Email notifications at each stage
- Automatic status updates
- End-flow condition handling

---

## 📂 Project Structure

| Folder / File | Description |
|----------------|-------------|
| README.md | Project documentation |
| images/ | Contains screenshots like the Flow Designer diagram |
| Update Sets/ | ServiceNow update set exports |
| Documentation/ | Additional project documentation |
| Demo/ | Demo video and related files |
| Screenshots/ | UI and workflow screenshots |

---

## 📊 Benefits

| Benefit | Description |
|---------|-------------|
| Faster Fulfillment | Automated flow eliminates manual delays |
| Reduced Manual Work | Engineers focus on actual tasks, not coordination |
| Better User Experience | Real-time updates keep requesters informed |
| Automated Notifications | Every alert is triggered automatically — no manual emails |
| Centralized Tracking | All requests visible from a single dashboard |
| Audit-Ready Process | Full record history for compliance reporting |
| Scalable Workflow | Handles growing request volumes without additional effort |
| Improved Compliance | Enforced process steps reduce policy gaps |

---

## 🔒 Security

| Control | Implementation |
|---------|----------------|
| RBAC | Role-based access at catalog, task, and record level |
| Approval Validation | No task created without an approved request |
| Restricted Catalog Access | Only authorized users can submit requests |
| Audit Logging | Every record change is tracked and timestamped |
| Secure Task Assignment | Tasks only visible to authorized network engineers |

---

## 📈 Future Enhancements

- Integration with Cisco DNA Center
- REST API Integration for external systems
- AI-based Request Classification
- Predictive Approval Recommendations
- Mobile Approval Support
- Dashboard and Performance Analytics Integration

---

## 🎥 Demo Video

▶️ **[Click here to watch the project demo](https://drive.google.com/file/d/1FfBrNp-yji4CrOYN8mZdaaSG9_4KTWno/view?usp=sharing)**

---

## 👨‍💻 Author

**Burjangi Krishna**
ServiceNow Developer | B.Tech CSE (Data Science)

[![GitHub](https://img.shields.io/badge/GitHub-Krishnaburjangi720-181717?style=flat-square&logo=github)](https://github.com/Krishnaburjangi720)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Krishna_Burjangi-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/krishna-burjangi-576324338/)

---

## 📄 License

This project is developed for **educational and learning purposes**.

---

<div align="center">

⭐ **If you found this project helpful, please give it a star!** ⭐

</div>
