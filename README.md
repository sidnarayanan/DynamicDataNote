DynamicDataNote
===============

Dynamic Data Note for T3

These are tex files to be used for a standard CMS document repository.
For reference, check this 

```
svn update utils
svn update -N notes
mkdir -p notes/IN-14-XXX/trunk
eval `./notes/tdr runtime -sh` # for sh. use -csh for tcsh.
cd notes/IN-14-XXX/trunk
git clone https://github.com/sidnarayanan/DynamicDataNote.git .
tdr --style=in b IN-14-XXX
```
