
ReadMe File for Move-VMandESX Example

Last update: Jan-2014
Tested on: vSphere 5.5 and later releases

Introduction and Purpose

This sample code provides functions that moves an inventory object such as VM or ESXi host

Running This Sample

Before running this sample, you can make sure you have the right version of PowerClI installed and in your path by running this command:
Get-PowerCLIVersion
You should see version 5.5 or later.

You can run this sample code with the following two instructions:
1. Import the functions to your powershell session:
..\Move-VMandESX
2. Run any given function that are present on the file Move-VMandESX.psm1:
Example: Move-VirtualMachine -VMName w2k8R2 -Destination 10.20.30.40
