# AIM:
To Schematic and Simulate Inverter using CADENCE virtuoso.
# APPARATUS REQUIRED:
CADENCE VIRTUOSO
# PROCEDURE:
Procedure for Commands to get into Cadence
```
Right Click and open the terminal window
Type the following commands as follows and press enter.
i) tcsh
ii) source /home/install/cshrc
iii) virtuoso
```
Procedure for Schematic simulation using Cadence
```
Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…"
Close the 2nd window
Use 1st window i.e virtuoso window(CIW) for further processing.
i) Create a New Library
ii) Create Schematic Cell view.
iii) Create the Symbol for schematic Cell view.
iv) Create the test Cell view.
v) Analog simulation by spectre
```
Procedure for Creating New Library.
```
a) File –New – Library
b) Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK
c) Attach the library to the technology library gpdk045.Click OK
```
Create Schematic Cell view.
```
a) Go to 1st window i.e virtuoso(CIW)
b) File-New-Cell view
c) Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic
d) Type: Schematic press OK
e) Add the required components from the libraries and make the connections.
f) Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos
g) Analog library Vdd, Gnd, Vcc, Vpulse, Vsin
h) Make the connections by using fixed narrow wire key
i) Click Check and Save button
```
Creating the Symbol for schematic Cell view
```
a. In the schematic window, execute Crate – Cell view – From Cell view The cell view from cell view window appears Check Lib Name, Cell Name, From View name must be schematic Press ok
b. Now Symbol generation form appears. Click Ok If No changes required
c. A new window with with default symbol is created.
d. Edit the symbol if you want to give actual symbol shape else continue.
i. Execute Create-Cell view-from cell view
ii. Library Name and Cell Name must be same which you have used for schematic. Press OK
iii. Check for the position of pin side.Prss OK
iv. Edit for the shape by Create-Shape-Choose required options to edit
```
Creating the new test cell view
```
a) Go to CIW window, Execute File-New-Cell view
b) Setup the new file form
Library: Select the one you a created.
Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test
View: Schematic
Type: Schematic press OK
Analog simulation by SPECTRE.
a. In test cell view window
b. Launch – ADE L(Analog Design Environment)
c. Execute Setup—Simulation/directory/Host A new window opens
d. Set the simulation window to spectre and click ok
e. Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK.
f. Execute Analysis – Choose. A window opens.
g. Select the type and set the specifications and press OK
h. Execute Output s—to be plotted – Select on Schematic
i. Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse
j. Execute Simulation -- Net list and Run
```
Simulation Settings
```
Stop time = 400n
Setup for D.C analysis
Component to be selected in schematic is for d.c analysis
Start = -1 Stop = 1 resp.
```
# CMOS INVERTER
![image](https://github.com/Devikavijaya/VLSI-LAB-EXP-6/assets/164987794/8046b109-37bf-4a64-8ce4-f2b141b4beb0)
![image](https://github.com/Devikavijaya/VLSI-LAB-EXP-6/assets/164987794/be02c35b-fdde-4fba-ae34-df2c3df687e4)
# OUTPUT:
![image](https://github.com/Devikavijaya/VLSI-LAB-EXP-6/assets/164987794/6807b234-e505-4d6b-8035-c061db965d30)

# NANDGATE:
![image](https://github.com/Devikavijaya/VLSI-LAB-EXP-6/assets/164987794/b2c7f139-d087-40ff-bd60-63f30c32b245)
![image](https://github.com/Devikavijaya/VLSI-LAB-EXP-6/assets/164987794/3c8658a6-f39e-43e1-95b5-f4ddcc700291)
# OUTPUT:
![image](https://github.com/Devikavijaya/VLSI-LAB-EXP-6/assets/164987794/b7941475-e246-4dfd-8535-52e477438f5b)

# NORGATE:
![image](https://github.com/Devikavijaya/VLSI-LAB-EXP-6/assets/164987794/f11f55a2-e0e2-4212-bfb5-ed0b9c9517a5)
![image](https://github.com/Devikavijaya/VLSI-LAB-EXP-6/assets/164987794/f5f84161-de3d-4dd2-9dc1-1f5ea5c8c0ad)
# OUTPUT:
![image](https://github.com/Devikavijaya/VLSI-LAB-EXP-6/assets/164987794/163e2ee4-fee5-414e-97ef-ac849a71ec12)

# RESULT:
```
The schematic and simulate inverter using CADENCE is done and verified successfully.
```















