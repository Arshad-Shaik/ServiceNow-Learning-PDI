# ServiceNow Learning / ServiceNow Developer

## Why I'm Learning

I am learning ServiceNow practically to understand how it works in real-world scenarios. My goal is to learn how ServiceNow Developers, Support Engineers, ServiceNow Administrators, ITSM teams, Business Analysts, and other stakeholders collaborate on projects. I want to understand how requirements are gathered, how tasks are assigned to ServiceNow Developers, how applications are built on the ServiceNow platform, and how business workflows are automated. Through this hands-on learning, I aim to develop the skills required to become a ServiceNow Developer or ServiceNow Engineer.


## Where to Gain Practical Experience

To gain practical experience with ServiceNow, you can use the free ServiceNow cloud environment called the ServiceNow Personal Developer Instance (PDI).


## PDI

“PDI = Personal Developer Instance”

PDI is a free personal ServiceNow cloud instance used for learning, development, testing, and building applications.


## What ServiceNow Actually Is

ServiceNow is NOT just ticket tool. It is workflow automation platform so, It automates company work.


## Without ServiceNow

Employee emails manager manually.


## With ServiceNow

* Form submitted
* Approval triggered
* Tasks created automatically
* Notifications sent
* Status tracked automatically


## INTERNAL WORKING

Everything in ServiceNow runs on:


TABLES : “Everything in ServiceNow is stored in tables.”

Examples:

* Incident table
* User table
* Change table
* Asset table


Example Image:

![alt text](image.png)

"This record is stored in Incident table."


## What is a table in ServiceNow?

A table stores records/data in rows and columns similar to a database table.



## REAL COMPANY INTERNAL FLOW

Now understand how real developers work.

**Example Project: Employee Onboarding Automation**

**Business Requirement:**

“When employee joins:

* manager approval needed
* laptop task create
* ID card task create
* HR notification send”



**Developer does:**

1. Create form
2. Create table
3. Create workflow
4. Add approvals
5. Add automation scripts
6. Add notifications
7. Test process
8. Deploy

This is REAL ServiceNow work.










# Day 01 - Incident Basics

## What is an Incident?

An Incident is an unplanned interruption or reduction in the quality of an IT service that needs to be restored as quickly as possible.

## Real Examples

* Laptop WiFi not working
* VPN not connecting
* Email not working
* Printer issue, etc.,

## Incident Lifecycle

User Problem

↓

Incident Created

↓

Assigned

↓

In Progress

↓

Resolved

↓

Closed


## Important Fields

### Number

Unique identifier of an Incident.

**Example:**
INC0010001

### Caller

The user who reported the issue.

### State

Current status of the Incident.

**Examples:**

* New
* In Progress
* Resolved
* Closed

### Urgency

How quickly the issue needs attention.

### Priority

Determines the order in which incidents are handled.

### Short Description

One-line summary of the issue.

## Practical Work

Created Incident:

* INC0010001 - Laptop WiFi not working
* INC0010002 - VPN not connecting

## Interview Questions

### What is an Incident?

An Incident is an unplanned interruption to an IT service that needs to be restored quickly.

### Why do we use Incidents?

To track, manage, assign, resolve, and monitor user issues.






