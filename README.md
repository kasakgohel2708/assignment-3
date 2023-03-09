# assignment-3
ass 2 
kasak@Kasak MINGW64 ~
$ cd desktop

kasak@Kasak MINGW64 ~/desktop
$ mkdir patronus

kasak@Kasak MINGW64 ~/desktop
$ cd patronus

kasak@Kasak MINGW64 ~/desktop/patronus
$ touch patronus.txt

kasak@Kasak MINGW64 ~/desktop/patronus
$ git add patronus.txt
fatal: not a git repository (or any of the parent directories): .git

kasak@Kasak MINGW64 ~/desktop/patronus
$ git init
Initialized empty Git repository in C:/Users/kasak/Desktop/patronus/.git/

kasak@Kasak MINGW64 ~/desktop/patronus (master)
$ git add patronus.txt

kasak@Kasak MINGW64 ~/desktop/patronus (master)
$ git commit -m 'add empty patronus file'
[master (root-commit) 63aca78] add empty patronus file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 patronus.txt

kasak@Kasak MINGW64 ~/desktop/patronus (master)
$ git branch harry

kasak@Kasak MINGW64 ~/desktop/patronus (master)
$ git branch snape

kasak@Kasak MINGW64 ~/desktop/patronus (master)
$ git checkout harry
Switched to branch 'harry'

kasak@Kasak MINGW64 ~/desktop/patronus (harry)
$ git checkout snape
Switched to branch 'snape'
M       patronus.txt

kasak@Kasak MINGW64 ~/desktop/patronus (snape)
$ git branch lily

kasak@Kasak MINGW64 ~/desktop/patronus (snape)
$ git checkout lily
Switched to branch 'lily'
M       patronus.txt

kasak@Kasak MINGW64 ~/desktop/patronus (lily)
$ git add .

kasak@Kasak MINGW64 ~/desktop/patronus (lily)
$ git commit -m 'add lilys doe patronus'
[lily 5db0cba] add lilys doe patronus
 1 file changed, 48 insertions(+)

kasak@Kasak MINGW64 ~/desktop/patronus (lily)
$ git branch -a
  harry
* lily
  master
  snape

kasak@Kasak MINGW64 ~/desktop/patronus (lily)
$
