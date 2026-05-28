SBMN Interview - Inventory Replenishment Management
Foram feitas 68 perguntas ao longo de toda a entrevista.
Contagem:
•	Coleta inicial: 
o	Nome do processo: 1 
o	Domínio: 1 
o	Lista de atividades: 1 
o	Subtotal: 3 
•	Perguntas de elicitação estrutural (dependências, XOR, validações, etc.): 
o	65 perguntas 
Total geral = 3 + 65 = 68 perguntas.

1. Q: What is the name of the process you want to model?
   A: Inventory Replenishment Management
2. Q: What is the domain or business area of this process?
   A: Supply Chain/Inventory
3. Q: Please provide the complete list of activities in this process.
   A: Check current inventory level; Send an automated alert; Send a manual alert; Place order with suppliers; Update inventory system with expected delivery dates; Receive stock; Inspect stock for quality; Record stock in system; Place stock on shelves; Place stock in storage; Update inventory levels
4. Q: After Check current inventory level, can Send an automated alert occur only if Check current inventory level has occurred before it?
   A: YES
5. Q: When Send an automated alert occurs, must Check current inventory level occur before it, after it, or can both occur in any order depending on the execution?
   A: BEFORE
6. Q: Are there valid executions where Check current inventory level occurs but Send an automated alert does not occur?
   A: YES
7. Q: Can Send a manual alert occur only if Check current inventory level has occurred before it?
   A: YES
8. Q: When Send a manual alert occurs, must Check current inventory level occur before it, after it, or can both occur in any order?
   A: BEFORE
9. Q: Are there valid executions where Check current inventory level occurs but Send a manual alert does not occur?
   A: YES
10. Q: Can Send an automated alert and Send a manual alert occur together in the same process execution?
   A: NO
11. Q: Can Place order with suppliers occur only if Send an automated alert has occurred before it?
   A: NO
12. Q: Can Place order with suppliers occur only if Send a manual alert has occurred before it?
   A: NO
13. Q: Can Place order with suppliers occur only if Check current inventory level has occurred before it?
   A: YES
14. Q: When Place order with suppliers occurs, must Check current inventory level occur before it, after it, or can both occur in any order?
   A: BEFORE
15. Q: Are there valid executions where Check current inventory level occurs but Place order with suppliers does not occur?
   A: NO
16. Q: Can Update inventory system with expected delivery dates occur only if Place order with suppliers has occurred before it?
   A: YES
17. Q: When Update inventory system with expected delivery dates occurs, must Place order with suppliers occur before it, after it, or can both occur in any order?
   A: BEFORE
18. Q: Are there valid executions where Place order with suppliers occurs but Update inventory system with expected delivery dates does not occur?
   A: NO
19. Q: Can Receive stock occur only if Update inventory system with expected delivery dates has occurred before it?
   A: YES
20. Q: When Receive stock occurs, must Update inventory system with expected delivery dates occur before it, after it, or can both occur in any order?
   A: BEFORE
21. Q: Are there valid executions where Update inventory system with expected delivery dates occurs but Receive stock does not occur?
   A: NO
22. Q: Can Inspect stock for quality occur only if Receive stock has occurred before it?
   A: YES
23. Q: When Inspect stock for quality occurs, must Receive stock occur before it, after it, or can both occur in any order?
   A: BEFORE
24. Q: Are there valid executions where Receive stock occurs but Inspect stock for quality does not occur?
   A: NO
25. Q: Can Record stock in system occur only if Inspect stock for quality has occurred before it?
   A: NO
26. Q: Can Inspect stock for quality occur only if Record stock in system has occurred before it?
   A: NO
27. Q: Can Place stock on shelves occur only if Record stock in system has occurred before it?
   A: NO
28. Q: Can Record stock in system occur only if Place stock on shelves has occurred before it?
   A: NO
29. Q: Can Place stock in storage occur only if Record stock in system has occurred before it?
   A: NO
30. Q: Can Update inventory levels occur only if Record stock in system has occurred before it?
   A: YES
31. Q: When Update inventory levels occurs, must Record stock in system occur before it, after it, or can both occur in any order?
   A: BEFORE
32. Q: Are there valid executions where Record stock in system occurs but Update inventory levels does not occur?
   A: NO
33. Q: Can Inspect stock for quality and Record stock in system occur together in the same process execution?
   A: YES
34. Q: Before Record stock in system can happen, must Inspect stock for quality already be completed?
   A: NO
35. Q: Can Place stock on shelves occur only if Inspect stock for quality has occurred before it?
   A: YES
