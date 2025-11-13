# Vacation Tracking System (VTS) – Analysis & Design

This repository contains the analysis and design artifacts for the **Vacation Tracking System (VTS)**, based on Chapter 12 of the _Object-Oriented Analysis & Design_ (3rd Edition). The system enables employees to submit vacation requests, managers to review and approve, and to mange employees information in the system and System Admin for the system's infrastructure.

## Motivation

The exercise is a mentorship task that aims to prepare us with Interpersonal & Technical skills required for the market.

## What’s Included

- Vision document
- Functional & Non-Functional Requirements.
- Actors, Constraints, Business Requirements, Assumptions.
- Relational Schema (tables).
- UML diagrams: Sequence diagram.
- Flowcharts representing key system flows from high level perspective.
- Pseudocode for major system operations.

## Tools Used

- Draw.io for diagrams and charts
- Microsoft Word for documentation.

## How to Browse

All diagrams with it's preconditions are in the [VTS-Analysis](VTS-Analysis.pdf).

---

<h2 align=center>Data Model</h2>

[![Data Model](VTS-Data%20Model.png)](VTS-Data%20Model.png)

---

<h2 align=center>High Level UI View</h2>

## Employee View

[![Employee View](./UI/Employee-View.png)](./UI/Employee-View.png)

## Manager View

[![Employee View](./UI/Manager-View.png)](./UI/Manager-View.png)

---

<h2 align=center>Request State Diagram</h2>

[![State Diagram](Request_State-Diagram.png)](Request_State-Diagram.png)

---

<h2 align=center>(Manage Time Use Case) Diagrams & Flowcharts</h2>

### Flowchart (Employee Scenario)

<div align=center>

[![Create New Request flowchart](./Manage-Time_Diagrams/EmpNewReq-flowchart.png)](./Manage-Time_Diagrams/EmpNewReq-flowchart.png)

</div>

### Flowchart (Manger Scenario - Approve / Reject)

<div align=center>

<div align=center>

[![Mange Request flowchart](./Manage-Time_Diagrams/ManagerMangesRequest-flowchart.png)](./Manage-Time_Diagrams/ManagerMangesRequest-flowchart.png)

</div>

</div>

### Sequence Diagram Employee Scenario

<div align=center>

[![Sequence Diagram](./Manage-Time_Diagrams/Employe-Scenario_Sequence-Diagram.png)](./Manage-Time_Diagrams/Employe-Scenario_Sequence-Diagram.png)

</div>

### Sequence Diagram Manager Scenario

<div align=center>

[![Sequence Diagram](./Manage-Time_Diagrams/Manager-Scenario_Sequence-Diagram.png)](./Manage-Time_Diagrams/Manager-Scenario_Sequence-Diagram.png)

</div>

---

<h2 align=center>(Cancel Approved Request) Diagrams & Flowcharts</h2>

## Flowchart

<div align=center>

[![Flow Chart](./Cancel-Approved-Request_Diagrams/flowchart.png)](./Cancel-Approved-Request_Diagrams/flowchart.png)

</div>

## Sequence Diagram

[![Sequence Diagram](./Cancel-Approved-Request_Diagrams/SequenceDiagram.png)](./Cancel-Approved-Request_Diagrams/SequenceDiagram.png)

---

<h2 align=center>(Edit Pending Request Use Case) Diagrams & Flowcharts</h2>

## Flowchart

[![FLowchart](./Edit-Pending-Request_Diagrams/Edit-Pending-Request_fowchart.png)](./Edit-Pending-Request_Diagrams/Edit-Pending-Request_fowchart.png)

## Sequence Diagram

[![Sequence Diagram](./Edit-Pending-Request_Diagrams/Sequence-Diagram.png)](./Edit-Pending-Request_Diagrams/Sequence-Diagram.png)

---

<h2 align=center>(Withdraw Request Use Case) Diagrams & Flowcharts</h2>

## Flowchart

[![Flowchart](./Withdraw-Request_Diagrams/flowchart.png)](./Withdraw-Request_Diagrams/flowchart.png)

## Sequence Diagram

[![Sequence Diagram](./Withdraw-Request_Diagrams/Sequence%20Diagram.png)](./Withdraw-Request_Diagrams/Sequence%20Diagram.png)

---

Thank you for your interest.
Feel free to review, provide feedback, or fork for your own implementation!
