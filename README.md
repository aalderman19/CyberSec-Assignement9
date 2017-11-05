# Project 9 - Modern Honeypot Network

Time spent: **2** hours spent in total setup

Honeypots ran for an additional **1** hour.

> Objective: Setup a honeypot and intercept some attempted attacks in the wild.

## Honeypots Deployed

Dionaea - Dionaea “the Nepenthes successor” is a malware capturing honeypot initially developed under The Honeynet Project's 2009 Google Summer of Code (GSoC). Dionaea aims to trap malware exploiting vulnerabilities exposed by services offered over a network, and ultimately obtain a copy of the malware.
 
Dionaea features a modular architecture, embedding Python as its scripting language in order to emulate protocols. Much superior to its predecessor (Nepenthes), it is able to detect shellcodes using LibEmu and supports IPv6 and TLS.

(From https://www.edgis-security.org/single-post/dionaea-malware-honeypot)



Wordpot - Wordpot is a Wordpress honeypot which detects probes for plugins, themes, timthumb and other common files used to fingerprint a wordpress installation.

(From https://github.com/gbrindisi/wordpot)



Shockpot - Shockpot is a web app honeypot designed to find attackers attempting to exploit the Bash remote code vulnerability, CVE-2014-6271.

(From https://github.com/threatstream/shockpot)

## Issues/Notes

 - Had an issue with the configuration of mhn-admin as the original command did not allow HTTP traffic.
 
 - All the honeypots went up at around 10 AM EST on Sunday, November 5, 2017.

## Summary of the data collected

 - As of 10:47 AM EST: There have been 96 attacks (29 from nmap step) all of which have attacked the dionaea honeypot.
 
 - No attacks have been observed on the other honeypots.

## Unresolved Questions

 - I do not have any questions as of right now.

