SBMN Interview Transcript
Process: Expense Payment Validation
Assistant: Welcome to the SBMN process interview.

Which language would you like to use for the interview?
User: english
Assistant: What is the name of the process you want to model?
User: Expense Payment Validation
Assistant: What is the business domain of the process?
User: Financial Management
Assistant: Please provide the complete list of activities involved in the “Expense Payment Validation” process.

List only the activities, one per line or separated by commas.
User: Incur Expense
Verify Expense Documentation
Do Not Record Payment
Record Payment
Receive Payment Confirmation
Receive Non-Payment Notification
Assistant: Can “Record Payment” and “Do Not Record Payment” occur together in the same execution of the process?
User: no
Assistant: Can “Receive Payment Confirmation” occur only if “Record Payment” occurred before it?
User: YES
Assistant: Are there valid executions where “Record Payment” occurs, but “Receive Payment Confirmation” does not occur?
User: NO
Assistant: Can “Receive Non-Payment Notification” occur only if “Do Not Record Payment” occurred before it?
User: YES
Assistant: Are there valid executions where “Do Not Record Payment” occurs, but “Receive Non-Payment Notification” does not occur?
User: NO
Assistant: Can “Verify Expense Documentation” occur only if “Incur Expense” occurred before it?
User: YES
Assistant: Are there valid executions where “Incur Expense” occurs, but “Verify Expense Documentation” does not occur?
User: NO
Assistant: Before “Record Payment” can happen, must “Verify Expense Documentation” already be completed?
User: YES
Assistant: Are there valid executions where “Verify Expense Documentation” occurs, but “Record Payment” does not occur?
User: YES
Assistant: Before “Do Not Record Payment” can happen, must “Verify Expense Documentation” already be completed?
User: YES
Assistant: Are there valid executions where “Verify Expense Documentation” occurs, but “Do Not Record Payment” does not occur?
User: YES
Assistant: If “Verify Expense Documentation” identifies a problem or failure, can the process return to an earlier activity and repeat it?
User: NO
SBMN Result
Verify Expense Documentation DEP Incur Expense
Do Not Record Payment XOR Record Payment
Record Payment REQ Verify Expense Documentation
Do Not Record Payment REQ Verify Expense Documentation
Receive Payment Confirmation DEP Record Payment
Receive Non-Payment Notification DEP Do Not Record Payment
Receive Payment Confirmation REQ Verify Expense Documentation
Receive Non-Payment Notification REQ Verify Expense Documentation
Receive Payment Confirmation XOR Do Not Record Payment
Receive Non-Payment Notification XOR Record Payment

This SBMN model is consistent and has at least one valid BPMN realization.
