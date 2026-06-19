# Record Triggered Flow - Customer Active Task Flow

## Requirement

When a Customer record is updated, automatically create a follow-up Task.

---

## Flow Type

Record-Triggered Flow

---

## Object

Customer

---

## Trigger

A record is updated

---

## Flow Configuration

- Object: Customer
- Trigger: Record Updated
- Optimize For: Actions and Related Records

---

## Action

Create Records

Object: Task

Field Values:

| Field | Value |
|---------|---------|
| Subject | Follow Up With Customer |
| Status | Not Started |
| Priority | Normal |

---

## Challenge Faced

The flow was not creating Tasks initially.

### Root Cause

Assigned To ID field mapping caused the flow to fail.

### Resolution

Removed the Assigned To ID mapping and activated a new flow version.

---

## Result

Successfully created Tasks automatically whenever the Customer record was updated.

---

## Key Learnings

- Record Triggered Flow
- Create Records Element
- Flow Activation
- Flow Versioning
- Troubleshooting Flow Errors
- Task Automation
