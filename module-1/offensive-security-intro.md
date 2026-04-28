📍 Module 1 • TryHackMe  
🧪 Lab / 🧠 Theory  
Status: Completed

##TASK-1: Think Like a Hacker
Objective
1. What is Offensive Security?

Result
• Offensive security is about simulating an attack like hackers do, to find system vulnerabilities

##TASK-2: Starting the Lab
💡note: A fake banking application called FakeBank will launch

Objective
1. Find the bank account number displayed in the browser

Result
• Bank account number identified in the FakeBank interface = 8881

##TASK-3: Find Hidden Pages

Learning
• a common mistake that websites have is that hidden pages are left accessible
• directory brute force -  used to discover hidden files, directories, and endpoints on a webserver 

Objective
a directory brute force is used to show accessible hidden pages
💡note: Command Used at Terminal is dirb http://sampleweb.thm

Action
1. View Site
2. type the following: dirb http://fakebank.thm
3. look for the other website shown after scan

Result
http://fakebank.thm/bank-transfer

##TASK-4: Attack the Admin Page
💡note: A hidden panel is accessed using the URL found at TASK3

Actions
1.Add /bank-transfer to the fakebank website http://fakebank.thm/(here)
💡note: bank-transfer is found at TASK3

2.Select Account: 8881
💡note: Account found at TASK2 = 8881

3.Deposit the Money: $2000

4.Submit
💡note: A code will appear which you will need to use to complete the task 



KEY TAKEAWAY
•Offensive security acts like hackers to find system vulnerability in order to make preventative countermeasures/defense
•common mistake found on websites is that hidden pages are sometimes left accessible(can be randomly stumbled upon or bruteforce it)
•dirb can be used for locating hidden pages
•logic flaws are exploitable without breaking security systems
• create a template block to use for every content to fill in (for tomorrows task)
  Learning
  Concepts
  
  Objective
  the task
  
  Actions taken
  steps taken
  
  Result
  outcome

  according to gpt :D
  
## 🧠 Task: [Name]

---

## 🎯 Objective
What the task is asking you to do

---

## 💡 Learning / Concepts
What this teaches you (theory behind it)

---

## 🔧 Actions Taken
Step-by-step actions you performed

```bash
(optional commands here)

