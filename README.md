# DeceptionFS
A sample using Windows Projected File System for Deception

Learning Here 
https://learn.microsoft.com/en-us/windows/win32/projfs/projected-file-system

Some good examples / References 

https://github.com/danielhodson/pyprojfs

https://scorpiosoftware.net/2024/02/20/projected-file-system/

https://github.com/adamplonka/RegFs-csharp

https://github.com/gtworek/PSBits/tree/master/ProjFS

Using Projected File System, we can do in User Mode, what we normally need a filter deiver for.

This repo is designed for 2 things. 

1. To show an example of Deception File System based on Canarytokens.

2. Show some of the primitives for building your own providers


To get started you only need Windows Notepad.

Step 0 - enable ProjFS.

`Enable-WindowsOptionalFeature -Online -FeatureName Client-ProjFS -NoRestart`

Step 1 - Compile and run the C# or use the PowerShell Script to install a scheduled Task.



