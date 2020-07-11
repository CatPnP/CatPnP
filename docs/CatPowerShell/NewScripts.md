# Creating New Scripts

To help make creating new scripts and functions easier while keeping them consistant 2 script templates have been created that you can copy and paste into the proper category folder for your new script.

```
Cat.{tech}--{FunctionName}.psm1
Cat.{tech}-{ScriptName}.ps1
```

The intent for these files is to keep our scripting best practices inside these file to give every script the same starting point.  As our best practices change, these files should be updated for future use.

## New Functions

For categories that have a functions folder there is also a Cat.{Category}Functions.psm1 file that is intended to load all functions from that category. If you create new functions, please ensure that the new functions is added to the category specific functions module.

## Documentation

We ask that all scripts be documented in a comments section at the start of the script the comments section should consist of the following information.

* Name
* Description
* Dependencies - Modules & tools that may need to be installed
* Potential enhancements that you may not have had time to implement
* Table of Contents

Please follow the [contribution standards](Contribution.md) and [naming conventions](Naming.md) when creating new Scripts.
