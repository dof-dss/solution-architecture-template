# Solution Architecture Document

Project Name | <i>Project Name</i> 
Owner | <i>Organisation which owns this solution</i>
Status | <i>Indicate the current status of this solution</i>

## 1. Introduction

### 1.1 Purpose

The purpose of this document is to describe the IT solution design for the *Insert Project Name Here*.

This solution design should allow us to:
* Communicate the end-to-end IT solution to all stakeholders
* Provide traceability of the solution back to business requirements and reference architecture
* Provide all views of the solution required for design, build, testing and implementation
* Define impacts of the solution for estimation, planning and delivery purposes

The goal of this document is to develop the solution from why it is needed, through to the conceptual non-technical view to the more concrete solution and delivery design.<br/>
*(See below)*

<img src="/images/SAD-Structure-Overview.png">

### 1.2 Definitions

> The following acronyms and definitions will be used in the *project* and within this document.

| Term/Acronym        | Definition |
| ------------- | ------------- |
|  NICS | Northern Ireland Civil Service 
|  DoF | Department of Finance 
|  NI | Northern Ireland
| GDS | Government Design Service
| ... | ...

<hr />

## 2. Solution Overview

### 2.1 Solution Background

Adipisicing est nisi ut commodo non. Est aute irure ad non ea nisi consectetur adipisicing reprehenderit aliqua ipsum est do eu. Quis labore adipisicing est occaecat occaecat ipsum officia mollit anim qui cillum occaecat nostrud adipisicing.

Reprehenderit consequat enim excepteur dolore labore aute aliquip. Consequat aliqua eu tempor cupidatat quis aute id adipisicing magna veniam. In incididunt adipisicing sint labore. Dolore do ex elit pariatur ipsum labore adipisicing laboris adipisicing. Aliquip eu consectetur consequat sit eiusmod nostrud id pariatur.

Sunt anim cupidatat sunt voluptate mollit culpa reprehenderit ipsum Lorem ut qui. Ea esse Lorem nostrud magna enim incididunt nulla. Dolore anim Lorem adipisicing nulla. In quis sit laboris duis minim.

### 2.2 Scope

#### 2.2.1 In Scope

> The functional scope for the project includes:

#### 2.2.2 Out of Scope

> The following are deemed to be out of scope

### 2.3 Objectives

| Objective No.        | Description |
| ------------- | ------------- |
| OB1 | Incididunt reprehenderit est ullamco laborum.
| OB2 | In irure aliquip proident minim deserunt ex duis consectetur nostrud eiusmod officia commodo.
| ... | ...

### 2.4 Constraints

> The following constraints apply to the project


| Constraint No.         | Description |
| ------------- | ------------- |
| CO1 | Labore adipisicing enim mollit Lorem.
| C02 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| ... | ...

### 2.5 Assumptions

> The following assumptions will be validated as part of the solution design and implementation

| Assumption No.         | Description |
| ------------- | ------------- |
| AS1 | Consectetur esse et commodo Lorem in nostrud mollit pariatur.
| AS2 | Aute nisi fugiat incididunt culpa amet ut incididunt ullamco labore magna sint qui qui ea.
| ... | ...

### 2.6 Dependencies

The solution is dependent on the following external items

| Dependency         | Description |
| ------------- | ------------- |
| DP01 | Consectetur esse et commodo Lorem in nostrud mollit pariatur.
| DP02 | Aute nisi fugiat incididunt culpa amet ut incididunt ullamco labore magna sint qui qui ea.
| ... | ...

### 2.7 High level focus & priorities

> This section captures the expectations of different aspects of potential solutions. Adjust the table to place the entries in your relative order of importance, with the most important as number 1 and the least important as number 6. If you have specific reasons for the relative ordering please record those reasons.

