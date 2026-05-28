SBMN Interview Transcript

ASSISTANT: Welcome to the SBMN interview process.

ASSISTANT: Which language would you like to use for the interview?

USER: ENGLISH

ASSISTANT: Great.
What is the name of the process you want to model?

USER: Reservation Management Process

ASSISTANT: What is the business domain of the “Reservation Management Process”?
(Example: hotel, airline, restaurant, healthcare, vehicle rental, etc.)

USER: Reservation System

ASSISTANT: Please provide the full list of activities involved in the Reservation Management Process.
List only the activities, one per line or separated by commas.

USER:
• Kontrola přihlášení
• Zadani rezervace
• Kontrola dostupnosti
• Dotaz na upravu pozadavku
• Potrvzeni o prijeti objednavky
• Odeslani emailu o 1...
• Uprava pozadavku
• Ulozeni do DB
• Odeslani emailu o 2...
• Odeslani potvrzovaciho emailu

ASSISTANT: After Kontrola přihlášení, can Zadani rezervace occur only after the login check is completed?

USER: YES

ASSISTANT: When Zadani rezervace occurs, must Kontrola přihlášení always have occurred before it in every valid execution?

USER: YES

ASSISTANT: Can Kontrola dostupnosti occur only after Zadani rezervace is completed?

USER: YES

ASSISTANT: When Kontrola dostupnosti occurs, must Zadani rezervace always have occurred before it in every valid execution?

USER: YES

ASSISTANT: Can Dotaz na upravu pozadavku occur only after Kontrola dostupnosti is completed?

USER: YES

ASSISTANT: When Dotaz na upravu pozadavku occurs, must Kontrola dostupnosti always have occurred before it in every valid execution?

USER: YES

ASSISTANT: Can Uprava pozadavku occur only after Dotaz na upravu pozadavku is completed?

USER: YES

ASSISTANT: When Uprava pozadavku occurs, must Dotaz na upravu pozadavku always have occurred before it in every valid execution?

USER: YES

ASSISTANT: Can Ulozeni do DB occur only after Uprava pozadavku is completed?

USER: NO

ASSISTANT: Can Ulozeni do DB occur before Uprava pozadavku, or can both occur independently depending on the execution?

USER: NO

ASSISTANT: Can Ulozeni do DB happen without Uprava pozadavku ever occurring?

USER: YES

ASSISTANT: When Ulozeni do DB occurs, must Kontrola dostupnosti have occurred before it?

USER: YES

ASSISTANT: Are there valid executions where Kontrola dostupnosti occurs but Ulozeni do DB does not occur?

USER: YES

ASSISTANT: Can Potrvzeni o prijeti objednavky occur only after Kontrola dostupnosti is completed?

USER: YES

ASSISTANT: When Potrvzeni o prijeti objednavky occurs, must Kontrola dostupnosti always have occurred before it in every valid execution?

USER: YES

ASSISTANT: Can Potrvzeni o prijeti objednavky and Dotaz na upravu pozadavku occur together in the same process execution?

USER: NO

ASSISTANT: Can Odeslani emailu o 1... occur only after Potrvzeni o prijeti objednavky is completed?

USER: YES

ASSISTANT: When Odeslani emailu o 1... occurs, must Potrvzeni o prijeti objednavky always have occurred before it in every valid execution?

USER: YES

ASSISTANT: Can Odeslani emailu o 2... occur only after Ulozeni do DB is completed?

USER: NO

ASSISTANT: Can Odeslani emailu o 2... occur before Ulozeni do DB, or can both occur independently depending on the execution?

USER: occur independently

ASSISTANT: When Odeslani emailu o 2... occurs, must Ulozeni do DB have occurred before it?

USER: NO

ASSISTANT: When Odeslani emailu o 2... occurs, must Uprava pozadavku have occurred before it?

USER: WHE OCCURRED, YES

ASSISTANT: Are there valid executions where Uprava pozadavku occurs but Odeslani emailu o 2... does not occur?

USER: YES

