# SBMN Interview Transcript

**Assistant:** Welcome!
Which language would you like to use for the interview?

**User:** english

---

**Assistant:** What is the name of the process you want to model?

**User:** Prepare Mortgage Documents

---

**Assistant:** What is the business domain of “Prepare Mortgage Documents”?

**User:** Mortgage Documentation

---

**Assistant:** Please provide the full list of activities involved in the “Prepare Mortgage Documents” process.
List all activities you want included in the model.

**User:**

* Send Main Document
* Send Supplement A
* Send Supplement B

---

**Assistant:** Can “Send Main Document” and “Send Supplement A” occur together in the same process execution?

**User:** yes

---

**Assistant:** Can “Send Main Document” and “Send Supplement B” occur together in the same process execution?

**User:** YES

---

**Assistant:** Can “Send Supplement A” and “Send Supplement B” occur together in the same process execution?

**User:** YES

---

**Assistant:** Can “Send Supplement A” occur only after “Send Main Document” has already been sent?

**User:** YES

---

**Assistant:** Are there valid executions where “Send Main Document” occurs but “Send Supplement A” does not occur?

**User:** YES

---

**Assistant:** Can “Send Supplement B” occur only after “Send Main Document” has already been sent?

**User:** YES

---

**Assistant:** Are there valid executions where “Send Main Document” occurs but “Send Supplement B” does not occur?

**User:** YES

---

**Assistant:** Can “Send Supplement A” occur only after “Send Supplement B” has already been sent?

**User:** NO

---

**Assistant:** Can “Send Supplement B” occur only after “Send Supplement A” has already been sent?

**User:** YES

---

**Assistant:** Are there valid executions where “Send Supplement A” occurs but “Send Supplement B” does not occur?

**User:** YES

---

**Assistant:** After completing “Send Supplement A,” can the process return to or skip directly to another non-adjacent activity?

**User:** NO

---

**Assistant:** After completing “Send Supplement B,” can the process return to or skip directly to another non-adjacent activity?

**User:** NO

---

# Final SBMN Model

**Process name:** Prepare Mortgage Documents

## Activity list

* Send Main Document
* Send Supplement A
* Send Supplement B

## SBMN relations

* Send Supplement A REQ Send Main Document
* Send Supplement B REQ Send Main Document
* Send Supplement B REQ Send Supplement A

This SBMN model is consistent and has at least one valid BPMN realization.
