# Customer Validation Rule Project

## Requirement
Active customers must have an email address.

## Solution
Created Validation Rule:

AND(
ISPICKVAL(Status__c, "Active"),
ISBLANK(Email__c)
)

## Result
Salesforce prevents saving Active customers without an email address.

## Learning
Validation Rules enforce business rules and improve data quality.
