My First Network Reconnaissance Assessment

Project Overview

This is my first hands-on cybersecurity project. I used Kali Linux and Nmap to perform a basic network reconnaissance scan of my local machine.

Objective

To practise using Nmap, understand basic port scan results, and document my findings as part of my cybersecurity learning journey.

Tools Used

- Kali Linux
- Nmap 7.9

Target

- "127.0.0.1" — localhost, referring to the same machine running the scan.

Command Used

nmap -sV 127.0.0.1

Findings

The scan reported that the host was up and that all 1,000 default-scanned TCP ports were closed. No open TCP ports were identified in this scan.

What I Learned

- How to run a basic Nmap scan.
- What the localhost address means.
- The difference between open and closed ports.
- How to begin documenting cybersecurity findings.

Limitations

This was a basic scan of localhost covering Nmap's default 1,000 TCP ports. It was not a complete security audit and does not prove that the machine is fully secure.

Evidence

A screenshot of the Nmap scan will be added to this repository.

Next Steps

Practise scanning an authorised lab machine and learn more about network services and port states.

Author: Chiamaka Igboanugo
