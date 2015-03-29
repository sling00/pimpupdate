pimpupdate
==========

PiMP update script for fetching and deploying small patches.

Installation: cp pimpupdate/pimpupdate /opt/pimp

Usage: pimpupdate

or for command line options: 

Usage: pimpupdate help

This will give the list of applicable command line options.

==========
What does it do?
This script allows you to update integral parts of PiMP mining platform, 
Poolmanager, Seedmanager, nodm, misc os fixes created after release.
This allows for fixes to be rolled out without requiring a total reflash of the usb disk or hdd. 


What's Next?
============
1. Add support for changing installed miners to different versions (restore the shipped version, change between incremental milestones etc.)
2. Integrate mine start/stop functions. where needed. (Mostly done)
3. Integrate logging. ( /tmp/pimpupdate.log )
