SBMN Interview Report - Ticket Booking and Travel Management
Questions and Answers Captured
1. Q: Language?
A: English
2. Q: Process name?
A: Ticket Booking and Travel Management
3. Q: Domain?
A: Transportation/Travel
4. Q: Activities?
A: Customer searches for ticket; Select route; Select date and time; Provide personal information; Provide payment details; Generate ticket; Send ticket via email; Send ticket via SMS; Update seat inventory; Send reminder; Send instructions; Customer completes journey; Post-travel feedback or services
5. Q: Can Select route occur without Customer searches for ticket?
A: No
6. Q: Order between Customer searches for ticket and Select route?
A: Search before Select route
7. Q: Can Select date and time occur without Select route?
A: No
8. Q: Order between Select route and Select date and time?
A: Either order
9. Q: Can Provide personal information occur without Select date and time?
A: No
10. Q: Order between Select date and time and Provide personal information?
A: Date/time before personal information
11. Q: Can Provide payment details occur without Provide personal information?
A: Yes
12. Q: Order between Provide payment details and Provide personal information?
A: Any order
13. Q: Can Generate ticket occur without Provide payment details?
A: No
14. Q: Order between Provide payment details and Generate ticket?
A: Payment before Generate ticket
15. Q: Can Send ticket via email occur without Generate ticket?
A: No
16. Q: Can Generate ticket occur without Send ticket via email?
A: Yes
17. Q: Can Send ticket via SMS occur without Generate ticket?
A: No
18. Q: Can Generate ticket occur without Send ticket via SMS?
A: Yes
19. Q: Can Update seat inventory occur without Generate ticket?
A: No
20. Q: Can Generate ticket occur without Update seat inventory?
A: No
21. Q: Can Send reminder occur without Generate ticket?
A: No
22. Q: Can Generate ticket occur without Send reminder?
A: Yes
23. Q: Can Send instructions occur without Generate ticket?
A: No
24. Q: Can Generate ticket occur without Send instructions?
A: Yes
25. Q: Can Customer completes journey occur without Generate ticket?
A: No
26. Q: Can Generate ticket occur without Customer completes journey?
A: No
27. Q: Mandatory before journey?
A: Update seat inventory and exactly one delivery channel; reminder/instructions optional
28. Q: Can Post-travel feedback occur without journey?
A: No
29. Q: Order between journey and post-travel feedback?
A: Journey before feedback
30. Q: Can journey occur without post-travel feedback?
A: Yes
31. Q: Can email and SMS occur together?
A: No
32. Q: Can reminder and instructions occur together?
A: Yes
33. Q: Can Send instructions occur without Send reminder?
A: Yes
34. Q: Can Send reminder occur without Send instructions?
A: Yes
35. Q: Does journey require update seat inventory?
A: Yes
36. Q: Does journey require one delivery channel?
A: Yes
37. Q: Must reminder occur before journey?
A: Yes
38. Q: Can journey occur without reminder?
A: Yes
39. Q: Must instructions occur before journey?
A: Yes
40. Q: Can journey occur without instructions?
A: Yes
41. Q: Self-loop on reminder?
A: Yes
42. Q: Self-loop on instructions?
A: Yes
43. Q: Any other JMP relations?
A: No
Final SBMN Model

Process name: Ticket Booking and Travel Management

Activities:
- Customer searches for ticket
- Select route
- Select date and time
- Provide personal information
- Provide payment details
- Generate ticket
- Send ticket via email
- Send ticket via SMS
- Update seat inventory
- Send reminder
- Send instructions
- Customer completes journey
- Post-travel feedback or services

Relations:
Select route DEP Customer searches for ticket
Provide personal information DEP Select route
Provide personal information DEP Select date and time
Generate ticket DEP Provide personal information
Generate ticket DEP Provide payment details
Generate ticket DEP Select route
Generate ticket DEP Select date and time
Send ticket via email REQ Generate ticket
Send ticket via SMS REQ Generate ticket
Update seat inventory DEP Generate ticket
Send ticket via email XOR Send ticket via SMS
Send reminder REQ Generate ticket
Send instructions REQ Generate ticket
Customer completes journey DEP Generate ticket
Customer completes journey DEP Update seat inventory
Customer completes journey REQ Send reminder
Customer completes journey REQ Send instructions
Post-travel feedback or services REQ Customer completes journey

JMP:
Send reminder JMP Send reminder
Send instructions JMP Send instructions

