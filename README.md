# SysTools IMAP Migration Tool 🚀

![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS-blue)
![License](https://img.shields.io/badge/License-Demo%20%7C%20Commercial-brightgreen)
![Version](https://img.shields.io/badge/Version-7.4-orange)

**Universal, secure, and automated email migration between any IMAP-enabled servers.**

The **SysTools IMAP Migration Tool** is an enterprise-grade utility designed to safely move bulk email accounts between different hosting providers without data loss. Whether you are transitioning to Office 365, Google Workspace, or migrating between custom cPanel servers, this tool ensures all emails, attachments, folder hierarchies, and metadata are seamlessly transferred. 

---

## ✨ Core Features

* **Universal IMAP Support:** Migrate to and from any IMAP-enabled server (Gmail, Yahoo, Outlook, Zoho, Rackspace, Fastmail, custom domains, etc.).
* **Zero-Knowledge Security:** The software runs 100% locally on your machine. Data is transferred directly from source to destination without being cached or stored on third-party servers, ensuring full GDPR compliance.
* **Bulk Account Processing:** Upload a CSV file to map multiple source and destination accounts and migrate them concurrently.
* **Smart Delta Migration:** Eliminate duplicates. If you need to re-run the tool, the Delta feature automatically detects and transfers only the newly arrived emails.
* **VIP User Prioritization:** Use the "Star" feature to prioritize specific accounts (like the CEO or IT Admin) so they are processed first in the migration queue.
* **Pre-Migration Health Check:** Automatically validates credentials and server permissions before the transfer begins, preventing mid-migration authentication failures.
* **Granular Date Filtering:** Apply a specific date range to leave behind old clutter and migrate only the data you actually need.
* **Intact Folder Hierarchy & Metadata:** Perfectly preserves the original folder structure (Inbox, Sent, Custom Labels), attachments, inline images, and the Read/Unread status of messages.

---

## 💻 System Requirements

### Windows
* **OS:** Windows 11, 10, 8, 7 & Windows Server 2019, 2016, 2012
* **Processor:** Minimum 8-core Processor recommended
* **RAM:** 8 GB recommended for optimal concurrent processing
* **Disk Space:** 500 MB for installation, plus a minimum of 20 GB free space to process data.
* **Prerequisites:** Microsoft .NET framework v4.8.0 and VC++ Redistributable.

### macOS
* **OS:** macOS 11.0 (Big Sur) through macOS 15.0 (Sequoia)
* **Processor:** Intel processors or Apple Silicon (M1/M2/M3/M4)
* **RAM:** 8 GB recommended
* **Disk Space:** 1 GB for installation, plus 5 GB minimum free space.

---

## 🛠️ Quick Start Guide

1. **Enable IMAP & App Passwords:** Ensure IMAP is enabled on both the source and destination servers. Generate App Passwords for the accounts (standard passwords are not supported due to modern security policies).
2. **Launch & Filter:** Open the software and select your desired Date Filter (optional).
3. **Configure Source:** Select your source IMAP provider from the dropdown (or choose "Other" and enter your server URL and Port). Validate the connection.
4. **Configure Destination:** Select your destination IMAP provider, enter the details, and validate.
5. **Map Users:** Add users manually or upload a CSV file to map multiple source accounts to their new destination addresses.
6. **Migrate:** Review the user list, assign priority if needed, and click **Start Migration**. 

A detailed, live-updating CSV report will be generated as the migration processes.

---

## 💳 Licensing: Free vs. Paid

| Feature | Free Demo Version | Full Version |
| :--- | :--- | :--- |
| **Migrate Emails** | First 100 Emails per folder | Unlimited |
| **Universal IMAP Support** | ✅ | ✅ |
| **Folder Hierarchy Maintenance** | ✅ | ✅ |
| **Date-Range Filtering** | ✅ | ✅ |
| **Delta Migration** | ✅ | ✅ |
| **VIP User Priority** | ✅ | ✅ |
| **Cost** | **FREE** | **Starts at $25 (5 Users)** |

> **Note:** The Demo version is perfect for running a Proof of Concept (PoC) to test connection parameters and verify the folder structure on the destination server before purchasing.

---

## 🔗 Useful Links

* **Official Website:** [SysTools IMAP Migration Tool](https://www.systoolsgroup.com/imap/migration/)
* **Support & Contact:** [SysTools Support Center](https://www.systoolsgroup.com/support.html)
* **Comprehensive Guides:** [How to Transfer Email Data](https://www.systoolsgroup.com/how-to/transfer-email-data-to-another-account/)

---
*Developed with ❤️ by the team at [SysTools Software Pvt. Ltd.](https://www.systoolsgroup.com/)*
