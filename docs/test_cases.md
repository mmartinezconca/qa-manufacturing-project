# Test Cases

## TC01 - Negative Quantity Check
* Requirement: R1
* Description: Validate that batch quantity is positive
* Expected Result: Records with quantities less than or equal to 0 should be flagged

## TC02 - Future Date Check
* Requirement: R2
* Description: Validate production date is not in the future 
* Expected Result: Future production dates should be flagged

## TC03 - Missing Production Date Check
* Requirement: R2
* Description: Validate production is not null
* Expected Result: Null values are flagged

## TC04 - Invalid Status Check
* Requirement: R3
* Description: Validate status is within allowed values
* Expected Result: Invalid statuses are flagged

## TC05 - Duplicate Batch ID Check
* Requirement: R4
* Description: Validate batch IDs are unique
* Expected Result: Duplicate IDs are flagged
* 
