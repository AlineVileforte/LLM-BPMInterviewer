# SBMN Interview Report

## Process Information

**Process Name:** Inventory Procurement and Supplier Payment Process\
**Domain:** Procurement

## Activities

-   Check Inventory
-   Construct Purchase Order
-   Review PurchaseOrder
-   Send PurchaseOrder toSupplier
-   Match Order
-   Send packingslip
-   Send Invoice
-   Receive Confirmation
-   Release Funds
-   Reserve Fund

## Final SBMN Relations

-   Construct Purchase Order REQ Check Inventory
-   Review PurchaseOrder DEP Construct Purchase Order
-   Send PurchaseOrder toSupplier REQ ReviewPurchaseOrder
-   Match Order DEP Send PurchaseOrder toSupplier
-   Reserve Fund REQ ReviewPurchaseOrder
-   Send PurchaseOrder toSupplier XOR Reserve Fund
-   Send packingslip DEP Match Order
-   Send Invoice DEP Match Order
-   Receive Confirmation DEPC Send packingslip
-   Receive Confirmation DEPC Send Invoice
-   Receive Confirmation DEPC Reserve Fund
-   Release Funds DEP Receive Confirmation

## JMP Relations

-   ReviewPurchaseOrder JMP Construct Purchase Order

## Interview Statistics

Approximate number of questions: Not available

------------------------------------------------------------------------

# Complete Interview Trace

The original complete interview trace was not available.

The report was reconstructed from the final SBMN model.

Recovered structural conclusions:

Q: Must Construct Purchase Order occur after Check Inventory? A: Yes

Q: Can Check Inventory occur without Construct Purchase Order? A: Yes

Q: Must Review PurchaseOrder occur after Construct Purchase Order? A:
Yes

Q: Must Send PurchaseOrder toSupplier occur after ReviewPurchaseOrder?
A: Yes

Q: Can ReviewPurchaseOrder occur without Send PurchaseOrder toSupplier?
A: Yes

Q: Must Match Order occur after Send PurchaseOrder toSupplier? A: Yes

Q: Must Reserve Fund occur after ReviewPurchaseOrder? A: Yes

Q: Can Send PurchaseOrder toSupplier and Reserve Fund occur together? A:
No

Q: Must Send packingslip occur after Match Order? A: Yes

Q: Must Send Invoice occur after Match Order? A: Yes

Q: If Send packingslip occurs, must Receive Confirmation occur? A: Yes

Q: If Send Invoice occurs, must Receive Confirmation occur? A: Yes

Q: If Reserve Fund occurs, must Receive Confirmation occur? A: Yes

Q: Must Release Funds occur after Receive Confirmation? A: Yes

Q: Can ReviewPurchaseOrder return to Construct Purchase Order? A: Yes

------------------------------------------------------------------------

Final validation:

This SBMN model is consistent and has at least one valid BPMN
realization.

Note: The interview trace above was reconstructed from the final SBMN
model and may not represent the original interview sequence.
