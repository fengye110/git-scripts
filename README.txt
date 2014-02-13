Usage:

$git config --global diff.tool meld
$git config --global alias.diffcur git-difcur


git-difcur
==============
##  meld diff current working directory with special commit
--------------------------------------
$git config --global diff.tool meld
$git config --global alias.diffcur git-difcur  #put git-difcur in PATH env, so git can find it.
USAGE:
   $ git diffcur HEAD~2   # compare HEAD~2 with working_dir
   $ git diffcur master -- app/   # compare master:/app/ with app/

git-difone
==============
$git config --global diff.tool meld
$git config --global alias.difone git-difone   #put git-difone in PATH env, so git can find it.
USAGE:
    $git difone master:./main.c 
    $git difone HEAD:./main.c 
