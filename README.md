*Nikitha_SATech-Challenge*
worked on tendable.com 
used **Cypress** Framework - in **Javascript** language
**Steps to run test project:**
1. Create an account in gitHub
2. Create a repository for the project
3. Copy the link and then go to cmd then give commands like cd desktop and git clone
4. Empty repo created
5. then in editor (i am using VScode), open terminal and give git init
6. project with package.json and others can be seen
7. Add **cypess** using npm cypress --save --dev
8. Now add tests in e2e by adding regression, smoke folders as user wish
9. Add page objects by adding folder t0 cypress project and ass objects inside it
10. Add test data in fixtures
11. Add commands in commands.js
12. Add scripts which to run in Package.json file
13. Add configuration files in cypress.config.js
14. Now in terminal give commands as mkdir .github, mkdir workflows
15. then directory is created
16. inside it, add built.yml files
17. their can be 'n' no. of yml files for running single spec or pararrel job execution file or to run a foler/suite
18. in yml file give the code extracting from git official site and under name: <name of the built file>
19. after creating yml files give commands in terminal like git status, git add <path of the built file>, git commit and git push
20. Now we can see in git>actions>workflow> under cypress run > execution goes on
21. it has many components like what is the suite /file runned, report, logs etc
22. give name: my-artifact, path: <path of the artifact> in the script of yml and add, commit, push then reports section added in gitHub actions
23. we can use that reports for  the screenshot and vedios
24. if we want to see **failed** reports, add if: always() in the above 21st point , so failed reports can also be seen (as we have created bug report in the tendale test scenario, we can add this screenshot for that bug report)
25. just attach this report to the bug reports and can be sent to the dev/related team via jira or any agile managment tool. We can also  simplicly send the ticket/defect ID by attaching files and providing all the steps created in bug report .
 

git commit -m "added all about what is the test process in cypress"
