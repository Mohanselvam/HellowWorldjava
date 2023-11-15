Started by user Mohananselvam M
Running as SYSTEM
Building in workspace C:\Users\USER\.jenkins\workspace\HellowWorldJava
[WS-CLEANUP] Deleting project workspace...
[WS-CLEANUP] Deferred wipeout is used...
[WS-CLEANUP] Done
The recommended git tool is: NONE
No credentials specified
Cloning the remote Git repository
Cloning repository https://github.com/Mohanselvam/HellowWorldjava.git
 > git.exe init C:\Users\USER\.jenkins\workspace\HellowWorldJava # timeout=10
Fetching upstream changes from https://github.com/Mohanselvam/HellowWorldjava.git
 > git.exe --version # timeout=10
 > git --version # 'git version 2.41.0.windows.2'
 > git.exe fetch --tags --force --progress -- https://github.com/Mohanselvam/HellowWorldjava.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git.exe config remote.origin.url https://github.com/Mohanselvam/HellowWorldjava.git # timeout=10
 > git.exe config --add remote.origin.fetch +refs/heads/*:refs/remotes/origin/* # timeout=10
Avoid second fetch
 > git.exe rev-parse "refs/remotes/origin/main^{commit}" # timeout=10
Checking out Revision 08bc6b2595fe3421e256aba2c279ace91c3fd7e1 (refs/remotes/origin/main)
 > git.exe config core.sparsecheckout # timeout=10
 > git.exe checkout -f 08bc6b2595fe3421e256aba2c279ace91c3fd7e1 # timeout=10
Commit message: "The first java commited"
 > git.exe rev-list --no-walk 08bc6b2595fe3421e256aba2c279ace91c3fd7e1 # timeout=10
Finished: SUCCESS
