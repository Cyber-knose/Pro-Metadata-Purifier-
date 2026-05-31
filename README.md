# Pro-Metadata-Purifier-
PRO METADATA PURIFIER is a cyber forensics investigation platform tool that enables secure evidence collection, metadata and EXIF analysis, integrity verification, timeline reconstruction, anti-forensics detection, and generation of downloadable PDF forensic reports containing investigation logs and forensic findings.

---
## 🖼️ Project Preview

<p align="center">
  <img src="pro.png" alt="PRO METADATA PURIFIER Interface" width="800">
</p>

## ⚠️ DISCLAIMER - IMPORTANT

**THIS APPLICATION IS STRICTLY FOR EDUCATIONAL PURPOSE.**

> The tools and features provided in this project are designed solely for learning and academic research in the field of digital forensics. The developers and contributors assume NO LIABILITY for any misuse of this software. 
> 
> **USE AT YOUR OWN RISK.** 
> 
> Always ensure you have proper authorization before analyzing any digital evidence. Unauthorized access to computer systems or data may be illegal and is strictly prohibited.

---


📖 Feature Breakdown & Detailed Explanation

1. Dashboard
The central command center that provides investigators with a real-time overview of all active cases, collected evidence, timeline events, and investigation statistics.

Active Case Monitoring: View all ongoing investigations at a glance
Evidence Overview: Track total evidence collected across all cases
Investigation Statistics: Visualize case progress and findings
Quick Actions: Fast access to recent evidence and open cases

2. Evidence Locker
A secure digital repository for storing evidence files such as images, videos, documents, emails, browser artifacts, and audio files while maintaining forensic integrity.

Secure Storage: Upload and store files in an organized, secure environment
File Type Support: Supports images, videos, PDFs, audio, and more
Integrity Preservation: Ensures original files remain unaltered
Evidence Categorization: Organize evidence by type, case, or date

3. Deep Analysis
Performs advanced examination of collected evidence to uncover hidden information, suspicious patterns, metadata correlations, and digital footprints.

Pattern Detection: Identify suspicious activities within files
Data Correlation: Link related evidence across different sources
Hidden Data Discovery: Uncover steganographic content and covert data
Forensic Reconstruction: Rebuild events from fragmented data

4. EXIF Intel
Extracts and analyzes image metadata including device information, GPS coordinates, timestamps, camera details, and editing history.

Device Identification: Identify camera make, model, and serial numbers
GPS Coordinates: Extract location data embedded in images
Timestamp Analysis: Analyze original creation and modification times
Editing History: Detect software used to edit or modify images

5. Integrity / Hash
Generates and verifies cryptographic hash values (MD5, SHA-1, SHA-256) to ensure evidence authenticity and detect any tampering.

Hash Generation: Create unique fingerprints for files (MD5, SHA-1, SHA-256)
Integrity Verification: Check if files have been modified
Tamper Detection: Alert investigators of any evidence tampering
Chain Verification: Verify the integrity of evidence over time

6. Anti-Forensics Detection
Identifies attempts to conceal, alter, delete, or manipulate digital evidence through steganography, metadata wiping, timestamp modification, and other anti-forensic techniques.

Metadata Wiping Detection: Identify cleaned or removed metadata
Timestamp Manipulation: Detect altered file dates and times
Steganography Detection: Identify hidden data within files
Deletion Analysis: Recover evidence of deleted files or data

7. Timeline
Creates a chronological reconstruction of events by correlating file activities, system logs, communications, and evidence timestamps.

Event Correlation: Link events across multiple evidence sources
Temporal Mapping: Visualize events in chronological order
Log Integration: Incorporate system and application logs
Investigation Timeline: Build a complete picture of incidents

8. Geo Intel
Maps and analyzes geographical data extracted from evidence, enabling investigators to track locations, movements, and location-based activities.

Location Mapping: Plot GPS coordinates on interactive maps
Movement Tracking: Analyze travel patterns and locations
Geo-Data Analysis: Correlate multiple location data points
Location Visualization: Visualize evidence locations geographically

9. Document Forensics
Examines documents for hidden metadata, authorship details, modification history, embedded objects, and signs of document tampering.

Metadata Extraction: Extract author, creation, and modification data
Hidden Content: Identify embedded objects or macros
Authorship Analysis: Determine document origin and author
Tamper Detection: Identify signs of document modification


10. Chain of Custody
Maintains a complete audit trail of evidence handling, recording who accessed, modified, or transferred evidence throughout the investigation process.

Access Logging: Track every instance of evidence access
User Identification: Record who handled evidence and when
Modification Tracking: Document any changes to evidence
Audit Trail: Maintain a complete history for legal proceedings


11. Case Management
Allows investigators to create, organize, track, and manage multiple forensic cases efficiently from a centralized interface.

Case Creation: Start new investigations with case details
Case Organization: Organize cases by status, priority, or date
Progress Tracking: Monitor investigation status and milestones
Multi-Case Handling: Manage multiple cases simultaneously


12. Notes
Provides a dedicated workspace for investigators to record observations, findings, conclusions, and case-related documentation.

Investigation Notes:
Document observations and findings
Case Documentation: 
Record conclusions and theories
Collaboration: 
Prepare notes for team sharing
Reporting Support:
Use notes in PDF report generation

📑 PDF Report Generation
The platform automatically generates comprehensive forensic investigation reports in PDF format. Investigators can download detailed reports containing:

📊 Evidence Collection Logs

🖼️ Metadata Analysis Results

📷 EXIF Data Extraction Reports

🔐 File Hash Verification Results (MD5, SHA-1, SHA-256)

⏳ Timeline Investigation Data

⛓️ Chain of Custody Records

🌍 Geo-Location Intelligence Findings

📝 Document Forensics Results

🚨 Anti-Forensics Detection Logs

📝 Investigator Notes and Case Summary
The generated PDF serves as a court-ready forensic report that preserves investigation findings in a structured and professional format for legal, compliance, and incident response purposes.

<p align="justify">
  <img src="more pro.png" alt="PRO METADATA PURIFIER Interface" width="800">
</p>

## 🛠️ Tech Stack

**Languages:** ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript)

**Database:** ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql) ![JDBC](https://img.shields.io/badge/JDBC-CC6699?style=flat&logo=database)

**APIs & Libraries:** ![REST API](https://img.shields.io/badge/REST_API-009688?style=flat) ![JSON](https://img.shields.io/badge/JSON-000000?style=flat) ![iText PDF](https://img.shields.io/badge/iText_PDF-5C8D2E?style=flat)

**Server:** ![Apache Tomcat](https://img.shields.io/badge/Apache_Tomcat-F8C75A?style=flat&logo=apache) ![Servlet](https://img.shields.io/badge/Servlet-FF6F00?style=flat) ![JSP](https://img.shields.io/badge/JSP-BF360C?style=flat)

