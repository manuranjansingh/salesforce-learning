# Automation Basics

## Introduction

Automation in Salesforce helps reduce manual work by automatically performing actions based on predefined rules and conditions.

Benefits:

* Saves time
* Reduces human errors
* Improves productivity
* Standardizes business processes

---

## Workflow Rules

Workflow Rules are automation tools used to perform actions when specific criteria are met.

Actions:

* Email Alert
* Field Update
* Task Creation
* Outbound Message

Example:

When a Case is closed, send an email notification to the customer.

### Limitations

* Supports simple automation
* No longer recommended for new implementations

---

## Process Builder

Process Builder provides advanced automation capabilities compared to Workflow Rules.

Features:

* Multiple IF/THEN conditions
* Record creation
* Record updates
* Invoking flows

Example:

When an Opportunity is marked Closed Won, automatically create a follow-up task.

### Note

Salesforce recommends using Flow instead of Process Builder for new automation.

---

## Flow

Flow is Salesforce's primary automation tool.

Capabilities:

* Create records
* Update records
* Delete records
* Send emails
* Call Apex actions
* Screen-based user interactions

Types of Flows:

* Record-Triggered Flow
* Scheduled Flow
* Screen Flow
* Autolaunched Flow

Example:

Automatically assign new Leads to the appropriate sales team.

### Advantages

* Most powerful automation tool
* Replaces Workflow Rules and Process Builder
* Highly flexible

---

## Approval Process

An Approval Process automates record approvals.

Process:

1. Submit record for approval
2. Approver reviews request
3. Approve or reject
4. Salesforce performs configured actions

Example:

Manager approval required for discounts above 20%.

---

## Workflow Rule vs Process Builder vs Flow

| Feature            | Workflow Rule | Process Builder | Flow |
| ------------------ | ------------- | --------------- | ---- |
| Simple Automation  | Yes           | Yes             | Yes  |
| Complex Logic      | No            | Limited         | Yes  |
| Multiple Actions   | Limited       | Yes             | Yes  |
| Future Recommended | No            | No              | Yes  |
| Most Powerful      | No            | No              | Yes  |

---

## Summary

Workflow Rules and Process Builder were earlier automation tools in Salesforce. Today, Flow is the recommended automation solution because it provides advanced capabilities and flexibility for business processes.
