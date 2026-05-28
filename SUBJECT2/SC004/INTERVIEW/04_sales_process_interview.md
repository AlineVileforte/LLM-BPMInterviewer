# SBMN Interview Report

## Process Information

**Process Name:** Sales Process\
**Domain:** Online Software Sales

## Activities

1.  Customer Places Order
2.  Order License Upgrade
3.  Order New License
4.  Check Which Version of the Game the Customer Has
5.  Register Customer Information
6.  Requested Item plus Invoice is Sent to Customer by Post
7.  Copy of Customer Invoice is Received
8.  Payment is Received

## Number of Questions Asked

Total interview questions: 17

## Final SBMN Relations

### XOR

-   Order License Upgrade XOR Order New License

### DEP

-   Check Which Version of the Game the Customer Has DEP Order License
    Upgrade
-   Register Customer Information DEP Order New License
-   Payment is Received DEP Copy of Customer Invoice is Received

### REQ

-   Order License Upgrade REQ Customer Places Order
-   Order New License REQ Customer Places Order

### DEPC

-   Requested Item plus Invoice is Sent to Customer by Post DEPC Check
    Which Version of the Game the Customer Has
-   Requested Item plus Invoice is Sent to Customer by Post DEPC
    Register Customer Information
-   Copy of Customer Invoice is Received DEPC Check Which Version of the
    Game the Customer Has
-   Copy of Customer Invoice is Received DEPC Register Customer
    Information

### JMP

-   None confirmed

------------------------------------------------------------------------

# Complete Interview Trace

Q1: Can Order License Upgrade and Order New License occur together in
the same process execution?\
A: No

Q2: Can Check Which Version of the Game the Customer Has occur only
after Order License Upgrade has occurred?\
A: Yes

Q3: Are there valid executions where Order License Upgrade occurs but
Check Which Version of the Game the Customer Has does not occur?\
A: No

Q4: Can Register Customer Information occur only after Order New License
has occurred?\
A: Yes

Q5: Are there valid executions where Order New License occurs but
Register Customer Information does not occur?\
A: No

Q6: Can Customer Places Order occur only before Order License Upgrade
and Order New License?\
A: Yes

Q7: Are there valid executions where Customer Places Order occurs but
neither Order License Upgrade nor Order New License occurs?\
A: No

Q8: When Customer Places Order occurs, must Order License Upgrade and
Order New License both occur, or does exactly one of them occur?\
A: Exactly one of them

Q9: Can Requested Item plus Invoice is Sent to Customer by Post occur
only after Check Which Version of the Game the Customer Has?\
A: Clarified later

Q10: Can Requested Item plus Invoice is Sent to Customer by Post occur
after both branches?\
A: Yes, for both

Correction: Requested Item plus Invoice is Sent to Customer by Post DEPC
Check Which Version of the Game the Customer Has

Q11: Are there valid executions where Check Which Version of the Game
the Customer Has occurs but Requested Item plus Invoice is Sent to
Customer by Post does not occur?\
A: No

Q12: Can Requested Item plus Invoice is Sent to Customer by Post occur
only after Register Customer Information?\
A: Yes

Correction: Requested Item plus Invoice is Sent to Customer by Post DEPC
Register Customer Information

Q13: Are there valid executions where Register Customer Information
occurs but Requested Item plus Invoice is Sent to Customer by Post does
not occur?\
A: No

Q14: Copy of Customer Invoice is Received depends circumstantially on: -
Register Customer Information - Check Which Version of the Game the
Customer Has

A: Yes

Q15: Can Payment is Received occur only after Copy of Customer Invoice
is Received has occurred?\
A: Yes

Q16: Are there valid executions where Copy of Customer Invoice is
Received occurs but Payment is Received does not occur?\
A: No

Q17: Can the process return to an earlier activity (rework/loop)?\
A: No

------------------------------------------------------------------------

## Final Statement

This SBMN model is consistent and has at least one valid BPMN
realization.
