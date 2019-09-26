##Readme for the Tripwire Enterprise Add-on for Splunk
##Author: Tripwire, Inc
##Version: 3.1.0

#PREREQUISITES:
* Splunk 7.0.0 or above
* Tripwire Enterprise 8.2.x or above

#CHANGES AND NEW FEATURES

VERSION 3.0.0
   1. Added a new "te_assets_lookuptable_builder" index to fix a bug in distributed environments.
   2. Added new documentation for installing and configuring the add-on.
   3. Added documentation and support for pulling data from multiple TE consoles.
   4. Renamed the Tripwire Technology Add-On for consistency and compatibility with Splunk ES.

VERSION 2.1.0
   1. Added options to use the REST API for FIM/SCM.
   2. Various bug fixes and improvements.
   3. Added new tripwire.log in the Splunk log directory.

VERSION 2.0.0
   1. Added a stand-alone TA for Tripwire Enterprise
   2. Addressed CIM Compliance for FIM data source
      a. FIM data sources have been normalized to the "Change Analysis" data model
      
VERSION 1.5.4
   1. Addressed defect for Splunk Enterprise 6.3 support

VERSION 1.5.3
   1. Added ability to load more detailed change data
   2. Addressed defect with special characters in passwords

VERSION 1.5.2
   1. Addressed defect in Windows SetUp screen

VERSION 1.5.1
   1. Availability of two add ons: TA_te and SA_te for distributed deployments
   2. Addresses minor issues deploying to Linux based Heavy Forwarders

#Features
	- The Tripwire Enterprise Add-On for Splunk enables a Tripwire Enterprise administrator to collect FIM, SCM, and audit events from Tripwire Enterprise, map them to the Splunk Common Information Model (CIM), and input the data into Splunk. This data can be visualized through other Splunk Apps, such as the Splunk App for Enterprise Security
	- The Tripwire Enterprise Add-On for Splunk works on single installation as well as distributed environments
	- Multiple Tripwire Enterprise consoles are also supported for use with this Add-On

#Documentation
	- For detailed documentation, including installation and configuration instructions, please see the included "TripwireEnterpriseSplunk.pdf" file
