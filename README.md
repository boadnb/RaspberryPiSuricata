Raspberry Pi IDS/IPS

Purpose:


Requirements:  
  Raspberry Pi 4 or 5  
  USB Ethernet Dongle  
  Micro SD Card  

Steps (Expand on these)  
Connect Dongle to Raspberry Pi  
Create Raspbian SD Card  
Setup Raspbian  
  
Setup Suricata  
-  Installation:  
    - sudo apt-get install software-properties-common  
    - sudo add-apt-repository ppa:oisf/suricata-stable  
    - sudo apt update  
    - sudo apt install suricata jq  
-  Confirm Suricata Installation and Version:  
    - suricata -V  
-  Set Suricata Service to run on startup:  
    - sudo systemctl enable suricata.service
-  Stop service, so that configurations can be made:  
    - sudo systemctl stop suricata
  
  
Add Dongle to Pi  
Connect ethernet cable to modem  
Connect ethernet cable to router/switch  
Set up SIEM  

