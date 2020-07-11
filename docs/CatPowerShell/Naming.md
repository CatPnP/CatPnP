# Naming Conventions

Please follow the following naming convention for scripts in this repository.

## Folders

Folders in this repo act as "categories" or "types" of scripts.  Please make them clear and concise.  Ideally folders should be general enough to describe multiple scripts not just the new script being created.

## Integrated Scripts

All scripts and functions should follow the below naming convention.

```
Cat.{Tech}-{ScriptName}.ps1
```

There is flexibility around both the script name and the technology.  As long as the script name is descriptive enough for people to know what it does. The following technology abbreviations are currently in use.  If you have a new one, please update this documentation.

* PnP - Leverages PnP PowerShell modules.  You may need to update your modules based on the version of SharePoint.
* SP10 - Designed for SharePoint 2010 server powershell modules
* SP13 - Designed for SharePoint 2013 server powershell modules
* SP16 - Designed for SharePoint 2016 server powershell modules
* SP19 - Designed for SharePoint 2019 server powershell modules
* SPO - Designed for SharePoint Online powershell modules
* m365 - This technology is used because the script covers multiple Microsoft cloud modules/technologies. IE Azure, SPO, Teams, Etc.
* AD - Designed for the on premises Active Directory modules
* CM - Designed to work with Content Matrix for migrations
* GIT - Script for common Git commands in GitBash
* PS - General PowerShell scripts

## Integrated Functions

Similar to scripts, functions should follow a very similar naming convention.

```
Cat.{tech}-{FunctionName}.psm1
```

Inside the psm1 file functions should follow the below naming convention.  Updating this is in progress to help standardize.

```
{Action}-Cat{FunctionName}
```

For categories that have a functions folder there is also a Cat.{Category}Functions.psm1 file that is intended to load all functions from that category.

## Stand Alone Scripts

Stand alone script should follow a similar naming convention when providing to the client.

```
{Client}.{Tech}-{ScriptName}.ps1
```

After a script has been provided to the client and before you do a pull request in to the main repo please do a find & replace in the file to replace the client name with "{Client}".  Do the same for the file name to make it more generic for the general repo.
