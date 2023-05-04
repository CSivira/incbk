# incbk
Incremental backup script in bash


## TODO
- Better progress log (flag -p) that shows data units and current file 
  transferred.
- Handle Cancel signal (ctrl+c/d) and remove the incomplete backup.
- Profile initialization. REPL that ask for profile name and source. 
  Internally it creates the .bkignore.profile file and add the source in the 
  .config file.
- Debug option (o flag) that enables set -o xtrace.
- Project description and user guide