36. Q: When Place stock on shelves occurs, must Inspect stock for quality occur before it, after it, or can both occur in any order?
   A: BEFORE
37. Q: Are there valid executions where Inspect stock for quality occurs but Place stock on shelves does not occur?
   A: YES
38. Q: Can Place stock in storage occur only if Inspect stock for quality has occurred before it?
   A: YES
39. Q: When Place stock in storage occurs, must Inspect stock for quality occur before it, after it, or can both occur in any order?
   A: BEFORE
40. Q: Are there valid executions where Inspect stock for quality occurs but Place stock in storage does not occur?
   A: YES
41. Q: Can Place stock on shelves and Place stock in storage occur together in the same process execution?
   A: NO
42. Q: Before Update inventory levels can happen, must Place stock on shelves already be completed?
   A: NO
43. Q: Before Update inventory levels can happen, must Place stock in storage already be completed?
   A: NO
44. Q: Before Update inventory levels can happen, must Inspect stock for quality already be completed?
   A: YES
45. Q: When Update inventory levels occurs, must Inspect stock for quality occur before it, after it, or can both occur in any order?
   A: BEFORE
46. Q: Are there valid executions where Inspect stock for quality occurs but Update inventory levels does not occur?
   A: NO
47. Q: Can Record stock in system occur only if Receive stock has occurred before it?
   A: YES
48. Q: When Record stock in system occurs, must Receive stock occur before it, after it, or can both occur in any order?
   A: BEFORE
49. Q: Are there valid executions where Receive stock occurs but Record stock in system does not occur?
   A: NO
50. Q: Can Place stock on shelves occur only if Receive stock has occurred before it?
   A: YES
51. Q: When Place stock on shelves occurs, must Receive stock occur before it, after it, or can both occur in any order?
   A: BEFORE
52. Q: Are there valid executions where Receive stock occurs but Place stock on shelves does not occur?
   A: YES
53. Q: Can Place stock in storage occur only if Receive stock has occurred before it?
   A: YES
54. Q: When Place stock in storage occurs, must Receive stock occur before it, after it, or can both occur in any order?
   A: BEFORE
55. Q: Are there valid executions where Receive stock occurs but Place stock in storage does not occur?
   A: YES
56. Q: Can Place stock on shelves occur only if Record stock in system has occurred before it?
   A: NO
57. Q: Can Place stock on shelves occur only if Inspect stock for quality has occurred before it?
   A: YES
58. Q: Are there valid executions where Inspect stock for quality occurs but Place stock on shelves does not occur?
   A: YES
59. Q: Can Place stock in storage occur only if Record stock in system has occurred before it?
   A: NO
60. Q: Can Record stock in system occur only if Place stock in storage has occurred before it?
   A: NO
61. Q: Can Place stock in storage and Record stock in system occur together in the same process execution?
   A: YES
62. Q: Can Record stock in system and Place stock on shelves occur together in the same process execution?
   A: YES
63. Q: Before Update inventory levels can happen, must Receive stock already be completed?
   A: YES
64. Q: Are there valid executions where Receive stock occurs but Update inventory levels does not occur?
   A: NO
65. Q: Can Update inventory levels occur only if Place stock on shelves has occurred before it?
   A: NO
66. Q: Can Update inventory levels occur only if Place stock in storage has occurred before it?
   A: NO
67. Q: If Inspect stock for quality identifies a problem or fails, can the process return to an earlier activity?
   A: NO
68. Q: After Update inventory levels is completed, can the process return to or skip directly to any earlier non-adjacent activity?
   A: NO
 
Process name: Inventory Replenishment Management

Activity list:

* Check current inventory level
* Send an automated alert
* Send a manual alert
* Place order with suppliers
* Update inventory system with expected delivery dates
* Receive stock
* Inspect stock for quality
* Record stock in system
* Place stock on shelves
* Place stock in storage
* Update inventory levels

SBMN relations:

Send an automated alert REQ Check current inventory level

Send a manual alert REQ Check current inventory level

Send an automated alert XOR Send a manual alert

Place order with suppliers DEP Check current inventory level

Update inventory system with expected delivery dates DEP Place order with suppliers

Receive stock DEP Update inventory system with expected delivery dates

Inspect stock for quality DEP Receive stock

Record stock in system DEP Receive stock

Update inventory levels DEP Record stock in system

Update inventory levels DEP Inspect stock for quality

Place stock on shelves REQ Inspect stock for quality

Place stock in storage REQ Inspect stock for quality

Place stock on shelves XOR Place stock in storage

This SBMN model is consistent and has at least one valid BPMN realization.
