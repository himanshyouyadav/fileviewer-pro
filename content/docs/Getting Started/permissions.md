---
title: "Permissions"
description: "Understand the permissions required for FileViewer Pro and how to grant them securely."
summary: ""
date: 2023-11-24T10:00:00+02:00
lastmod: 2023-11-24T10:00:00+02:00
draft: false
weight: 820
toc: true
seo:
  title: "FileViewer Pro Permissions Guide"
  description: "Learn about the permissions needed for FileViewer Pro to function and how they are securely managed."
  canonical: ""
  robots: ""
---

**FileViewer Pro** requires specific permissions to access and display files within Google Sheets. Here's a breakdown of what permissions are needed and why:

### Permissions Breakdown

1. **Google Drive Access:**
   - **Purpose:** Allows the add-on to fetch files from your Google Drive for viewing purposes.
   - **Usage:** Access is limited to files you select explicitly within the add-on interface.

2. **Manage Google Sheets Add-Ons:**
   - **Purpose:** Enables integration with Google Sheets for seamless operation.
   - **Usage:** Used only to launch and render the modal window for file viewing.

3. **Public Link Usage:**
   - **Purpose:** Fetches files from public links provided by the user.
   - **Usage:** Files are retrieved temporarily for rendering and are not stored.

### Granting Permissions

- During installation, you’ll see a permissions dialog. Review the permissions and click “Allow” to proceed.

### Managing Permissions

- To revoke or manage permissions:
  1. Visit [Google Account Permissions](https://myaccount.google.com/permissions).
  2. Locate “FileViewer Pro” in the list of connected apps.
  3. Click “Remove Access” if you wish to stop using the add-on.

**Note:** We prioritize your privacy and do not store or share your files or data. Permissions are used strictly to provide the intended functionality.

---

For any questions about permissions, feel free to [contact us](#).
