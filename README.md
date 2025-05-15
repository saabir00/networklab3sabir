# Network Fundamentals lab.3:
Simulate a packet drop scenario by disabling your adapter mid-ping. What output do you observe?<br /><br />
For example choose 'Google.com'. This command will send an unlimited number of pings to the Google DNS server.<br /><br />
8.8.8.8 is a DNS server provided by Google.<br /><br />
![alt text](https://github.com/saabir00/networklab3sabir/blob/main/Screenshot%202025-05-15%20224617.png)<br /><br />
Then, we disable the Active Wifi adapter by typing 'ncpa.cpl'.<br />
![alt text](https://github.com/saabir00/networklab3sabir/blob/main/Screenshot%202025-05-15%20224013.png)<br /><br />
![alt text](https://github.com/saabir00/networklab3sabir/blob/main/Screenshot%202025-05-15%20224036.png)<br /><br />
Ping results will now show lines like this:<br />
![alt text](https://github.com/saabir00/networklab3sabir/blob/main/Screenshot%202025-05-15%20224114.png)<br /><br />
This indicates that packets do not reach the other party, that is, packet drop.
