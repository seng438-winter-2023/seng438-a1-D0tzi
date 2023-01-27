>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: Group Number 7 |
|---------------------------------|
| Student 1 name: Arion Hamel |   
| Student 2 name: Brenek Spademan |   
| Student 3 name: Jack Rovere |   
| Student 4 name: Ben Leggett |   

# Introduction

Prior to this lab, the group members had previous experience with unit testing; using JUnit 4 in a recent course. Jack Rovere had the most experience with testing, as he previously worked as a Software Quality Intern at Garmin. Jack's responsiblilities included python scripting, manual testing; and regression testing Garmin products. The rest of the group has had experience with exploratory testing when working on previous projects, but have not had any experience regression testing and very limited experience with manual testing. 

# High-level description of the exploratory testing plan

For the exploratory testing, our team divided into two groups - Brenek and Jack formed the first, while Arion and Ben formed the second. Brenek and Jack decided to  spend their half hour of exploratory testing by keeping the scope broad and testing every feature a little bit, as opposed to very detailed tests on a single feature. They ran all their tests using card 1 in order to keep behaviour consistent. Arion and Ben approached it from a different angle, running broad scope testing on both cards, in order to ensure the functionality remained consistent across multiple accounts. 
We tested the following functions:
- System Startup
- System Shutdown
- Transaction
- Withdrawal
- Deposit
- Transfer
- Inquiry
- Entering PIN

To create our use cases, we explored many of the common functions of the system and observed which were used the most, and had the most importance in ensuring the overall quality of the system. 

# Comparison of exploratory and manual functional testing

The exploratory testing phase allowed for a large degree of freedom when running through the ATM program. Each pair was able to find unique reproduceable bugs that were not present within the manual test cases. Further, each pair got practice entering bugs into Azure DevOps. There was some overlap of bugs found during the exploratory phase that were included in the list of manual test cases. As expected, the outcome of such cases held consistent when we progressed to the manual testing phase. 

# Notes and discussion of the peer reviews of defect reports

The manual testing from both pairs produced the exact same results, on both version 1.0 and 1.1. However the exploratory testing was useful in catching unique bugs, as each pair had the opportunity to traverse the system in their own way. After going through regression testing on version 1.1, it was found that while many of issues discovered during exploratory testing were resolved, most of the manual test cases remained active. When we peer reviewed each others results, we found that our report style was a bit different, so we made sure to agree on a standard, and compromised to a certain type of writing.

# How the pair testing was managed and team work/effort was divided 

Pair testing was handled in the same groups created during the exploratory testing phase. Brenek and Jack split the effort evenly. Brenek ran through the test cases on the ATM program, while communicating with Jack; who tracked each bug report in Azure DevOps. Arion and Ben split it evenly as well, with Ben becoming the testor - running the ATM program on his laptop and going through the test cases one by one. Arion watched beside him and documented the steps, state of the system, and actual output compared to the expected output for each test cases. 

# Difficulties encountered, challenges overcome, and lessons learned

This lab was challenging as the only group member familiar with Azure DevOps was Jack Rovere. The rest of the group had to familiarize themselves with a new technology while working on this lab. It was also challenging as it was our group's first time working together. Through doing this lab, we learned the importance of different types of testing. When doing our exploratory testing, the group discovered quite a few bugs that would not have been discovered with just manual testing. Likewise, the manual testing discovered bugs that were not discovered by either pair in exploratory testing. The importance of regression testing was also learned as through regression testing, the group was able to discover what bugs had been fixed, what bugs still persisted, and what new bugs were in the new version.

# Comments/feedback on the lab and lab document itself

We really enjoyed doing this lab and are looking forward to further developing our software testing skills.
