Convert-FQDNtoDN
================

SYNOPSIS
^^^^^^^^
Converts FQDN to FQDN

DESCRIPTION
^^^^^^^^^^^
This converts a user supplied Fully Qualified DOmain Name (FQDN) into a Distinguished Name (DN).

PARAMETER
^^^^^^^^^
**Name:** domainFQDN

**Description:** This is the Fully Qualified Domain Name (FQDN) that needs to be turned into a Distinguished Name (DN).

NOTES
^^^^^
This is a PoshSec Utility Function

EXAMPLE
^^^^^^^
PS> Convert-FQDNtoDN -domainFQDN 'poshsec.com'

DC=poshsec,DC=com

EXAMPLE
^^^^^^^
PS> Convert-FQDNtoDN 'dev.contoso.net'

DC=dev,DC=contoso,DC=NET