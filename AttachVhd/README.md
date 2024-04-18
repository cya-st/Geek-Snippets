## Mount VHD or VHDX file in Command Prompt 

In order to attach a 'vhd' or 'vhdx' disk, we need to create a file, for example, 'attach.txt' with the contents:
```
select vdisk file="path_to_vhdx"
attach vdisk
```
after that we can invoke command:
```
diskpart /s "attach.txt"
```
