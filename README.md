# 🧩 Task 7: Suspicious Browser Extensions Review

## 🔍 Overview
This task involved auditing installed Chrome extensions to identify and remove those that could pose security or privacy risks. The goal was to ensure a safer browsing experience by eliminating high-risk or unnecessary add-ons.

---

## ✅ Steps Performed
1. Opened "chrome://extensions/" to review all installed extensions.
2. Inspected each extension’s permissions, publisher, and functionality.
3. Identified extensions with excessive permissions or unclear origins.
4. Removed the suspicious or unused extensions.
5. Restarted the browser to observe performance improvements.
6. Documented each step with notes and screenshots.
7. Researched how malicious extensions can harm users through data theft, stealth, and persistence techniques.

---

## 🗑️ Extensions Removed
| Extension      | Risk Level | Reason for Removal |
|----------------|------------|---------------------|
| **Hola VPN**   | 🔴 High     | Known for privacy abuse and traffic rerouting through user devices. |
| **SuperTab**   | 🟠 Medium   | Unknown developer, broad permissions, not essential. |
| **Honey**      | 🟠 Medium   | Tracks shopping behavior; removed for privacy preference. |

---

## ✅ Extensions Kept
| Extension             | Reason |
|---------------------- |--------|
| **AdGuard AdBlocker** | Trusted ad blocker with minimal, necessary permissions. |
| **Privacy Badger**    | Developed by EFF; blocks trackers without tracking the user. |

---

## 📸 Screenshots
- "before_removal.png" – Shows all extensions before cleanup.
- "after_removal.png" – Final extension list after removals.
- Additional screenshots of individual extension permission details.

---

## browser-extension-review/
├── README.md
├── suspicious_extensions_review.txt
├── extensions_to_remove.txt
├── post_removal_summary_and_research.txt
├── screenshots/
│   ├── before_removal.png
│   ├── after_removal.png
│   ├── hola_vpn_details.png
│   ├── supertab_details.png
│   ├── honey_details.png
│   ├── adguard_details.png
│   └── privacy_badger_details.png


## 📁 Files Included
- "suspicious_extensions_review.txt" – Detailed extension analysis.
- "extensions_to_remove.txt" – List of removed extensions and reasons.
- "post_removal_summary_and_research.txt" – Performance notes + research on malicious extensions.
- "screenshots/" – All related visual documentation.

---

## 🔐 Key Takeaways
- Extensions can have deep access to browser data; always review permissions.
- Remove what you don’t use or don’t recognize.
- Malicious extensions can steal data, track behavior, or remain hidden through stealth and persistence.
- Browser hygiene is a simple but powerful step toward better cybersecurity.

---

## 🏁 Conclusion
Through this task, I gained hands-on experience in identifying security risks associated with browser extensions. By carefully reviewing and removing unnecessary or potentially harmful add-ons, I improved both browser performance and personal privacy. This exercise highlighted the importance of regularly auditing extensions and being mindful of the permissions we grant. Staying secure online starts with small but essential steps like managing what runs inside our browser. 🛡️✨
