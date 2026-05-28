INTERVIEW TRANSCRIPT

Assistant:
Welcome to the SBMN interview process.

Please inform:
1. Language of the interview
2. Process name
3. Process domain
4. Complete activity list

User:
1. english
2. Nico Activity Decision Process
3. Personal Activities
4. • Nico ist langweilig 
• Nico hat Hunger 
• Nico hat unbändige Lust 
• Nico will fischen 
• Nico schaut funny Filmchen 
• Nico geht fischen 
• Nico isst eine Banane 
• Nico ist glücklich

Assistant:
Thank you. The activity list is now frozen.

To begin the structural analysis:

Can “Nico hat Hunger” and “Nico hat unbändige Lust” occur together in the same execution of the process?

User:
NO

Assistant:
Understood.

I will record:

- “Nico hat Hunger” XOR “Nico hat unbändige Lust”

Next question:

Can “Nico schaut funny Filmchen” and “Nico geht fischen” occur together in the same execution of the process?

User:
NO

Assistant:
Understood.

I will record:

- “Nico schaut funny Filmchen” XOR “Nico geht fischen”

Next question:

Before “Nico geht fischen” can happen, must “Nico will fischen” already have occurred?

User:
SIM

Assistant:
When “Nico geht fischen” occurs, must “Nico will fischen” occur BEFORE it, AFTER it, or can both occur in any order depending on the execution?

User:
BEFORE

Assistant:
Are there valid executions where “Nico will fischen” occurs but “Nico geht fischen” does not occur?

User:
NO

Assistant:
Understood.

I will record:

- “Nico geht fischen” DEP “Nico will fischen”

Next question:

Before “Nico schaut funny Filmchen” can happen, must “Nico hat unbändige Lust” already have occurred?

User:
YES

Assistant:
When “Nico schaut funny Filmchen” occurs, must “Nico hat unbändige Lust” occur BEFORE it, AFTER it, or can both occur in any order depending on the execution?

User:
BEFORE

Assistant:
Are there valid executions where “Nico hat unbändige Lust” occurs but “Nico schaut funny Filmchen” does not occur?

User:
NO

Assistant:
Understood.

I will record:

- “Nico schaut funny Filmchen” DEP “Nico hat unbändige Lust”

Next question:

Before “Nico isst eine Banane” can happen, must “Nico hat Hunger” already have occurred?

User:
YES

Assistant:
When “Nico isst eine Banane” occurs, must “Nico hat Hunger” occur BEFORE it, AFTER it, or can both occur in any order depending on the execution?

User:
BEFORE

Assistant:
Are there valid executions where “Nico hat Hunger” occurs but “Nico isst eine Banane” does not occur?

User:
NO

Assistant:
Understood.

I will record:

- “Nico isst eine Banane” DEP “Nico hat Hunger”

Next question:

Can “Nico geht fischen” and “Nico isst eine Banane” occur together in the same execution of the process?

User:
NO

Assistant:
Understood.

I will record:

- “Nico geht fischen” XOR “Nico isst eine Banane”

Next question:

Before “Nico ist glücklich” can happen, must “Nico geht fischen” already be completed?

User:
NO

Assistant:
Before “Nico ist glücklich” can happen, must “Nico schaut funny Filmchen” already be completed?

User:
NO

Assistant:
Before “Nico ist glücklich” can happen, must “Nico isst eine Banane” already be completed?

User:
NO

Assistant:
Can “Nico ist glücklich” occur without any of these activities occurring?

- “Nico geht fischen”
- “Nico schaut funny Filmchen”
- “Nico isst eine Banane”

User:
NO

Assistant:
Must at least one of these activities occur before “Nico ist glücklich”?

- “Nico geht fischen”
- “Nico schaut funny Filmchen”
- “Nico isst eine Banane”

User:
YES

Assistant:
Are valid executions possible with:

- only “Nico geht fischen”
- only “Nico schaut funny Filmchen”
- only “Nico isst eine Banane”
- combinations of some of them together before “Nico ist glücklich”?

User:
only “Nico geht fischen”
only “Nico schaut funny Filmchen”
only “Nico isst eine Banane”

Assistant:
Understood.

I will record that the three alternatives cannot combine before “Nico ist glücklich”:

- “Nico geht fischen” XOR “Nico schaut funny Filmchen”
- “Nico geht fischen” XOR “Nico isst eine Banane”
- “Nico schaut funny Filmchen” XOR “Nico isst eine Banane”

Next question:

If “Nico geht fischen” occurs, must “Nico ist glücklich” always occur afterward in that execution?

User:
YES

Assistant:
When “Nico ist glücklich” occurs after “Nico geht fischen”, are there valid executions where “Nico geht fischen” occurs but “Nico ist glücklich” does not occur?

User:
NO

Assistant:
Understood.

I will record:

- “Nico ist glücklich” DEPC “Nico geht fischen”

Next question:

If “Nico schaut funny Filmchen” occurs, must “Nico ist glücklich” always occur afterward in that execution?

