Welcome to the SBMN interview.
Which language would you like to use for the interview?
USER: english

Please provide:
Process name
Process domain
Full activity list
USER: Send Account Documents

Please provide:
Process domain
Full activity list
USER: Baking
Mail Pin 
Mail TANs 
Mail Card

Can “Mail TANs” occur without “Mail Pin” occurring at some point in the same process execution?
USER: NO

When “Mail TANs” occurs, must “Mail Pin” occur BEFORE, AFTER, or can both occur in any order depending on the execution?
USER: BEFORE

Are there valid executions of the process where “Mail Pin” occurs but “Mail TANs” does not occur?
Are there valid executions of the process where “Mail TANs” occurs but “Mail Card” does not occur?
USER: NO

After completing “Mail Card”, can the process return to or skip directly to another non-adjacent activity?
USER: no

Process name: Send Account Documents
Domain:Baking

Activity list:
Mail Pin
Mail TANs
Mail Card

SBMN relations:
Mail TANs DEP Mail Pin
Mail Card DEP Mail TANs
Mail Card DEP Mail Pin
This SBMN model is consistent and has at least one valid BPMN realization
