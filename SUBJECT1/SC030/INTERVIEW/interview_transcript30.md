SBMN Interview Transcript
Process: Product Prototype Development
Full Interview
Assistant: Welcome to the SBMN interview. Which language would you like to use for the interview?
User: english
Assistant: What is the name of the process you want to model?
User: Product Prototype Development
Assistant: What is the business domain or industry of the “Product Prototype Development” process?
User: Product Development/R&D
Assistant: Please provide the complete list of activities involved in the process.
User: Identify idea for new product or improvement
Conduct initial research
Conduct feasibility studies
Draft design concepts
Select promising design
Build prototype
Test safety
Test market potential
Test functionality
Collect feedback from testing phase
Refine prototype
Approve prototype for further development
Discard prototype
Assistant: Does “Conduct initial research” always require “Identify idea for new product or improvement” to have occurred before it?
User: YES
Assistant: Are there valid executions where “Identify idea for new product or improvement” occurs but “Conduct initial research” does not occur?
User: NO
Assistant: Does “Conduct feasibility studies” always require “Conduct initial research” to have occurred before it?
User: NO
Assistant: Can “Conduct feasibility studies” occur before “Conduct initial research,” or must “Conduct initial research” happen before it whenever feasibility studies occur?
User: NO, IN ANY ORDER
Assistant: Does “Draft design concepts” require either “Conduct initial research” or “Conduct feasibility studies” beforehand?
User: YES, BOTH
Assistant: When “Draft design concepts” occurs, must “Conduct initial research” happen before it?
User: YES
Assistant: Are there valid executions where “Conduct initial research” occurs but “Draft design concepts” does not occur?
User: NO
Assistant: When “Draft design concepts” occurs, must “Conduct feasibility studies” happen before it?
User: YES
Assistant: Are there valid executions where “Conduct feasibility studies” occurs but “Draft design concepts” does not occur?
User: NO
Assistant: Does “Select promising design” always require “Draft design concepts” to have occurred before it?
User: YES
Assistant: Are there valid executions where “Draft design concepts” occurs but “Select promising design” does not occur?
User: NO
Assistant: Does “Build prototype” always require “Select promising design” to have occurred before it?
User: YES
Assistant: Are there valid executions where “Select promising design” occurs but “Build prototype” does not occur?
User: NO
Assistant: Do the testing activities all require “Build prototype” beforehand?
User: YES
Assistant: Are there valid executions where “Build prototype” occurs but one or more testing activities do not occur?
User: NO
Assistant: Do all three testing activities always occur in every valid execution once “Build prototype” occurs?
User: Do all three testing activities always occur
Assistant: After all required testing activities are completed, does “Collect feedback from testing phase” require all three testing activities beforehand?
User: YES
Assistant: Are there valid executions where all three testing activities occur, but “Collect feedback from testing phase” does not occur?
User: NO
Assistant: Does “Refine prototype” always require “Collect feedback from testing phase” beforehand?
User: YES
Assistant: Are there valid executions where “Collect feedback from testing phase” occurs but “Refine prototype” does not occur?
User: YES
Assistant: Can “Approve prototype for further development” happen without “Refine prototype” occurring first?
User: YES
Assistant: Does “Approve prototype for further development” require “Collect feedback from testing phase” beforehand?
User: YES
Assistant: Are there valid executions where “Collect feedback from testing phase” occurs but “Approve prototype for further development” does not occur?
User: YES
Assistant: Can “Discard prototype” occur in the same execution where “Approve prototype for further development” occurs?
User: NO
Assistant: Does “Discard prototype” require “Collect feedback from testing phase” beforehand?
User: YES
Assistant: Are there valid executions where “Collect feedback from testing phase” occurs but “Discard prototype” does not occur?
User: YES
Assistant: Can “Discard prototype” happen without “Refine prototype” occurring first?
User: YES
Assistant: If “Refine prototype” occurs, can the process later return to testing activities?
User: YES ALL THE TREE ACTIVITIES TEST
Assistant: After “Refine prototype,” can the process return specifically to “Test safety”?
User: YES
Assistant: After “Refine prototype,” can the process also return to “Test market potential”?
User: YES
Assistant: After “Refine prototype,” can the process also return to “Test functionality”?
User: YES
Final SBMN Model
Activities
1. Identify idea for new product or improvement
2. Conduct initial research
3. Conduct feasibility studies
4. Draft design concepts
5. Select promising design
6. Build prototype
7. Test safety
8. Test market potential
9. Test functionality
10. Collect feedback from testing phase
11. Refine prototype
12. Approve prototype for further development
13. Discard prototype
SBMN Relations
Conduct initial research DEP Identify idea for new product or improvement
Draft design concepts DEP Conduct initial research
Draft design concepts DEP Conduct feasibility studies
Select promising design DEP Draft design concepts
Build prototype DEP Select promising design
Test safety DEP Build prototype
Test market potential DEP Build prototype
Test functionality DEP Build prototype
Collect feedback from testing phase DEP Test safety
Collect feedback from testing phase DEP Test market potential
Collect feedback from testing phase DEP Test functionality
Refine prototype REQ Collect feedback from testing phase
Approve prototype for further development REQ Collect feedback from testing phase
Discard prototype REQ Collect feedback from testing phase
Approve prototype for further development XOR Discard prototype
JMP Relations
Refine prototype JMP Test safety
Refine prototype JMP Test market potential
Refine prototype JMP Test functionality
This SBMN model is consistent and has at least one valid BPMN realization.
