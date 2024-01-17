# Microsoft-Azure-Observe ICMP Traffic (Video below)
**Part 2 (Create our Resources)**

5. Use Remote Desktop to connect to your Windows 10 Virtual Machine

6. Within your Windows 10 Virtual Machine, Install Wireshark
   
7. Open Wireshark and filter for ICMP traffic only

8. Retrieve the private IP address of the Ubuntu VM and attempt to ping it from within the Windows 10 VM
   
   a. Observe ping requests and replies within WireShark
   
9. From The Windows 10 VM, open command line or PowerShell and attempt to ping a public website (such as www.google.com) and observe the traffic in WireShark

10. Initiate a perpetual/non-stop ping from your Windows 10 VM to your Ubuntu VM

       a. Open the Network Security Group your Ubuntu VM is using and disable incoming (inbound) ICMP traffic

       b. Back in the Windows 10 VM, observe the ICMP traffic in WireShark and the command line Ping activity

       c. Re-enable ICMP traffic for the Network Security Group your Ubuntu VM is using
   
       d. Back in the Windows 10 VM, observe the ICMP traffic in WireShark and the command line Ping activity (should start working)
   
       e. Stop the ping activity

   

https://github.com/Searcher121978/Microsoft-Azure-Virtual-Machine-Resource-Group/assets/124515149/3392107f-8673-4c2c-8043-95b1178a6d6b
