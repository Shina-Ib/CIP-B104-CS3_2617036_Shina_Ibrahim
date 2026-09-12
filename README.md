# Case Study 3  Rhino Hunting / Illegal Possession Investigation

**Overview**

This lab investigates a forensic evidence package containing a USB image and network traces to recover and identify rhinoceros images.

**Evidence**
1. RHINOUSB.dd – USB forensic image
2. rhino.log – FTP traffic
3. rhino2.log – HTTP traffic
4. rhino3.log – Executable/network traffic


**Objectives**
1. Examine the FAT16 USB filesystem.
2. Recover allocated, deleted, and carved images.
3. Investigate steganography and hidden files.
4. Reconstruct FTP and HTTP transfers.
5. Recover and examine the encrypted ZIP archive.
6. Perform safe static analysis of the transferred executable.
7. Hash and deduplicate recovered images.
8. Correlate evidence and build a UTC timeline.
9. Determine the total number of unique rhinoceros images.


**Tools**
1. Sleuth Kit / Autopsy
2. PhotoRec
3. Wireshark
4. File/hash analysis tools
5. Approved steganography tools
6. Static malware-analysis tools


**Evidence Handling**
All original evidence remains unmodified. Analysis is performed on verified working copies inside the protected ICDFA laboratory environment.

Sensitive recovered images, credentials, forensic images, archives, and executables are not stored in this GitHub repository.
