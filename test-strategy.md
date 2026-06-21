### ground yourself
## Q1 : Every piece of data in this HRMS flows toward one output. What is that output, and why does everything else revolve around it?
  ans : every piece of data in this HRMS the workers correct " monthly pay slip". like from checking in,manager logs backend servers everything exist only to make sure payslip is correct if payslip is wrong everything is useless
## q2 : Who is the most vulnerable person in this system, and what does a system failure mean for them specifically — not in the abstract, but this month?
  ans : the most vulnerable person in system is "contract worker" and if the system fails they can't pay their bills like meals , groceries , medicines because their daily life runs on their payslip 
## q3 : race what happens when a site manager enters the wrong overtime hours for a worker. Where does that error travel, who should catch it, and who actually catches it?
 ans : 1: site manager enters wrong data inputs 
       2: payroll operator calculates manually and do errors while calculating
       3: without double check or authentication payslips are rolled out
    * there are no check points at all right now
    *the site should catch the errors while entering and data next the payroll operator should find it while calculating if he find and irreregularities

## markdown
  ## q1 : What specific screens and endpoints does this HRMS actually have? Did you open the app and click through it?
  ## q2 : When the test strategy says 'payroll module' — which exact calculation? Salary × days worked? Overtime × rate? Deductions? Each one is a different test.
    ans : for exact calculation we need to make sure the code handles base formula it is calculated by days worked are multiplied by daily wage rate and then overtime formula
  ## q3 : Who are the actual users? A site manager on a phone is not the same as an admin at a desktop. What does each person actually do in the system?
    ans : every user have different needs the site manager working sun need huge buttons and offline saving and other end payroll operator need a warning set if it finds any errors it alerts for fast checking 
  ## q4 : What happened the last two times broken code reached production? Those specific failures should drive your test priorities — not a generic risk matrix.
     ans: the first crash happened because developer forgot to add the database link to live server and the second one broke because of small typo mistake in the backend
  ## q5 : 