ASSISTANT: Can Odeslani potvrzovaciho emailu occur only after Ulozeni do DB is completed?

USER: YES

ASSISTANT: Are there valid executions where Ulozeni do DB occurs but Odeslani potvrzovaciho emailu does not occur?

USER: NO

ASSISTANT: When Odeslani potvrzovaciho emailu occurs, must Ulozeni do DB always have occurred before it in every valid execution?

USER: YES

ASSISTANT: Before Odeslani potvrzovaciho emailu can happen, must Odeslani emailu o 1... already be completed when that branch is executed?

USER: YES

ASSISTANT: Are there valid executions where Odeslani emailu o 1... occurs but Odeslani potvrzovaciho emailu does not occur?

USER: YES

ASSISTANT: Are there valid executions where Potrvzeni o prijeti objednavky occurs but Odeslani emailu o 1... does not occur?

USER: NO

ASSISTANT: When Odeslani potvrzovaciho emailu occurs, must Odeslani emailu o 1... always have occurred before it in every valid execution?

USER: INDEPENDENT

ASSISTANT: Can Potrvzeni o prijeti objednavky and Ulozeni do DB occur together in the same process execution?

USER: YES

ASSISTANT: Are valid executions possible with only Potrvzeni o prijeti objednavky, only Ulozeni do DB, and both Potrvzeni o prijeti objednavky and Ulozeni do DB?

USER: only Potrvzeni o prijeti objednavky and both

ASSISTANT: Can Ulozeni do DB occur only after Potrvzeni o prijeti objednavky is completed?

USER: YES

ASSISTANT: Can Ulozeni do DB and Dotaz na upravu pozadavku occur together in the same process execution?

USER: YES

ASSISTANT: When Ulozeni do DB occurs, must Dotaz na upravu pozadavku have occurred before it?

USER: NO

ASSISTANT: You stated that before Odeslani potvrzovaciho emailu can happen, Odeslani emailu o 1... must already be completed in that branch.

But later you said they are independent.

Please clarify:

When Odeslani potvrzovaciho emailu occurs, is Odeslani emailu o 1... always required beforehand?

USER: OCCUR TOGETHER

ASSISTANT: When Odeslani emailu o 2... occurs, must Uprava pozadavku occur BEFORE it?

USER: NO

ASSISTANT: Can Odeslani emailu o 2... occur even when Uprava pozadavku did not occur at all in that execution?

USER: YES

ASSISTANT: When Odeslani potvrzovaciho emailu occurs, must Odeslani emailu o 1... occur BEFORE it, or can they happen in any order?

USER: can they happen in any order

ASSISTANT: If Uprava pozadavku is completed, can the process return to an earlier activity such as Kontrola dostupnosti for rechecking availability?

USER: YES FOR Kontrola dostupnosti

ASSISTANT:

Process name: Reservation Management Process

Activity list:
- Kontrola přihlášení
- Zadani rezervace
- Kontrola dostupnosti
- Dotaz na upravu pozadavku
- Potrvzeni o prijeti objednavky
- Odeslani emailu o 1...
- Uprava pozadavku
- Ulozeni do DB
- Odeslani emailu o 2...
- Odeslani potvrzovaciho emailu

SBMN relations:
- Zadani rezervace DEP Kontrola přihlášení
- Kontrola dostupnosti DEP Zadani rezervace
- Dotaz na upravu pozadavku DEP Kontrola dostupnosti
- Uprava pozadavku DEP Dotaz na upravu pozadavku
- Potrvzeni o prijeti objednavky DEP Kontrola dostupnosti
- Odeslani emailu o 1... DEP Potrvzeni o prijeti objednavky
- Ulozeni do DB REQ Kontrola dostupnosti
- Ulozeni do DB REQ Potrvzeni o prijeti objednavky
- Odeslani potvrzovaciho emailu DEP Ulozeni do DB
- Potrvzeni o prijeti objednavky XOR Dotaz na upravu pozadavku

JMP relations:
- Uprava pozadavku JMP Kontrola dostupnosti

This SBMN model is consistent and has at least one valid BPMN realization.

