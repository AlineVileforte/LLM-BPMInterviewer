SBMN Interview - Full Transcript
Assistant: Welcome to the SBMN Process Interview.

Which language would you like to use for the interview?
User: english
Assistant: What is the name of the process you want to model?
User: Paying Fees Process
Assistant: What is the domain or business context of the “Paying Fees Process”?
User: E-Commerce
Assistant: Please provide the complete list of activities involved in the Paying Fees Process. Use short activity names, one per line if possible.
User: · Pay the book/s fee
· Choose existing shipping address
· Enter new shipping address
· Edit exist shipping address
· Choose shipping detail
· Choose a shipping preference
· Choose a shipping speed
· Change quantities or delete items
· Order the exist gift items
· Select a payment method
· Credit or Debit Cards
· Amazon.com Store Card
· Checking Account
· Gift Cards & Promotional Codes
· Review your order
· Place order
· Switch currency
· Change billing address
· Place order in default currency
Assistant: Does “Pay the book/s fee” always require either “Choose existing shipping address”, “Enter new shipping address”, or “Edit exist shipping address” to occur before it?
User: no
Assistant: Can “Choose existing shipping address” and “Enter new shipping address” occur together in the same execution of the process?
User: no
Assistant: Can “Choose existing shipping address” and “Edit exist shipping address” occur together in the same execution?
User: NO
Assistant: Can “Enter new shipping address” and “Edit exist shipping address” occur together in the same execution?
User: NO
Assistant: Before “Choose shipping detail” can occur, must one of the shipping address activities already be completed?
(“Choose existing shipping address”, “Enter new shipping address”, or “Edit exist shipping address”)
User: YES
Assistant: When “Choose shipping detail” occurs, must at least one of those shipping address activities occur BEFORE it?
User: YES
Assistant: Are there valid executions where “Choose existing shipping address” occurs but “Choose shipping detail” does not occur?
User: NO
Assistant: Are there valid executions where “Enter new shipping address” occurs but “Choose shipping detail” does not occur?
User: NO
Assistant: Are there valid executions where “Edit exist shipping address” occurs but “Choose shipping detail” does not occur?
User: NO
Assistant: Can “Choose a shipping preference” occur only after “Choose shipping detail”?
User: YYES
Assistant: Are there valid executions where “Choose shipping detail” occurs but “Choose a shipping preference” does not occur?
User: NO
Assistant: Can “Choose a shipping speed” occur only after “Choose shipping detail”?
User: YES
Assistant: Are there valid executions where “Choose shipping detail” occurs but “Choose a shipping speed” does not occur?
User: NO
Assistant: Can “Choose a shipping preference” and “Choose a shipping speed” occur in any order, or must one always happen before the other?
User: OCCUR IN ANY ORDER
Assistant: Before “Review your order” can occur, must both “Choose a shipping preference” and “Choose a shipping speed” already be completed, even though they may happen in any order?
User: YES
Assistant: Can “Change quantities or delete items” occur after the shipping-related activities have already started, and then require the process to return to an earlier activity such as selecting shipping details again?
User: occur after the shipping-related activities have already started
Assistant: If “Change quantities or delete items” occurs after shipping activities have started, can the process return to “Choose shipping detail”?
User: NO
Assistant: Before “Review your order” can occur, must “Change quantities or delete items” be completed if that activity was performed?
User: YES
Assistant: Can “Review your order” occur without “Change quantities or delete items” ever occurring?
User: YES
Assistant: Can “Order the exist gift items” and “Change quantities or delete items” occur together in the same execution?
User: YES
Assistant: Before “Review your order” can occur, must “Order the exist gift items” already be completed whenever that activity is performed?
User: YES
Assistant: Before “Review your order” can occur, must “Select a payment method” already be completed?
User: NO
Assistant: Can “Review your order” occur before any payment method activity is selected, or must a payment method always be selected first?
User: occur before any payment method activity is selected
Assistant: Can “Place order” occur only after “Review your order”?
User: NO
Assistant: Can “Place order” occur without “Review your order” ever occurring?
User: YES
Assistant: Can “Review your order” and “Place order” occur together in the same execution?
User: NO
Assistant: Can “Review your order” and “Place order” ever both occur in the same process execution, even at different times?
User: YES
Assistant: Can “Select a payment method” occur after “Review your order”?
User: YES
Assistant: If “Select a payment method” occurs after “Review your order”, can the process later return to “Review your order” before placing the order?
User: YES
Assistant: When “Select a payment method” is performed, must exactly one of these payment options be chosen in that execution?
- “Credit or Debit Cards”
- “Amazon.com Store Card”
- “Checking Account”
- “Gift Cards & Promotional Codes”
User: YES
Assistant: Can “Credit or Debit Cards” and “Amazon.com Store Card” occur together in the same execution?
User: NO
Assistant: Can “Credit or Debit Cards” and “Checking Account” occur together in the same execution?
User: NO
Assistant: Can “Credit or Debit Cards” and “Gift Cards & Promotional Codes” occur together in the same execution?
User: NO
Assistant: Can “Amazon.com Store Card” and “Checking Account” occur together in the same execution?
User: NO
Assistant: Can “Amazon.com Store Card” and “Gift Cards & Promotional Codes” occur together in the same execution?
User: NO
Assistant: Can “Checking Account” and “Gift Cards & Promotional Codes” occur together in the same execution?
User: NO
Assistant: Before “Credit or Debit Cards” can occur, must “Select a payment method” already have occurred?
User: SIM
Assistant: Are there valid executions where “Select a payment method” occurs but “Credit or Debit Cards” does not occur?
User: YES
Assistant: Before “Amazon.com Store Card” can occur, must “Select a payment method” already have occurred?
User: YES
Assistant: Are there valid executions where “Select a payment method” occurs but “Amazon.com Store Card” does not occur?
User: YES
Assistant: Before “Checking Account” can occur, must “Select a payment method” already have occurred?
User: YES
Assistant: Are there valid executions where “Select a payment method” occurs but “Checking Account” does not occur?
User: YES
Assistant: Before “Gift Cards & Promotional Codes” can occur, must “Select a payment method” already have occurred?
User: YES
Assistant: Are there valid executions where “Select a payment method” occurs but “Gift Cards & Promotional Codes” does not occur?
User: YES
Assistant: Before “Place order” can occur, must exactly one payment option already be completed?
User: NO
Assistant: Can “Place order” occur before any of these payment option activities occur?
- “Credit or Debit Cards”
- “Amazon.com Store Card”
- “Checking Account”
- “Gift Cards & Promotional Codes”
User: NO
Assistant: Before “Place order” can occur, must “Select a payment method” already have occurred?
User: NO
Assistant: If one of these payment option activities occurs:
- “Credit or Debit Cards”
- “Amazon.com Store Card”
- “Checking Account”
- “Gift Cards & Promotional Codes”
must “Place order” eventually occur afterward in that execution?
User: YES
Assistant: Can “Switch currency” and “Place order in default currency” occur together in the same execution?
User: YES
Assistant: Before “Place order in default currency” can occur, must “Switch currency” already have occurred?
User: NO
Assistant: Can “Place order in default currency” occur without “Place order” occurring?
User: NO
Assistant: When “Place order in default currency” occurs, must “Place order” already have occurred before it?
User: YES
Assistant: Before “Change billing address” can occur, must one of the shipping address activities already have occurred first?
- “Choose existing shipping address”
- “Enter new shipping address”
- “Edit exist shipping address”
User: YES
Assistant: When “Change billing address” occurs, must it happen BEFORE “Place order”?
User: YES
Assistant: If “Change billing address” occurs, must “Place order” always eventually occur afterward in that execution?
User: NO
Assistant: If “Select a payment method” occurs after “Review your order”, can the process return to “Review your order” again before “Place order”?
User: YES
Assistant: After “Select a payment method”, can the process return directly to “Review your order” multiple times before the final “Place order”?
User: YES
Final SBMN Model

