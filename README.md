This project mainly focuses on implementing features of wireshark using pyshark
and pyqt5 to do packet snifing to analyze wlanpackets, capturing can be done 
either livecapture or filecapture.

LiveCapture
live capture is performed with live network, please connect the device to the 
wireless local area network to capture the packets.the sniffing can be limited 
by either packet count or timeout. The pyqt5 is a GUI which is used to get user
input data. The pyshark takes this user input data and process accordingly. the 
output file is stored with pcap(packetcapture)extension which can be displayed
using Wireshark.

FileCapture
The FileCapture is usefull only when we want to analyze a preexisting pcap file
the pcap file uses tshark to analyze and the output.here the packets can be viewd
by selecting the desired protocol.for a detailed and nondetaied description of the
data in the only summeries option would be useful.
