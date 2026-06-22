
 ## What are the 5 most critical flows in this HRMS? Rank by business impact — who gets hurt worst when it breaks — not by what's easiest to test.
 ans : 1: mobile attendence  : site manager gets poor connection that stops the day logs forcing them to guess hours to remenber aprox time .
       2: over time calculation : a small error in system can completely wipe out their extra hrs of work causing an immidiate financial emergency at home
       3: new worker onboarding : during onboarding if their profile is incomplete system stops logging their attendence resulting no payslip
       4: exit employee : if their exit is not marked system keeps sending salaries to workers who already left 
## For each flow: what's the worst thing that happens if it breaks? Name the person. Name the consequence.
  ans : overtime flow :  the constructio worker gets hurt first because their lose their hard earned money facing fiancial crisis
        onboarding flow : if new joinie id is incomplete their will not tracked and they receive no payslip
        exit flow : the company loses because if their exit not marked system keeps apying them
## What will you automate vs. test manually? Explain the tradeoff for each decision. Include the team dynamic — the senior dev doesn't want a 20-minute CI pipeline. How do you keep it fast?
  ans : to keep it fast we skip the testing of frond end/UI because it keeps changing constantly we mainly focus on testing the backend like logical building error          identification and i automate backend using CI/CD pipeline to keep fast and manually test the things like how system is working low network and is it saving          data like it should do there is no network
## What will you deliberately NOT test, and why? This tells us more about your judgment than what you do test.
  ans : i will choose to skip testing front end if because it does not effect daily our main reason/goal like calculating an generating correct payslip 
        
