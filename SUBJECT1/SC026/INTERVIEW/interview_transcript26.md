Supplier Selection and Onboarding - SBMN Interview Transcript

Se contarmos apenas as perguntas de elicitação estrutural (excluindo as 3 perguntas iniciais de contexto: nome, domínio e atividades), foram 47 perguntas de modelagem.
Portanto:
•	50 perguntas no total 
•	47 perguntas de elicitação SBMN propriamente dita.

1. Q: What is the name of the process you would like to model?
   A: Supplier Selection and Onboarding
2. Q: What is the business domain of this process?
   A: Procurement/Supply Chain
3. Q: Please provide the complete list of activities in the process.
   A: Identify need for new supplier or vendor; Issue request for proposals (RFP); Receive supplier proposals; Evaluate proposal; Conduct site visit; Conduct interview; Select supplier; Begin contract negotiations; Sign contract; Onboard supplier; Execute contract
4. Q: Need identified -> RFP always follows and RFP cannot occur first?
   A: Yes
5. Q: RFP -> Receive proposals always?
   A: Yes
6. Q: Receive proposals -> Evaluate proposal always?
   A: Yes
7. Q: Evaluate proposal vs Conduct site visit?
   A: A site visit occurs only for some evaluated proposals.
8. Q: When site visit occurs, must Evaluate proposal have occurred before?
   A: Yes
9. Q: Evaluate proposal vs Conduct interview?
   A: An interview occurs only for some evaluated proposals.
10. Q: When interview occurs, must Evaluate proposal have occurred before?
   A: Yes
11. Q: Can site visit and interview occur together?
   A: No
12. Q: If site visit occurs, must Select supplier occur after it?
   A: Yes
13. Q: Can Select supplier occur without site visit?
   A: No
14. Q: Can site visit occur without Select supplier?
   A: No
15. Q: If interview occurs, must Select supplier occur after it?
   A: Yes
16. Q: Can Select supplier occur after interview even when no site visit occurred?
   A: Yes
17. Q: Can Select supplier occur after site visit even when no interview occurred?
   A: Yes
18. Q: Select supplier -> Begin contract negotiations always?
   A: Yes
19. Q: Begin contract negotiations -> Sign contract always?
   A: Yes
20. Q: Sign contract -> Onboard supplier always?
   A: Yes
21. Q: Onboard supplier -> Execute contract always?
   A: Yes
22. Q: Can interview occur without Select supplier?
   A: No
23. Q: Can supplier be selected directly after evaluation without site visit/interview?
   A: Yes
24. Q: When Select supplier occurs, must Evaluate proposal occur before?
   A: Before/Yes
25. Q: Can Evaluate proposal occur without Select supplier?
   A: No
26. Q: Can Evaluate proposal occur without site visit?
   A: Yes
27. Q: Can Evaluate proposal occur without interview?
   A: Yes
28. Q: Do Select supplier and Begin contract negotiations always occur together?
   A: Yes
29. Q: Must Select supplier occur before Begin contract negotiations?
   A: Yes
30. Q: Can Begin contract negotiations occur without Select supplier?
   A: No
31. Q: Can Begin contract negotiations occur without Sign contract?
   A: No
32. Q: Can Sign contract occur without Onboard supplier?
   A: No
33. Q: Can Onboard supplier occur without Execute contract?
   A: No
34. Q: Must Onboard supplier occur before Execute contract?
   A: Yes
35. Q: Must Sign contract occur before Onboard supplier?
   A: Yes
36. Q: Can site visit occur without Select supplier eventually occurring?
   A: No
37. Q: After Execute contract, can process return to an earlier activity?
   A: No
38. Q: If evaluation is unsatisfactory, can process return to earlier activity?
   A: Yes
39. Q: Can process return to Evaluate proposal?
   A: Yes
40. Q: Can Evaluate proposal be repeated?
   A: Yes
41. Q: Can Evaluate proposal loop directly to itself?
   A: Yes
42. Q: Can site visit issues return to Evaluate proposal?
   A: Yes
43. Q: Can interview issues return to Evaluate proposal?
   A: Yes
44. Q: Can failed negotiations return to Select supplier?
   A: No
45. Q: Can failed contract signing return to negotiations?
   A: No
46. Q: Can onboarding problems return to Sign contract?
   A: No
47. Q: Can execution problems return to Evaluate proposal?
   A: No
48. Q: Does site visit return directly to Evaluate proposal?
   A: Yes
49. Q: Does interview return directly to Evaluate proposal?
   A: Yes
50. Q: Does unsatisfactory evaluation return directly to Evaluate proposal?
   A: Yes
Process name
Supplier Selection and Onboarding
Activity list
•	Identify need for new supplier or vendor
•	Issue request for proposals (RFP)
•	Receive supplier proposals
•	Evaluate proposal
•	Conduct site visit
•	Conduct interview
•	Select supplier
•	Begin contract negotiations
•	Sign contract
•	Onboard supplier
•	Execute contract
SBMN relations
Issue request for proposals (RFP) DEP Identify need for new supplier or vendor
Receive supplier proposals DEP Issue request for proposals (RFP)
Evaluate proposal DEP Receive supplier proposals
Conduct site visit REQ Evaluate proposal
Conduct interview REQ Evaluate proposal
Conduct site visit XOR Conduct interview
Select supplier DEP Evaluate proposal
Select supplier DEPC Conduct site visit
Select supplier DEPC Conduct interview
Begin contract negotiations DEP Select supplier
Sign contract DEP Begin contract negotiations
Onboard supplier DEP Sign contract
Execute contract DEP Onboard supplier
JMP relations
Evaluate proposal JMP Evaluate proposal
Conduct site visit JMP Evaluate proposal
Conduct interview JMP Evaluate proposal
This SBMN model is consistent and has at least one valid BPMN realization.
 
Final SBMN Model
Process name: Supplier Selection and Onboarding
Activities:
- Identify need for new supplier or vendor
- Issue request for proposals (RFP)
- Receive supplier proposals
- Evaluate proposal
- Conduct site visit
- Conduct interview
- Select supplier
- Begin contract negotiations
- Sign contract
- Onboard supplier
- Execute contract

SBMN Relations:
Issue request for proposals (RFP) DEP Identify need for new supplier or vendor
Receive supplier proposals DEP Issue request for proposals (RFP)
Evaluate proposal DEP Receive supplier proposals
Conduct site visit REQ Evaluate proposal
Conduct interview REQ Evaluate proposal
Conduct site visit XOR Conduct interview
Select supplier DEP Evaluate proposal
Select supplier DEPC Conduct site visit
Select supplier DEPC Conduct interview
Begin contract negotiations DEP Select supplier
Sign contract DEP Begin contract negotiations
Onboard supplier DEP Sign contract
Execute contract DEP Onboard supplier

JMP Relations:
Evaluate proposal JMP Evaluate proposal
Conduct site visit JMP Evaluate proposal
Conduct interview JMP Evaluate proposal

This SBMN model is consistent and has at least one valid BPMN realization.

