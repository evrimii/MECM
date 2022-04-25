# Windows 11 Compatibility Report for Microsoft Endpoint Configuration Manager

If you're looking for Windows 11 comabilibility report for your own environment you can use this. I modified official Windows 11 compatibility script and wrote results to registry. Gathered data with HW Inventory extension and created this report.

![screenshot](https://user-images.githubusercontent.com/61293970/165160189-9c6b6892-88d8-480d-b857-75f2d9a08f72.png)


Installation
-------------
1- Use BaselinePS.ps1 poweshell script and create a Configuration Baseline. Then deploy.

2- Add configurationMof.txt file into your Configuration.mof file.

3- Import Win11.mof file to you Default Client Settings > Hardware Inventory > Classes

4- Import Windows 11 Compatibility Report.rdl to you reporting services.


You can mail me if you have any questions.
evrimi@microsoft.com
