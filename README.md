# CSE1106-INTRO-PROJECT
labuser@CSE137912:~$ mkdir cse1106-intro-project
mkdir: cannot create directory ‘cse1106-intro-project’: File exists
labuser@CSE137912:~$ echo "# CSE1106-INTRO" >> README.md
labuser@CSE137912:~$ git init
Reinitialized existing Git repository in /home/labuser/.git/
labuser@CSE137912:~$ /home/labuser/.git/
-bash: /home/labuser/.git/: Is a directory
labuser@CSE137912:~$ git add README.md
labuser@CSE137912:~$ git commit -m "Initial project commit"
[main (root-commit) ea398e0] Initial project commit
 1 file changed, 2 insertions(+)
 create mode 100644 README.md
labuser@CSE137912:~$ git branch -M main
labuser@CSE137912:~$ git remote add origin https://github.com/Taiwo22-22/CSE1106-INTRO.git
labuser@CSE137912:~$ git push -u origin main
