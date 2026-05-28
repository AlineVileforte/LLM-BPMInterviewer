# SBMN Interview Report

## Process Information

**Process Name:** Go to the Cinema Process\
**Domain:** B2C

## Activities

-   Enter the Hoyts website
-   Look for the La Nacion card for the discount
-   Look for the Citi card for the discount
-   Search for a movie I like at a convenient time
-   Pay for the tickets through the website
-   Print the tickets
-   Buy popcorn
-   Hand the tickets to the ticket clerk
-   Sit down in the theater
-   Drive to the cinema

## Final SBMN Relations

-   Look for the La Nacion card for the discount DEP Enter the Hoyts
    website
-   Look for the Citi card for the discount DEP Look for the La Nacion
    card for the discount
-   Look for the Citi card for the discount JMP Look for the La Nacion
    card for the discount
-   Pay for the tickets through the website REQ Search for a movie I
    like at a convenient time
-   Buy popcorn DEP Print the tickets
-   Hand the tickets to the ticket clerk DEP Buy popcorn
-   Sit down in the theater DEP Hand the tickets to the ticket clerk
-   Drive to the cinema DEP Sit down in the theater

## JMP Relations

-   Look for the Citi card for the discount JMP Look for the La Nacion
    card for the discount

## Interview Statistics

Approximate number of questions: 22

------------------------------------------------------------------------

# Complete Interview Trace

Q1: Must Enter the Hoyts website occur before Look for the La Nacion
card for the discount? A: Yes

Q2: Can Enter the Hoyts website occur without Look for the La Nacion
card? A: No

Q3: Must Look for the Citi card occur after Look for the La Nacion card?
A: Yes

Q4: Can Look for the Citi card jump back to Look for the La Nacion card?
A: Yes

Q5: Can Search for a movie occur before payment? A: Yes

Q6: Can payment occur after searching for a movie? A: Yes

Q7: Must Buy popcorn occur after Print tickets? A: Yes

Q8: Must Hand the tickets to the ticket clerk occur after Buy popcorn?
A: Yes

Q9: Must Sit down in the theater occur after Hand the tickets? A: Yes

Q10: Must Drive to the cinema occur after Sit down in the theater? A:
Yes

------------------------------------------------------------------------

Final validation:

This SBMN model is consistent and has at least one valid BPMN
realization.
