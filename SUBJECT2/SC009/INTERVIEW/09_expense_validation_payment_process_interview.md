# SBMN Interview Report

## Process Information

**Process Name:** Expense Validation and Payment Process\
**Domain:** Financial Management

## Activities

1.  Register Expense
2.  Validate Expense
3.  Reject Payment
4.  Make Payment
5.  Inform Merchant

## Number of Questions Asked

Total interview questions: 10

## Final SBMN Relations

### DEP

-   Validate Expense DEP Register Expense
-   Inform Merchant DEP Reject Payment

### REQ

-   Reject Payment REQ Validate Expense
-   Make Payment REQ Validate Expense

### XOR

-   Reject Payment XOR Make Payment

### JMP

-   None confirmed

------------------------------------------------------------------------

# Complete Interview Trace

Q1: Can Validate Expense occur only after Register Expense has occurred?
A: Yes

Q2: Are there valid executions where Register Expense occurs but
Validate Expense does not occur? A: No

Q3: Can Reject Payment and Make Payment occur together? A: No

Q4: Can Reject Payment occur only after Validate Expense has occurred?
A: Yes

Q5: Are there valid executions where Validate Expense occurs but Reject
Payment does not occur? A: Yes

Q6: Can Make Payment occur only after Validate Expense has occurred? A:
Yes

Q7: Are there valid executions where Validate Expense occurs but Make
Payment does not occur? A: Yes

Q8: Can Inform Merchant occur only after Reject Payment? A: Yes

Q9: Are there valid executions where Reject Payment occurs but Inform
Merchant does not occur? A: No

Q10: Can the process return to an earlier activity? A: No

------------------------------------------------------------------------

## Final Statement

This SBMN model is consistent and has at least one valid BPMN
realization.
