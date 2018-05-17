Get-EnterpriseAdmins
====================

Synopsis
--------

Obtains the list of Enterprise Admins

Description
-----------

Obtains the list of Enterprise admins for the current or specified domain.

Parameter
---------

**Name:** Domain

**Description:** This is the Active Directory name to pull the Enterprise Admins list from.

Examples
--------

::

    PS> Get-EnterpriseAdmins
            DisplayName     SamAccountName      DistinguishedName
            ----------      -------------       -----------------'
            TestAccount     TestAccount         cn=TestAccount,OU=PoshSec,DC=PoshSec,DC=Com
            Bob Uncle       Bob.Uncle           cn=Bob Uncle,OU=PoshSec,DC=PoshSec,DC=Com

    PS> Get-EnterpriseAdmins
            DisplayName     SamAccountName      DistinguishedName
            ----------      -------------       -----------------'
            TestAccount     TestAccount         cn=TestAccount,OU=PoshSec,DC=PoshSec,DC=Com
            Bob Uncle       Bob.Uncle           cn=Bob Uncle,OU=PoshSec,DC=PoshSec,DC=Com

Notes
-----

Part of the PoshSec PowerShell Module.