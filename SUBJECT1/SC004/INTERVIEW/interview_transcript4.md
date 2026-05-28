SBMN Interview Transcript

Assistant: Welcome to the SBMN interview process.

Assistant: Which language would you like to use for the interview?

User: english

Assistant: What is the name of the process you want to model?

User: AFFE Sales Process

Assistant: What is the business domain or context of the AFFE Sales Process?

User: Sales

Assistant: Please provide the full list of activities involved in the AFFE Sales Process.
List each activity separately.

User:
CUSTOMER PLACES ORDER
ORDER LICENSE UPGRADE
ORDER NEW LICENSE
CHECK WHICH VERSION OF THE GAME THE CUSTOMER HAS
REGISTER CUSTOMER — INFORMATION IN CUSTOMER REGISTER
REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST
COPY OF CUSTOMER INVOICE IS RECEIVED
PAYMENTE IS RECEIVED

Assistant: Can both activities below occur in the same process execution?

- “ORDER LICENSE UPGRADE”
- “ORDER NEW LICENSE”

User: no

Assistant: Before “CHECK WHICH VERSION OF THE GAME THE CUSTOMER HAS” can happen, must one of these activities already have occurred?

- “ORDER LICENSE UPGRADE”
- “ORDER NEW LICENSE”
- or either one depending on the execution?

User: YES, ORDER LICENSE UPGRADE

Assistant: Are there valid executions where “ORDER LICENSE UPGRADE” occurs but “CHECK WHICH VERSION OF THE GAME THE CUSTOMER HAS” does not occur?

User: NO

Assistant: Does “CHECK WHICH VERSION OF THE GAME THE CUSTOMER HAS” always occur after “ORDER LICENSE UPGRADE”?

User: YES

Assistant: Does “CHECK WHICH VERSION OF THE GAME THE CUSTOMER HAS” occur only in the license-upgrade branch, and not in the new-license branch?

User: YES

Assistant: Does every execution begin with “CUSTOMER PLACES ORDER” before either order type is selected?

User: YES

Assistant: Can “ORDER LICENSE UPGRADE” and “ORDER NEW LICENSE” both occur directly after “CUSTOMER PLACES ORDER”, depending on the execution path?

User: YES

Assistant: Before “ORDER LICENSE UPGRADE” can happen, must “CUSTOMER PLACES ORDER” already have occurred?

User: YES

Assistant: Are there valid executions where “CUSTOMER PLACES ORDER” occurs but “ORDER LICENSE UPGRADE” does not occur?

User: YES

Assistant: Before “ORDER NEW LICENSE” can happen, must “CUSTOMER PLACES ORDER” already have occurred?

User: YES

Assistant: Are there valid executions where “CUSTOMER PLACES ORDER” occurs but “ORDER NEW LICENSE” does not occur?

User: YES

Assistant: Are there valid executions where “ORDER NEW LICENSE” occurs but “REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST” does not occur?

User: NO

Assistant: Before “REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST” can happen in the new-license branch, must “ORDER NEW LICENSE” already have occurred?

User: YES

Assistant: Does “REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST” also occur in the license-upgrade branch after “CHECK WHICH VERSION OF THE GAME THE CUSTOMER HAS”?

User: YES

Assistant: Before “REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST” can happen in the license-upgrade branch, must “CHECK WHICH VERSION OF THE GAME THE CUSTOMER HAS” already have occurred?

User: YES

Assistant: Are there valid executions where “CHECK WHICH VERSION OF THE GAME THE CUSTOMER HAS” occurs but “REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST” does not occur?

User: NO

Assistant: Before “REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST” can happen, is it enough that either “ORDER NEW LICENSE” occurred or “CHECK WHICH VERSION OF THE GAME THE CUSTOMER HAS” occurred, depending on the branch?

User: YES

Assistant: Before “REGISTER CUSTOMER — INFORMATION IN CUSTOMER REGISTER” can happen, must “CUSTOMER PLACES ORDER” already have occurred?

User: YES

Assistant: Are there valid executions where “CUSTOMER PLACES ORDER” occurs but “REGISTER CUSTOMER — INFORMATION IN CUSTOMER REGISTER” does not occur?

User: YES

Assistant: Does “REGISTER CUSTOMER — INFORMATION IN CUSTOMER REGISTER” have to occur before “REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST”?

User: NO

Assistant: Before “COPY OF CUSTOMER INVOICE IS RECEIVED” can happen, must “REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST” already have occurred?

User: NO

Assistant: Can “COPY OF CUSTOMER INVOICE IS RECEIVED” occur independently of “REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST”, or is there another activity that must happen before the invoice copy is received?

User: CAN occur independently

Assistant: Before “PAYMENTE IS RECEIVED” can happen, must “REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST” already have occurred?

User: NO

Assistant: Before “PAYMENTE IS RECEIVED” can happen, must “COPY OF CUSTOMER INVOICE IS RECEIVED” already have occurred?

User: YES

Assistant: Are there valid executions where “COPY OF CUSTOMER INVOICE IS RECEIVED” occurs but “PAYMENTE IS RECEIVED” does not occur?

User: NO

Assistant: After “PAYMENTE IS RECEIVED”, can the process return to or skip directly to any earlier non-adjacent activity for rework, correction, or repetition?

User: NO

Assistant:

Process name:
AFFE Sales Process

Activity list:

- CUSTOMER PLACES ORDER
- ORDER LICENSE UPGRADE
- ORDER NEW LICENSE
- CHECK WHICH VERSION OF THE GAME THE CUSTOMER HAS
- REGISTER CUSTOMER — INFORMATION IN CUSTOMER REGISTER
- REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST
- COPY OF CUSTOMER INVOICE IS RECEIVED
- PAYMENTE IS RECEIVED

SBMN relations:

ORDER LICENSE UPGRADE XOR ORDER NEW LICENSE

ORDER LICENSE UPGRADE REQ CUSTOMER PLACES ORDER

ORDER NEW LICENSE REQ CUSTOMER PLACES ORDER

CHECK WHICH VERSION OF THE GAME THE CUSTOMER HAS DEP ORDER LICENSE UPGRADE

REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST DEPC ORDER NEW LICENSE

REQUESTED ITEM + INVOICE IS SENT TO CUSTOMER BY POST DEP CHECK WHICH VERSION OF THE GAME THE CUSTOMER HAS

REGISTER CUSTOMER — INFORMATION IN CUSTOMER REGISTER REQ CUSTOMER PLACES ORDER

PAYMENTE IS RECEIVED DEP COPY OF CUSTOMER INVOICE IS RECEIVED

This SBMN model is consistent and has at least one valid BPMN realization.

