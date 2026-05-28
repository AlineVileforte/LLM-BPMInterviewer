Complete SBMN Interview Transcript

This document contains the most complete reconstruction possible of the SBMN interview,
including the questions asked by the interviewer and the answers provided by the interviewee,
followed by the final SBMN model.

Q1. Which language would you like to use for the interview?
A1. English
Q2. What is the name of the process?
A2. Order Fulfillment and Customer Management Process
Q3. What is the domain of the process?
A3. Sales and Logistics
Q4. Please provide the complete list of activities.
A4. Activity list provided
Q5. Can Check Payment History occur only after Check Customer?
A5. Yes, after
Q6. Can Check Customer Type occur only after Check Payment History?
A6. Yes, after
Q7. Can Declining Message occur only after Check Customer Type?
A7. Yes, after
Q8. Can Create new Customer and Declining Message occur together?
A8. No
Q9. Can Create new Customer occur only after Check Customer Type?
A9. Yes, after
Q10. Can Check Availability occur only after Create new Customer?
A10. Yes, after
Q11. Can Sending Confirmation to Customer occur only after Check Availability?
A11. Yes, after
Q12. Can Producing missing goods occur only after Check Availability?
A12. Yes
Q13. Can Sending Confirmation to Customer and Producing missing goods occur together?
A13. Yes
Q14. Can getting ready for delivery occur only after Sending Confirmation to Customer?
A14. Yes, after
Q15. Can Pack the Goods occur only after getting ready for delivery?
A15. Yes, after
Q16. Can Deliver the Goods occur only after Pack the Goods?
A16. Yes, after
Q17. Can Preparing Invoice occur only after Deliver the Goods?
A17. Initially yes
Q18. Can Send the Invoice to Customer occur only after Preparing Invoice?
A18. Yes, after
Q19. Can Check for Payment occur only after Send the Invoice to Customer?
A19. Yes, after
Q20. Can closing order ou occur only after Check for Payment?
A20. Yes, after
Q21. Can Checking the reminders occur only after Check for Payment?
A21. Yes, after
Q22. Can Dunning Process occur only after Checking the reminders?
A22. Yes, after
Q23. Can closing order ou and Dunning Process occur together?
A23. No
Q24. Can the process return from Checking the reminders to Check for Payment?
A24. Yes
Q25. Can Declining Message and Check Availability occur together?
A25. No
Q26. Can Declining Message and Sending Confirmation to Customer occur together?
A26. No
Q27. Can Producing missing goods and getting ready for delivery occur together?
A27. Yes
Q28. Can Pack the Goods occur without Producing missing goods?
A28. Yes
Q29. Must Sending Confirmation to Customer occur before Pack the Goods?
A29. Yes
Q30. Must Deliver the Goods occur before closing order ou?
A30. Yes
Q31. Must Deliver the Goods occur before Dunning Process?
A31. Yes
Q32. Are Check Payment History and Check Customer Type exclusive?
A32. Yes
Q33. Can Declining Message occur after Check Payment History?
A33. Yes
Q34. Can Create new Customer occur after either Check Customer Type or Check Payment History?
A34. Yes
Q35. Must Create new Customer occur before Check Availability?
A35. Yes
Q36. Must Sending Confirmation to Customer always occur after Check Availability?
A36. Yes
Q37. Must getting ready for delivery always occur after Sending Confirmation to Customer?
A37. Yes
Q38. Must Pack the Goods always occur after getting ready for delivery?
A38. Yes
Q39. Can Preparing Invoice and Deliver the Goods occur in any order?
A39. Yes
Q40. Must Send the Invoice to Customer occur after Preparing Invoice?
A40. Yes
Q41. Must Check for Payment occur after Send the Invoice to Customer?
A41. Yes
Q42. Must Check for Payment occur before closing order ou?
A42. Yes
Q43. Must Checking the reminders occur before Dunning Process?
A43. Yes
Q44. Must Check for Payment occur before Dunning Process?
A44. Yes
Q45. Can Dunning Process return to Check for Payment?
A45. No
Q46. Can Checking the reminders directly return to Check for Payment?
A46. Yes
Q47. Can any other activity return to another non-adjacent activity?
A47. No
Final SBMN Model

Process name:
Order Fulfillment and Customer Management Process

Activity list:
- Check Customer
- Check Payment History
- Check Customer Type
- Declining Message
- Create new Customer
- Check Availability
- Sending Confirmation to Customer
- Producing missing goods
- getting ready for delivery
- Pack the Goods
- Deliver the Goods
- Preparing Invoice
- Send the Invoice to Customer
- Check for Payment
- closing order ou
- Checking the reminders
- Dunning Process

SBMN Relations

Check Payment History REQ Check Customer
Check Payment History XOR Check Customer Type
Declining Message XOR Create new Customer
Declining Message XOR Check Availability
Declining Message XOR Sending Confirmation to Customer
Check Availability DEP Create new Customer
Check Availability REQ Check Customer Type
Sending Confirmation to Customer DEP Check Availability
Producing missing goods REQ Check Availability
getting ready for delivery DEP Sending Confirmation to Customer
getting ready for delivery DEPC Producing missing goods
Pack the Goods DEP getting ready for delivery
Pack the Goods DEP Sending Confirmation to Customer
Deliver the Goods DEP Pack the Goods
Send the Invoice to Customer DEP Preparing Invoice
Check for Payment DEP Send the Invoice to Customer
closing order ou REQ Check for Payment
closing order ou REQ Deliver the Goods
Checking the reminders REQ Check for Payment
Dunning Process REQ Checking the reminders
Dunning Process REQ Check for Payment
closing order ou XOR Dunning Process

JMP Relations

Checking the reminders JMP Check for Payment

