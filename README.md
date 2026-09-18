# CIP-B105-CS3 – Module 3: Memory Forensics  
**Illegal File Transferring Investigation**

**Student:** Mary Ekwughaonu  
**Registration Number:** c11.dfit2617295  
**Course:** ICDFA – Second Semester  
**Module:** 3 – Memory Forensics (CIP-B105-CS3)  
**Submission Date:** 18 September 2026

---

## Case Overview
A Windows 7 memory image (`memdumpWin7.mem`) was examined to determine whether a suspect downloaded a file and transferred it to removable storage.  

**Key Finding:**  
On 2019-01-06 the interactive user **IEUser** attached a USB device (General UDisk) assigned drive letter **F:**, viewed the Downloads folder, and successfully executed:

```cmd
copy secret_file.docx F:

├── Reports/                  # All lesson reports + main Module 3 report
├── Plugin_Output/            # Raw Volatility plugin results
├── Hashes/                   # SHA-256 of original and working copy
├── Notes/                    # Environment and analysis notes
├── Screenshots/              # Supporting screenshots
└── README.md
