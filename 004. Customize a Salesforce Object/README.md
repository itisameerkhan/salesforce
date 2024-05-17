# 📍 Customize a Object in Salesforce

<div align="center">
<img src="https://www.bacancytechnology.com/blog/wp-content/uploads/2023/04/Examples-of-Salesforce-Objects.webp" alt="demo" />
</div>

## ⭐ Lookup Relationship

* In Salesforce, a lookup relationship is a way to connect two objects together based on a common field.

* With a lookup relationship, one object (the child) has a reference (or lookup field) to another object (the parent).

* This allows you to establish a link between records of the child object and the parent object.

* In a lookup relationship, the child record can exist without a parent record, and the relationship is not required.

* Lookup relationships are typically used when there is a loose or optional connection between objects.

* For example, in a CRM system, you might have a lookup relationship between the "Contact" object and the "Account" object. Each contact can be associated with one account, but it's not mandatory for a contact to have an account.

#### Example

* **Lookup Relationship**: In this scenario, you would create a lookup relationship between the "Contact" object and the "Account" object. Each contact (representing a person) can be associated with an account (representing a company).

* **Real-time Example**: Let's say you're managing contacts for a sales team. Each contact (e.g., John Doe) belongs to a specific account (e.g., ABC Company). By creating a lookup relationship between the "Contact" object and the "Account" object, you can easily link John Doe to the ABC Company account. This allows you to view all contacts associated with a particular account, making it easier to track relationships and communications.
## ⭐ Master Detail Relationship

* A master-detail relationship in Salesforce is a more tightly-coupled connection between two objects.

* With a master-detail relationship, one object (the detail) is dependent on another object (the master).

* The master object controls certain behaviors of the detail object, such as record ownership and deletion behavior.

* In a master-detail relationship, the detail record cannot exist without a corresponding master record.

* Master-detail relationships are typically used when there is a strict and mandatory relationship between objects.

* For example, in a project management system, you might have a master-detail relationship between the "Project" object and the "Task" object. Each task belongs to exactly one project, and if the project is deleted, all associated tasks are also deleted.

#### Example 

* **Master-Detail Relationship**: In this scenario, you would create a master-detail relationship between the "Task" object and the "Project" object. Each task (representing a specific task or activity) is associated with a project (representing a larger project or initiative).

* **Real-time Example**: Imagine you're managing a software development project. Each task (e.g., "Develop Login Page," "Test Database Integration") is part of a larger project (e.g., "Website Redesign Project"). By creating a master-detail relationship between the "Task" object and the "Project" object, you can ensure that each task is linked to a specific project. This allows you to track progress, assign tasks, and analyze project performance more effectively. Additionally, if the project is deleted, all associated tasks will also be deleted, ensuring data integrity and consistency.