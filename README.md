# ConnectWise-Automate-Meltdown-and-Spectre-Detection-Scripts
Adapted Powershell Script to extract fields into EDFs within ConnectWise Automate. If you have problems generating the EDFs then import the XML twice.

Only the .XML is needed - this has the .PS1 included here attached within it.

Usage:

1) Import XML Script (twice); if you're still having problems reload the system cache and try again
2) Ensure EDFs have created by opening an Agent, going to EDFs, going to the Meltdown and Spectre Detection Section
3) Make sure EDFs are all there
4) Run the script (by default, this imports into Scripts > Meltdown and Specte Detection), against an agent, which will populate the EDFs

This should work on any Machine with Powershell 2 or above.

As per the attached license, THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED. This exploit/bug is complex and multi-layered.

