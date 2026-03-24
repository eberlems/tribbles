# tribbles
lackeyccg plugin for [Star Trek] Tribbles CCG.

HOWTO update

branch the repo branch playable

get new card data from https://www.trekcc.org/lackey/2020.php

copy the missing lines to sets/tribbles.txt with the new data. 
Errata and new cards will need changes to filenames. 
place new images in sets/setimages/general/ as 357x499px jpg

update changelog.txt

add new expansion to formats.txt and setlist.txt

set new date to yesterday and add replaced images uninstall.txt

update the date, version number and add short changes version.txt

Set new date at the top of updatelist.txt

generate new checksum ```/mkupdate plugins/tribbles/updatelist.txt```

make new PR