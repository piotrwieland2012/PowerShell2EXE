# PowerShell2EXE
Converting PS Script to Executable File
GUI support:

- expanded every output and input function like Write-Host, Write-Output, Write-Error, Out-Default, Prompt, ReadLine to use WinForms message boxes or input boxes automatically when compiling a GUI application
- no console windows appears, real windows executables are generated
- just compile with switch "-noConsole" for this feature (i.e. .\ps2exe.ps1 .\output.ps1 -noConsole)
- see remarks below for formatting of output in GUI mode

