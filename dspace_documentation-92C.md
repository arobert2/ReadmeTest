# Index  1. [dSPACE Setup](#dspace-setup)
	1. [Installing MATLAB](#installing-matlab)
	1. [Installing .Net 3.5](#installing-net-35)
	1. [Install dSPACE](#install-dspace)
	1. [Install dSPACE Installation Manager](#install-dspace-installation-manager)
	1. [Licensing dSPACE For All Dongles](#licensing-dspace-for-all-dongles)

<!doctype

#dSPACE Setup
[top](#index)  

##Installing MATLAB
[top](#index)  

1. Run auto install script *as Administrator*  located at \\inas2.win.kennesaw.edu\applications\MATLAB\MATLAB <YearVersion>\matlab_R<YearVersion>_win64\matlab_2017a_win64_install.bat
2. Relax and wait a long time.

##Installing .Net 3.5
[top](#index)  
(You can skip this if you are on Windows 7)

1. Run auto install script *as Administrator* located at \\ksucmfiles.lab.kennesaw.edu\SCCMFiles\Software Packages\dot_net_3.5_offline\<Windows Version>\install_dot_net_3_5.bat

##Install dSPACE
[top](#index)  

1. Browse to \\itsstore01.win.kennesaw.edu\groups\Client Support\dSPACE\<CURRENT_YEAR>\Disc1
2. Run dSPACE_MasterSetup.exe
3. After accepting the license agreement you will be asked for a license file. The license files are any of the PIZ files in \\itsstore01.win.kennesaw.edu\groups\Client Support\dSPACE\<CURRENT_YEAR>\LicenseFiles
4. Select all three pieces of software to install.
5. During installation you should be asked an inordinate amount of times to press next. The setup should remain default except for very specific compilers that will be covered during the guide. *You must install all drivers you are prompted for*
6. Copy and Paste the directory for disk 2 in the textbox and click next. Disk 2 is located at \\itsstore01.win.kennesaw.edu\groups\Client Support\dSPACE\<CURRENT_YEAR>\Disc2
7. During installation you will be asked for the location of 3rd party compilers. If they have not been specifically requested and the media provided to you you can skip them by clicking the Skip button. By default dSPACE and MATLAB use the GNU compiler GC++. It is installed during MATLAB's installation.
8. Once the installation is finished you will need to reboot.

##Install dSPACE Installation Manager
[top](#index)  

1. Browse to \\itsstore01.win.kennesaw.edu\groups\Client Support\dSPACE
2. Run dSPACE Installation Manager 4.3 Full.exe

##Licensing dSPACE For All Dongles
[top](#index)  

1. Launch dSPACE Installation Manager
2. Click the Licenses button with the padlock.
3. On the right side of the screen click "Renew and add by file..."
4. In the new window click the "..." button next to the text box to browse.
5. Browse to \\itsstore01.win.kennesaw.edu\Groups\Client Support\dSPACE\<CURRENT_YEAR>\LicenseFiles
6. Select a PIZ file you have not already used during this installation.
7. Repeat until you are out of PIZ files.

You will now have installed MATLAB, dSPACE, and licensed dSPACE for all dongles.


