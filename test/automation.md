
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


## Quality Reflection

## Honest question: When you write code in your own projects — side projects, personal repos, contributions — do you write tests? Do you have a testing habit? If yes, describe it honestly — show us your actual workflow, your actual repos. If no, say so, and tell us what you think would make you start.
  ans : i do not write test for my projects , i manually check around by clicking the new setting and features that are because that helps to under it more deeply from user perspective like how it feels and works 
  ## Describe a time you shipped something you knew wasn't fully tested — or found a bug in production that should have been caught earlier. What happened? What did you learn? How does that experience connect to how you'd approach quality at this company?
  ans:  once i deployed a small project without proper testing only doing manual testing later found out that at number input user can add negative values which caused crashes in calculations at this company i keep every untested feature as risked potential and build automated CI/CD pipelines to make it fast and avoid mistakes i made last time
  ## Take a stand: This team has no QA process, no test coverage, and ships by pushing directly to main. What does this team need MOST right now? Pick ONE thing and commit to it. Not 'comprehensive testing strategy.' Not 'it depends on the codebase.' One thing. Tell us what you believe and why you believe it.
  ans: first i try to convence senior dev that we will build automated testing pipeline which helps in making testing fast and prevent accidently pushing the bugs into production which might crash the system 
  ## The senior developer has been on this codebase for 3 years. He thinks test automation is overhead — when something breaks, he fixes it from memory in 20 minutes. He's not hostile, but he doesn't believe QA adds value. How do you get him to care about quality without being condescending? Not a generic 'build trust' answer. What specifically would you say or do in your first week?
  ans : ill have a talk with senior developer personally and ask him what is the most complex part of the system and ask him what can a junior developer do when it crashed when you are unable or in an meeting by setting automate testing pipelines we fix it easily even when you are unable by lifting off presure fron you and junior developer
  ## Connect your test strategy to something personal. Not testing-related. A time you built a system for yourself — a habit, a process, a way of organizing something — that worked not because it was technically right but because it fit how you actually operate. What can that experience teach you about building quality systems that a team will actually follow?
