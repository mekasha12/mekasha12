
Steps to contributies to other person github source code
---------------------------------------------------------
<!---
mekasha12/mekasha12 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

1. click on the project name of the person we want to contribute to, then on the top right corner of the page clcik on 
"Fork" icon
2. After fork is generated click 'Code' button in a blue color and copy Https
   e.g:- https://github.com/Username/abebe.git
3. on the terminal/command prompt write:-
  e.g:- git clone https://github.com/Username/abebe.git
4. Navigate to your local repository
 e.g:- cd cd abebe ----which is downloaded
5. Check that your fork is the "origin" remote
 e.g:- git remote -v 
If you don't see an "origin" remote, you can add it using: 
git remote add origin https://github.com/Username/abebe.git
6. Add the project repository as the "upstream" remote
 e.g:- git remote add upstream https://github.com/Username/abebe.git
  //check it as:- git remote -v
7. Pull the latest changes from upstream into your local repository
Before you start making any changes to your local files, it's a good practice to first synchronize your 
local repository with the project repository. Use git pull upstream master to "pull" any changes from 
the "master" branch of the "upstream" into your local repository. (If the project repository uses 
"main" instead of "master" for its default branch, then you would use git pull upstream main instead.)
8. CHeck existed branchs 
 eg:- git checkout
 e.g:git checkout -b edeme //to create new branch
9. Make changes in your local repository you downloaded as fork
10. Add your changes
    e.g:- git add . //to add whole current folder
          git add filename //to add single file
