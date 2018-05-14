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
    SamAccountName      DisplayName
    --------------      -----------
    Administrator

    PS> Get-EnterpriseAdmins -Domain 'poshsec.com'
    SamAccountName      DisplayName
    --------------     -----------
    Administrator  

Notes
-----

Part of the PoshSec PowerShell Module.