# OSX86-Ventura for IvyBridge (with Kepler GPU)

GA-H77M-D3H rev1.0 (Ivy-Bridge motherboard) and a GTX770 (Kepler-based) GPU


OS: macOS 13.2 22D49 x86_64 

Host: Hackintosh (SMBIOS: iMac19,1) 

Kernel: 22.3.0 

CPU: Intel i5-3570 (4) @ 3.40GHz 

GPU: NVIDIA GeForce GTX 770 

Memory: 13768MiB / 24576MiB 
       

Installation: copy "EFI" folder to a Ventura USB flash disk installer, after updating your serial# and the rest of SMBIOS info (as per Dortania's OpenCore guide).
When on the desktop, download Opencore Legacy Patcher (OCLP) and install root patches.


Credits:
- the Dortania team (AcidAnthera, mainly)
- https://github.com/nickw444/opencore-efi-z77
- https://github.com/chris1111/Geforce-Kepler-patcher/issues/73 (to enable Safari's "Developmental Features" and fix poor page rendering/crashes)
