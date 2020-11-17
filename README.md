A repository of some Extension Attributes I've written or adapted from others for use in Jamf Pro.

Note that many of these can work in other management products such as Workspace ONE/Airwatch, but would need some minor adjustments to them.

**Full-Model-Name.sh** 

*Description:* An EA to get the full proper Mac model name using an Apple lookup process based on a portion of the model serial number.  
In order to prevent continuous lookups each time the Extension Attribute script runs, the first time it is run it will store the model name information into a local file. On each subsequent run, it will check for the file and read back it's contents so it does not perform a lookup over the internet.
