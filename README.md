# Nikitha_SATech-Challenge
worked on tendable.com
**Steps to run test project:**
1. Create an account in gitHub
2. Create a repository for the project
3. Copy the link and then go to cmd then give commands like cd desktop and git clone
4. Empty repo created
5. then in editor (i am using VScode), open terminal and give git init
6. project with package.json and others can be seen
7. Now add tests in e2e by adding regression, smoke folders as user wish
8. Add page objects by adding folder t cypress project and ass objects inside it
9. Add test data in fixtures
10. Add commands in commands.js
11. Add scripts which to run in Package.json file
12. Ass configuration files in cypress.config.js
13. Now in terminal give command as mkdir .github, mkdir workflows
14. then directory is created
15. iside it bilt.add yml files
16. their can be n no. of yml files for running single spec or pararrel job execution file or to run a foler/suite
17. in yml file give the code extracting from git official site and under name: <name of the built file>
18. after creating yml files give commands in terminal like git status, git add <path of the built file>, git commit and git push
19. Now we can see in git>actions>workflow> under cypress run > execution goes on
20. it has many components like what is the suite /file runned, report, logs etc
21. give name: my-artifact, path: <path of the artifact> in the script of yml and add, commit, push then reports section added in gitHub actions
22. we can use that reports for chack the screen shot and vedios
23. if we want to see failed reports, add if: always() in the above 21st point , so failed reports can also be seen
24. just attach this report tot thebug reports and can be sent to the dev/related team
 

git commit -m "added all about what is the test process in cypress"
