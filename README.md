FB_group_archiver-
==================
Example OSdc
<a href="https://kippt.com/rohit29/osdc-links">Kippt</a> links of <a href="https://www.facebook.com/groups/jiitlug/">OSDC FB GROUP</a> 


archives the facebook post and stores them in db ,also  parses the link from them and post that to kippt

Init.py
=====
Run Init.py with configuration file as argument for the first time
It archives all post since beginning.
Basically it calls sync_fb with json data

cron_tab.py
=======
Should run every few minutes to get updated post from group

configuration folder
======
change the settings here
also it has db dump
import you db from this file


 
