# MPPT-Interface-Board
Author: Ravi Shah  
This Power and CAN interface board for the TPPE SEC-B175-7A Maximum Power Point Tracker provides an interface allowing them to connect to fuse box power and CarCAN. Since CarCAN on Daybreak operates at 5V, a 12V (fusebox) to 9V isolated buck converter is used to meet the minimum 6V requirement of the MPPTs.
## BOM
Mouser Cart: https://www.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=ef21a76273  
IBOM: BOM/ibom.html (open and view in browser)
## Connectors
TODO
## 3D Model
![image](https://github.com/user-attachments/assets/b9f51563-b8e6-491c-8bcf-144f7e9c13bb)
## PCB
![image](https://github.com/user-attachments/assets/4565632e-ae53-46b6-96fe-2774cdfd52b4)
## Schematic
![image](https://github.com/user-attachments/assets/490e2959-f3a6-40f2-a834-77bac7a0ffe5)
## Application Note
The FIRST MPPT connector is for the first MPPT this board connects to. From there, up to 4 (unverified!) MPPTs can be daisy chained by connecting the output of the first MPPT to the input of the second and so on. The LAST MPPT connector is where the output of the last MPPT in the daisy chain should be connected.
