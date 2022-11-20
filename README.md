# Leave Management System
## Introduction
Leave management system is a system that manages the leave of employees in an organization. It is a web-based application that is used to automate the process of applying for leave, processing leave applications, and approving leave applications.

## Project overview
The leave management system will be able to do the following:

* Apply for leave. The user will be able to apply for leave. The user will be redirected to the leave application page. The leave application page will have the following fields.:

    * Leave type. The user will be able to selecte the type of leave they want to apply for. The leave types will be fetched from the database. The leave types will be displayed in a drop-down list.
    * Start date. The user will be able to select the start date of the leave. The start date will be displayed in a calendar.
    * End date. The user will be able to select the end date of the leave. The end date will be displated in a calendar.
    * Reason. The user will be able to enter the reason for the leave. The reason will be saved in the database.
    * Attachment. The user will be able to attach a file to the leave application. The file will be saved in the database.
    * Submit. The user will be able to submit the leave application. The leave application will be saved in the database. The user will be redirected to the leave application list page. The leave application list page will display all the leave applications in the database. The leave application list page will have a search box that will enable the user to search for a leave application by name or ID. The leave application list page will have a button that will enable the user to add a new leave application. 
    
    The leave application list page will have a button that will enable the user to edit a leave application. The leave application list page will have a button that will enable the user to delete a leave application. The leave application list page will have a button that will enable the user to view a leave application's details. The leave application list page will have a button that will enable the user to print a leave application's details.

* Process leave application. The user will be able to process a leave application. Te user will be redirected to the leave application list page. The leave application list page will display all the leave applications in the database. The leave application list page will have a button that will enable the user to search for a leave application by name or ID.

The leave application list page will have a button that will enable the user to add a new leave application. The leave application list page will have a button that will enable the user to edit a leave application. The leave application list page will have a button that will enable the user to delete a leave application. The leave application list page will have a button that will enable the user to view a leave application's details.

The leave application list page will have a button that will enable the user to print a leave application's details. The leave application list page will have a button that will enable the user to approve a leave application. The leave application list page will have a button that will enable the user to reject a leave application.

The leave application list page will have a button that will enable the user to cancel a leave application. The leave application list page will have a button that will enable the user to view the leave application's history. The leave application list page will have  button that will enable the user to view the leave application's comments. The leave application list page will have a button that will enable the user to add a comment to the leave application. The leave application list page will have a button that will enable the user to view the leave application's attachments.

The leave application list page will have a button that will enable the user to add an attachment to the leave application. The leave application list page will have a button that will enable the user to view the leave application's workflow. The leave application list page will have a button that will enable the user to view the leave application's workflow history. The leave application list page will have a button that will enable the user to view the leave application's workflow comments.

The leave application list page will have a button that will enable the user to add a workflow comment to the leave application. The leave application list page will have a button that will enable the user to view the leave application's workflow attachments. The leave application list page will have a button that will enable the user to add a workflow attachment to the leave application. The leave application list page will have a button that will enable the user

* Approve leave application. The user will be able to approve a leave application. The user will be redirected to the leave application list page. The leave application list page will display all the leave applications in the database. The leave application list page will have a search box that will enable the user to search for a leave application by name or ID. 

The leave application list page will have a button that will enable the user to add a new leave application. The leave application list page will have a button that will enable the user to edit a leave application. The leave application list page will have a button that will enable the user to delete a leave application. 

The leave application list page will have a button that will enable the user to view a leave application's details. The leave application list page will have a button that will enable the user to print a leave application's details. The leave application list page will have a button that will enable the user to approve a leave application. The leave application list page will have a button that will enable the user to reject a leave application. The leave application list page will have a button that will enable the user to cancel a leave application. The leave application list page will have a button that will enable the user to view the leave application's history. The leave application list page will have a button that will enable the user to view the leave application's comments.

 The leave application list page will have a button that will enable the user to add a comment to the leave application. The leave application list page will have a button that will enable the user to view the leave application's attachments. The leave application list page will have a button that will enable the user to add an attachment to the leave application. The leave application list page will have a button that will enable the user to view the leave application's workflow. The leave application list page will have a button that will enable the user to view the leave application's workflow history. 
 
 The leave application list page will have a button that will enable the user to view the leave application's workflow comments. The leave application list page will have a button that will enable the user to add a workflow comment to the leave application. The leave application list page will have a button that will enable the user to view the leave application's workflow attachments. The leave application list page will have a button that will enable the user to add a workflow attachment to the leave application. The leave application list page will have a button that will enable the

## Tools used
- Apache Tomcat v9.0
- I am using the `layout-combo.html` which is a template from Tabler. I have already created a template that I will use when starting a new page. I have named it `My template for this and other projects too.jsp`.

## The design

This is the system design that I am using for this project.

![Leave management system design flow chart drawio](https://user-images.githubusercontent.com/33565767/202431260-930c3790-7937-429d-b6b9-293a85c8f9ff.png)

## The steps are:
1. User receives form from registry.
2. Selects leave type and applies for leave.
3. Send to section head(Director).
4. Approved by section head(Director).
5. Send to Chief officer or sub county administrator.
6. Approved by Chief Officer or sub county administrator.
7. Congratulations! You can now go for leave notification.

### 1. User receives form from registry
Things needed in the form are: 
- name, 
- Job title, 
- P/No, 
- Department, 
- when to start leave, 
- date applied, 
- who to leave duties to, 
- the leave type, 
- the amount of days requested, 
- any other remarks.

### 2. Selects leave type and applies for leave
- Annual, 
- Maternity, 
- Paternity, 
- Compassionate.

### 3. Send to section head(Director)

### 4. Approved by section head(Director)
- Recommend days
- Approve or decline

### 5. Send to Chief officer or sub county administrator.
- Approve or decline

### 6. Approved by Chief Officer or sub county administrator.
- Approve or decline




