Confirm-IsAdministrator
=======================

Sysnopsis
---------

Checks to see if user is running as administrator

Description
-----------

This function checks to see if the user is currently running as an administrator

Example
-------

::

    PS> Confirm-IsAdministrator
    False

    PS> if (Confirm-IsAdministrator) { Write-Host "You are an admin" }
    You are an admin

Notes
-----
Part of the PoshSec PowerShell Module.