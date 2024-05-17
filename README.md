## AIM: 
   To Schematic and Simulate Inverter using CADENCE virtuoso. 
## APPARATUS REQUIRED: 
   CADENCE VIRTUOSO 
## PROCEDURE: 
### Procedure for Commands to get into Cadence<br>
1.	Right Click and open the terminal window<br>
2.	Type the following commands as follows and press enter.<br>
    i)	tcsh<br>
    ii)	source /home/install/cshrc<br>
    iii)	virtuoso <br>
### Procedure for Schematic simulation using Cadence<br>
1.	Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…"<br>
2.	Close the 2nd window<br>
3.	Use 1st window i.e virtuoso window(CIW) for further processing.<br>
    i)	Create a New Library<br>
    ii)	Create Schematic Cell view.<br>
    iii)	Create the Symbol for schematic Cell view.<br>
    iv)	Create the test Cell view.<br>
    v)	Analog simulation by spectre<br>
### Procedure for Creating New Library.<br>
a)	File –New – Library<br>
b)	Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK<br>
c)	Attach the library to the technology library gpdk045.Click OK<br>
### Create Schematic Cell view.
a)	Go to 1st window i.e virtuoso(CIW)<br>
b)	File-New-Cell view<br>
c)	Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic<br>
d)	Type: Schematic press OK<br>
e)	Add the required components from the libraries and make the connections.<br>
f)	Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos<br>
g)	Analog library	Vdd, Gnd, Vcc, Vpulse, Vsin<br>
h)	Make the connections by using fixed narrow wire key<br>
i)	Click Check and Save button<br>
### Creating the Symbol for schematic Cell view
a.	In the schematic window, execute
Crate – Cell view – From Cell view
The cell view from cell view window appears
Check Lib Name, Cell Name, From View name must be schematic Press ok<br>
b.	Now Symbol generation form appears. Click Ok If No changes required<br>
c.	A new window with with default symbol is created.<br>
d.	Edit the symbol if you want to give actual symbol shape else continue.<br>
    i.	Execute Create-Cell view-from cell view<br>
    ii.	Library Name and Cell Name must be same which you have used for schematic. Press OK<br>
    iii.	Check for the position of pin side.Prss OK<br>
    iv.	Edit for the shape by Create-Shape-Choose required options to edit.<br>
## Creating the new test cell view<br>
a)	Go to CIW window, Execute File-New-Cell view<br>
b)	Setup the new file form<br>
Library: Select the one you a created.<br>
Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test<br>
View: Schematic<br>
Type: Schematic  press OK<br>
Analog simulation by SPECTRE.<br>
a.	In test cell view window<br>
b.	Launch – ADE L(Analog Design Environment)<br>
c.	Execute Setup—Simulation/directory/Host A new window opens<br>
d.	Set the simulation window to spectre and click ok<br>
e.	Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK.<br>
f.	Execute Analysis – Choose. A window opens.<br>
g.	Select the type and set the specifications and press OK<br>
h.	Execute Output s—to be plotted – Select on Schematic<br>
i.	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse<br>
j.	Execute Simulation -- Net list and Run<br>
## Simulation Settings

Setup for transient analysis:<br>
1. Stop time = 400n<br>
Setup for D.C analysis<br>
1. Component to be selected in schematic is	for d.c analysis<br>
2. Start = -1 Stop = 1 resp.<br>

## CMOS INVERTER
![image](https://github.com/Sachita02/VLSI-LAB-EXP-6/assets/162723490/5cf2781f-7798-4b04-9df3-948c4bf8f134)
![image](https://github.com/Sachita02/VLSI-LAB-EXP-6/assets/162723490/66c02494-ff8e-445e-ba3a-fb33a7b0aebc)

## OUTPUT
![image](https://github.com/Sachita02/VLSI-LAB-EXP-6/assets/162723490/ab02a726-02e3-4c4a-aa52-c7922a56883e)

## NANDGATE
![image](https://github.com/Sachita02/VLSI-LAB-EXP-6/assets/162723490/65c31616-59df-448f-8c7e-0b0d2f6cd3a7)
![image](https://github.com/Sachita02/VLSI-LAB-EXP-6/assets/162723490/028e93b9-b95c-4031-b210-5c8bd73626c1)

## OUTPUT
![image](https://github.com/Sachita02/VLSI-LAB-EXP-6/assets/162723490/eda6b0ab-27c7-427d-b8af-a2efef8d6683)

## NORGATE
![image](https://github.com/Sachita02/VLSI-LAB-EXP-6/assets/162723490/294cdf2b-4f7e-4757-949e-fa35f1beca48)
![image](https://github.com/Sachita02/VLSI-LAB-EXP-6/assets/162723490/a9008364-63af-452f-9232-5e84961124c3)

## OUTPUT

![image](https://github.com/Sachita02/VLSI-LAB-EXP-6/assets/162723490/806dc657-2a85-494e-8ecf-5c078a092366)

## RESULT
The schematic and simulate inverter using CADENCE is done and  verified successfully.
