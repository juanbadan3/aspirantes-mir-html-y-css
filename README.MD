
Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (develop)
$ git merge master
Already up to date.

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (develop)
$ git commit index.html "agregue el esqueleto del segundo ejercicio"
error: pathspec 'agregue el esqueleto del segundo ejercicio' did not match any file(s) known to git

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (develop)
$ git brancj
git: 'brancj' is not a git command. See 'git --help'.

The most similar command is
        branch

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (develop)
$ git branch
* develop
  master

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (develop)
$ git checkout master
Switched to branch 'master'
A       ejercicio3/ejercicio1-html-y-css/index.html
D       ejercicio3/index.html
D       ejercicio3/prueba.gitignore

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git commit index.html "aguere esqueleto"
error: pathspec 'aguere esqueleto' did not match any file(s) known to git

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git log --oneline
477e682 (HEAD -> master, develop) cambios en la rama develop
922f641 hola

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git status
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ../index.html
        deleted:    ../prueba.gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../../.bash_history
        ../../.gitconfig
        ../../.lesshst
        ../../.node_repl_history
        ../../.vscode/
        ../../AppData/
        ../../Contacts/
        ../../Desktop/
        ../../Documents/
        ../../Downloads/
        ../../Favorites/
        ../../Links/
        ../../Music/
        ../../NTUSER.DAT
        ../../NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TM.blf
        ../../NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TMContainer00000000000000000001.regtrans-ms
        ../../NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TMContainer00000000000000000002.regtrans-ms
        ../../OneDrive/
        ../../Pictures/
        ../../README.md/
        ../../Saved Games/
        ../../Searches/
        ../../Videos/
        ../.gitignore
        ../README.MD
        ../aspirantes-mir-html-y-css/
        ../node/
        ../../ejercicios/
        ../../ntuser.dat.LOG1
        ../../ntuser.dat.LOG2
        ../../ntuser.ini


Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git add index.html

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git commit index.html "agregue esqueleto"
error: pathspec 'agregue esqueleto' did not match any file(s) known to git

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ ^C

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git add

git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git add ejercicio-3-html-y-css
fatal: pathspec 'ejercicio-3-html-y-css' did not match any files

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git add ejercicio1-html-y-css
fatal: pathspec 'ejercicio1-html-y-css' did not match any files

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git add aspirantes-mir-html-y-css
fatal: pathspec 'aspirantes-mir-html-y-css' did not match any files

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git status
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ../index.html
        deleted:    ../prueba.gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../../.bash_history
        ../../.gitconfig
        ../../.lesshst
        ../../.node_repl_history
        ../../.vscode/
        ../../AppData/
        ../../Contacts/
        ../../Desktop/
        ../../Documents/
        ../../Downloads/
        ../../Favorites/
        ../../Links/
        ../../Music/
        ../../NTUSER.DAT
        ../../NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TM.blf
        ../../NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TMContainer00000000000000000001.regtrans-ms
        ../../NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TMContainer00000000000000000002.regtrans-ms
        ../../OneDrive/
        ../../Pictures/
        ../../README.md/
        ../../Saved Games/
        ../../Searches/
        ../../Videos/
        ../.gitignore
        ../README.MD
        ../aspirantes-mir-html-y-css/
        ../node/
        ../../ejercicios/
        ../../ntuser.dat.LOG1
        ../../ntuser.dat.LOG2
        ../../ntuser.ini


Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ ls
index.html

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git restore index.html

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git status
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ../index.html
        deleted:    ../prueba.gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../../.bash_history
        ../../.gitconfig
        ../../.lesshst
        ../../.node_repl_history
        ../../.vscode/
        ../../AppData/
        ../../Contacts/
        ../../Desktop/
        ../../Documents/
        ../../Downloads/
        ../../Favorites/
        ../../Links/
        ../../Music/
        ../../NTUSER.DAT
        ../../NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TM.blf
        ../../NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TMContainer00000000000000000001.regtrans-ms
        ../../NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TMContainer00000000000000000002.regtrans-ms
        ../../OneDrive/
        ../../Pictures/
        ../../README.md/
        ../../Saved Games/
        ../../Searches/
        ../../Videos/
        ../.gitignore
        ../README.MD
        ../aspirantes-mir-html-y-css/
        ../node/
        ../../ejercicios/
        ../../ntuser.dat.LOG1
        ../../ntuser.dat.LOG2
        ../../ntuser.ini


Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ index.htcode .
bash: index.htcode: command not found

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ code .

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git add index.html

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git commit index.html
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
Aborting commit due to empty commit message.

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$ git status
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ../index.html
        deleted:    ../prueba.gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../../.bash_history
        ../../.gitconfig
        ../../.lesshst
        ../../.node_repl_history
        ../../.vscode/
        ../../AppData/
        ../../Contacts/
        ../../Desktop/
        ../../Documents/
        ../../Downloads/
        ../../Favorites/
        ../../Links/
        ../../Music/
        ../../NTUSER.DAT
        ../../NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TM.blf
        ../../NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TMContainer00000000000000000001.regtrans-ms
        ../../NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TMContainer00000000000000000002.regtrans-ms
        ../../OneDrive/
        ../../Pictures/
        ../../README.md/
        ../../Saved Games/
        ../../Searches/
        ../../Videos/
        ../.gitignore
        ../README.MD
        ../aspirantes-mir-html-y-css/
        ../node/
        ../../ejercicios/
        ../../ntuser.dat.LOG1
        ../../ntuser.dat.LOG2
        ../../ntuser.ini


Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicio3/ejercicio1-html-y-css (master)
$
