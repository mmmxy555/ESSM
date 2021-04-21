# ESSM
This is the source code depository of the experimental part of the paper ESSM, including the SPDL format input file of scyther tool for six sample protocols.

Obtaining the scyther tool
----------------------

Scyther is being developed on *Github*, and its complete source files are
availabe from
<https://github.com/cascremers/scyther>.

Protocol Models
---------------

The protocol models have the extension `.spdl` and can be found in the following directories:

  * [./Protocols](Protocols)
  
Usage
-----

You can run 


	scyther protocol.spdl 
  in Command-line 

or use command

	python ./scyther-gui.py
to enter graphical user interface.
