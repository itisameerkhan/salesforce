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

1. **Salesforce Lightning Platform:**
   - The Salesforce Lightning Platform serves as the foundation for building and deploying custom applications on Salesforce. It provides a suite of tools and services for declarative and programmatic development, including:
     - **App Builder:** A visual tool for designing custom user interfaces using Lightning Components.
     - **Process Builder:** A point-and-click tool for automating business processes and workflows.
     - **Flow Builder:** A visual workflow tool for creating guided user experiences and automating complex business processes.
     - **Schema Builder:** A graphical interface for designing custom data models and relationships between objects.
     - **Security Controls:** Built-in security features for controlling access to data and features within applications.

2. **Apex:**
   - Apex is a powerful, object-oriented programming language used for building custom business logic and data manipulation operations on the Salesforce platform. Developers can write Apex code to create custom controllers, triggers, batch processes, and web services that extend the functionality of Salesforce applications.

3. **Visualforce:**
   - Visualforce is a markup language that allows developers to build custom user interfaces and pages within Salesforce applications. Developers can use Visualforce to create custom layouts, forms, and interactive components using a mix of HTML-like tags and Apex code.

4. **Lightning Web Components (LWC):**
   - Lightning Web Components is a modern framework for building responsive and performant web components on the Salesforce platform. LWC leverages standard web technologies like HTML, CSS, and JavaScript, and provides a lightweight, standards-based approach to building custom user interfaces.

5. **Salesforce DX (Developer Experience):**
   - Salesforce DX is a set of tools and features designed to enhance the development lifecycle and collaboration among developers. It includes:
     - **Command-Line Interface (CLI):** A command-line tool for managing Salesforce projects, automating tasks, and interacting with the Salesforce platform.
     - **Scratch Orgs:** Disposable, customizable environments for developing and testing Salesforce applications in isolation.
     - **Version Control Integration:** Integration with version control systems like Git for managing source code and collaborative development.

6. **Heroku:**
   - Heroku is a cloud application platform that supports multiple programming languages (e.g., Node.js, Ruby, Python) and provides a flexible environment for building, deploying, and scaling applications independently of Salesforce. Developers can use Heroku to build custom applications and integrations that extend Salesforce capabilities.

7. **AppExchange:**
   - The Salesforce AppExchange is a marketplace for third-party applications and integrations built on the Salesforce platform. Developers can publish and distribute their applications on the AppExchange to reach Salesforce customers and partners worldwide.

### ✨ Fields 

In Salesforce, fields are the building blocks of data storage, representing individual pieces of information within a record. They define the attributes and properties of objects, allowing users to capture, store, and organize data effectively. There are two main types of fields in Salesforce: standard fields and custom fields.

#### 🌐Standard Fields 

Standard fields are predefined by Salesforce and are available out-of-the-box in every Salesforce org. They represent common data types and are commonly used across various standard objects. Some examples of standard fields include:

* **Name**: A compound field that typically includes fields like First Name and Last Name, used for storing names of individuals or accounts.
 
* **Email**: A field for storing email addresses.
* **Phone**: A field for storing phone numbers.
* **Date**: A field for storing dates without a time component.
* **Text**: A field for storing alphanumeric text.

#### Audit fields 

n Salesforce, audit fields are standard fields automatically included in every object that help track changes to records and provide valuable insights into record history and activity. These fields capture metadata about when a record was created, last modified, and who made the changes. 


1. **Created By:**
   - The "Created By" field stores the Salesforce user who originally created the record. It records the user's username, profile, and user ID. This field is useful for tracking the creator of a record and understanding its origin.

2. **Created Date:**
   - The "Created Date" field records the date and time when the record was initially created in Salesforce. It provides a timestamp indicating when the record was added to the system.

3. **Last Modified By:**
   - The "Last Modified By" field stores the Salesforce user who most recently modified the record. Similar to the "Created By" field, it includes details about the user's username, profile, and user ID.

4. **Last Modified Date:**
   - The "Last Modified Date" field records the date and time of the most recent modification to the record. It updates automatically whenever the record is edited or updated, providing a timestamp for the last activity on the record.

