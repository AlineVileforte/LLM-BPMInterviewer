# SBMN Interview Report

## Process Information

**Process Name:** Order Fulfillment and Customer Management Process\
**Domain:** Sales and Logistics

## Activities

1.  Check Customer
2.  Check Payment History
3.  Check Customer Type
4.  Create New Customer
5.  Declining Message
6.  Check Availability
7.  Sending Confirmation to Customer
8.  Getting ready for delivery
9.  Producing Missing Goods
10. Pack the Goods
11. Deliver the Goods
12. Preparing Invoice
13. Send the Invoice invoice to customer
14. Check for Payment
15. Closing Order
16. Checking the reminders
17. Dunning Process

## Number of Questions Asked

Total interview questions: 33

## Final SBMN Relations

### DEP

-   Check Payment History DEP Check Customer
-   Check Customer Type DEP Check Customer
-   Check Availability DEP Create New Customer
-   Sending Confirmation to Customer DEP Check Availability
-   Getting ready for delivery DEP Sending Confirmation to Customer
-   Pack the Goods DEP Getting ready for delivery
-   Deliver the Goods DEP Pack the Goods
-   Preparing Invoice DEP Getting ready for delivery
-   Send the Invoice invoice to customer DEP Preparing Invoice
-   Check for Payment DEP Deliver the Goods
-   Check for Payment DEP Send the Invoice invoice to customer
-   Dunning Process DEP Checking the reminders

### REQ

-   Create New Customer REQ Check Customer Type
-   Create New Customer REQ Check Payment History
-   Declining Message REQ Check Payment History
-   Closing Order REQ Check for Payment
-   Checking the reminders REQ Check for Payment

### DEPC

-   Getting ready for delivery DEPC Producing Missing Goods

### XOR

-   Declining Message XOR Create New Customer
-   Closing Order XOR Dunning Process

### JMP

-   Dunning Process JMP Check for Payment

------------------------------------------------------------------------

## Final Statement

This SBMN model is consistent and has at least one valid BPMN
realization.
