# matebook-x-pro-config
Matebook X Pro Hackintosh Seb

## Fix DSDT$

## After Windows Install$
To recover Clover, easy way:$
- on the EFI partition: rename EFI/Microsoft/Boot/bootmgfw.efi to bootmgfw-orig.efi$

After a Windows update, Windows may re-create bootmgfw.efi with updated code. To fix after a Windows update:$
- on the EFI partition, remove EFI/Microsoft/Boot/bootmgfw-orig.efi$
- rename EFI/Microsoft/Boot/bootmgfw.efi to bootmgfw-orig.efi$
