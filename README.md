![FABRIC](https://github.com/RoseGPE/FABRIC/raw/master/logo.png)

FABRIC - FABRication Information Consortium

### Data

The things that this software interacts with are:

Part
 - List of Processes associated with the part
 - Part ID
 - Part Description
 - Part Owner
 - QTY Requested
 - Priority

Process
 - Type
 - Assignee
 - Material Location
 - Parameters
 - Notes
 - Started Date
 - Due Date
 - Accomplished Date
 - Progress (Blocked, Ready, Working, Finished)

Person
 - Rose Username (a unique ID for external suppliers)
 - Plain English Name
 - Contact Info

### Types of Processes
- EDM (Special parameters: material, thickness)
- Waterjet (Special parameters: material, thickness)
- Sheetmetal Bending
- CNC Routing
- CNC Mill
- CNC Lathe
- Mill
- Lathe
- Finishing (filing, sanding, polishing- specify type)
- Welding
- Heat treatment (Special parameters: specification)
- Assembly (bolts, press fits, etc.)
- Other (sawing, hand drilling, weird stuff)

### UI
Three main screens:
- Main overview (shows all parts in the system)
- Part view (also includes all processes)
- Worklist (the processes relevant to a user)
Auxillary screens like logins, password changes, account creation may be necessary...
![UI Proposal](https://github.com/RoseGPE/FABRIC/raw/master/ui_proposal.jpg)


### Other Features
- Email notifications to assigned members when they have something to do
