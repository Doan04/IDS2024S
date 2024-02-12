2. The .md stands for markdown language, and we use .md for README files in GitHub because the page can use the md syntax to format text
3. The git software does index and track empty folders in our projects, but GitHub won't show these empty folders
4. Yes
5. .git folder stores information about the repository, like the commit logs and where the remote repository is.
6. cd changes directory
7. Shows all the files and sub-folders in the current directory, hidden or not.
8. pwd displays the path to the current directory, all the way from root.
9. Working directory, where changes aren't tracked and aren't set to be committed. The staging area, where the specified files are ready to be committed to the repository area.
10. A VCS keeps track of changes to our projects, and revert changes if needed.
11. Lower risk of data loss, ease of collaboration, standardized way to resolve conflict in file changes, cloning the projects to new computers is easier, less storage space needed from not having to store entire copies of the project between versions, easier tracking of which member was responsible for which changes.
12. Local, Centralized, and Distributed.
13. Git is the main software responsible for version control, while GitHub is a place to host remote repositories.
14. git status gives a list of files with changes, and whether they've been staged for a commit or not.
15. git push --all pushes all changes on the local repository that have been committed to the remote repository.
16. git pull updates the local repository to match changes made to the remote repository.
17. Markdown is a formatting language.
18. Surround the text with **2 asterisks on each side**.
19. Surround the text with _an underline on each side_.
20. git init
21. . means current directory, .. means parent directory.  
22. 

thanh@DESKTOP-6P9T3U5:~$ pwd  
/home/thanh

thanh@DESKTOP-6P9T3U5:~$ mkdir testdir  
  
**testdir isn't a git repository yet. Use git init to fix this.**  
**Vim is a command-line text editor. Save content by pressing ESC, then typing :wq.**
  
thanh@DESKTOP-6P9T3U5:~/testdir$ cat README.md  
This is a README.md file for the test git project of quiz1.  
  
thanh@DESKTOP-6P9T3U5:~/testdir$ git status  
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)  
  
**Stage using git add --all, then commit using git commit -m "message for commit".**  
  
thanh@DESKTOP-6P9T3U5:~/testdir$ git add --all  

thanh@DESKTOP-6P9T3U5:~/testdir$ git commit -m "created README.md"  
[main (root-commit) 3124bb2] created README.md  
 1 file changed, 1 insertion(+)  
 create mode 100644 README.md  
  
thanh@DESKTOP-6P9T3U5:~/testdir$ git status  
On branch main
nothing to commit, working tree clean  
  
**cd && rm -rf ./testdir means first go back to home directory, and if successful, delete the testdir directory forcefully and recursively.**

23. Relative path relates to the current directory the path address is read in. Absolute path is a specific path all the way from the root of the system. Typically it's more appropriate to use relative paths, so the project is easier to migrate.
24. git --help.
