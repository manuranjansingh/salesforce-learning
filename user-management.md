# User Management

## What is a User?

A User is an individual who can log in and access Salesforce based on assigned permissions.

## Profiles

Profiles determine what users can do in Salesforce.

Profiles control:
- Object permissions
- Field permissions
- App access
- User permissions

## Roles

Roles determine what records users can see.

Roles help create a role hierarchy for record visibility.

## Permission Sets

Permission Sets provide additional permissions to users without changing their profile.

Benefits:
- Flexible access management
- Temporary permissions
- Additional object access

## Role Hierarchy

Role hierarchy allows users higher in the hierarchy to access records owned by users below them.

Example:

CEO
└── Manager
    └── Employee

Managers can access employee records based on sharing settings.

## Summary

Users, Profiles, Roles, and Permission Sets work together to manage access and security in Salesforce.
