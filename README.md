<div align="center">

# 📧 Email Attachment Organizer

### Professional Edition v1.0

[![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?logo=windows)](https://github.com/cortexfile/EmailAttachmentOrganizer/releases)
[![License](https://img.shields.io/badge/License-Commercial-green)](LICENSE.txt)
[![Python](https://img.shields.io/badge/Python-3.10+-yellow?logo=python)](https://python.org)

**Automate your document workflow securely. Save hours of manual downloading.**

[⬇️ Download Latest Release](https://github.com/cortexfile/EmailAttachmentOrganizer/releases/latest) | [📖 User Guide](USER_GUIDE_EN.html) | [📧 Support](mailto:cortexfile.fm@gmail.com)

</div>

---

## 🚀 Key Features

*   **Background Auto-Processing**: Set it and forget it. The application monitors your inbox in the background and processes new emails as they arrive.
*   **Intelligent Filtering**: Don't download everything. Filter precisely by file type (PDFs, Excel, Images), sender domain, specific dates, or subject lines.
*   **Smart Organization**: Automatically sort downloaded files into folders based on date, sender, or file type to keep your workspace clutter-free.
*   **Built-in OCR Engine**: Includes optical character recognition to detect text within scanned PDFs and images (requires Tesseract).
*   **Privacy-First Design**: Zero cloud dependencies. All processing happens on your machine.
*   **Visual Dashboard**: Monitor activity with real-time charts and detailed processing logs.
*   **Global Language Support**: Native interface support for English, Arabic (RTL), French, German, and Spanish.

---

## 📸 Screenshots

<details>
<summary><b>🖼️ Click to expand screenshots gallery</b></summary>

### Dashboard
![Dashboard](screenshots/12-dashboard.png)

### Setup Wizard
| Connect Your Account | Setup Complete |
|:---:|:---:|
| ![Setup Connect](screenshots/01-setup-wizard-connect.png) | ![Setup Complete](screenshots/02-setup-wizard-complete.png) |

### Main Interface
| Connection Tab | Processing Tab |
|:---:|:---:|
| ![Connection](screenshots/03-connection-tab.png) | ![Processing](screenshots/04-processing-tab.png) |

### Advanced Features
| Archive Search | Rules Editor |
|:---:|:---:|
| ![Archive Search](screenshots/05-archive-search.png) | ![Rules Editor](screenshots/06-rules-editor.png) |

| Subscriptions Manager | History Log |
|:---:|:---:|
| ![Subscriptions](screenshots/07-subscriptions.png) | ![History](screenshots/08-history.png) |

### Settings & Help
| Settings | About |
|:---:|:---:|
| ![Settings](screenshots/09-settings.png) | ![About](screenshots/10-about.png) |

### Help Panel
![Help Panel](screenshots/11-help-panel.png)

</details>

---

## 🛡️ Security & Privacy Architecture

We understand that your emails contain sensitive data. Our security model is simple: **We don't see your data.**

1.  **Local Execution**: The software runs entirely on your local hardware. No file is ever uploaded to our servers.
2.  **Encrypted Credentials**: Your email App Passwords are encrypted at rest using industry-standard AES-256 encryption.
3.  **Source Transparency**: The application operates transparently, providing full logs of every action taken.
4.  **No Tracking**: We do not collect usage telemetry or personal information.

---

## 💻 System Requirements

*   **Operating System**: Windows 10 or Windows 11 (64-bit recommended).
*   **Processor**: Modern dual-core processor or better.
*   **Memory**: 4GB RAM minimum (8GB recommended for OCR tasks).
*   **Disk Space**: 200MB for installation (+ space for downloaded files).
*   **Connectivity**: Active internet connection for IMAP server access.
*   **Optional**: Tesseract OCR installed (for text recognition features).

---

## 📦 Installation & First Run

1.  **Install**: Run the `EmailAttachmentOrganizer_Setup.exe` installer or unzip the portable package to a folder of your choice.
2.  **Launch**: Open `EmailAttachmentOrganizer.exe`.
3.  **Connect**:
    *   Enter your Email Address.
    *   Enter your **IMAP App Password** (See *Configuration* below).
    *   Select your provider (Gmail, Outlook, Yahoo, or Custom IMAP).
4.  **Configure**: Navigate to the **Settings** tab to select your destination folder and filter rules.
5.  **Run**: Click **Start Processing** on the dashboard.

> **Important**: This application requires an **App Password**. You cannot use your standard login password if you have 2FA enabled (which is standard for Gmail/Outlook). You must generate a specific App Password in your email provider's security settings.

---

## 💡 Usage Tips

*   **Start Small**: When running for the first time, use the "Date Filtering" option to process only the last 7 days. This helps you verify your rules before scanning years of history.
*   **OCR Performance**: OCR is resource-intensive. detailed logs. If you are processing thousands of files, consider disabling OCR unless specifically needed for image-based PDFs.
*   **Folder Structure**: Use the "Group by Sender" feature in settings. It creates a dedicated folder for each client or contact, making it much easier to find specific documents later.

---

## ❓ Frequently Asked Questions

**Q: Does this safeguard my emails? Will it delete them?**
A: The application works in **Read-Only** mode by default. It copies attachments to your computer. It does *not* delete emails from your server unless you explicitly enable a post-processing deletion rule (if available in your version).

**Q: Can I use this with a corporate Exchange server?**
A: Yes, provided your IT administrator has enabled IMAP access. You may need to ask them for the specific IMAP host and port settings.

**Q: Where are my files saved?**
A: You choose the destination! By default, it creates a `Downloads` folder inside the application directory, but you can change this to any path (e.g., your Desktop or a network drive) in the Settings tab.

**Q: Why isn't my password working?**
A: 99% of login failures are due to using a regular password instead of an **App Password**. Major providers block third-party add-ons from using standard passwords. Please check our "Connection Help" guide.

---

## ⚖️ Limitations & Disclaimer

*   **Compliance**: You are responsible for ensuring your use of this software complies with the Terms of Service of your email provider.
*   **Fair Use**: Rapidly downloading thousands of emails may temporarily trigger rate limits from your provider. We recommend processing in reasonable batches.
*   **File Ownership**: You must have the legal right to access and download the content from the configured accounts.

---

## ⚖️ License

**Commercial Use**: This software is licensed, not sold.
Use of this application is governed by the **End User License Agreement (EULA)** included with this installation. By using the software, you agree to these legal terms.

---

## 📞 Support and Contact

Need help? Found a bug?
Contact our support team at: **cortexfile.fm@gmail.com**

**Copyright © 2026 CortexFile. All Rights Reserved.**
