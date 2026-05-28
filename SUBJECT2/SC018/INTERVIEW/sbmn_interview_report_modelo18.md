# SBMN Interview Report

## Process Information

**Process Name:** Cinema Reservation and Customer Registration Process\
**Domain:** E-commerce Operations

## Activities

-   Customer connects to the information system
-   Choose the type of search to perform
-   Select theater room
-   Select movie
-   Select time
-   Select movie and time
-   Select theater room and time
-   Select movie and theater room
-   Selection summary
-   Is the customer already registered?
-   Log in
-   Create an account
-   Reservation
-   Payment decision
-   Confirm reservation by sending an email
-   Manage satisfaction survey

## Final SBMN Relations

-   Choose the type of search to perform DEP Customer connects to the
    information system
-   Select theater room REQ Choose the type of search to perform
-   Select movie REQ Choose the type of search to perform
-   Select time REQ Choose the type of search to perform
-   Select theater room XOR Select movie
-   Select theater room XOR Select time
-   Select movie XOR Select time
-   Select movie and time DEP Select theater room
-   Select theater room and time DEP Select movie
-   Select movie and theater room DEP Select time
-   Selection summary DEPC Select movie and time
-   Selection summary DEPC Select theater room and time
-   Selection summary DEPC Select movie and theater room
-   Is the customer already registered? DEP Selection summary
-   Log in REQ Is the customer already registered?
-   Create an account REQ Is the customer already registered?
-   Log in XOR Create an account
-   Reservation DEPC Log in
-   Reservation DEPC Create an account
-   Payment decision DEP Reservation
-   Confirm reservation by sending an email DEP Payment decision
-   Manage satisfaction survey DEP Confirm reservation by sending an
    email

## JMP Relations

None

## Interview Statistics

Approximate number of questions: 29

## Complete Interview Trace

Q1: Customer connects → Choose search type\
A: Yes

Q2: Customer connects without Choose search type?\
A: No

Q3: Select theater room after search type?\
A: Yes

Q4: Search type without theater room?\
A: Yes

Q5: Theater room, movie and time mutually exclusive?\
A: Yes

Q6-Q9: Movie and time branch validations\
A: Yes

Q10-Q15: Composite selection branch validations\
A: Yes

Q16-Q19: Selection summary convergence validations\
A: Yes

Q20-Q24: Registration/Login/Create account validations\
A: Yes

Q25: Reservation after login/create account\
A: Yes

Q26: Payment decision after reservation\
A: Yes

Q27: Confirmation email after payment decision\
A: Yes

Q28: Satisfaction survey after confirmation\
A: Yes

Q29: Loop/JMP validation\
A: No

Final validation: This SBMN model is consistent and has at least one
valid BPMN realization.
