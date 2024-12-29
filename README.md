# install-window-11-in-virtual-machines
   How to Install Windows 11 in a Virtual Machine &amp; Fix Common Installation Issues

          INSTRUCTION OF  WINDOW 11 INSTALL
1.Open a Command Prompt (Run as Administrator) and use the following commands
   a.path of the your machine =cd "C:\Program Files\Oracle\VirtualBox"                                                           
   b.VBoxManage.exe modifyvm "<Your VM Name>" --tpmdev "tpm0"                            
   c.VBoxManage.exe modifyvm "<Your VM Name>" --tpm-type "2.0"



   
2.Enable TPM and Secure Boot in VirtualBox:
  Open VirtualBox and select the virtual machine you created for Windows 11                                      
      Click Settings > System > Motherboard:
 1.Enable EFI (Special OSes only) to emulate Secure Boot.
 Go to Settings > System > Processor:
 2.Ensure at least 2 CPU cores are allocated.
 Navigate to Settings > System > Acceleration:
 3.Enable VT-x/AMD-V or other hardware virtualization option
