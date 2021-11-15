[ ] Create a new git repository (Existsing vs New)
create a new repository on the command line:
echo “# name” >> README.md
git init
git add README.md
git commit -m “first commit”
git branch -M main
git remote add origin URL
git push -u origin main

push an existing repository from the command line
git remote add origin URL
git branch -M main
git push -u origin main

[ ] Fork repository locally
A fork is a copy of a repository that allows you to freely experiment with changes without affecting the original project .
You can fork any repo by clicking the fork button in the upper right-hand corner of a repo page. Click on the Fork button to fork any repo on github.com.

[ ] Clone project locally
git clone URL
[ ] Create locally branch with your name
git branch xyz ==>
it creates new branch named ‘xyz’ but still keep being on the locally current branch
git checkout xyz ==>
it will change your locally current branch to the develop xyz
git checkout -b xyz ==>
it creates also a branch named xyz and switches to it automatically
However, all of these changes (including the new branch) is still only in your local machine.
git push -u origin xyz
To publish the new branch you created in GitHub and make it available for everyone in your team
Branch Frequently, Commit Often

[ ] Check the previous checkboxes steps finished on readme.
[ ] Commit Changes
git commit -m “My message”
The recommended commit message:

Title

What changed from the last version? Why did you make the change?
[ ] Push Changes
git push origin branch
[ ] Open a pull request
How to create a pull request
[ ] Team approves
[ ] Merge
[ ] Go locally to main branch
git checkout xyz
[ ] Pull changes.
git pull origin xyz