<table class="govuk-table">
  <thead class="govuk-table__head">
    <tr class="govuk-table__row">
      <th scope="col" class="govuk-table__header">Priority Area</th>
      <th scope="col" class="govuk-table__header">Relative Importance</th>
      <th scope="col" class="govuk-table__header">Reasoning</th>
    </tr>
  </thead>
  <tbody class="govuk-table__body">   
    <tr class="govuk-table__row">
     <td class="govuk-table__cell"  style="width: 50%;">
     <b>Architecture</b> <br/>Architecture refers to the structure and design of the solution. 
     The architecture determines how the system is to perform in terms of response times and the 
     amount of work that it can do and how easy it will be to develop and improve the solution in future.</td>
     <td class="govuk-table__cell">1</td>
     <td class="govuk-table__cell">Do culpa proident sint incididunt aliquip tempor ut veniam deserunt consequat laboris.</td>
    </tr>
     <tr class="govuk-table__row">
     <td class="govuk-table__cell">
     <b>Cost</b> <br/>Cost refers to the funds available to support the development, implementation and on-going maintenance of the the solution.</td>
     <td class="govuk-table__cell">2</td>
     <td class="govuk-table__cell">Do culpa proident sint incididunt aliquip tempor ut veniam deserunt consequat laboris.</td>
    </tr>
     <tr class="govuk-table__row">
     <td class="govuk-table__cell">
     <b>Function</b> <br/>Function refers to the specific actions, calculations and operations provided by the proposed solution. </td>
     <td class="govuk-table__cell">3</td>
     <td class="govuk-table__cell">Do culpa proident sint incididunt aliquip tempor ut veniam deserunt consequat laboris.</td>
    </tr>
     <tr class="govuk-table__row">
     <td class="govuk-table__cell">
     <b>Time</b> <br/>Time refers to the time taken to deliver the proposed solution.</td>
     <td class="govuk-table__cell">4</td>
     <td class="govuk-table__cell">Do culpa proident sint incididunt aliquip tempor ut veniam deserunt consequat laboris.</td>
    </tr>
     <tr class="govuk-table__row">
     <td class="govuk-table__cell">
     <b>Quality</b> <br/>Quality refers to the overall ability of the solution to fulfill its purpose with certainty. This will normally address the level to which each property of the solution must operate exactly as specified</td>
     <td class="govuk-table__cell">5</td>
     <td class="govuk-table__cell">Do culpa proident sint incididunt aliquip tempor ut veniam deserunt consequat laboris.</td>
    </tr>
     <tr class="govuk-table__row">
     <td class="govuk-table__cell">
     <b>Level of Risk</b> <br/>Level of Risk refers to the degree of risk that the solution should include.</td>
     <td class="govuk-table__cell">6</td>
     <td class="govuk-table__cell">Do culpa proident sint incididunt aliquip tempor ut veniam deserunt consequat laboris.</td>
    </tr>
  </tbody>
</table>

### 2.8 Key Business Requirements

> Identify any business requirements which are key to the solution. Note, this is not an exhaustive list as requirements will be captured as part of the normal requirements gathering processing.

| Requirement No.         | Description |
| ------------- | ------------- |
| FRO1 | Labore adipisicing enim mollit Lorem.
| FR02 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| ... | ...

> Include a Requirements View diagram to highlight how requirements align to business goals (See example below)

<img src="/diagrams/examples/Requirements-View.jpg">

### 2.9 Non Functional Requirements

> Describe any requirements which specify criteria that can be used to judge the operation of the system, rather than specific behaviours.

#### 2.9.1 Performance 

| Requirement No.         | Description |
| ------------- | ------------- |
| PMO1 | Labore adipisicing enim mollit Lorem.
| PM02 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| PM03 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| ... | ...

#### 2.9.2 Integration

| Requirement No.         | Description |
| ------------- | ------------- |
| INO1 | Labore adipisicing enim mollit Lorem.
| IN02 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| IN03 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| ... | ...

#### 2.9.3 Compatibility

| Requirement No.         | Description |
| ------------- | ------------- |
| CMO1 | Labore adipisicing enim mollit Lorem.
| CM02 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| CM03 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| ... | ...

#### 2.9.4 Usability 

| Requirement No.         | Description |
| ------------- | ------------- |
| USO1 | Labore adipisicing enim mollit Lorem.
| US02 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| US03 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| ... | ...

#### 2.9.5 Reliability 

| Requirement No.         | Description |
| ------------- | ------------- |
| REO1 | Labore adipisicing enim mollit Lorem.
| RE02 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| RE03 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| ... | ...

#### 2.9.6 Security 

| Requirement No.         | Description |
| ------------- | ------------- |
| SCO1 | Labore adipisicing enim mollit Lorem.
| SC02 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| SC03 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| ... | ... | ... 

#### 2.9.7 Maintainability 

| Requirement No.         | Description |
| ------------- | ------------- |
| MNO1 | Labore adipisicing enim mollit Lorem.
| MN02 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| MN03 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| ... | ...

#### 2.9.8 Portability

| Requirement No.         | Description |
| ------------- | ------------- |
| PTO1 | Labore adipisicing enim mollit Lorem.
| PT02 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| PT03 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| ... | ...

#### 2.9.9 Accessibility

| Requirement No.         | Description |
| ------------- | ------------- |
| ACO1 | Labore adipisicing enim mollit Lorem.
| AC02 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| AC03 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat.
| ... | ...

### 2.9 Solution Concept

