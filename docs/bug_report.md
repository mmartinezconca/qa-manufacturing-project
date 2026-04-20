# Bug Report

This report summarizes data validation defects identified during QA testing of the batch dataset grouped by severity

----------------------------------

## High Severity Issues

### BUG01 - Negative or zero quantity
* **Test Case:** TC01
* **Description:** Records contain zero or negative quantities
* **Affected Rows:** B004, B010
* **Impact:** Could lead to incorrect inventory calculations

### BUG02 - Duplicate batch IDs
* **Test Case:** TC02
* **Description:** Records contain duplicate baych IDs
* **Affected Rows:** B004, B010
* **Impact:** Could lead to incorrect inventory calculations

### BUG03 - Missing Production Date
* **Test Case:** TC01
* **Description:** Records contain zero or negative quantities
* **Affected Rows:** B004, B010
* **Impact:** Could lead to incorrect inevntory calculations

