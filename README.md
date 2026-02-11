# Technical-Support-Fundamentals
Technical Support Fundamentals
Name: Esther Khumalo
# System Troubleshooting Report

## 1. System Information

Operating System: Windows 10 Pro  
System Type: 64-bit  
Processor: Intel Core i5  
RAM: 8GB  

<img width="1474" height="752" alt="P1" src="https://github.com/user-attachments/assets/337d51bb-a443-4fa4-8fd4-8ed29abf7ca9" />


---

## 2. Network Verification

Command Used:
ipconfig

Findings:
- IPv4 Address: 192.168.x.x
- Default Gateway: 192.168.x.1

Internet Test:
ping google.com

Result:
Successful replies received.



---

## 3. Simulated Issue

Issue Simulated:
Internet disconnection by disabling network adapter.
<img width="949" height="518" alt="P2" src="https://github.com/user-attachments/assets/83cb32a1-a20a-4d33-9964-f33b9b6c0e78" />

Steps Taken:
1. Opened Network Connections (ncpa.cpl)
2. Disabled Wi-Fi adapter
3. Tested internet connectivity

Result:
Ping request failed. No internet connection.


<img width="965" height="517" alt="P3" src="https://github.com/user-attachments/assets/5ce2e3b6-fc41-47b5-9576-fbd4b198e385" />

---

## 4. Troubleshooting Steps

Steps Taken to Resolve:
<img width="1127" height="297" alt="P4" src="https://github.com/user-attachments/assets/4b1f1ff1-8839-45cc-bf15-ebc8cce7604d" />

1. Enabled network adapter
2. Retested connectivity using ping google.com

Result:
Internet successfully restored.



---

## 5. Conclusion

<img width="1122" height="217" alt="P5" src="https://github.com/user-attachments/assets/1b59a0df-5210-4f74-a9d0-edcfe303ddf5" />

The issue was successfully simulated and resolved by re-enabling the network adapter.  
Basic troubleshooting techniques such as checking network status and using ping were applied.
