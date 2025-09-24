# Phishing Email Analysis

## Goal
Break down a phishing email to identify all the red flags and techniques attackers use.  
The point was to practice spotting details users often miss.

## Steps I Took
1. Pulled the raw email and examined full headers
2. Noticed a mismatch between "From" and "Return-Path"
3. Identified a lookalike domain (tiny spelling change)
4. Hovered over links to reveal redirects to shady sites
5. Tested the attachment in a sandboxed environment
6. Documented indicators of compromise and what users should look out for

## Tools Used
- Email header analyzers
- WHOIS and DNS lookups
- Sandbox VM
- VirusTotal for file and link scanning

## What I Learned
- How attackers disguise their identity with spoofing
- Common phishing tricks like urgency, scare tactics, and fake logos
- Why training users to pause and check details is just as important as filters

