# Suspicious Process Tree Investigation

## Scenario
An alert was triggered for unusual process execution on an endpoint.

## Alert Details
- Parent Process: explorer.exe  
- Child Process: cmd.exe  
- Child of cmd.exe: powershell.exe  

## Investigation Steps
1. Reviewed process hierarchy  
2. Identified chained execution  
3. Checked command-line behavior  

## Findings
- Multi-level execution chain observed  
- Behavior not typical  

## MITRE ATT&CK Mapping
- Execution: T1059  
- Execution: T1059.001  

## Conclusion
Suspicious activity detected
