# Client Use

There are 2 brands of scripting that Quisitive does with it's clients and this repo is intended to help us share those scripting scenarios with the broader Quisitive consulting base.

## Consulting Service

The primary use of this library is to support our consulting services and client delivery. When you are on a client project you can fork this repo and even sync it with get to have the scripts local on a client server when necessary.  When using these scripts in a project scenario you are likely to generate log files, output files, input files or all of th above.  Please do not check these files in to the repo or remove them prior doing a pull request and merging you changes/improvements.

In all of our projects where these scripts are used there should be estimated effort for improvements.  Typically the scripting bucket is larger than actually required to run the scripts.  This is by design the hope is that consultants have budget to improve these scripts with every client use.  Estimates should be less time than the original creation of the script, but enough time to make improvements.  The over arching goal is a state of continues improvement through our client engagements.

When you are done with your client engagement (unless otherwise included in project deliverables) the repo should be deleted from our client servers when necessary.  It is also good to clean up the windows credential manager for any git or github credentials. A common exception to this is when we have an ongoing & regular relationship with the client (IE. Managed Services), in this scenario we should remember to clean this up when the relationship is terminated by the client.

## As a Deliverable

Often our clients ask us to make a script specifically for them.  If one doesn't exist, please [Make a new Script](NewScripts.md) and build it initially to be fully integrated with our repo.  Once the script is completed and tested then create a copy in the Stand Alone folder.  In the stand alone folder you can then remove the functions or add them to the script file directly. This way we build out the repo while also meeting our client needs. It is understood that this may take a little "extra" time and our estimates should accommodate this, but it is of a huge benefit to the Quisitive organization.
