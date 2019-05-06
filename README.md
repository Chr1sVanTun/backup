# backup
Backup using python and batch-file

This batch-repository is copied from speedgiude.net from 2004

here's the Original Link: https://www.speedguide.net/articles/how-to-backup-using-batch-files-1547


----------------------------------------------------------------------------------------------------------------


Using python shutil module to copy, move, rename files please keep in mind the following:

The shutil module takes strings, so there can be problems whith these strings. 
If an Error occures, there are three ways to fix them.

1. Just put r before your normal string it converts normal string to raw string
2. Use forward slashes 
3. Use double backslashes (as i used in the move.py document)


shutil.copy(source, destination)
