# AndroidWatchSimpleUDPStreaming
For samsung galaxy 5 watch, streaming a set payload (1,2,3,4) over UDP port 12345. 

To use: edit the IP address in MainActivity.kt to match the IP address of the intended receiving device, and make sure ports match (currently set to 12345). 
You can edit port in MainActitvity.kt

If issues are encountered:
  1) Check both devices are on the same wifi network
  2) Check that a secondary UDP receiving program isn't also active, that can interfere with other receiving programs.
  3) Check version dependencies are up to date
  4) Check if wifi network is public and your public network firewall configuration
