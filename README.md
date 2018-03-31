## ICS-packets-Analyzer  
This is a small tool for analysing ICS network packets.  

### Requirements    
pip install dpkt    
test platform: ubuntu 16.04 64bit  

### Usage  
**help infor:**     
python main.py -h  
![Image test](https://github.com/scu-igroup/ICS-packets-Analyzer/blob/master/image/help.png)  
  
**view 4-tuple flow info:**    
python main.py -v --pcapfile=./train.pcap     
![Image test](https://github.com/scu-igroup/ICS-packets-Analyzer/blob/master/image/4-tuple.png)  
  
**save into pcap:**  
python main.py -f --pcapfile=./train.pcap --outputfile=./102.pcap --srcip=192.168.1.33 --srcport=1110 --dstip=192.168.1.10 --dstport=102       
![Image test](https://github.com/scu-igroup/ICS-packets-Analyzer/blob/master/image/savetopcap.png)  
  
**flow info with a fixed length:**    
python main.py -i --pcapfile=./102.pcap    
head -20 ./out_77.txt
![Image test](https://github.com/scu-igroup/ICS-packets-Analyzer/blob/master/image/lengthflowinfo.png)  
  


