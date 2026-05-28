# SBMN Interview Report

## Process Information

**Process Name:** Purchase Order Process\
**Domain:** Supply Chain Management

## Activities

1.  Check Inventory
2.  Inventory Available
3.  Inventory Not Available
4.  Confirm Purchase Order
5.  Reject Purchase Order
6.  Ship Product
7.  Send Invoice

## Number of Questions Asked

Total interview questions: 16

## Final SBMN Relations

### XOR

-   Inventory Available XOR Inventory Not Available

### REQ

-   Inventory Available REQ Check Inventory
-   Inventory Not Available REQ Check Inventory

### DEP

-   Confirm Purchase Order DEP Inventory Available
-   Reject Purchase Order DEP Inventory Not Available
-   Ship Product DEP Confirm Purchase Order
-   Send Invoice DEP Confirm Purchase Order

### No Relation

-   Ship Product ↔ Send Invoice

### JMP

-   None confirmed

------------------------------------------------------------------------

# Complete Interview Trace

Q1: Can Inventory Available and Inventory Not Available occur together?
A: No

Q2: Can Inventory Available occur only after Check Inventory? A: Yes

Q3: Are there valid executions where Check Inventory occurs but
Inventory Available does not occur? A: Yes

Q4: Can Inventory Not Available occur only after Check Inventory? A: Yes

Q5: Are there valid executions where Check Inventory occurs but
Inventory Not Available does not occur? A: Yes

Q6: Can Confirm Purchase Order occur only after Inventory Available? A:
Yes

Q7: Are there valid executions where Inventory Available occurs but
Confirm Purchase Order does not occur? A: No

Q8: Can Reject Purchase Order occur only after Inventory Not Available?
A: Yes

Q9: Are there valid executions where Inventory Not Available occurs but
Reject Purchase Order does not occur? A: No

Q10: Can Ship Product occur only after Confirm Purchase Order? A: Yes

Q11: Are there valid executions where Confirm Purchase Order occurs but
Ship Product does not occur? A: No

Q12: Can Send Invoice occur only after Ship Product? A: No

Q13: Can Send Invoice occur only after Confirm Purchase Order? A: Yes

Q14: Are there valid executions where Confirm Purchase Order occurs but
Send Invoice does not occur? A: No

Q15: Is there dependency between Ship Product and Send Invoice? A: No

Q16: Is there loop/rework behavior? A: No

------------------------------------------------------------------------

## Final Statement

This SBMN model is consistent and has at least one valid BPMN
realization.
