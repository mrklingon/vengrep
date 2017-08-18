# vengrep
Vendor lookup tool - uses ieee ethernet data to identify mac address vendors


FILES

getdbm - simple shell script uses wget to collect current ouidbm file 

vengrep - perl script to search newouidbm file for vendor information

NOTE both scripts need to be customized:
       1) set the path to the "home" directory for newouidbm file
       2) set the path for wget in getdbm
       
You may wish to put getdbm on a cron job to update the dbm file.
