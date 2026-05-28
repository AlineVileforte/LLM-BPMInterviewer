### SBMN Interview (Complete Transcript)

**Interviewer:** Welcome to the SBMN process elicitation interview. I will conduct a structured interview to capture the process and build a logically consistent SBMN model.

Which language would you like to use for the interview? (e.g., English, Portuguese, Spanish, etc.)

**Interviewee:** ENGLISH

---

**Interviewer:** What is the name of the process you want to model?

**Interviewee:** Purchase Order Process

---

**Interviewer:** What is the business domain or industry of the Purchase Order Process? (For example: Manufacturing, Retail, Healthcare, Construction, IT Services, etc.)

**Interviewee:** Supply Chain Management

---

**Interviewer:** Please provide the complete list of activities in the Purchase Order Process.

List all activities that can occur in the process, one per line or separated by commas. After you provide the list, the activity list will be frozen and no new activities can be added.

**Interviewee:**

* Check Inventory
* Inventory Available
* Inventory Not Available
* Reject Purchase Order
* Confirm Purchase Order
* Ship Product
* Send Invoice

---

**Interviewer:** After Check Inventory, can Inventory Available and Inventory Not Available occur together in the same execution of the process? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** Does Inventory Available always lead to Confirm Purchase Order? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Can Confirm Purchase Order occur without Inventory Available occurring first? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** Are there valid executions where Inventory Available occurs but Confirm Purchase Order does not occur? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** Before Confirm Purchase Order occurs, must Inventory Available occur before it? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Does Inventory Not Available always lead to Reject Purchase Order? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Can Reject Purchase Order occur without Inventory Not Available occurring first? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** Are there valid executions where Inventory Not Available occurs but Reject Purchase Order does not occur? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** Before Reject Purchase Order occurs, must Inventory Not Available occur before it? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Does Check Inventory always occur before Inventory Available whenever Inventory Available occurs? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Are there valid executions where Check Inventory occurs but Inventory Available does not occur? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Does Check Inventory always occur before Inventory Not Available whenever Inventory Not Available occurs? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Are there valid executions where Check Inventory occurs but Inventory Not Available does not occur? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Does Confirm Purchase Order always occur before Ship Product whenever Ship Product occurs? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Can Ship Product occur without Confirm Purchase Order occurring first? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** Are there valid executions where Confirm Purchase Order occurs but Ship Product does not occur? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** Before Ship Product occurs, must Confirm Purchase Order occur before it? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Does Ship Product always occur before Send Invoice whenever Send Invoice occurs? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** Can Send Invoice occur without Ship Product occurring first? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Does Confirm Purchase Order always occur before Send Invoice whenever Send Invoice occurs? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Can Send Invoice occur without Confirm Purchase Order occurring first? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** Are there valid executions where Confirm Purchase Order occurs but Send Invoice does not occur? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** Before Send Invoice occurs, must Confirm Purchase Order occur before it? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** After Check Inventory, must either Inventory Available or Inventory Not Available occur in every execution? (Yes/No)

**Interviewee:** YES

---

**Interviewer:** Can Confirm Purchase Order and Reject Purchase Order occur together in the same execution of the process? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** When both Ship Product and Send Invoice occur in the same execution, must one always occur before the other, or can they occur in any order?

* Ship Product must occur before Send Invoice
* Send Invoice must occur before Ship Product
* They can occur in any order
* They never occur together

**Interviewee:** They can occur in any order

---

**Interviewer:** If Reject Purchase Order occurs, can the process return to any earlier activity (for example, rechecking inventory or repeating a previous step)? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** If Send Invoice occurs, can the process return to any earlier activity (for example, rechecking inventory, reconfirming the order, or reshipping)? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** If Ship Product occurs, can the process return to any earlier activity (for example, reconfirming the order or rechecking inventory)? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** If Confirm Purchase Order occurs, can the process return to any earlier activity (for example, rechecking inventory)? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** If Inventory Available occurs, can the process return to any earlier activity (for example, repeating Check Inventory)? (Yes/No)

**Interviewee:** NO

---

**Interviewer:** If Inventory Not Available occurs, can the process return to any earlier activity (for example, repeating Check Inventory)? (Yes/No)

**Interviewee:** NO

---

## Final SBMN Model

**Process name:** Purchase Order Process

**Activity list:**

* Check Inventory
* Inventory Available
* Inventory Not Available
* Reject Purchase Order
* Confirm Purchase Order
* Ship Product
* Send Invoice

**SBMN relations:**

Inventory Available REQ Check Inventory

Inventory Not Available REQ Check Inventory

Inventory Available XOR Inventory Not Available

Confirm Purchase Order REQ Inventory Available

Reject Purchase Order REQ Inventory Not Available

Confirm Purchase Order XOR Reject Purchase Order

Ship Product REQ Confirm Purchase Order

Send Invoice REQ Confirm Purchase Order

**This SBMN model is consistent and has at least one valid BPMN realization.**
