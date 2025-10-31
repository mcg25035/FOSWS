# FOMO Online Shopping Website System (FOSWS)

Welcome to the FOSWS project! This document provides instructions for AI agents participating in the development of this e-commerce platform.

## Agent Task: Subsystem Implementation

Your primary task is to **claim and implement one of the core subsystems** of the FOSWS platform.

### Step 1: Read the Main Plan

Before starting, you **must** read the main project plan:
- **[Main Project Plan](./agent-plan-and-report/main.md)**

This document contains the overall system architecture, development plan, and links to detailed specification documents for each subsystem.

### Step 2: Claim a Task from the To-Do List

Choose **one** unclaimed task from the list below. To claim a task, create a file named after the subsystem in the project root (e.g., `AS.claimed`) to signify it's "In Progress."

| Subsystem | Status      | Description                               | Specification Document                               |
| :-------- | :---------- | :---------------------------------------- | :--------------------------------------------------- |
| **AS**    | **Unclaimed** | Administrator Subsystem (Admin Panel)     | [AS-specifications.md](./agent-plan-and-report/AS-specifications.md) |
| **CS**    | **Unclaimed** | Customer Subsystem (Main Website)       | [CS-specifications.md](./agent-plan-and-report/CS-specifications.md) |
| **PS**    | **Unclaimed** | Payment Subsystem (Payment Gateway)      | [PS-specifications.md](./agent-plan-and-report/PS-specifications.md) |
| **DBS**   | **Unclaimed** | Database Subsystem (Data Layer & Schema) | [DBS-specifications.md](./agent-plan-and-report/DBS-specifications.md) |

### Step 3: Implement and Submit

Once you have claimed a task, follow the instructions in the `main.md` and the relevant specification document to complete the implementation.

---

## Proposed Tech Stack

The following technology stack is recommended for this project, based on the requirements outlined in `requirements.md`.

- **Frontend:**
  - **Framework:** React.js or Vue.js
  - **Styling:** Tailwind CSS or Material-UI
- **Backend:**
  - **Framework:** Spring Boot (Java) or Django (Python) for robust, scalable APIs.
  - **API Specification:** RESTful APIs with JSON.
- **Database:**
  - **RDBMS:** PostgreSQL or MySQL (as per `DBSD003`).
  - **ORM:** Hibernate (Java) or Django ORM (Python).
- **Asynchronous Communication:**
  - **Message Queue:** RabbitMQ or Apache Kafka (as per `IF003`).
- **DevOps & Deployment:**
  - **Containerization:** Docker (as per `PSD002`).
  - **CI/CD:** Jenkins, GitLab CI, or GitHub Actions (as per `ASD002`).
  - **Cloud Provider:** AWS, Azure, or GCP (as per `PSD003`).

Good luck, agent!
