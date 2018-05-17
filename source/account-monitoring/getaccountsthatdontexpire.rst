Get-AccountsThatDontExpire
==========================

Synopsis
--------
Gets a list of the accounts that don't expire.

Description
-----------
Gets a list of the accounts from the active directory domain that don't expire.

Parameter
---------
**Name:** SizeLimit

**Description:** Number of objects to return in results.

Examples
--------
::

    PS> Get-AccountThatDontExpire
            DisplayName     SamAccountName      DistinguishedName
            ----------      -------------       -----------------'
            TestAccount     TestAccount         cn=TestAccount,OU=PoshSec,DC=PoshSec,DC=Com
            Bob Uncle       Bob.Uncle           cn=Bob Uncle,OU=PoshSec,DC=PoshSec,DC=Com

Notes
-----
Part of the PoshSec PowerShell Module
