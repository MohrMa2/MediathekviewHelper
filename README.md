# MediathekviewHelper
It is a bash script to mass download file links from mediathekview. 
You can select multiple files. They get downloadad in a batch and even renamed to match the content.

It is a manual process, but I use it like this for serveral years and it works for me.


Usage:
- open Mediathekview and look for files. Mark them with a Ctrl-click. Press Ctrl-C to copy all selected files
- open a text file (e.g. "alles") and paste all text. Close file
- do > CreateURLandRename alles 
- a file named links and rename.sh have been created
- do > wget -i links  do download all files
- optional: do rename.sh to rename the downloaded files with better names
- optional: use Cleanup to clean the filenames further from unnecessary contents.


Issues: 
- cannot change the quality


FAQ:
- I cannot download, only a filename with *sendepause* is created
Watch for geofencing, your server needs to be in the country, where the mediathek is accessible.
