# Week-9-Honeypot

Time spent: **11** hours spent in total

> Objective: Stand up a basic honeypot and demonstrate its effectiveness at detecting and/or collecting data about an attack.

## Write-up
I had quite a few issues with installation when attepting to follow the walkthrough given on the assignment page. Instead, I decided to use a honeypot software found online. I utilized Atomic Software Solutions tool Honeybot to moniter scans on an IP address. The image below shows nmap scan before opening any ports:

<a href="https://imgur.com/YTotYj9"><img src="https://i.imgur.com/YTotYj9.jpg" title="source: imgur.com" /></a>

And after opening 3 new ports:
<a href="https://imgur.com/YTotYj9"><img src="https://i.imgur.com/YTotYj9.jpg" title="source: imgur.com" /></a>

The honeypot showed which IP tried to invade, through which server, and at what time.
Since I did not utilize MHN, I have attached a log from the honeypot I used in the repository instead of a JSON file.
