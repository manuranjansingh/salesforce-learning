# Validation Rules

## Introduction

Validation Rules ensure that users enter data according to business requirements.

They prevent incorrect or incomplete data from being saved.

---

## Why Use Validation Rules?

Benefits:

- Improve data quality
- Enforce business rules
- Reduce manual errors
- Maintain consistency

---

## How Validation Rules Work

Validation Rules evaluate data when a record is created or updated.

If the condition is TRUE:
- Record is not saved
- Error message is displayed

If the condition is FALSE:
- Record is saved successfully

---

## Example 1

Business Requirement:

Opportunity Amount must be greater than 0.

Formula:

Amount <= 0

Error Message:

Amount must be greater than zero.

---

## Example 2

Business Requirement:

Phone Number is mandatory.

Formula:

ISBLANK(Phone)

Error Message:

Phone Number is required.

---

## Common Functions

- ISBLANK()
- ISPICKVAL()
- LEN()
- AND()
- OR()
- NOT()

---

## Best Practices

- Write clear error messages
- Keep formulas simple
- Test thoroughly
- Document validation rules

---

## Summary

Validation Rules help maintain data accuracy by preventing users from entering invalid information.

## Hands-On Practice #1

### Requirement

Phone Number should be mandatory while creating an Account.

### Validation Rule Created

**Rule Name:** Phone_Mandatory

**Formula:**

