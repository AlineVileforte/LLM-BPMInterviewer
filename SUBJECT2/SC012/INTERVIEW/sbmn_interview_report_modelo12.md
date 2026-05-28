# SBMN Interview Report

## Process Information

**Process Name:** Nico Activity Decision Process\
**Domain:** Decision Making

## Activities

-   Nico is bored
-   Nico is hungry
-   Nico has an irresistible urge
-   Nico wants to go fishing
-   Nico eats a banana
-   Nico watches funny videos
-   Nico goes fishing
-   Nico is happy

## Final SBMN Relations

-   Nico is hungry REQ Nico is bored
-   Nico has an irresistible urge REQ Nico is bored
-   Nico wants to go fishing REQ Nico is bored
-   Nico eats a banana DEP Nico is hungry
-   Nico watches funny videos DEP Nico has an irresistible urge
-   Nico goes fishing DEP Nico wants to go fishing
-   Nico is happy DEPC Nico eats a banana
-   Nico is happy DEPC Nico watches funny videos
-   Nico is happy DEPC Nico goes fishing

## JMP Relations

None

## Interview Statistics

Approximate number of questions: 11

------------------------------------------------------------------------

# Complete Interview Trace

Q1: Before Nico is hungry can occur, must Nico is bored have occurred
before? A: Yes

Q2: Are there valid executions where Nico is bored occurs but Nico is
hungry does not occur? A: Yes

Q3: Before Nico has an irresistible urge can occur, must Nico is bored
have occurred before? A: Yes

Q4: Are there valid executions where Nico is bored occurs but Nico has
an irresistible urge does not occur? A: Yes

Q5: Before Nico wants to go fishing can occur, must Nico is bored have
occurred before? A: Yes

Q6: Are there valid executions where Nico is bored occurs but Nico wants
to go fishing does not occur? A: Yes, when Nico has an irresistible urge
or Nico is hungry occurs.

Q7: Before Nico eats a banana can occur, must Nico is hungry have
occurred before? A: Yes

Q8: Are there valid executions where Nico is hungry occurs but Nico eats
a banana does not occur? A: No

Q9: Before Nico watches funny videos can occur, must Nico has an
irresistible urge have occurred before? A: Yes

Q10: Are there valid executions where Nico has an irresistible urge
occurs but Nico watches funny videos does not occur? A: No

Q11: Before Nico goes fishing can occur, must Nico wants to go fishing
have occurred before? A: Yes

Q12: Are there valid executions where Nico wants to go fishing occurs
but Nico goes fishing does not occur? A: No

Q13: Before Nico is happy can occur, must one of the three paths be
completed? A: Yes

Q14: If Nico eats a banana occurs, must Nico is happy occur afterward?
A: Yes

Q15: If Nico watches funny videos occurs, must Nico is happy occur
afterward? A: Yes

Q16: If Nico goes fishing occurs, must Nico is happy occur afterward? A:
Yes

Q17: Can the process return to an earlier activity? A: No

------------------------------------------------------------------------

Final validation:

This SBMN model is consistent and has at least one valid BPMN
realization.
