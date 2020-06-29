# array-operations
Written in C++03
It has 20 different operations on 2D arrays, using only pointers, and dynamic allocation without signs "[" and "]"
AFR w e0 ... ew-1 - Add row at begining of structure with w number of elements: e0, e1, ..., ew-1
ALR w e0 ... e2-1 - Add row at the end of structure with w number of elements: e0, e1, ..., ew-1
AFC h e0 ... eh-1 - Add collumn at begining of structure with h number of elements: e0, e1, ..., ew-1
ALC h e0 ... eh-1 - Add collumn at the end of structure with h number of elements: e0, e1, ..., ew-1
IBR r w e0 ... eh-1 - Add row before row r with w number of elements: e0, e1, ..., ew-1
IAR r w e0 ... eh-1 - Add row after row r with w number of elements: e0, e1, ..., ew-1
IBC c h e0 ... eh-1 - Add collumn before collumn c with w number of elements: e0, e1, ..., ew-1
IAC c h e0 ... eh-1 - Add collumn after collumn c with w number of elements: e0, e1, ..., ew-1
SWR r s - swap r row with s row
SWC c d - swap c collumn with d collumn
DFR - delete first row
DLR - delete last row
DFC - delete first collumn
DLC - delete last collumn
RMR r - delete row r
RMC c - delete collumn c
ISB r c h w e0,0 ... e0,w-1 ... eh1,0 ... eh-1,w-1 - insert structure from row r and collumn c with h rows and w collumns with elements e0,0 ...
RMB r h c w - remove h rows starting from row r and w columns starting from collumn c
PRT - print structure
END - delete structure
