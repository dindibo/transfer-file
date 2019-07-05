# transfer-file
This python script is used to transfer file between two computers on the same LAN.

Usage: transport_file <IP> <Port> [File_Name / -l]
  
IP - Machine's IP
Port - Port to be use
File_name - Specify file name to upload to another computer
l - Use this flag to download file from another computer

Note: use either -l flag or specify file name.

Warning:
Use this tool on your own risk. Some attacks like IP spoofing can be used against you while you're listening for a new connection, to force your computer to download payloads.
