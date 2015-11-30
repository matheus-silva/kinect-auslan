# How to Install OpenNI #

Instructions on how to download and install OpenNI for Windows 7 32bit or 64bit. For further installation information the following tutorials may be useful:
  * [The Code Project: How to successfully install Kinect on Windows (OpenNI and NiTE)](http://www.codeproject.com/Articles/148251/How-to-Successfully-Install-Kinect-on-Windows-Open)
  * [Coding Beta: Kinect on Windows using OpenNI - Installing the Kinect](http://www.codingbeta.com/kinect-on-windows-7-using-openni-tutorial-part-1-installing-the-kinect/)
  * [PrimeSense Sensor Modules for OpenNI (Kinect Mod) Readme](https://github.com/avin2/SensorKinect#readme)

## Downloads ##

  * [OpenNI Binaries](http://openni.org/Downloads/OpenNIModules.aspx) - Select OpenNI Binaries > Unstable > Unstable Build for Windows (x86 or x64)
  * [PrimeSense Sensor Modules for OpenNI (Kinect Mod)](https://github.com/avin2/SensorKinect) - Select download repository as zip
  * [NiTE Middleware Binaries](http://openni.org/Downloads/OpenNIModules.aspx) - Select OpenNI Compliant Middleware Binaries > Unstable > Prime Sense NiTE Unstable Build for Windows (x86 or x64)

## Installation Procedure ##

  1. Ensure any other Kinect drivers and Microsoft Kinect SDK are uninstalled.
  1. Install the OpenNI Binaries.
  1. Unzip the Prime Sense Sensor Modules file and navigate to and run the Win32 or Win64 .msi in /bin, follow the instructions to install.
  1. Install the NiTE Middleware Binaries.
  1. Plug in the Kinect to a USB port and wait until the driver software is found - check that the Kinect Camera, Kinect Motor and Kinect Audio are listed under Prime Sensor in Device Manager.
  1. Run installed sample programs in the OpenNI folder to check correct installation.