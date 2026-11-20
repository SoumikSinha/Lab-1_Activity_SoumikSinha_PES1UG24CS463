# Lab 1: Requirements Engineering & UML Use-Case Modelling

**Student Name:** Soumik Sinha  
**USN / SRN:** PES1UG24CS463  
**Section:** 5H  
**Roll / Sl. No:** 32  
**Problem Statement #32:** Personal Subscription & Recurring Expense Auditor  

---

## Overview
This repository contains the completed deliverables for **Lab 1: Requirements Engineering & UML Use-Case Modelling**, based on Problem Statement #32 (Retail, E-Commerce & Finance).

The system is a personal finance micro-application that aggregates recurring bank charges, alerts users ahead of renewal dates, calculates monthly burn rates, and provides one-click cancellation guides.

---

## Deliverables

### 1. Requirements Table
- **File:** [`Requirements_Table.pdf`](./Requirements_Table.pdf)
- Contains exactly 5 Functional Requirements (FR-001 to FR-005) and 2 Non-Functional Requirements (NFR-001 & NFR-002).
- Each requirement details: Req ID, Type, Description ("The system shall..."), Priority, Measurable Acceptance Criteria (Pass/Fail), and Rationale.

### 2. UML Use-Case Diagram
- **File:** [`UseCase_Diagram_PS32.jpg`](./UseCase_Diagram_PS32.jpg)
- Models target stakeholders / actors: **Individual User** and **Finance Auditor**.
- Captures system boundary and primary use cases:
  - Import Transactions
  - Detect Recurring Subscriptions
  - Send Renewal Alert
  - Calculate Monthly Burn Rate
  - Provide Cancellation Guide
  - Export Audit Report
- Demonstrates standard UML notation including `<<include>>` (Validate & Securely Parse Data) and `<<extend>>` (Alert on Approaching Renewal Date) relationships.

### 3. Use-Case Flow Specification
- **File:** [`Usecase_Flow.pdf`](./Usecase_Flow.pdf)
- 1-page detailed flow specification for core use case: **Import Transactions & Detect Subscriptions**.
- Outlines Preconditions, Success & Failure Postconditions, a 10-step Main Success Scenario, and an Alternate Flow (handling invalid file format or parse failure).

### 4. Problem Statement Reference
- **File:** [`32_SE_Lab1_SE_Problem_Statements.pdf`](./32_SE_Lab1_SE_Problem_Statements.pdf)
- Official department problem statement handout for Problem Statement #32.
