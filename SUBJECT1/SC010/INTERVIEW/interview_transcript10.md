INTERVIEWER:
Welcome to the SBMN structured interview.

Which language would you like to use for the interview?

USER:
ENGLISH


INTERVIEWER:
Great. Let's begin.

What is the name of the process you want to model?

USER:
Emergency Insurance Assistance Process



INTERVIEWER:
What is the business domain or context of PROCESS 10?

USER:
INSURANCE


INTERVIEWER:
Please provide the full list of activities involved in the process. Use short activity names, one per line if possible.

USER:
ANALYZE INSURANCE AGREEMENT
SEND OUT OFFER FOR EMERGENCY HELP
OFFER IMMEDIATE HELP
DO INTERNAL ACCOUNTING
ASK FOR REJECTION NOTIFICATIO


INTERVIEWER:
Thank you. The activity list is now frozen.

First question:

Can “SEND OUT OFFER FOR EMERGENCY HELP” occur only after “ANALYZE INSURANCE AGREEMENT”?

USER:
YES

INTERVIEWER:
When “SEND OUT OFFER FOR EMERGENCY HELP” occurs, must “ANALYZE INSURANCE AGREEMENT” occur before it, or can both occur in any order depending on the execution?

USER:
BEFORE

INTERVIEWER:
Are there valid executions where “ANALYZE INSURANCE AGREEMENT” occurs but “SEND OUT OFFER FOR EMERGENCY HELP” does not occur?

USER:
YES

INTERVIEWER:
Can “OFFER IMMEDIATE HELP” occur only after “SEND OUT OFFER FOR EMERGENCY HELP”?

USER:
NO

INTERVIEWER:
Can “SEND OUT OFFER FOR EMERGENCY HELP” and “OFFER IMMEDIATE HELP” occur together in the same process execution?

USER:
NO

INTERVIEWER:
Can “OFFER IMMEDIATE HELP” occur only after “ANALYZE INSURANCE AGREEMENT”?

USER:
YES

INTERVIEWER:
When “OFFER IMMEDIATE HELP” occurs, must “ANALYZE INSURANCE AGREEMENT” occur before it, or can both occur in any order depending on the execution?

USER:
BEFORE

INTERVIEWER:
Are there valid executions where “ANALYZE INSURANCE AGREEMENT” occurs but “OFFER IMMEDIATE HELP” does not occur?

USER:
YES

INTERVIEWER:
Can “SEND OUT OFFER FOR EMERGENCY HELP” and “DO INTERNAL ACCOUNTING” occur together in the same process execution?

USER:
NO

INTERVIEWER:
Can “OFFER IMMEDIATE HELP” and “DO INTERNAL ACCOUNTING” occur together in the same process execution?

USER:
YES

INTERVIEWER:
Can “DO INTERNAL ACCOUNTING” occur only after “ANALYZE INSURANCE AGREEMENT”?

USER:
YES. But not immediately after.

INTERVIEWER:
When “DO INTERNAL ACCOUNTING” occurs, must “ANALYZE INSURANCE AGREEMENT” occur before it, or can both occur in any order depending on the execution?

USER:
BEFORE

INTERVIEWER:
Are there valid executions where “ANALYZE INSURANCE AGREEMENT” occurs but “DO INTERNAL ACCOUNTING” does not occur?

USER:
YES

INTERVIEWER:
Can “DO INTERNAL ACCOUNTING” occur only after “OFFER IMMEDIATE HELP”?

USER:
YES

INTERVIEWER:
When “DO INTERNAL ACCOUNTING” occurs, must “OFFER IMMEDIATE HELP” occur before it, or can both occur in any order depending on the execution?

USER:
BEFORE

INTERVIEWER:
Are there valid executions where “OFFER IMMEDIATE HELP” occurs but “DO INTERNAL ACCOUNTING” does not occur?

USER:
YES

INTERVIEWER:
Can “ASK FOR REJECTION NOTIFICATIO” occur only after “ANALYZE INSURANCE AGREEMENT”?

USER:
YES

INTERVIEWER:
When “ASK FOR REJECTION NOTIFICATIO” occurs, must “ANALYZE INSURANCE AGREEMENT” occur before it, or can both occur in any order depending on the execution?

USER:
BEFORE

INTERVIEWER:
Are there valid executions where “ANALYZE INSURANCE AGREEMENT” occurs but “ASK FOR REJECTION NOTIFICATIO” does not occur?

USER:
YES

INTERVIEWER:
Can “ASK FOR REJECTION NOTIFICATIO” and “OFFER IMMEDIATE HELP” occur together in the same process execution?

USER:
YES

INTERVIEWER:
Can “ASK FOR REJECTION NOTIFICATIO” occur only after “OFFER IMMEDIATE HELP”?

USER:
YES

INTERVIEWER:
When “ASK FOR REJECTION NOTIFICATIO” occurs, must “OFFER IMMEDIATE HELP” occur before it, or can both occur in any order depending on the execution?

USER:
BEFORE

INTERVIEWER:
Are there valid executions where “OFFER IMMEDIATE HELP” occurs but “ASK FOR REJECTION NOTIFICATIO” does not occur?

USER:
YES

INTERVIEWER:
Can “DO INTERNAL ACCOUNTING” and “ASK FOR REJECTION NOTIFICATIO” occur together in the same process execution?

USER:
NO

INTERVIEWER:
Can “SEND OUT OFFER FOR EMERGENCY HELP” and “ASK FOR REJECTION NOTIFICATIO” occur together in the same process execution?

USER:
NO

INTERVIEWER:
After completing any of these activities, can the process return to or skip directly to an earlier non-adjacent activity?

- ANALYZE INSURANCE AGREEMENT
- SEND OUT OFFER FOR EMERGENCY HELP
- OFFER IMMEDIATE HELP
- DO INTERNAL ACCOUNTING
- ASK FOR REJECTION NOTIFICATIO

USER:
NO
INTERVIEWER:
Process name: Emergency Insurance Assistance Process
Domain: Insurance


Activity list:
- ANALYZE INSURANCE AGREEMENT
- SEND OUT OFFER FOR EMERGENCY HELP
- OFFER IMMEDIATE HELP
- DO INTERNAL ACCOUNTING
- ASK FOR REJECTION NOTIFICATIO

SBMN relations:

SEND OUT OFFER FOR EMERGENCY HELP REQ ANALYZE INSURANCE AGREEMENT
OFFER IMMEDIATE HELP REQ ANALYZE INSURANCE AGREEMENT
DO INTERNAL ACCOUNTING REQ ANALYZE INSURANCE AGREEMENT
DO INTERNAL ACCOUNTING REQ OFFER IMMEDIATE HELP
ASK FOR REJECTION NOTIFICATIO REQ ANALYZE INSURANCE AGREEMENT
ASK FOR REJECTION NOTIFICATIO REQ OFFER IMMEDIATE HELP
SEND OUT OFFER FOR EMERGENCY HELP XOR OFFER IMMEDIATE HELP
SEND OUT OFFER FOR EMERGENCY HELP XOR DO INTERNAL ACCOUNTING
SEND OUT OFFER FOR EMERGENCY HELP XOR ASK FOR REJECTION NOTIFICATIO
DO INTERNAL ACCOUNTING XOR ASK FOR REJECTION NOTIFICATIO

This SBMN model is consistent and has at least one valid BPMN realization.
