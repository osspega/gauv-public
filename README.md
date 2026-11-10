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

Before each `gauv run`, gauv.com reads the latest release on this page. If the release is newer, gauv.com downloads the zip file and does a check of its SHA-256 hash. Then gauv.com replaces the files in its folder and starts the run. gauv keeps the `Data`, `Reports` and `Logs` folders. If gauv.com cannot connect to GitHub in 5 s, the run starts with the installed version.
