EXECUTE
 
ENGLISH
 
1. Exam Enrollment Process
2. Academic
3. ACCESS ESSE3 
ENTER LOGIN 
ENTER PASSWORD 
PRESS CONFIRM 
CLICK THE “EXAMS” ITEM 
CLICK THE “EXAM SESSIONS” ITEM 
CHOOSE THE COURSE 
PRESS CONFIRM 3 TIMES WITHOUT READING WHAT IS WRITTEN 
PRINT THE ENROLLMENT CONFIRMATION 
fine iscrizione 
HOPE FOR A GOOD OUTCOME 
ENROLL IN ANOTHER EXAM
 
Can “ENTER LOGIN” occur without “ACCESS ESSE3” occurring at some point in the same process execution?
 
NO
 
When “ENTER LOGIN” occurs, must “ACCESS ESSE3” occur BEFORE, AFTER, or can both occur in any order depending on the execution?
 
BEFORE
 
Are there valid executions of the process where “ACCESS ESSE3” occurs but “ENTER LOGIN” does not occur?
 
NO
 
Can “ENTER PASSWORD” occur without “ENTER LOGIN” occurring at some point in the same process execution?
 
NO
 
When “ENTER PASSWORD” occurs, must “ENTER LOGIN” occur BEFORE, AFTER, or can both occur in any order depending on the execution?
 
can both occur in any order depending
 
Are there valid executions of the process where “ENTER LOGIN” occurs but “ENTER PASSWORD” does not occur?
 
NO
 
If “ENTER PASSWORD” and “ENTER LOGIN” always occur together, but neither structurally precedes or enables the other, is there any mandatory structural ordering between them?
 
NO
 
Can “PRESS CONFIRM” occur without “ENTER PASSWORD” occurring at some point in the same process execution?
 
NO
 
When “PRESS CONFIRM” occurs, must “ENTER PASSWORD” occur BEFORE, AFTER, or can both occur in any order depending on the execution?
 
BEFORE
 
Are there valid executions of the process where “ENTER PASSWORD” occurs but “PRESS CONFIRM” does not occur?
 
NO
 
Can “CLICK THE “EXAMS” ITEM” occur without “PRESS CONFIRM” occurring at some point in the same process execution?
 
NO
 
When “CLICK THE “EXAMS” ITEM” occurs, must “PRESS CONFIRM” occur BEFORE, AFTER, or can both occur in any order depending on the execution?
 
BEFORE
 
Are there valid executions of the process where “PRESS CONFIRM” occurs but “CLICK THE “EXAMS” ITEM” does not occur?
 
Can “CLICK THE “EXAM SESSIONS” ITEM” occur without “CLICK THE “EXAMS” ITEM” occurring at some point in the same process execution?
 
NO
NO
 
When “CLICK THE “EXAM SESSIONS” ITEM” occurs, must “CLICK THE “EXAMS” ITEM” occur BEFORE, AFTER, or can both occur in any order depending on the execution?
 
BEFORE
 
Are there valid executions of the process where “CLICK THE “EXAMS” ITEM” occurs but “CLICK THE “EXAM SESSIONS” ITEM” does not occur?
 
NO
 
Can “CHOOSE THE COURSE” occur without “CLICK THE “EXAM SESSIONS” ITEM” occurring at some point in the same process execution?
 
NO
 
When “CHOOSE THE COURSE” occurs, must “CLICK THE “EXAM SESSIONS” ITEM” occur BEFORE, AFTER, or can both occur in any order depending on the execution?
 
BEFORE
 
Are there valid executions of the process where “CLICK THE “EXAM SESSIONS” ITEM” occurs but “CHOOSE THE COURSE” does not occur?
 
NO
 
Can “PRESS CONFIRM 3 TIMES WITHOUT READING WHAT IS WRITTEN” occur without “CHOOSE THE COURSE” occurring at some point in the same process execution?
 
NO
 
When “PRESS CONFIRM 3 TIMES WITHOUT READING WHAT IS WRITTEN” occurs, must “CHOOSE THE COURSE” occur BEFORE, AFTER, or can both occur in any order depending on the execution?
 
BEFORE
 
Are there valid executions of the process where “CHOOSE THE COURSE” occurs but “PRESS CONFIRM 3 TIMES WITHOUT READING WHAT IS WRITTEN” does not occur?
 
