pimpupdate
==========

PiMP update script for fetching and deploying small patches.

Installation: cp pimpupdate/pimpupdate /opt/pimp

Usage: pimpupdate

==========
What does it do?
This script allows you to update integral parts of PiMP mining platform, 
Poolmanager, Seedmanager, nodm, misc os fixes created after release.
This allows for fixes to be rolled out without requiring a total reflash of the usb disk or hdd. 


What's Next?
============
1. Add support for changing installed miners to different versions (Most pressing is rolling sgminer back to 4.1.153 to fix api issue in newest release.)
2. Integrate mine start/stop functions. where needed.
3. Integrate logging.
