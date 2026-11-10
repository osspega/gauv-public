# gauv

gauv is a Windows program that does stress tests and diagnostics on a PC.

## Install gauv

1. Open the [latest release](https://github.com/osspega/gauv-public/releases/latest).
2. Download the file `gauv-<version>-win-x64.zip`.
3. Extract the zip file to a folder, for example `C:\gauv`.

The zip file is for Windows on a 64-bit (x64) processor.

## Start gauv

- To open the window, start `gauv.exe`.
- To start a run from a terminal, go to the folder of gauv. Type `gauv run <profile>` or `gauv run --tests <list>`.
- To see all the commands and options, type `gauv --help`.
- To read the CPU temperature, start gauv as administrator.

## Updates

At each start, gauv.com and gauv-diag.exe read the latest release on this page. If the release is newer, they download the zip file and do a check of its SHA-256 hash. Then they replace the files in their folder and continue with the new version. gauv keeps the `Data`, `Reports` and `Logs` folders. If gauv cannot connect to GitHub in 5 s, gauv continues with the installed version.

When you start `gauv.exe`, the window looks for a new version. If a new version is available, the title bar shows the button "Install <version>". The button closes gauv, installs the new version and opens gauv again. During a test, you cannot use the button.
