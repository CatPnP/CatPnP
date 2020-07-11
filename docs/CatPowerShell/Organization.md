# Repository Organization

This repository is structured into folders intended to define the category or use of the scripts & functions inside of them. Each folder has a readme.md file that should be used to explain the intent behind that directory.  

## Documentation

The `_Documentation` folder should be used for repository documentation outside of the individual readme files in each directory. As you add necessary content feel free to add additional directories to group your documentation.  As a best practice please try to think about what documentation should be created or updated based on your contributions.

## Input, Output, Templates & Log Files

The `_Input Files`, `_Output Files`, & `_Log Files` folders are intended to store input, output log files, etc.  

The scripts in this repository should all be configured to look for the provide input files ("sample.json") in the root of `_Input Files`. Files that reside in the sub folders can also be referenced by providing the sub folder name ("Testing\sample.json").

The reporting scripts use `_Output Files` to store the data being collected by the scripts.

All Scripts should leverage PowerShell's transcript capability to log everything that is output to the screen in the `_Log Files` folder. This is especially helpful for long running scripts that you may not see all the errors when they happen.  Not that my scripts ever have errors =)

## Script Categories / Functions

This repository is primarily organized into type/categories (IE. Configuration).  Each category folder should have a Readme file to help outline the purpose for that directory.  In each category folder there is also a `Functions` folder.  

### Functions

Inside the functions folder each reusable function is in it's own dedicated file.  There is then a category functions file (Cat.ConfigurationFunctions.psm1) that should reference all functions that live in that category.  This allows all scripts the ability to load all functions within a single command or just load the individual function that is required.
