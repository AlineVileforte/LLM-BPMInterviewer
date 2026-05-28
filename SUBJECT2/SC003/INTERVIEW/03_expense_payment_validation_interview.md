# SBMN Interview Report

## Process Information

**Process Name:** Expense Payment Validation\
**Domain:** Financial Management

## Activities

1.  Incur Expense
2.  Verify Expense Documentation
3.  Do Not Record Payment
4.  Record Payment
5.  Receive Payment Confirmation
6.  Receive Non-Payment Notification

## Number of Questions Asked

Total interview questions: 13

## Final SBMN Relations

### DEP

-   Verify Expense Documentation DEP Incur Expense
-   Receive Payment Confirmation DEP Record Payment
-   Receive Non-Payment Notification DEP Do Not Record Payment

### REQ

-   Record Payment REQ Verify Expense Documentation
-   Do Not Record Payment REQ Verify Expense Documentation

### XOR

-   Record Payment XOR Do Not Record Payment
-   Receive Payment Confirmation XOR Receive Non-Payment Notification

### JMP

-   None confirmed

------------------------------------------------------------------------

# Complete Interview Trace

Q1: Can Record Payment and Do Not Record Payment occur together in the
same process execution?\
A: No

Q2: Can Verify Expense Documentation occur only after Incur Expense has
occurred?\
A: Yes

Q3: Are there valid executions where Incur Expense occurs but Verify
Expense Documentation does not occur?\
A: No

Q4: Can Record Payment occur only after Verify Expense Documentation has
occurred?\
A: Yes

Q5: Are there valid executions where Verify Expense Documentation occurs
but Record Payment does not occur?\
A: Yes

Q6: Can Do Not Record Payment occur only after Verify Expense
Documentation has occurred?\
A: Yes

Q7: Are there valid executions where Verify Expense Documentation occurs
but Do Not Record Payment does not occur?\
A: Yes

Q8: Can Receive Payment Confirmation occur only after Record Payment has
occurred?\
A: Yes

Q9: Are there valid executions where Record Payment occurs but Receive
Payment Confirmation does not occur?\
A: No

Q10: Can Receive Non-Payment Notification occur only after Do Not Record
Payment has occurred?\
A: Yes

Q11: Are there valid executions where Do Not Record Payment occurs but
Receive Non-Payment Notification does not occur?\
A: No

Q12: Can Receive Payment Confirmation and Receive Non-Payment
Notification occur together in the same process execution?\
A: No

Q13: Can the process return to an earlier activity (rework/loop), for
example after Receive Non-Payment Notification, or is there no return
behavior?\
A: No

------------------------------------------------------------------------

## Final Statement

This SBMN model is consistent and has at least one valid BPMN
realization.
