# comp1711

Author: Charlotte 

👋 Welcome to Codespaces! You are on our default image. 
   - It includes runtimes and tools for Python, Node.js, Docker, and more. See the full list here: https://aka.ms/ghcs-default-image
   - Want to use a custom image instead? Learn more here: https://aka.ms/configure-codespace

🔍 To explore VS Code to its fullest, search using the Command Palette (Cmd/Ctrl + Shift + P or F1).

📝 Edit away, run your app as usual, and we'll automatically make it available for you to access.

@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ git add README.md
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ git commit -m "A"
[main 8ebb1c3] A
 1 file changed, 3 insertions(+), 1 deletion(-)
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ git push 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 291 bytes | 291.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/cbroadbent4104/comp1711
   0f05900..8ebb1c3  main -> main
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ mkdir Dir1
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ mkdir dir1
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ cd dir1/
@cbroadbent4104 ➜ /workspaces/comp1711/dir1 (main) $ cd ..
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ mkdir test1
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ touch file1
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ ls
Dir1  README.md  dir1  file1  test1
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ ls -l
total 16
drwxrwxrwx+ 2 codespace codespace 4096 Oct  2 15:20 Dir1
-rw-rw-rw-  1 codespace root        39 Oct  2 14:55 README.md
drwxrwxrwx+ 2 codespace codespace 4096 Oct  2 15:20 dir1
-rw-rw-rw-  1 codespace codespace    0 Oct  2 15:21 file1
drwxrwxrwx+ 2 codespace codespace 4096 Oct  2 15:21 test1
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ ls -al
total 28
drwxrwxrwx+ 6 codespace root      4096 Oct  2 15:21 .
drwxr-xrwx+ 5 codespace root      4096 Oct  2 14:53 ..
drwxrwxrwx+ 9 codespace root      4096 Oct  2 14:59 .git
drwxrwxrwx+ 2 codespace codespace 4096 Oct  2 15:20 Dir1
-rw-rw-rw-  1 codespace root        39 Oct  2 14:55 README.md
drwxrwxrwx+ 2 codespace codespace 4096 Oct  2 15:20 dir1
-rw-rw-rw-  1 codespace codespace    0 Oct  2 15:21 file1
drwxrwxrwx+ 2 codespace codespace 4096 Oct  2 15:21 test1
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ mv file1 dir1/.
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ history
    1  git status
    2  git add README.md
    3  git status
    4  git commit -m "A"
    5  git push 
    6  mkdir Dir1
    7  mkdir dir1
    8  cd dir1/
    9  cd ..
   10  mkdir test1
   11  touch file1
   12  ls
   13  ls -l
   14  ls -al
   15  mv file1 dir1/.
   16  history
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ touch file2
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ rm file2
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ pwd
/workspaces/comp1711
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ ls
Dir1  README.md  dir1  test1
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ git add README.md
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ git commit -m "Changed name"
[main 335fd0c] Changed name
 1 file changed, 1 insertion(+), 1 deletion(-)
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ git push 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 292 bytes | 292.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/cbroadbent4104/comp1711
   8ebb1c3..335fd0c  main -> main
@cbroadbent4104 ➜ /workspaces/comp1711 (main) $ 