* Mount VHD or VHDX file in Command Prompt

In order to attach 'vhd' or 'vhdx' disk we have to create some file for example 'attach.txt' with content:

```
select vdisk file="path_to_vhdx"
attach vdisk
```

after that invoke command:

...
diskpart /s "attach.txt"
...
