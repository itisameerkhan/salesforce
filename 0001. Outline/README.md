<div align="center">
<img src="https://www.salesforcesathish.com/wp-content/uploads/2022/01/SF_Cerification_1440x810.png" />
</div>
<br>


# Outline

### ✨Developer Fundamentals

* Understand multi-tenant concepts and design frameworks, such as MVC architecture and Lightning Component Framework.

* Given a scenario, identify common use cases and best practices for declarative versus programmatic customizations, including governor limits, formula fields, and roll-up summaries.

* Given a scenario, determine, create, and access the appropriate data model including objects, fields, relationships, and external IDs.

* Given a scenario, identify the options and considerations when importing and exporting data into development environments.


### ⚡ MVC Architecture 



**What is MVC Architecture in Salesforce?**

**Model-view-controller (MVC) Architecture in Salesforce is a software pattern that separates information representation from user interaction. It divides the application into three manageable parts.**

<div align="center">
<img src="https://s2-labs.com/wp-content/uploads/2019/04/mvc.webp" />
</div>
<br>

In Salesforce development, the MVC (Model-View-Controller) architecture divides an app into three parts: the Model, View, and Controller. The Model handles data and rules, like what information to store and how to process it, while the View is all about how things look to users, like buttons and forms. The Controller acts as the go-between, taking user actions, talking to the Model to get or change data, and then updating the View to show any changes. This setup helps keep things organized, making it easier to build and improve apps over time. It's like having separate teams for planning (Model), designing (View), and coordinating (Controller) a project, all working together to make something awesome!

**UI View**- HTML, CSS, JS (VF Page, LWG, Aura, Page Layout, Flexi Page) 

**Data Model** / Data - **Model** - Oracle, MySQL, MongoDB ( Object. Fields ) 

**Business Logic** - **Controller** - Code Java, NodeJS (Apex. Trigger Flows. Process Buider, Workflows, Approval Process)

Certainly! Here's a breakdown of the MVC-like components in Salesforce development using the provided analogy:

1. **UI View (User Interface):**
   - HTML, CSS, JS: These are the standard web technologies used to create user interfaces. In the Salesforce context, you can achieve UI views using:
     - Visualforce Pages: Markup language for building custom UIs in Salesforce.
     - Lightning Web Components (LWC): Modern framework for building interactive UI components.
     - Aura Components: Legacy framework for building dynamic UI components.
     - Page Layouts: Configuration settings to arrange fields and sections on Salesforce record pages.
     - Flexi Pages: Customizable pages for Salesforce Lightning Experience.

2. **Data Model / Data (Model):**
   - Oracle, MySQL, MongoDB: These are database systems used to store and manage data. In Salesforce, the data model is represented by:
     - Salesforce Objects: Entities that represent different types of data (e.g., Account, Contact, Opportunity).
     - Fields: Attributes that define the properties and characteristics of data stored in Salesforce objects.

3. **Business Logic (Controller):**
   - Code Java, NodeJS: Programming languages used to implement business logic. In Salesforce, the controller components include:
     - Apex: Server-side programming language used to write custom logic and process data in Salesforce.
     - Triggers: Apex code that executes before or after data manipulation operations (e.g., insert, update, delete) on Salesforce objects.
     - Flows: Visual workflows that automate business processes without code.
     - Process Builder: Point-and-click tool for automating business processes and workflows.
     - Workflows: Automated processes triggered by record changes and criteria evaluation.
     - Approval Processes: Sequential processes for approving records based on predefined criteria.

### ✨ Declarative and Programmatic

1. **Model (M):**
   - Objects: In Salesforce, objects represent the data model. They include standard objects (e.g., Account, Contact, Opportunity) and custom objects created by users to store specific types of data.
   - Fields: Fields define the attributes and properties of objects, such as text fields, picklists, and checkboxes.
   - Relationship Fields: Relationship fields establish connections between objects, such as lookup relationships and master-detail relationships.

2. **View (V):**
   - App: An app in Salesforce is a collection of tabs that provide access to different functionalities. Apps organize and display related tabs and objects to users based on their roles and permissions.
   - Tab: Tabs are user interface elements that provide access to specific objects, list views, or Visualforce pages within Salesforce. They allow users to navigate and interact with different parts of the application.
   - Page Layout: Page layouts define the arrangement and organization of fields, related lists, and buttons on record detail pages in Salesforce. They determine how information is presented to users and what actions they can take.
   - Flexi Page: Flexi pages are customizable pages in Salesforce Lightning Experience that allow users to design and arrange components (e.g., charts, reports, related lists) based on their preferences.
   - Quick Action: Quick actions are shortcuts or buttons that allow users to perform common tasks (e.g., creating records, sending emails) directly from list views, record detail pages, or home pages.
   - Global Action: Global actions are quick actions that are accessible from any page in Salesforce, allowing users to perform actions like creating records or logging calls from anywhere in the application.
   - List Views: List views display a filtered list of records from an object, allowing users to view, search, and perform bulk actions on multiple records at once.

3. **Controller (C):**
   - Workflow Rules: Workflow rules automate business processes by defining criteria and actions that trigger automated tasks (e.g., field updates, email alerts) based on record changes.
   - Process Builder: Process Builder is a visual tool for designing and automating business processes using a simple point-and-click interface. It allows users to define complex processes with multiple criteria and actions.
   - Flows: Flows are visual workflows that automate complex business processes and guide users through interactive screens and decision branches. They can be used to streamline data entry, automate approvals, and integrate with external systems.
   - Approval Process: Approval processes automate the approval of records (e.g., sales opportunities, expense reports) by defining criteria, approval steps, and approval actions to be taken based on user responses.

## ⭐ Salesforce Application Development Tools 