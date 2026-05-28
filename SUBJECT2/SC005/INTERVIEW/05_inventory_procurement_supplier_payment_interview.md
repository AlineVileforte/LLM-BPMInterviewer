# SBMN Interview Report

## Process Information

**Process Name:** Inventory Procurement and Supplier Payment Process\
**Domain:** Supply Chain Management

## Activities

1.  Check Current Inventory Level
2.  Create Purchase Order
3.  Review Purchase Order
4.  Rework Purchase Order
5.  Accept Purchase Order
6.  Reserve Purchase Funds
7.  Send Purchase Order to Supplier
8.  Receive Order Packing Slip
9.  Record Order Packing Slip
10. Receive Order Invoice
11. Record Order Invoice
12. Release Funds
13. Issue Payment to Supplier

## Number of Questions Asked

Total interview questions: 25

## Final SBMN Relations

### REQ

-   Create Purchase Order REQ Check Current Inventory Level
-   Accept Purchase Order REQ Review Purchase Order
-   Rework Purchase Order REQ Review Purchase Order

### DEP

-   Review Purchase Order DEP Create Purchase Order
-   Reserve Purchase Funds DEP Accept Purchase Order
-   Send Purchase Order to Supplier DEP Accept Purchase Order
-   Receive Order Packing Slip DEP Send Purchase Order to Supplier
-   Record Order Packing Slip DEP Receive Order Packing Slip
-   Receive Order Invoice DEP Send Purchase Order to Supplier
-   Record Order Invoice DEP Receive Order Invoice
-   Release Funds DEP Record Order Packing Slip
-   Release Funds DEP Record Order Invoice
-   Release Funds DEP Reserve Purchase Funds
-   Issue Payment to Supplier DEP Release Funds

### JMP

-   Rework Purchase Order JMP Review Purchase Order

------------------------------------------------------------------------

# Complete Interview Trace

Q1: Can Create Purchase Order occur only after Check Current Inventory
Level has occurred? A: Yes

Q2: Are there valid executions where Check Current Inventory Level
occurs but Create Purchase Order does not occur? A: Yes

Q3: Can Review Purchase Order occur only after Create Purchase Order has
occurred? A: Yes

Q4: Are there valid executions where Create Purchase Order occurs but
Review Purchase Order does not occur? A: No

Q5: Can Accept Purchase Order occur only after Review Purchase Order has
occurred? A: Yes

Q6: Are there valid executions where Review Purchase Order occurs but
Accept Purchase Order does not occur? A: Yes

Q7: Can Rework Purchase Order occur only after Review Purchase Order has
occurred? A: Yes

Q8: Are there valid executions where Review Purchase Order occurs but
Rework Purchase Order does not occur? A: Yes

Q9: Can Accept Purchase Order and Rework Purchase Order occur together?
A: Yes

Q10: Can Rework Purchase Order lead back to Review Purchase Order? A:
Yes

Q11: Can Reserve Purchase Funds occur only after Accept Purchase Order?
A: Yes

Q12: Are there valid executions where Accept Purchase Order occurs but
Reserve Purchase Funds does not occur? A: No

Q13: Can Send Purchase Order to Supplier occur only after Accept
Purchase Order? A: Yes

Q14: Are there valid executions where Accept Purchase Order occurs but
Send Purchase Order to Supplier does not occur? A: No

Q15: Can Receive Order Packing Slip occur only after Send Purchase Order
to Supplier? A: Yes

Q16: Are there valid executions where Send Purchase Order to Supplier
occurs but Receive Order Packing Slip does not occur? A: No

Q17: Can Record Order Packing Slip occur only after Receive Order
Packing Slip? A: Yes

Q18: Are there valid executions where Receive Order Packing Slip occurs
but Record Order Packing Slip does not occur? A: No

Q19: Can Receive Order Invoice occur only after Send Purchase Order to
Supplier? A: Yes

Q20: Are there valid executions where Send Purchase Order to Supplier
occurs but Receive Order Invoice does not occur? A: No

Q21: Can Record Order Invoice occur only after Receive Order Invoice? A:
Yes

Q22: Are there valid executions where Receive Order Invoice occurs but
Record Order Invoice does not occur? A: No

Q23: Before Release Funds can happen, must Record Order Packing Slip,
Record Order Invoice and Reserve Purchase Funds be completed? A: Yes

Q24: Can Issue Payment to Supplier occur only after Release Funds? A:
Yes

Q25: Are there valid executions where Release Funds occurs but Issue
Payment to Supplier does not occur? A: No

------------------------------------------------------------------------

## Final Statement

This SBMN model is consistent and has at least one valid BPMN
realization.
