We prodive a dataset contains full HTTPS raw PCAP files of crawling top 779 accessed HTTPS websites. 
The scan was made daily based using Goolge Chrome and Mozilla Firefox Web browsers.

- The database is constructed by crawling HTTPS websites over two weeks (September 2016).
- The full PCAP files are given with full HTTPS payloads.
- The scanning process was automated using a local machine and a pre-configured remote proxy to dump all packets with port   
  number 443 (HTTPS port).
- The Google Chrome pcap files include 250,185 HTTPS flows related to 7977 services/websites.
- The Firefox pcap files include 237,127 HTTPS flow related to 7322 services/websites.
- pkt2flow (https://github.com/caesar0301/pkt2flow) tool can be used to extract flows from PCAP files.

License:
Use of the datasets above for research or other purposes is subject to the "Creative Commons 4.0 Attribution-Sharealike license" (http://creativecommons.org/licenses/by-sa/4.0/).

Link to download page: http://betternet.lhs.inria.fr/datasets/https/
