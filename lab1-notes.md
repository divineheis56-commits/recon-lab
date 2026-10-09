# Lab 1: recon-ng on scanme.nmap.org
Goal: learn recon-ng and gather public info on a practice target.
What I did: made a workspace, added the domain, ran HackerTarget (found 45.33.32.156), tried Shodan (no results, probably my free account), exported an HTML report.
Problems: had to run back before installing modules. A network drop broke one install. The report module needed a CUSTOMER option. Firefox couldn't read /root, so I copied the report to /home/kali.
What I learned: read the error messages carefully. Most problems were typos and permissions.
