# How to create a Visual Studio Project with OpenNI #

Instructions on how to create a basic Visual Studio 2010 project with OpenNI libraries and include files. Further useful resources:

  * [MSDN: Property Sheets (C++)](http://msdn.microsoft.com/en-us/library/a4xbdz1e)

## Procedure ##

  1. Open Visual Studio 2010 and create a new project.
  1. Select View > Other Windows > Property Manager.
  1. Right click either the debug or release folder listed under the project name in the Property Manager window and select Add New Project Property Sheet.
  1. Give a name to the property sheet and select ok.
  1. Right click the new property sheet in the Project Manager window and select Properties.
  1. Under the C/C++ > General tab add the location of the OpenNI Include folder, e.g. C:/Program Files/OpenNI/Include, to Additional Include Directories.
  1. Under the Linker > General tab add the location of the OpenNI Libraries folder, e.g. C:/Program Files/OpenNI/Lib, to Additional Library Directories.
  1. Under the Linker > Input tab add OpenNI.lib to Additional Depedendcies.
  1. Select apply, return to the property manager page and save the new property sheet.
  1. Copy this property sheet to a useful location for future use.
  1. When creating further Visual Studio projects with OpenNI add this property sheet to both the Release and Debug folders in the Property Manager window by right clicking the folder and selecting Add Existing Property Sheet.