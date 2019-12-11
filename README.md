# [WIP] Pharmaceutical-Refinement-Pipeline
This is a project to develop a full stack research pipeline for creating, testing, and refining ligands that specifically bind to a previously discovered location. 

Currently utilizes *AutoGrow 3.1.3* as the backbone for the algorithm; however, it is being updated for newer technologies and less dependencies. It is also being face-lifted with a GUI and newer implementations of other docking software. 

**Progress**

- [WIP] Java UI
  - [x] Interfaces with AutoGrow
  - [WIP] Capture commandline output
  - [x] Visualize compounds in generation folder
  - [WIP] Handles multithreading jobs with UI views
  - [WIP] Supports editing settings with UI
  - [WIP] Support pausing runs to view and manually modify in new molecules
  
- [WIP] AutoGrow Updates
  - [x] Removed MGLTools dependency (for 64-bit)
  - [x] Fixed redundency bug in removing ligands
  - [WIP] Add optional sequences of multiple docking suites (LeDock & AutoDock Vina)
  - [WIP] Add ADME filters in conjucntion with simple pharmacological rules
  - [WIP] Add support for adding manual filters for ligand refinement
  - [WIP] Add support for multiple docking screenings before proceeding to next generation 
  - [x] Fpocket is used to identify potential pockets
  - [WIP] Method to calculate grid box coordinates of pocket

*Possible Py4J support to add callback server interopability coming*


**DISCLAIMER**: I am not affiliated with the development team at AutoGrow. I am thankful that they keep their software open-sourced to allow for projects like this. However, on my end, I will keep most of software I develop closed-source to protect my research group's intellectual property rights. If there is an inquistion as to where the project is currectly at, please reach out to me. 
