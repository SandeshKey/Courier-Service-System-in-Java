<p align="center">
  <sub>OPERATIONAL INTERFACES · JAVA DEVELOPMENT · OBJECT-ORIENTED PROGRAMMING</sub>
</p>

<h1 align="center">Courier Service System</h1>

<p align="center">
  <em>Exploring the everyday workflows behind a delivery operation.</em>
</p>

<p align="center">
  Academic desktop application
  <br>
  Java / NetBeans / Ant
</p>

<p align="center">
  <a href="#inside-the-application"><strong>Explore the interfaces ↓</strong></a>
  &nbsp; · &nbsp;
  <a href="#implementation">Browse the implementation</a>
  &nbsp; · &nbsp;
  <a href="https://www.sandesh.design/">My portfolio ↗</a>
</p>

<br>

## Looking beyond the delivery itself.

A courier operation involves more than moving a package. Staff accounts, driver information, invoices, reports, and feedback all need interfaces of their own.

This academic Java project explores those supporting workflows through a desktop application. The repository includes interface source files, NetBeans form definitions, project configuration, and documentation of object-oriented programming concepts.

It provides another view of my technical work: the application structures behind operational interfaces.

<br>

## Inside the application

### 01 / Enter the system
**Establish a starting point for the workflow.**

Welcome, sign-in, and account-creation screens provide entry points into the application.

![Courier Service System main interface](https://github.com/SandeshKey/Courier-Service-System-in-Java/assets/98152515/fd3e0d3b-9b63-467b-a760-f6ffc75dc111)

[Explore the main interface ↗](src/MainPage.java)
&nbsp; · &nbsp;
[Explore sign-in ↗](src/LogInPage.java)
&nbsp; · &nbsp;
[Explore account creation ↗](src/createAccount.java)

---

### 02 / Manage people
**Organize the information supporting day-to-day work.**

The project includes interfaces for profiles, employees, and drivers, alongside separate staff-related screens.

![Courier Service System employee-management interface](https://github.com/SandeshKey/Courier-Service-System-in-Java/assets/98152515/d9494043-bec3-44a2-ac45-cdb2437ee095)

[Explore employee entry ↗](src/AddEmployee.java)
&nbsp; · &nbsp;
[Explore driver entry ↗](src/AddDriver.java)
&nbsp; · &nbsp;
[Explore profile editing ↗](src/ProfileEditing.java)

---

### 03 / Prepare invoices
**Give transaction information a dedicated interface.**

The invoice screen represents another operational task within the application, connecting interface controls with the underlying Java implementation.

![Courier Service System invoice interface](https://github.com/SandeshKey/Courier-Service-System-in-Java/assets/98152515/4c085a17-3272-4442-8bae-20e5e2f8707b)

[Explore invoice code ↗](src/GenerateInvoice.java)

---

### 04 / Review reports and feedback
**Make recorded information available for review.**

Report and feedback screens extend the application beyond data entry to include reviewing information.

![Courier Service System report-details interface](https://github.com/SandeshKey/Courier-Service-System-in-Java/assets/98152515/bb4eefd2-285c-4c72-b73a-a86f28f55613)

[Explore report generation ↗](src/GenerateReport.java)
&nbsp; · &nbsp;
[Explore report details ↗](src/ReportDetails.java)
&nbsp; · &nbsp;
[Explore feedback review ↗](src/Viewfeedback.java)

<br>

## Implementation

The repository contains **Java source files**, accompanying **NetBeans form files**, and an **Ant build configuration**.

The original project documentation includes examples of classes, constructors, inheritance, encapsulation, and polymorphism.

| Area | Where to look |
| :--- | :--- |
| **Application interfaces** | [`src/`](src/) |
| **Main page** | [`MainPage.java`](src/MainPage.java) |
| **Management staff interface** | [`ManagingStaff.java`](src/ManagingStaff.java) |
| **Delivery staff interface** | [`DeliveryStaff.java`](src/DeliveryStaff.java) |
| **Invoice generation** | [`GenerateInvoice.java`](src/GenerateInvoice.java) |
| **Report generation** | [`GenerateReport.java`](src/GenerateReport.java) |
| **Ant build definition** | [`build.xml`](build.xml) |
| **Project properties** | [`nbproject/project.properties`](nbproject/project.properties) |

<br>

## What to look for

**How tasks are separated.**  
Compare account, staff, invoice, and reporting interfaces to understand how the application organizes operational work.

**How information moves through the interface.**  
Review the Java source alongside the form definitions to examine the connection between controls and application behavior.

**How programming concepts support the application.**  
Explore the classes and their relationships in the context of concrete workflows rather than isolated programming exercises.

<br>

<details>
<summary><strong>Project diagrams & original documentation</strong></summary>

<br>

### Use-case overview

![Use-case diagram for the Courier Service System](https://github.com/SandeshKey/Courier-Service-System-in-Java/assets/98152515/149d1204-1d21-4e25-9f0e-b596c8e0ac9b)

### Class structure

![Class diagram for the Courier Service System](https://github.com/SandeshKey/Courier-Service-System-in-Java/assets/98152515/ecb23a4a-6f44-4ebe-980c-8d82955687e4)

These diagrams are retained from the original project documentation. Review them alongside the checked-in source when examining the implementation.

</details>

<br>

<details>
<summary><strong>Development environment & setup notes</strong></summary>

<br>

This is a historical NetBeans Java project with an Ant build configuration.

Suggested inspection sequence:

1. Review `nbproject/project.properties` for the expected Java configuration.
2. Open the repository as an existing project in a compatible NetBeans environment.
3. Review dependencies, resource references, and file-storage paths.
4. Replace machine-specific paths with appropriate local development paths.
5. Use synthetic data when testing account and staff workflows.
6. Build the project and verify the relevant screens and interactions.

The repository includes text-based data files and machine-specific path artifacts. Inspect these before attempting a run rather than assuming the original environment is portable.

**Current verification status:** a clean build and end-to-end application run have not yet been verified for this documentation update.

</details>

<br>

<details>
<summary><strong>Project scope & limitations</strong></summary>

<br>

This repository documents an academic application, not a production courier service.

The interface screenshots show the project's recorded appearance. They do not establish current functionality, secure authentication, or verified access controls.

No commercial deployment, operational savings, or independently verified security or accessibility compliance is claimed here.

</details>

<br>

---

<p align="center">
  <strong>Part of Sandesh Subedi’s design and development work.</strong>
</p>

<p align="center">
  <a href="https://www.sandesh.design/">Portfolio</a>
  &nbsp; · &nbsp;
  <a href="https://www.linkedin.com/in/sandeshxd/">LinkedIn</a>
  &nbsp; · &nbsp;
  <a href="mailto:subedi.38@wright.edu">Get in touch</a>
</p>
