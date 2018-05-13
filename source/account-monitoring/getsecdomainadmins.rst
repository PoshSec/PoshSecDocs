Get-SecDomainAdmins
================

Synopsis
--------

Obtains the list of Domain Admins

Description
-----------

Obtains the list of domain admins for the current or specified domain.

PARAMETER
---------

**Name:** Domain

**Description:** This is the Active Directory name to pull the Domain Admins list from.

Examples
--------
::

    PS> Get-SecDomainAdmins
    SamAccountName      DisplayName
    --------------     -----------
    Administrator       
    mjadmin             Matt Johnson - Admin

    PS> Get-SecDomainAdmins -Domain 'poshsec.com'
    SamAccountName      DisplayName
    --------------     -----------
    Administrator      

Notes
-----
Part of the PoshSec PowerShell Module