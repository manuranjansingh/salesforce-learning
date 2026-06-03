# Security & Access

## Introduction

Salesforce provides multiple layers of security to protect organizational data and control user access.

## Organization-Wide Defaults (OWD)

OWD defines the baseline level of access for records.

Common settings:
- Private
- Public Read Only
- Public Read/Write

## Role Hierarchy

Role Hierarchy allows users higher in the hierarchy to access records owned by users below them.

Example:

CEO
└── Manager
    └── Employee

## Sharing Rules

Sharing Rules provide additional record access beyond OWD settings.

Types:
- Owner-Based Sharing Rules
- Criteria-Based Sharing Rules

## Profiles

Profiles define what users can do.

Profiles control:
- Object access
- Field access
- App access
- User permissions

## Permission Sets

Permission Sets grant additional permissions without modifying profiles.

Benefits:
- Flexible access control
- Temporary access assignment
- Additional object permissions

## Security Model Summary

Salesforce security is built using:

1. Organization-Wide Defaults (OWD)
2. Role Hierarchy
3. Sharing Rules
4. Profiles
5. Permission Sets

Together these components help secure data while providing appropriate user access.
