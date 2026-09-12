# Case Study 3  Rhino Hunting / Illegal Possession Investigation

**Overview**

This lab investigates a forensic evidence package containing a USB image and network traces to recover and identify rhinoceros images.

**Evidence**
1. RHINOUSB.dd – USB forensic image
2. rhino.log – FTP traffic
3. rhino2.log – HTTP traffic
4. rhino3.log – Executable/network traffic


**Objectives**
-Examine the FAT16 USB filesystem.
-Recover allocated, deleted, and carved images.
-Investigate steganography and hidden files.
-Reconstruct FTP and HTTP transfers.
-Recover and examine the encrypted ZIP archive.
-Perform safe static analysis of the transferred executable.
-Hash and deduplicate recovered images.
-Correlate evidence and build a UTC timeline.
-Determine the total number of unique rhinoceros images.


**Tools**
-Sleuth Kit / Autopsy
-PhotoRec
-Wireshark
-File/hash analysis tools
-Approved steganography tools
-Static malware-analysis tools


**Evidence Handling**
All original evidence remains unmodified. Analysis is performed on verified working copies inside the protected ICDFA laboratory environment.

Sensitive recovered images, credentials, forensic images, archives, and executables are not stored in this GitHub repository.
