# Flow Builder Basics

## Introduction

Flow Builder is Salesforce's primary automation tool.

It helps automate business processes without writing code.

---

## What Can Flow Do?

- Create Records
- Update Records
- Delete Records
- Send Emails
- Route Approvals
- Automate Processes

---

## Types of Flows

### Record-Triggered Flow

Runs automatically when a record is created or updated.

Example:

Automatically assign Leads.

---

### Scheduled Flow

Runs at a specified time.

Example:

Daily reminder emails.

---

### Screen Flow

Provides a user interface.

Example:

Guided data entry process.

---

### Autolaunched Flow

Runs in the background without user interaction.

---

## Flow Components

### Start

Defines how the flow begins.

### Decision

Adds conditional logic.

### Assignment

Stores values in variables.

### Create Records

Creates new records.

### Update Records

Updates existing records.

### Delete Records

Deletes records.

---

## Example

Business Requirement:

When a Lead is created, assign it to the Sales Queue.

Flow:

1. Lead Created
2. Check Criteria
3. Assign Queue
4. Save Record

---

## Why Flow is Important

Salesforce recommends Flow as the replacement for:

- Workflow Rules
- Process Builder

---

## Summary

Flow Builder is the most powerful no-code automation tool in Salesforce and is used to automate business processes efficiently.
