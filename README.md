# PLPBasicGitAssignment
Hands-on assignment for basic Git and GitHub Workflow.
cd PLPBasicGitAssignment/
git init
git remote add origin https://github.com/BioforY/PLPBasicGitAssignment/.git/
touch hello.txt
echo "Hellow, Git!" > hello.txt
git add hello.txt
git commit -m "Add hello.txt with a greeting"
git push -u origin master
