DEMO
====
.Synopsis
=====
   Get all the running Virtual Machines from a host.

.DESCRIPTION
======
   Enumerate all the Virtualmachines from a Hyper-V host
   
   Requirements : 
   Windows Server 2012 R2 HYPER-V
   Windows Server 2012 R2

.PARAMETER HyperV
=====
    This can be a single servername or an array of servers.
    This is mandatory parameter, so if this parameter is not provided
    the values will be asked.
.EXAMPLE
=====
   .\Enum-vm.ps1 -HyperV <server1>,<Server2>,......

.EXAMPLE
=====
   .\Enum-VM.ps1

        cmdlet Enum-VM.ps1 at command pipeline position 1
        Supply values for the following parameters:
        HyperV[0]: <Server1>
        HyperV[1]: <Server2>
        HyperV[2]: