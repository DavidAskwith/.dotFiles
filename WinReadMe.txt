This will cause vim to auto open all filetypes

##Useful apps
* SharpKeys - remap keys
* Text Edit Anywhere - launches text from anywhere in a text editor

##cmder

* resolves powershell error
** Run as Admin: set-execution policy remotesigned
* Add context menu
* save as .reg
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\Directory\Background\shell\cmder]
  @="Open in Cmder"
  "Icon"="C:\\cmder\\Cmder.exe,0"

[HKEY_CLASSES_ROOT\Directory\Background\shell\cmder\command]
  @="\"C:\\cmder\\Cmder.exe\" \"%V\""

[HKEY_CLASSES_ROOT\Directory\shell\cmder]
  @="Open in &Cmder"
  "Icon"="C:\\cmder\\Cmder.exe,0"

[HKEY_CLASSES_ROOT\Directory\shell\cmder\command]
  @="\"C:\\cmder\\Cmder.exe\" \"%1\""
