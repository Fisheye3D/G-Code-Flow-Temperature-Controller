# G-Code-Flow-Temperature-Controller
A Post Processing Script for Slic3r based Slicers and Klipper Printers. It can be run separately and open G-Code file manually

Note that Klipper_Estimator Script is required for time estimation using Klipper Look-Ahead kinematics, and must be in the same Folder with this Script.  
Klipper_estimator repositorie : https://github.com/Annex-Engineering/klipper_estimator

This 3D Printing Concept is Based on my personal approach and with a minimum of Delphi programming skills.

This Script is free and open source, created to prove the effectiveness of automatic nozzle temperature change during 3D printing in order to get the best Quality/Speed Optimization, but it is not intended to be a definitive solution as I believe that integrating this concept in slicers will be more effective.

Hoping to soon find this concept in current slicers, because I think this will be the future of 3D printing.

# Operation and Instructions

Note that current Script version (bin/SB53-Systems.exe) is still under development and will be updated daily.

Take into account that this script is supposed to work under certain conditions :
- Does not accept G2 and G3 in G-Code.
- Time Estimation is based in Klipper Look-ahead kinematics (may not be compatible with Marlin or Others).
- Reading or generating large G-Code files with this Script can takes up to 2 minutes, depending in your CPU.
- Generated G-Code are 30% to 80% larger than the original one due to Temp and Speed adjustment (can be optimized).
- This Script is not tested with Print Start Moves in G-Code (My Print Start moves are in klipper Macro).
- This Script is currently only available for windows os.


Be responsible and careful with this Script by using reasonable values ​​and monitoring the behavior of your printer, and Happy Smart 3D Printing...

# Installation and Use
Note that there is no official Release yet, you can temporarily download the Bin folder which contains the necessary files
# About the Developer :
By Salim BELAYEL.  
Developed in June 2024 with (delphi 7 !!!!)  
Email : sb53systems@gmail.com  

![SB53-Systems~1](https://github.com/sb53systems/G-Code-Flow-Temperature-Controller/assets/33290411/b94703a1-cf21-4109-bfa6-b9bcff438a1d)  
------SB53-Systems-------  
If you find my work worthy, Bay me a coffee with PayPal using my Email.  
-------Thank you--------


