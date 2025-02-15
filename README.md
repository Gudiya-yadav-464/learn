# learn
Learning Python, SQL, Linux.
 

linux prompts--

mkdir -  creates a directory
rm - to go a file
rm dir - r = remove drectory

pwd - check present working dir

-rw-rw-rw- 1 codespace codespace 0 Feb 15 11:40 ReadME.md
-rw-rw-rw- 1 codespace codespace 0 Feb 15 12:00 test.sh



Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls
README.md
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ mkdir
mkdir: missing operand
Try 'mkdir --help' for more information.
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ mk dir Linux things
bash: mk: command not found
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ mkdir Linux
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ mkdir linux
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ rm Linux
rm: cannot remove 'Linux': Is a directory
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ rm Linux -r
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ touch text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ cat README.md
# learn
Learning Python, SQL, Linux.
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ pwd
/workspaces/learn
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls
README.md  linux  text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ touch linux/ReadME.md
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls
README.md  linux  text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls -l
total 8
-rw-rw-rw-  1 codespace root        37 Feb 15 11:01 README.md
drwxrwxrwx+ 2 codespace codespace 4096 Feb 15 11:40 linux
-rw-rw-rw-  1 codespace codespace    0 Feb 15 11:35 text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ date
Sat Feb 15 11:45:00 UTC 2025
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ git add README.md 
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ git commit
[main 4967659] add basic linux prompts
 1 file changed, 11 insertions(+)
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 405 bytes | 405.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Gudiya-yadav-464/learn
   02804b2..4967659  main -> main
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls
README.md  linux  text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls linux 
ReadME.md
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ touch linux/test.sh
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls
README.md  linux  text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ pwd
/workspaces/learn
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls linux
ReadME.md  test.sh
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls
README.md  linux  text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls /workspaces/learn/
README.md  linux  text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls /workspaces/learn/linux
ReadME.md  test.sh
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls linux
ReadME.md  test.sh
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls linux -l
total 0
-rw-rw-rw- 1 codespace codespace 0 Feb 15 11:40 ReadME.md
-rw-rw-rw- 1 codespace codespace 0 Feb 15 12:00 test.sh
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ 
