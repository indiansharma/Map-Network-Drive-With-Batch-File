# Batch File Script is given below read before you create yours with this sample:

#NOTE: \\NetworkDrive\Path Change to the drive or network folder you would like to map automatically. (For Example: \\abcd\efgh\myfolder) rest do not remove any space or do not make any changes.

@echo Create new L: drive mapping
@net use Z: \\NetworkDrive\Path /persistent:yes
:exit
@pause