User:
YES

Assistant:
When “Nico ist glücklich” occurs after “Nico schaut funny Filmchen”, are there valid executions where “Nico schaut funny Filmchen” occurs but “Nico ist glücklich” does not occur?

User:
NO

Assistant:
Are there valid executions where “Nico schaut funny Filmchen” occurs but “Nico ist glücklich” does not occur?

User:
NO

Assistant:
Understood.

I will record:

- “Nico ist glücklich” DEPC “Nico schaut funny Filmchen”

Next question:

If “Nico isst eine Banane” occurs, must “Nico ist glücklich” always occur afterward in that execution?

User:
YES

Assistant:
When “Nico ist glücklich” occurs, must “Nico isst eine Banane” occur BEFORE it, AFTER it, or can both occur in any order depending on the execution?

User:
BEFORE

Assistant:
Are there valid executions where “Nico isst eine Banane” occurs but “Nico ist glücklich” does not occur?

User:
NO

Assistant:
Understood.

I will record:

- “Nico ist glücklich” DEPC “Nico isst eine Banane”

Next question:

Can “Nico will fischen” and “Nico hat Hunger” occur together in the same execution?

User:
NO

Assistant:
Understood.

I will record:

- “Nico will fischen” XOR “Nico hat Hunger”

Next question:

Can “Nico will fischen” and “Nico hat unbändige Lust” occur together in the same execution?

User:
NO

Assistant:
Understood.

I will record:

- “Nico will fischen” XOR “Nico hat unbändige Lust”

Next question:

Can “Nico ist langweilig” occur together with “Nico hat Hunger” in the same execution?

User:
YES

Assistant:
Can “Nico ist langweilig” occur together with “Nico hat unbändige Lust” in the same execution?

User:
YES

Assistant:
Can “Nico ist langweilig” occur together with “Nico will fischen” in the same execution?

User:
YES

Assistant:
Before “Nico will fischen” can happen, must “Nico ist langweilig” already have occurred?

User:
YES

Assistant:
When “Nico will fischen” occurs, must “Nico ist langweilig” occur BEFORE it, AFTER it, or can both occur in any order depending on the execution?

User:
BEFORE

Assistant:
Are there valid executions where “Nico ist langweilig” occurs but “Nico will fischen” does not occur?

User:
YES

Assistant:
Understood.

I will record:

- “Nico will fischen” REQ “Nico ist langweilig”

Next question:

Before “Nico hat Hunger” can happen, must “Nico ist langweilig” already have occurred?

User:
YES

Assistant:
When “Nico hat Hunger” occurs, must “Nico ist langweilig” occur BEFORE it, AFTER it, or can both occur in any order depending on the execution?

User:
BEFORE

Assistant:
Are there valid executions where “Nico ist langweilig” occurs but “Nico hat Hunger” does not occur?

User:
YES

Assistant:
Understood.

I will record:

- “Nico hat Hunger” REQ “Nico ist langweilig”

Next question:

Before “Nico hat unbändige Lust” can happen, must “Nico ist langweilig” already have occurred?

User:
YES

Assistant:
When “Nico hat unbändige Lust” occurs, must “Nico ist langweilig” occur BEFORE it, AFTER it, or can both occur in any order depending on the execution?

User:
BEFORE

Assistant:
Are there valid executions where “Nico ist langweilig” occurs but “Nico hat unbändige Lust” does not occur?

User:
YES

Assistant:
Understood.

I will record:

- “Nico hat unbändige Lust” REQ “Nico ist langweilig”

Next question:

Can the process return to an earlier activity after “Nico ist glücklich” is reached?

User:
NO

Assistant:
Process name:
Nico Activity Decision Process
Domain: Personal Activities

Activity list:

- Nico ist langweilig
- Nico hat Hunger
- Nico hat unbändige Lust
- Nico will fischen
- Nico schaut funny Filmchen
- Nico geht fischen
- Nico isst eine Banane
- Nico ist glücklich

SBMN relations:

- Nico hat Hunger XOR Nico hat unbändige Lust
- Nico schaut funny Filmchen XOR Nico geht fischen
- Nico geht fischen DEP Nico will fischen
- Nico schaut funny Filmchen DEP Nico hat unbändige Lust
- Nico isst eine Banane DEP Nico hat Hunger
- Nico geht fischen XOR Nico isst eine Banane
- Nico schaut funny Filmchen XOR Nico isst eine Banane
- Nico ist glücklich DEPC Nico geht fischen
- Nico ist glücklich DEPC Nico schaut funny Filmchen
- Nico ist glücklich DEPC Nico isst eine Banane
- Nico will fischen XOR Nico hat Hunger
- Nico will fischen XOR Nico hat unbändige Lust
- Nico will fischen REQ Nico ist langweilig
- Nico hat Hunger REQ Nico ist langweilig
- Nico hat unbändige Lust REQ Nico ist langweilig

This SBMN model is consistent and has at least one valid BPMN realization.