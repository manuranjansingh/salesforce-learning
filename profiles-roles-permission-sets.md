# Profiles, Roles & Permission Sets

## Introduction

Profiles, Roles, and Permission Sets are key Salesforce security components used to control user access.

They help determine:

* What users can do
* What data users can see
* What records users can access

---

## What is a Profile?

A Profile controls what a user can do in Salesforce.

A user must have one Profile.

Profiles control:

* Object permissions
* Field permissions
* User permissions
* App access
* Tab visibility

Examples:

* System Administrator
* Standard User
* Read Only User

---

## What is a Role?

A Role controls record-level visibility through the role hierarchy.

Roles determine which records users can view.

Example:

```text
CEO
├── Sales Manager
│   ├── Sales Executive 1
│   └── Sales Executive 2
```

A Sales Manager can view records owned by Sales Executives below them in the hierarchy.

---

## What is a Permission Set?

A Permission Set provides additional permissions without changing a user's profile.

A user can have:

* One Profile
* Multiple Permission Sets

Example:

Profile:

* Standard User

Permission Set:

* Export Reports
* Manage Campaigns

This allows temporary or additional access without modifying the profile.

---

## Profile vs Role

| Profile             | Role                  |
| ------------------- | --------------------- |
| Controls actions    | Controls visibility   |
| Mandatory           | Optional              |
| One per user        | One per user          |
| Defines permissions | Defines record access |

---

## Profile vs Permission Set

| Profile                       | Permission Set           |
| ----------------------------- | ------------------------ |
| Required                      | Optional                 |
| One per user                  | Multiple allowed         |
| Base permissions              | Additional permissions   |
| Assigned during user creation | Assigned later as needed |

---

## Real-World Example

User: Support Executive

Profile:

* Read Cases
* Create Cases
* Edit Cases

Role:

* Support Team Member

Permission Set:

* Export Reports

Result:

The user performs support activities, sees records based on role hierarchy, and receives additional report export permissions through the permission set.

---

## Best Practice

* Use Profiles for baseline access
* Use Roles for record visibility
* Use Permission Sets for additional access
* Avoid creating too many custom profiles

---

## Summary

Profiles control what users can do, Roles control what records users can see, and Permission Sets provide additional permissions without changing the user's profile.
