# PowerDoc

PowerShell Module to build function and class documentation.

## About

This project was made to make it easier for PowerShell Developers to be able to build class and function documentation easier.  My goald was to add PowerDoc to the build process to document the code for public use.

## Install

TBD

## How to use

1. Import-Module PowerDoc
2. Start-PowerDoc
3. Enjoy

## Documentation Result

### Functions

Funtions will pull information from the Get-Help command and expose it in the files.  Write it once as your are working on your function and PowerDoc will convert that into documntation for GitHub or on a project site with HTML files.

[Basic Example]

PowerDoc is an example of what type of files you would be able to request.  Currently .md and .html files are generated.  This only documents the classes and functions though, if you have more you want to add you will need to adjust your files.