#### 2.9.1 Current Solution

*If available add a diagram to document the current state (baseline architecture)*

#### 2.9.2 Target Solution

*Add a conceptual solution diagram and description here*

### 2.10 Key Architecture Decisions

| Decision No.         | Title | Decision |
| ------------- | ------------- | ------------- |
| ADO1 | Labore adipisicing enim mollit Lorem. | Labore adipisicing enim mollit Lorem.
| AD02 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat. | abore adipisicing enim mollit Lorem.
| AD03 | Cupidatat fugiat et voluptate ea magna velit elit cupidatat. | Labore adipisicing enim mollit Lorem. 
| ... | ... | ...

<hr />

## 3. Business Architecture

### 3.1 Actors

> A person, organisation, or system that has one or more roles that initiates or interacts with activities; for example, a sales representative who travels to visit customers. Actors may be internal or external to an organisation.

| Name | Description | Location |
| ------------- | ------------- | ------------- |
|  e.g. Administration Officer | e.g. Performs main administrative tasks  |  e.g. Internal
|  e.g. Claimant | e.g. Makes new claims for compensation  |  e.g. External
| ... | ... | ...

<img src="/diagrams/examples/Business-Actors-View.jpg">

### 3.2 Roles

> The usual or expected function of an actor, or the part somebody or something plays in a particular action or event. An actor may have a number of roles.


| Name | Description | 
| ------------- | ------------- | 
|  e.g. Claim Processor| e.g. This role allows users to perform actions to process a claim
|  e.g.  Claim Creator | e.g. This role allows users to create a new claim 
| ... | ... 


### 3.3 Key business processes

#### 3.3.1 Example Process Name

Eiusmod eu eu sit est minim labore laboris incididunt veniam dolor. Esse velit ad ad non pariatur in cupidatat deserunt dolore excepteur id sit labore. Adipisicing nulla tempor incididunt eu nisi cupidatat consectetur in nisi. Tempor duis esse id eiusmod officia reprehenderit ad qui incididunt Lorem minim aliquip. Consequat enim culpa ipsum ut dolor pariatur Lorem eiusmod consectetur adipisicing reprehenderit.

Id voluptate proident adipisicing aute cupidatat sunt irure qui pariatur reprehenderit. Elit qui qui proident ex occaecat ullamco velit sint sint quis. Qui aliqua pariatur ad ea nulla et ipsum laboris ea cupidatat. Cupidatat sit in pariatur esse ut. Anim pariatur exercitation non aliquip aliqua aliqua sunt duis ex ex ad quis.

*Insert Diagram here*
<img src="/diagrams/examples/Business-Process-View.jpg">

<img src="/diagrams/examples/Business-Process-View-With-Swimlanes-As-Roles-of-a-Process-A-Layered-Approach-2-1.jpg">

#### 3.3.2 *Process Name*

Process Description

*Insert Diagram here*


<hr />

## 4. Data Architecture

### 4.1 Data Entities

| Ref No.         | Name | Description | Source of Truth |
| ------------- | ------------- | ------------- | ------------- |
| DEO1 | e.g. User |  |  e.g. Active Directory
| ... | ... | ... | ...

### 4.2 Conceptual Data Model

*Add a conceptual ERD here*

### 4.3 Logical Data Model

*Add a logical ERD here* 

<hr />

## 5. Application Architecture

*Add an application diagram and description here*
<img src="/diagrams/examples/Application-Architecture-768x497.jpg">

### 5.1 Logical Application Components

| Ref No.         | Name | Description | Vendor/Supported by | Strategic Alignment |
| ------------- | ------------- | ------------- | ------------- |  ------------- | 
| APCO1 | e.g. Notify | e.g. Provides SMS, Email notifications |  e.g. GDS | Strategic | 
| ... | ... | ... | ... | ...

<hr />

## 6. Solution Delivery

### 6.1 Implementation Plan

### 6.2 Roadmap

> Detail the component roadmap

<img src="/diagrams/examples/Implementation-Roadmap-View-1.jpg">

### 6.3 Work Packages

> List the individual work packages which will be required to realise this solution


| Name | Description | Supplier | Strategy | Status |
| ------------- | ------------- | ------------- |  ------------- | ------------- | 
| Web Portal | Develop a bespoke web portal which provides the core functionality to citizens | Internal Development | Build | To be delivered
| Gov.uk Pay | Provide a way for citizens to make online payments | GDS | Buy | Awaiting Procurement
| ... | ... | ... | ... | ...


## 7. Solution Management

### 7.1 System Support and Incident Management

### 7.2 Backup/Restore/Data Retention
