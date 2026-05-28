# SBMN Interview Report

## Process Information

**Process Name:** Order Fulfillment and Customer Management Process\
**Domain:** Operations and Customer Service

## Activities

1.  Login verification
2.  Enter reservation
3.  Check availability
4.  Request requirement modification
5.  Modify requirements
6.  Order acceptance confirmation
7.  Send email about 1...
8.  Save to database
9.  Send email about 2...
10. Send confirmation email
11. Deliver the Goods
12. Preparing Invoice
13. Send the Invoice to Customer
14. Check for Payment
15. closing order
16. Checking the reminders

## Final SBMN Relations

-   Enter reservation XOR Check availability
-   Enter reservation REQ Login verification
-   Check availability REQ Login verification
-   Request requirement modification DEP Check availability
-   Order acceptance confirmation DEP Request requirement modification
-   Send email about 1... DEP Order acceptance confirmation
-   Save to database DEP Send email about 1...
-   Save to database DEPC Send email about 2...
-   Send confirmation email DEP Save to database
-   Deliver the Goods DEP Send confirmation email
-   Preparing Invoice DEP Save to database
-   Send the Invoice to Customer DEP Preparing Invoice
-   Check for Payment DEP Send the Invoice to Customer
-   Check for Payment DEP Deliver the Goods
-   closing order REQ Check for Payment
-   Checking the reminders REQ Check for Payment
-   closing order XOR Checking the reminders

## JMP Relations

-   Enter reservation JMP Order acceptance confirmation
-   Checking the reminders JMP Check for Payment

## Interview Statistics

Approximate number of interview questions: 27

------------------------------------------------------------------------

# Complete Interview Trace

Q: Can Enter reservation occur only after Login verification?\
A: Yes.

Q: Can Login verification occur without Enter reservation?\
A: Yes, through Check availability.

Q: Can Check availability occur only after Login verification?\
A: Yes.

Q: Can Login verification occur without Check availability?\
A: Yes, through Enter reservation.

Q: Can Request requirement modification occur only after Enter
reservation?\
A: No, Check availability must occur before.

Q: Can Check availability occur without Request requirement
modification?\
A: No.

Q: Does Modify requirements depend on Request requirement modification?\
A: No.

Q: Does Modify requirements depend on Check availability?\
A: No. It depends on Enter reservation when that branch is executed.

Q: Can Modify requirements occur after Enter reservation?\
A: Sometimes. Sometimes Enter reservation jumps directly to Order
acceptance confirmation.

Q: Does Order acceptance confirmation require Request requirement
modification?\
A: Yes.

Q: Can Request requirement modification occur without Order acceptance
confirmation?\
A: No.

Q: Does Send email about 1 require Order acceptance confirmation?\
A: Yes.

Q: Can Order acceptance confirmation occur without Send email about 1?\
A: No.

Q: Does Save to database require Send email about 1?\
A: Yes.

Q: Can Send email about 1 occur without Save to database?\
A: No.

Q: Does Send email about 2 depend on Save to database?\
A: No. It may occur in parallel with Send email about 1 and before Save
to database.

Q: Clarification on Send email about 2\
A: Save to database depends circumstantially on Send email about 2.

Q: Does Send confirmation email require Save to database?\
A: Yes.

Q: Can Save to database occur without Send confirmation email?\
A: No.

Q: Does Deliver the Goods require Send confirmation email?\
A: Yes.

Q: Can Send confirmation email occur without Deliver the Goods?\
A: No.

Q: Does Preparing Invoice require Save to database?\
A: Yes. It can occur in parallel with Send confirmation email.

Q: Does Send the Invoice to Customer require Preparing Invoice?\
A: Yes.

Q: Does Check for Payment require Send the Invoice to Customer and
Deliver the Goods?\
A: Yes.

Q: Does closing order require Check for Payment?\
A: Yes, but sometimes reminders occur instead.

Q: Does Checking the reminders require Check for Payment?\
A: Yes.

Q: Are closing order and Checking the reminders mutually exclusive?\
A: Yes.

Q: Can Checking the reminders return to Check for Payment?\
A: Yes.

------------------------------------------------------------------------

Final validation:

This SBMN model is consistent and has at least one valid BPMN
realization.
