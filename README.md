automate-ucf_xls
================

These scripts may be used to test your commands (ex. SCPI or Standard Commands for Programmable Instruments) to control your instruments with an Ethernet or Serial (RS-232 port to USB) Connection. These scripts have a user-interface and will take commands directly. 


Attached is two scripts:

tst_ethernet.py
- Sockets module is used to establish connection over Ethernet.

tst_serial.py
- PySerial is used to establish a Serial Connection.

You will also need to install PySerial:
- http://pyserial.sourceforge.net/
- sudo svn co http://svn.code.sf.net/p/pyserial/code/trunk/pyserial/
- cd pyserial
- sudo python setup.py install

Feel free to email me for any help:
- Bronson Edralin <bedralin@hawaii.edu>
- BS Electrical Engineering, May 2014
- MS Computer Engineering Graduate Student and Research Assistant
- Instrumentation Development Lab (IDL), Physics and Astronomy Department, University of Hawaii at Manoa

================