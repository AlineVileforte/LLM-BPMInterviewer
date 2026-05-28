ASSISTANT:
Welcome to the SBMN structured interview process. 

Which language would you like to use for the interview?

USER:
ENGLISH

ASSISTANT:
Great. Let’s begin.

What is the name of the process you want to model?

USER:
Expense Validation and Payment Process


ASSISTANT:
What is the business domain or context of PROCESS 9?

USER:
Financial Management

ASSISTANT:
Please provide the complete list of activities involved in PROCESS 9.

USER:
Register Expense,
Validate Expense,
Make Payment,
Reject Payment,
Inform Merchant

ASSISTANT:
Can “Validate Expense” occur without “Register Expense” having occurred before it?

USER:
NO

ASSISTANT:
When “Validate Expense” occurs, must “Register Expense” occur BEFORE it, AFTER it, or can both occur in any order depending on the execution?

USER:
BEFORE

ASSISTANT:
Are there valid executions where “Register Expense” occurs but “Validate Expense” does not occur?

USER:
NO

ASSISTANT:
Can “Make Payment” occur without “Validate Expense” having occurred before it?

USER:
NO

ASSISTANT:
When “Make Payment” occurs, must “Validate Expense” occur BEFORE it, AFTER it, or can both occur in any order depending on the execution?

USER:
BEFORE

ASSISTANT:
Are there valid executions where “Validate Expense” occurs but “Make Payment” does not occur?

ASSISTANT:
YES

USER:
YES

ASSISTANT:
Can “Reject Payment” occur together with “Make Payment” in the same process execution?

USER:
NO

ASSISTANT:
Can “Reject Payment” occur without “Validate Expense” having occurred before it?

USER:
NO

ASSISTANT:
When “Reject Payment” occurs, must “Validate Expense” occur BEFORE it, AFTER it, or can both occur in any order depending on the execution?

ASSISTANT:
BEFORE

ASSISTANT:
When “Reject Payment” occurs, must “Validate Expense” occur BEFORE it, AFTER it, or can both occur in any order depending on the execution?
BEFORE

Are there valid executions where “Validate Expense” occurs but “Reject Payment” does not occur?

USER:
BEFORE
YES

ASSISTANT:
Can “Inform Merchant” occur without “Reject Payment” having occurred before it?

USER:
NO

ASSISTANT:
When “Inform Merchant” occurs, must “Reject Payment” occur BEFORE it, AFTER it, or can both occur in any order depending on the execution?

USER:
BEFORE

ASSISTANT:
Are there valid executions where “Reject Payment” occurs but “Inform Merchant” does not occur?

ASSISTANT:
NO

USER:
NO

ASSISTANT:
Process name: Expense Validation and Payment Process
Domain: Financial Management

Activity list:
- Register Expense
- Validate Expense
- Make Payment
- Reject Payment
- Inform Merchant

SBMN relations:

Validate Expense DEP Register Expense
Make Payment REQ Validate Expense
Reject Payment REQ Validate Expense
Make Payment XOR Reject Payment
Inform Merchant DEP Reject Payment
Inform Merchant XOR Make Payment

This SBMN model is consistent and has at least one valid BPMN realization.