NO
 
Can “PRINT THE ENROLLMENT CONFIRMATION” occur without “PRESS CONFIRM 3 TIMES WITHOUT READING WHAT IS WRITTEN” occurring at some point in the same process execution?
 
NO
 
When “PRINT THE ENROLLMENT CONFIRMATION” occurs, must “PRESS CONFIRM 3 TIMES WITHOUT READING WHAT IS WRITTEN” occur BEFORE, AFTER, or can both occur in any order depending on the execution?
 
BEFORE
 
Are there valid executions of the process where “PRESS CONFIRM 3 TIMES WITHOUT READING WHAT IS WRITTEN” occurs but “PRINT THE ENROLLMENT CONFIRMATION” does not occur?
 
YES
 
Can “fine iscrizione” occur without “PRINT THE ENROLLMENT CONFIRMATION” occurring at some point in the same process execution?
 
YES
 
Can “PRINT THE ENROLLMENT CONFIRMATION” and “fine iscrizione” occur together in the same process execution?
 
NO
 
Can “HOPE FOR A GOOD OUTCOME” occur without “fine iscrizione” occurring at some point in the same process execution?
 
Can “HOPE FOR A GOOD OUTCOME” occur without “fine iscrizione” occurring at some point in the same process execution?
 
YES
 
Can “HOPE FOR A GOOD OUTCOME” and “fine iscrizione” occur together in the same process execution?
 
YES
 
When “HOPE FOR A GOOD OUTCOME” occurs, must “fine iscrizione” occur BEFORE, AFTER, or can both occur in any order depending on the execution?
 
BEFORE
 
Are there valid executions of the process where “fine iscrizione” occurs but “HOPE FOR A GOOD OUTCOME” does not occur?
 
NO
 
Can “ENROLL IN ANOTHER EXAM” occur without “HOPE FOR A GOOD OUTCOME” occurring at some point in the same process execution?
 
NO
 
When “ENROLL IN ANOTHER EXAM” occurs, must “HOPE FOR A GOOD OUTCOME” occur BEFORE, AFTER, or can both occur in any order depending on the execution?
 
BEFORE
 
Are there valid executions of the process where “HOPE FOR A GOOD OUTCOME” occurs but “ENROLL IN ANOTHER EXAM” does not occur?
 
YES
 
After completing any activity, can the process return to or skip directly to another non-adjacent activity?
 
YES
 
Which activity can the process return to or skip directly to?
 
From “ENROLL IN ANOTHER EXAM” to “CHOOSE THE COURSE”.
 
Process name: Exam Enrollment Process
Domain: Academic
 
Activity list:
- ACCESS ESSE3
- ENTER LOGIN
- ENTER PASSWORD
- PRESS CONFIRM
- CLICK THE “EXAMS” ITEM
- CLICK THE “EXAM SESSIONS” ITEM
- CHOOSE THE COURSE
- PRESS CONFIRM 3 TIMES WITHOUT READING WHAT IS WRITTEN
- PRINT THE ENROLLMENT CONFIRMATION
-END ENROLLMENT
- HOPE FOR A GOOD OUTCOME
- ENROLL IN ANOTHER EXAM
 
SBMN relations:
 
ENTER LOGIN DEP ACCESS ESSE3
 PRESS CONFIRM DEP ENTER PASSWORD
 CLICK THE “EXAMS” ITEM DEP PRESS CONFIRM
 CLICK THE “EXAM SESSIONS” ITEM DEP CLICK THE “EXAMS” ITEM
 CHOOSE THE COURSE DEP CLICK THE “EXAM SESSIONS” ITEM
 PRESS CONFIRM 3 TIMES WITHOUT READING WHAT IS WRITTEN DEP CHOOSE THE COURSE
 PRINT THE ENROLLMENT CONFIRMATION REQ PRESS CONFIRM 3 TIMES WITHOUT READING WHAT IS WRITTEN
 fine iscrizione XOR PRINT THE ENROLLMENT CONFIRMATION
 HOPE FOR A GOOD OUTCOME DEPEND ENROLLMENT
 ENROLL IN ANOTHER EXAM REQ HOPE FOR A GOOD OUTCOME
 
JMP relations:
 
ENROLL IN ANOTHER EXAM JMP CHOOSE THE COURSE
 This SBMN model is consistent and has at least one valid BPMN realization.
