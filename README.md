# 4MEngineeringDescription
A Readme File explaining how the site works and what I did to make it run

## Purpose
My client 4MEngineers.com asked me to to develop, test, and deploy a website efficiently while maintaining a clean workflow between local and hosted files.

## Tech Stack
- VS Code
- HTML/CSS/JS/PHP (vanilla or frameworks)
- GoDaddy cPanel (domain and hosting)
- FileZilla (SFTP file transfer)
- XAMPP (local Apache server for testing)

## 🛠️ Tools Overview

### **1. VS Code**
- **Purpose:** Code editor for writing and editing HTML, CSS, JS, and PHP files.
- **Usage:** Edit files locally before pushing changes to the live server.
- **Why:** Provides syntax highlighting, extension support, and Git integration for efficient coding.

---

### **2. XAMPP**
- **Purpose:** Creates a **local server environment** to run and test PHP files on my computer.
- **Key components used:**
  - **Apache:** Web server to process PHP files and serve them to localhost.
  - **PHP:** Server-side scripting language used for dynamic pages (e.g. password protection scripts).
- **Relevant folder:**
  - **`htdocs`:** Equivalent to GoDaddy’s `public_html`. All local website files must reside here for testing.

- **Why:** Browsers cannot run PHP directly. Apache interprets PHP just like GoDaddy’s server does, ensuring reliable local testing.

---

### **3. FileZilla FTP Client**
- **Purpose:** Securely transfers files between my local machine and GoDaddy hosting.
- **Usage:**
  - Download: Create local backups or sync current live files for editing.
  - Upload: Deploy tested changes to the live website.
- **Why:** Ensures seamless and secure file transfers (using FTPS for encryption).

---

### **4. GoDaddy Hosting / cPanel**
- **Purpose:** Live hosting environment for the website.
- **Key items:**
  - **public_html:** The root folder for all website files visible on the internet.
  - **FTP Accounts:** Credentials to connect via FileZilla.
  - **phpMyAdmin:** Online database management (if using MySQL).

---

## 📂 Folder Structure

### **On GoDaddy (`public_html`):**

