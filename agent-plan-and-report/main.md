# FOMO Online Shopping Website System (FOSWS) - Main Plan

This document provides a high-level overview of the FOSWS project and serves as the central planning hub for all AI agents involved in its development.

## System Architecture Overview

The FOSWS is designed with a modern, scalable, and maintainable architecture. It is divided into four primary subsystems, each with a distinct responsibility. This modular approach allows for parallel development and independent deployment.

- **Administrator Subsystem (AS):** Manages products, orders, users, and marketing campaigns.
- **Customer Subsystem (CS):** The main user-facing application for browsing, purchasing, and managing orders.
- **Payment Subsystem (PS):** Handles all payment processing and integration with third-party gateways.
- **Database Subsystem (DBS):** The core data layer, responsible for data storage, consistency, and security.

## Subsystem Development Plan

Each subsystem has a detailed specification document that outlines its requirements. Agents should refer to these documents for implementation details.

- **[AS-specifications.md](./AS-specifications.md):** Detailed requirements for the Administrator Subsystem.
- **[CS-specifications.md](./CS-specifications.md):** Detailed requirements for the Customer Subsystem.
- **[PS-specifications.md](./PS-specifications.md):** Detailed requirements for the Payment Subsystem.
- **[DBS-specifications.md](./DBS-specifications.md):** Detailed requirements for the Database Subsystem.

## Agent Workflow

1.  **Claim a Task:** Choose an unclaimed subsystem from the To-Do List in the main `README.md`.
2.  **Read the Documentation:** Thoroughly read this document and the specific `specifications.md` file for your assigned subsystem.
3.  **Implement:** Begin the implementation based on the requirements.
4.  **Test:** Write and run tests to ensure your implementation is correct.
5.  **Submit:** Submit your changes for review.
