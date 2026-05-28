Incident Resolution Management - Complete Interview Transcript
1. Q: Language
   A: ENGLISH
2. Q: Process name
   A: Incident Resolution Management
3. Q: Domain
   A: IT Service Management
4. Q: Activities
   A: Report incident; Log report into tracking system; Assign report to appropriate team; Gather necessary information; Identify cause of incident; Propose corrective actions; Implement fix; Conduct training; Change policy; Conduct follow-up; Close incident report; Notify all stakeholders
5. Q: When Log report into tracking system occurs, must Report incident occur BEFORE, AFTER, or ANY ORDER?
   A: BEFORE
6. Q: Are there valid executions where Report incident occurs but Log report into tracking system does not occur?
   A: NO
7. Q: When Assign report to appropriate team occurs, must Log report into tracking system occur BEFORE, AFTER, or ANY ORDER?
   A: BEFORE
8. Q: Are there valid executions where Log report into tracking system occurs but Assign report to appropriate team does not occur?
   A: NO
9. Q: When Gather necessary information occurs, must Assign report to appropriate team occur BEFORE, AFTER, or ANY ORDER?
   A: BEFORE
10. Q: Are there valid executions where Assign report to appropriate team occurs but Gather necessary information does not occur?
   A: NO
11. Q: When Identify cause of incident occurs, must Gather necessary information occur BEFORE, AFTER, or ANY ORDER?
   A: IN ANY ORDER
12. Q: Does either structurally enable/constrain the other?
   A: Neither structurally enables or constrains the other
13. Q: Every execution containing one also contains the other?
   A: YES
14. Q: When Propose corrective actions occurs, must Identify cause of incident occur BEFORE, AFTER, or ANY ORDER?
   A: BEFORE
15. Q: Are there valid executions where Identify cause of incident occurs but Propose corrective actions does not occur?
   A: NO
16. Q: When Implement fix occurs, must Propose corrective actions occur BEFORE, AFTER, or ANY ORDER?
   A: BEFORE
17. Q: Are there valid executions where Propose corrective actions occurs but Implement fix does not occur?
   A: YES
18. Q: Can Conduct training occur without Implement fix?
   A: YES
19. Q: Can Conduct training and Implement fix occur together?
   A: NO
20. Q: Can Implement fix occur without Conduct training?
   A: YES
21. Q: When Change policy occurs, must Propose corrective actions occur BEFORE, AFTER, or ANY ORDER?
   A: BEFORE
22. Q: Are there valid executions where Propose corrective actions occurs but Change policy does not occur?
   A: YES
23. Q: Can Conduct follow-up occur without both Implement fix and Change policy?
   A: YES
24. Q: Can Conduct follow-up occur together with Implement fix?
   A: YES
25. Q: Can Conduct follow-up occur together with Change policy?
   A: YES
26. Q: When Close incident report occurs, must Conduct follow-up occur BEFORE, AFTER, or ANY ORDER?
   A: BEFORE
27. Q: Are there valid executions where Conduct follow-up occurs but Close incident report does not occur?
   A: NO
28. Q: When Notify all stakeholders occurs, must Close incident report occur BEFORE, AFTER, or ANY ORDER?
   A: BEFORE
29. Q: Are there valid executions where Close incident report occurs but Notify all stakeholders does not occur?
   A: NO
30. Q: Must Conduct follow-up be completed before Notify all stakeholders?
   A: YES
31. Q: Can Implement fix and Change policy occur together?
   A: NO
32. Q: Before Conduct follow-up, must Propose corrective actions already have been completed?
   A: YES
33. Q: Are there valid executions where Propose corrective actions occurs but Conduct follow-up does not occur?
   A: NO
34. Q: After Notify all stakeholders, can process return/skip to earlier activity?
   A: NO
35. Q: After Conduct follow-up, can process return/skip to earlier activity?
   A: NO
36. Q: After Implement fix, can process return/skip to earlier activity?
   A: NO
37. Q: After Change policy, can process return/skip to earlier activity?
   A: NO
38. Q: After Identify cause of incident, can process return/skip to earlier activity?
   A: NO
39. Q: Can Conduct training and Change policy occur together?
   A: NO
40. Q: Are Conduct training and Change policy optional alternatives?
   A: YES
41. Q: If Conduct training occurs, must it be completed before Conduct follow-up?
   A: YES
42. Q: If Implement fix occurs, must it be completed before Conduct follow-up?
   A: YES
43. Q: If Change policy occurs, must it be completed before Conduct follow-up?
   A: YES
44. Q: Are there valid executions where Conduct follow-up occurs but Close incident report does not occur?
   A: NO
45. Q: Are there valid executions where Conduct follow-up occurs but Notify all stakeholders does not occur?
   A: NO
46. Q: Before Conduct training, must Propose corrective actions be completed?
   A: YES
47. Q: Before Change policy, must Propose corrective actions be completed?
   A: YES
48. Q: Are there valid executions where Propose corrective actions occurs but Conduct training does not occur?
   A: YES
49. Q: Can process go directly from Propose corrective actions to Conduct follow-up without any corrective measure?
   A: NO
50. Q: Must at least one of Conduct training, Implement fix, Change policy occur before Conduct follow-up?
   A: YES
51. Q: Are these the only alternatives?
   A: YES
52. Q: Must they occur BEFORE Conduct follow-up?
   A: BEFORE
53. Q: After Conduct training, can process return/skip to earlier activity?
   A: NO
54. Q: Can Implement fix and Conduct training occur together?
   A: NO
55. Q: Can Change policy and Conduct training occur together?
   A: NO
56. Q: Can Implement fix and Change policy occur together?
   A: NO
57. Q: After Propose corrective actions, must exactly one of the three alternatives occur?
   A: YES
58. Q: Does Conduct follow-up require only the selected alternative?
   A: YES
59. Q: Are there valid executions where Conduct training occurs and Conduct follow-up does not occur?
   A: NO
60. Q: Are there valid executions where Implement fix occurs and Conduct follow-up does not occur?
   A: NO
61. Q: Are there valid executions where Change policy occurs and Conduct follow-up does not occur?
   A: NO
62. Q: After Notify all stakeholders occurs, can any activity still occur afterward?
   A: NO
63. Q: After Close incident report, can process return/skip to earlier activity?
   A: NO
 
Generated SBMN Model

Process name: Incident Resolution Management

Activities:
Report incident
Log report into tracking system
Assign report to appropriate team
Gather necessary information
Identify cause of incident
Propose corrective actions
Implement fix
Conduct training
Change policy
Conduct follow-up
Close incident report
Notify all stakeholders

Relations:
Log report into tracking system DEP Report incident
Assign report to appropriate team DEP Log report into tracking system
Propose corrective actions DEP Identify cause of incident
Implement fix REQ Propose corrective actions
Conduct training REQ Propose corrective actions
Change policy REQ Propose corrective actions
Implement fix XOR Conduct training
Implement fix XOR Change policy
Conduct training XOR Change policy
Conduct follow-up DEP Propose corrective actions
Conduct follow-up REQ Implement fix
Conduct follow-up REQ Conduct training
Conduct follow-up REQ Change policy
Close incident report DEP Conduct follow-up
Notify all stakeholders DEP Close incident report

JMP: None

