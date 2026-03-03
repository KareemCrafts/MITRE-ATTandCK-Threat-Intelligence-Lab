# Carbanak vs FIN7 — Threat Intelligence Comparison

## Side by Side Navigator Maps
![Comparison](../Comparison/comparison-screenshot.png)

## Summary

Carbanak and FIN7 are both financially-motivated threat 
groups that share a striking number of tactical similarities, 
which is likely why MITRE itself notes they may be linked. 
Both groups rely heavily on phishing as their primary method 
of initial access, targeting employees to gain a foothold 
inside victim organizations. They also share a preference 
for using legitimate tools and credentials to blend into 
normal network activity making detection significantly 
harder for defenders. Both groups also use masquerading 
techniques to disguise malicious processes as legitimate 
ones, and both employ defense evasion by tampering with 
system firewalls.

When it comes to execution and persistence, the overlap 
continues. Both groups make use of PowerShell and Windows 
Command Shell for script execution, and both establish 
Command and Control through remote access tools. FIN7 
operates at a notably larger scale with a much wider 
technique footprint across the ATT&CK matrix, reflecting 
its evolution into big game hunting and ransomware 
deployment. However, the core playbook — phish, persist, 
blend in, exfiltrate — remains remarkably consistent 
between both actors.

## Key Overlapping Techniques

| Technique | Carbanak | FIN7 |
|---|---|---|
| Phishing | ✅ | ✅ |
| Valid Accounts | ✅ | ✅ |
| Masquerading | ✅ | ✅ |
| Impair Defenses | ✅ | ✅ |
| PowerShell | ✅ | ✅ |
| Remote Access Tools | ✅ | ✅ |
| Data Exfiltration | ✅ | ✅ |