Process name: Paying Fees Process

Activity list:
- Pay the book/s fee
- Choose existing shipping address
- Enter new shipping address
- Edit exist shipping address
- Choose shipping detail
- Choose a shipping preference
- Choose a shipping speed
- Change quantities or delete items
- Order the exist gift items
- Select a payment method
- Credit or Debit Cards
- Amazon.com Store Card
- Checking Account
- Gift Cards & Promotional Codes
- Review your order
- Place order
- Switch currency
- Change billing address
- Place order in default currency

SBMN relations:

Choose existing shipping address XOR Enter new shipping address
Choose existing shipping address XOR Edit exist shipping address
Enter new shipping address XOR Edit exist shipping address
Choose shipping detail DEPC Choose existing shipping address
Choose shipping detail DEPC Enter new shipping address
Choose shipping detail DEPC Edit exist shipping address
Choose a shipping preference DEP Choose shipping detail
Choose a shipping speed DEP Choose shipping detail
Review your order DEP Choose a shipping preference
Review your order DEP Choose a shipping speed
Review your order REQ Change quantities or delete items
Review your order REQ Order the exist gift items
Credit or Debit Cards XOR Amazon.com Store Card
Credit or Debit Cards XOR Checking Account
Credit or Debit Cards XOR Gift Cards & Promotional Codes
Amazon.com Store Card XOR Checking Account
Amazon.com Store Card XOR Gift Cards & Promotional Codes
Checking Account XOR Gift Cards & Promotional Codes
Credit or Debit Cards REQ Select a payment method
Amazon.com Store Card REQ Select a payment method
Checking Account REQ Select a payment method
Gift Cards & Promotional Codes REQ Select a payment method
Place order DEPC Credit or Debit Cards
Place order DEPC Amazon.com Store Card
Place order DEPC Checking Account
Place order DEPC Gift Cards & Promotional Codes
Place order in default currency DEP Place order

JMP relations:

Select a payment method JMP Review your order

This SBMN model is consistent and has at least one valid BPMN realization.

