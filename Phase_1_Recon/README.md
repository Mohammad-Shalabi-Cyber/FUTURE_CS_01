# Phase 1: Reconnaissance Report

## Summary of Findings
In Phase 1, I used Nmap to bypass ICMP filtering via the `-Pn` flag. I successfully mapped the target's attack surface, discovering that while the primary web port (80) is filtered, secondary communication ports (2000/5060) are exposed.

## Technical Details
- **Target:** testphp.vulnweb.com
- **IP Address:** 44.228.249.3
- **Command Used:** `nmap -T4 -A -v -Pn testphp.vulnweb.com`

## Evidence
The screenshots in this folder (Nmap Output, Ports Table, and Topology) verify these findings and show the path taken to reach the target.
