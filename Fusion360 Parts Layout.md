# Unofficial Fusion360 parts file
---  
It was mentioned that the Autodesk folks might be making a post-processor for MaslowCNC (GC). In preperation for optimization of Fusion360 for use with MaslowCNC I've created and shared a Fusion360 Project that incorporates and extends the 'All_Parts_Laid_Out.svg' document, designed for cutting MaslowCNC from a single sheet of plywood, and hope to continue to update this Fusion360 Project file to allow easier creation of additional MaslowCNCs and to make it easier for folks to begin building and working with Fusion360 to design things to be built with MaslowCNC.

Experienced Fusion 360 users and/or active MaslowCNC Developers are welcome to contact me in order to be added as collaborators on this project within the Fusion 360 Cloud platform.
  
---
### [MaslowCNC Beta3 Parts](http://a360.co/2sV4YRd)
---
  
### Updated (7/7/17): 
* Parts Sketch, suitable for cutting all parts from a single piece of Plywood.
* Seperate 'extrusions' for each part
* Simple Component Paths: The Bare minimum to make the shapes and cuts necessary for the MaslowCNC parts. 
* Advanced Component Paths: All part paths, Pockets for the Sled mounting bolts, the Rigid Router's own plastic sled, engraved angle braces.
  
### To be added:  
  * More accurate machine settings (Feeds and Speeds) for all paths.
  * Roundover cuts for the Advanced sled, using a V-Bit
---  
### Fusion 360 Customizations/Scripts/Add-On:
  
### To be Added:
   * MaslowCNC's custom Router Bits Tool Definitions for Fusion 360

### Alternative GRBL Post Processor

[Github: GRBL-Post-Processor](https://github.com/Strooom/GRBL-Post-Processor)
This purports to be a more accurate Fusion360 PostProcessor for GRBL than the one included with Fusion360 

### Dogbone
  
[Github: Dogbone](https://github.com/caseycrogers/Dogbone)
  
This scripting Add-In will automate the creation of Dogbone Fillets on interior corners, allowing easier parts assembly and preventing cracks common on these angles due to natural expansion and contraction. Dogbone fillets are widely recommended on all CNC Machined plywood interior angles < 90 deg. 

### Part Nester
  
[Github: NESTER](https://github.com/tapnair/NESTER)
  
This Scripting Add-In helps optimize the layout of parts from any model on a single plane (the work surface) for machining, allowing you to more easily use the 3D modeling in Fusion 360 to display both your completed design, and your machining layout as seperate views. 
