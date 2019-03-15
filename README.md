# Windows EVTX Samples:

This is a container for windows events samples associated to specific attack techniques. 
Can be useful for:

- Testing your detection scripts based on EVTX parsing

- Training on detection and threat hunting using event logs

- Designing detection use cases

## Reconnaissance:
1. PsLoggedOn.exe traces on the destination host
2. BloodHoundAD\SharpHound (with default scan options) traces on one target host

## Lateral Movement:
1. RemCom (open source psexec) traces on target host eventid 5145
2. PsExec traces on target host 

## Persistence:
1. 
