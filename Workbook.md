### 504.1
#### Lab 1.2: Enterprise-Wide Identification and Analysis
#### In this Lab we will focusing on Analysis (beaconing, URL, DNS)  
##### RITA
- **Real Intelligence Threat Analytics** [RITA](https://www.blackhillsinfosec.com/projects/rita/) : Ingested logs **e.g. zeek logs : use zeek because logging timestamp and connection metadata** and analysis the data to reveal anomalous activity that could be evidence of system compromise.

#### Tools That Create Beaconing 
1. [ASAgent](https://github.com/rev10d/504vsa) : It is backdoor that beacons at a very steady 10 second interval. all communication is based64 encoded and send over cleartext HTML
2. [DNSCat2](https://github.com/iagox86/dnscat2) : This tool is designed to create an encrypted command-and-control (C&C) channel over the DNS protocol, which is an effective tunnel out of almost every network.
***
