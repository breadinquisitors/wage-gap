# wage-gap

### Database dump

#### Importing the database
Note that if you make a restoration of the database, you must have a NEW database to restore to. This makes it to where you won't deal with conflicts. Just drop the old database you have when you make a new one!
When using the .dump file, in any database system application, when hovering over a database you make, go to "Database > Restore..." and you can restore the database in this way. 

#### Exporting the database
NOTE: ONLY DO THIS IF YOU MAKE CHANGES TO THE DATABASE!
After making changes to the database, you can go to "Database > Backup..." and don't change any settings. Do make sure to keep the name the same so the original file can be overridden. Save into the Git repository. 
After the changes are made, this needs to be pushed to the repository so everyone (or at least those using the database) can restore to the new database if needed. 