5. **System Modstamp:**
   - The "System Modstamp" field, also known as the "LastModifiedDate" field, is a system-generated timestamp that reflects the most recent modification to the record. It differs from the "Last Modified Date" field in that it captures changes made to the record itself, as well as changes made to related records or metadata that affect the record.

###  ✨ Custom field

Custom fields are created by users to extend the standard data model and capture additional information specific to their organization's requirements. They allow organizations to tailor Salesforce to their unique business processes and workflows. Some examples of custom fields include:

   - **Custom Text:** A field for storing custom text or alphanumeric data.

   - **Custom Number:** A field for storing numerical values, such as quantities or amounts.
   - **Custom Date/Time:** A field for storing date and time values, including both date and time components.
   - **Custom Picklist:** A field with a custom set of values defined by the user, allowing for more specific categorization or classification of data.
   - **Custom Lookup Relationship:** A field that establishes a relationship with another object, allowing users to link records between objects.
   - Custom fields are created and managed through the Salesforce Setup menu, allowing administrators and developers to define the data types, labels, picklist values, and other properties of the field. They can be added to both standard and custom objects to capture additional information beyond what is provided by standard fields.

<br>
<br>


# 🚀 Apex Programming

Apex is a powerful, strongly typed, object-oriented programming language used in Salesforce for building custom business logic, automating processes, and extending the capabilities of the Salesforce platform. Here's a comprehensive explanation of Apex programming:

1. **Server-Side Language:**
   - Apex runs entirely on the Salesforce servers, making it a server-side language. This means that Apex code executes within the Salesforce environment and interacts directly with the underlying database, business logic, and user interface components.

2. **Object-Oriented:**
   - Apex is an object-oriented language, meaning it supports concepts such as classes, objects, inheritance, polymorphism, and encapsulation. Developers can define custom classes and objects to encapsulate data and behavior, promoting modularity, reusability, and maintainability in their code.

3. **Data Manipulation:**
   - Apex allows developers to perform data manipulation operations on Salesforce objects (records) using a powerful set of APIs called the Salesforce Object Query Language (SOQL) and Salesforce Object Search Language (SOSL). Developers can query, insert, update, upsert, delete, and undelete records to interact with Salesforce data.

4. **Business Logic:**
   - Apex enables developers to implement custom business logic and rules using triggers, which are Apex code blocks that execute before or after specific data manipulation operations (e.g., insert, update, delete) on Salesforce objects. Triggers allow developers to enforce complex validation rules, perform data transformations, and trigger additional actions based on specific criteria.

5. **Web Services:**
   - Apex supports the creation of custom web services using Apex REST and SOAP web service annotations. Developers can expose custom Apex methods as RESTful or SOAP web services, allowing external systems to interact with Salesforce and perform operations on Salesforce data programmatically.

6. **Integration:**
   - Apex facilitates integration with external systems and services through callouts. Developers can make outbound HTTP requests to external endpoints, consume external web services, and interact with third-party APIs using Apex callouts. This enables seamless integration between Salesforce and other systems, such as ERP systems, marketing platforms, and payment gateways.

7. **Asynchronous Processing:**
   - Apex supports asynchronous processing through future methods, queueable Apex jobs, batch Apex, and scheduled Apex. These mechanisms allow developers to offload time-consuming or resource-intensive tasks to run asynchronously in the background, improving application performance and scalability.

8. **Testing Framework:**
   - Apex provides a robust testing framework for writing and executing unit tests to validate the behavior and functionality of Apex code. Developers can create test classes and methods to simulate different scenarios, assert expected outcomes, and ensure code quality and reliability.

9. **Governor Limits:**
   - Apex enforces governor limits to ensure fair resource usage and prevent abuse of system resources. These limits include restrictions on CPU time, heap size, database queries, DML operations, and callouts. Developers must adhere to these limits to ensure efficient and scalable Apex code execution.

```apex
public class HelloWorld {
    public static void main() {
        System.debug('Hello, World!');
    }
}

