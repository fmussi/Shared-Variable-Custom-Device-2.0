## Shared Variable Custom Device 2.0 ##
This custom device enables VeriStand to communicate with Network Published Shared Variables hosted on the local system or a remote system.

One use case is when communicating between VeriStand and Vector CANoe via Shared Variables.
See Documentation (Add....)

### LabVIEW Version ###

LabVIEW 2020

### Built Availability ###

Builds available in the builds directory, everything in project is there to build.

### Build Process ###

Build the following components in order (TBC)

1. Source\Modules\Channel\Channels.lvproj (build packed library)
2. Source\Modules\ImportExport\ImportExport.lvproj (build packed library)
3. Source\Modules\FileTypes\TXT\TXT.lvproj (build packed library)
4. Source\SV Interface\SV interface project.lvproj (build packed library)
5. Source\SV Interface\SV interface project (Linux_x64).lvproj (build packed library)
6. Source\Shared Variables CD 2.0\Shared Variables CD 2.0 Custom Device Project.lvproj (build Configuration, Engine on My Computer and Engine on RT CompactRIO Target for linux x64(

### Quality, Limitations ###

This IP only supports Boolean, SingleFloating Point, Double Floating Point, I8, I16, I32, U8, U16, U32 data types. 
Import/Export is in the menu, but not implemented yet.

Maximum tested update rate 1kHz.

### Dependencies ###

Real Time Module
OpenG Toolkit
(NI Distributed System Manager)

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*
