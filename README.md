# oscp-report-template
LaTeX Report Template For OSCP

This repository contains the LaTeX template I used for my OSCP report (the old one, with the buffer overflow). Putting it here so I can share with anyone else interested in using LaTeX; it may need some tweaking for the new OSCP report, not sure.

## First Steps

  1. Create a directory called 'images' in 'lab_hosts'. Use this directory to store all your screenshots and proofs.
  2. In main.tex, change lines 6-8 to reflect your information.
  3. Duplicate the host template and exploit template for each unique host and exploit, keeping them in their respective directories.

## Custom Functions

The following custom functions are included:

  - **\exploitcustom**{*exploit name*}{*author*}{*link*}{*description*}{*command line arguments*}{*changes and notes*}
  - **\exploitmodified**{*exploit name*}{*author*}{*link*}{*description*}{*command line arguments*}{*changes and notes*}
  - **\exploitunmodified**{*exploit name*}{*author*}{*link*}{*description*}{*command line arguments*}
  - **\reportnotice**{*information that should be shared "out of character", such as when Metasploit was used or there was an issue with the lab**}
  - **\screenshot**{*screen shot name, in the 'images' folder*}{*caption for image*}
  - **\screenshotproof**{*hostname or ip*}
    - *Standardized caption for privesc proof screenshot. Loads hostname-proof.png
  - **\screenshotprooflocal**{*hostname or ip*}
    - *Standardized caption for user proof screenshot. Loads hostname-localproof.png
 
