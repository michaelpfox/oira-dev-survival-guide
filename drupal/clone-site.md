Clone a Drupal Site
=================

## Backup Original
1. Get everything in version control and up-to-date
2. Dump/Backup the DB
>$ drush sql-dump  - -ordered-dump  - -result-file=dbdumpfile.sql  

**NOTE:** drush archive-dump/archive-restore (doesn't work on solaris)


## Local MAMP
Either use the MAMP package or brew install ...

