# CHALLENGE: weired
Find the web traffic.

Note : flag format WHL{a-zA-Z0-9_}

- its a pcap file

FLAG: WHL{4096b2b6ac329176d54a7d22e1fa034d}

# CHALLENGE: Dump

Only i know that editor is open on the system.

https://drive.google.com/file/d/16LqDU0oCFCyis0MwshOz-kgMEf8moU-o/view?usp=sharing

By strings command we can find it quickly

FLAG: `WHL{E4sy_t0_f1Nd_th3_pr0c3ss}`

# CHALLENGE: StarWar

Whilesec is the startup comapany which is working on technology docker ( containerization ).

https://drive.google.com/file/d/1H3WEBLL_Ttw2PeZh839zq6QlvmYysimU/view?usp=sharing

`strings each and every folder : )`

FLAG: `WHL{D0ck3R_F0r3nS1c}`

# CHALLENGE: HTTP

Santa captured the traffic but something messed out can you recover it.

Flag hash is : 78a76e53c2a9e0c72e8f3e35c01c37fa

https://drive.google.com/file/d/1U_8GZ7E3imqo49mfGbl0Ik6XBtoRPLwi/view?usp=sharing

- By analysing the message.pcap file's stream using wireshark i got this part of the flag 
- `flag:WHL{G???1_1S_4_fl4g}`
- now we have to guess those 3 letters . In the challenge the hash of the flag is given as 78a76e53c2a9e0c72e8f3e35c01c37fa
so now we can bruteforce it. now i created a custom wordlist using crunch and tried all the perumations of that unfilled flag part. now using hashcat tool , and using my custom wordlist i found the flag

FLAG:`WHL{GiNn1_1S_4_fl4g}` 

