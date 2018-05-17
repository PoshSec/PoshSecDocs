Get-Administrators
================

Synopsis
--------

Obtains the list of Domain Admins

Description
-----------

Obtains the list of domain admins for the current or specified domain.

Parameter
---------

**Name:** Domain

**Description:** This is the Active Directory name to pull the Domain Admins list from.

Examples
--------
::

    PS> Get-Administrators
            DisplayName     SamAccountName      DistinguishedName
            ----------      -------------       -----------------'
            TestAccount     TestAccount         cn=TestAccount,OU=PoshSec,DC=PoshSec,DC=Com
            Bob Uncle       Bob.Uncle           cn=Bob Uncle,OU=PoshSec,DC=PoshSec,DC=Com

    PS> Get-Administrators -Domain 'poshsec.com'
            DisplayName     SamAccountName      DistinguishedName
            ----------      -------------       -----------------'
            TestAccount     TestAccount         cn=TestAccount,OU=PoshSec,DC=PoshSec,DC=Com
            Bob Uncle       Bob.Uncle           cn=Bob Uncle,OU=PoshSec,DC=PoshSec,DC=Com    

Notes
-----
Part of the PoshSec PowerShell Module