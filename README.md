**Ex No: 01     Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools**


**Aim:**

To design and implement a CMOS inverter circuit using Cadence EDA tools, analyse its electrical characteristics, and understand the fundamental principles of CMOS technology, including the design process, layout, and simulation techniques.

**Tools Required:**

•	Personal Computer
•	Cadence Virtuoso Software

**S C H E M A T I C S I M U L A T I O N - PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION -Commands to get into Cadence**


1.	Right Click and open the terminal window
2.	Type the following commands as follows and press enter.
3.	csh
4.	source /cadence/install/cshrc
5.	virtuoso

**Procedure for Schematic simulation using Cadence**

1.	Now two windows must open i) virtuoso/command interpreter window ii)”Whats New…”
2.	Close the 2nd window
3.	Use 1st window i.e virtuoso window (CIW) for further processing.
4.	Create a New Library
5.	Create Schematic Cell view.
6.	Create the Symbol for schematic Cell view.
7.	Create the test Cell view.
8.	Analog simulation by spectre



**i)	Procedure for Creating New Library.**

•	File –New – Library

•	Name: Give name for ur library Ex: VLSILAB_EXP_1

•	Enable Attach to an existing technology library, Click OK

•	Attach the library to the technology library gpdk045.Click OK

**ii)	Create Schematic Cell view.**

•	Go to 1st window i.e virtuoso (CIW)

•	File-New-Cell view

•	Setup the new file form

	Library: Select the one you created.

	Cell: Give the experiment name Ex: Inverter ViewSchematic

	Type: Schematic press OK

•	Add the required components from the libraries and make the connections.

	Go to instance fixed menu or use shortcut key “I” from keypad to go instances

	Click on browse. This opens the library browser

	Now select the appropriate library for components like 

	Gpdk45 ------------------------nmos1v, pmos1v

	Create Input and Output pins

	Make the connections by using fixed narrow wire key

	Click Check and Save button

![WhatsApp Image 2025-02-28 at 14 38 30_a3eb5b84](https://github.com/user-attachments/assets/134bf956-090c-4178-ba02-7d0a98cf985b)


**iii)Analog simulation by SPECTRE.**

•	In test cell view window

•	Launch – ADE L(Analog Design Environment)

	Execute Setup—Simulation/directory/Host A new window opens

	Set the simulation window to spectre and click ok

	Execute Analysis – Choose. A window opens.

	Select the type and set the specifications and press OK

	Execute Output s—to be plotted – Select on Schematic

	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse

•	Execute Simulation -- Net list and Run

![image](https://github.com/user-attachments/assets/e9a0029e-bfeb-41b2-ac7e-c2ea76209c1d)

**For Transient Analysis Settings and Output**
 
 
![image](https://github.com/user-attachments/assets/9cda7755-7b8d-410b-8603-dfd4931f6c29)

![image](https://github.com/user-attachments/assets/9c950859-0aa3-4d1d-a109-cde290ee57fa)



 




 

**Results:**

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
   
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
   
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











