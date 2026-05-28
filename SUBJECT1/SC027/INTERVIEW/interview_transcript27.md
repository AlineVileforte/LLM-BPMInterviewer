SBMN Interview Transcript - Order Fulfillment and Delivery
Total real: 52 perguntas.
Se você considerar apenas as perguntas de descoberta estrutural (excluindo as perguntas de JMP/loop dos itens 41–52), então foram 40 perguntas. 

1. Q: What is the name of the process?
   A: Order Fulfillment and Delivery
2. Q: What is the domain of this process?
   A: Logistics/E-Commerce
3. Q: Please provide the complete list of activities in this process.
   A: Provided activity list
4. Q: Can Customer places order online and Customer places order over the phone occur together in the same process execution?
   A: NO
5. Q: Does Generate and send order confirmation always require one of the order placement activities to have occurred before it?
   A: YES
6. Q: When Generate and send order confirmation occurs, must the order placement activity occur before it, after it, or can both occur in any order?
   A: BEFORE
7. Q: Are there valid executions where the order placement activity occurs but Generate and send order confirmation does not occur?
   A: NO
8. Q: For both order placement alternatives, does Generate and send order confirmation always occur afterward?
   A: YES
9. Q: Does Pick and pack items always require Generate and send order confirmation to have occurred before it?
   A: YES
10. Q: When Pick and pack items occurs, must Generate and send order confirmation occur before it, after it, or in any order?
   A: BEFORE
11. Q: Are there valid executions where Generate and send order confirmation occurs but Pick and pack items does not occur?
   A: NO
12. Q: For both order placement alternatives, does Pick and pack items always occur afterward?
   A: YES
13. Q: Does Generate shipping label always require Pick and pack items to have occurred before it?
   A: NO
14. Q: Does Pick and pack items always require Generate shipping label to have occurred before it?
   A: NO
15. Q: Can Pick and pack items and Generate shipping label occur together in the same process execution?
   A: YES
16. Q: Are valid executions possible with only one of them or both?
   A: ONLY BOTH
17. Q: Before Hand over order to logistics provider can occur, must Pick and pack items already be completed?
   A: YES
18. Q: When Hand over order to logistics provider occurs, must Pick and pack items occur before it, after it, or in any order?
   A: BEFORE
19. Q: Are there valid executions where Pick and pack items occurs but Hand over order to logistics provider does not occur?
   A: NO
20. Q: Are there valid executions where Hand over order to logistics provider occurs but Pick and pack items does not occur?
   A: NO
21. Q: Before Hand over order to logistics provider can occur, must Generate shipping label already be completed?
   A: YES
22. Q: When Hand over order to logistics provider occurs, must Generate shipping label occur before it, after it, or in any order?
   A: BEFORE
23. Q: Are there valid executions where Generate shipping label occurs but Hand over order to logistics provider does not occur?
   A: NO
24. Q: Are there valid executions where Hand over order to logistics provider occurs but Generate shipping label does not occur?
   A: NO
25. Q: Does Send tracking information to customer always require Hand over order to logistics provider to have occurred before it?
   A: YES
26. Q: When Send tracking information to customer occurs, must Hand over order to logistics provider occur before it, after it, or in any order?
   A: BEFORE
27. Q: Are there valid executions where Hand over order to logistics provider occurs but Send tracking information to customer does not occur?
   A: NO
28. Q: Are there valid executions where Send tracking information to customer occurs but Hand over order to logistics provider does not occur?
   A: NO
29. Q: Before Monitor shipment can occur, must Send tracking information to customer already be completed?
   A: YES
30. Q: When Monitor shipment occurs, must Send tracking information to customer occur before it, after it, or in any order?
   A: BEFORE
31. Q: Are there valid executions where Send tracking information to customer occurs but Monitor shipment does not occur?
   A: NO
32. Q: Are there valid executions where Monitor shipment occurs but Send tracking information to customer does not occur?
   A: NO
33. Q: Before Successful delivery can occur, must Monitor shipment already be completed?
   A: YES
34. Q: When Successful delivery occurs, must Monitor shipment occur before it, after it, or in any order?
   A: BEFORE
35. Q: Are there valid executions where Monitor shipment occurs but Successful delivery does not occur?
   A: NO
36. Q: Are there valid executions where Successful delivery occurs but Monitor shipment does not occur?
   A: NO
37. Q: Before Process customer feedback or returns can occur, must Successful delivery already be completed?
   A: YES
38. Q: When Process customer feedback or returns occurs, must Successful delivery occur before it, after it, or in any order?
   A: BEFORE
39. Q: Are there valid executions where Successful delivery occurs but Process customer feedback or returns does not occur?
   A: YES
40. Q: Are there valid executions where Process customer feedback or returns occurs but Successful delivery does not occur?
   A: NO
41. Q: If Process customer feedback or returns identifies a return or problem, can the process return to any earlier activity?
   A: NO
42. Q: After Monitor shipment, if a shipment problem is detected, can the process return to any earlier activity or skip directly to another non-adjacent activity?
   A: YES, ITSELF
43. Q: After Monitor shipment completes, can Monitor shipment be executed again within the same process execution?
   A: YES
44. Q: After Successful delivery, can the process return to or skip directly to any earlier non-adjacent activity?
   A: NO
45. Q: After Hand over order to logistics provider, can the process return to or skip directly to any earlier non-adjacent activity?
   A: NO
46. Q: After Send tracking information to customer, can the process return to or skip directly to any earlier non-adjacent activity?
   A: NO
47. Q: After Generate and send order confirmation, can the process return to or skip directly to any earlier non-adjacent activity?
   A: NO
48. Q: After Pick and pack items, can the process return to or skip directly to any earlier non-adjacent activity?
   A: NO
49. Q: After Generate shipping label, can the process return to or skip directly to any earlier non-adjacent activity?
   A: NO
50. Q: After Customer places order online, can the process return to or skip directly to any earlier or non-adjacent activity?
   A: NO
51. Q: After Customer places order over the phone, can the process return to or skip directly to any earlier or non-adjacent activity?
   A: NO
52. Q: After Process customer feedback or returns, can the process return to or skip directly to any earlier non-adjacent activity?
   A: NO
 
Final SBMN Model
Process name: Order Fulfillment and Delivery
Activities:
Customer places order online
Customer places order over the phone
Generate and send order confirmation
Pick and pack items
Generate shipping label
Hand over order to logistics provider
Send tracking information to customer
Monitor shipment
Successful delivery
Process customer feedback or returns
SBMN Relations:
Customer places order online XOR Customer places order over the phone
Generate and send order confirmation DEP Customer places order online
Generate and send order confirmation DEP Customer places order over the phone
Pick and pack items DEP Generate and send order confirmation
Hand over order to logistics provider DEP Pick and pack items
Hand over order to logistics provider DEP Generate shipping label
Send tracking information to customer DEP Hand over order to logistics provider
Monitor shipment DEP Send tracking information to customer
Successful delivery DEP Monitor shipment
Process customer feedback or returns REQ Successful delivery
Monitor shipment JMP Monitor shipment
This SBMN model is consistent and has at least one valid BPMN realization.
