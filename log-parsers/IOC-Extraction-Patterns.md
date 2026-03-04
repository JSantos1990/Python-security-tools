# 🎯 IOC Extraction Patterns

Common patterns to extract Indicators of Compromise from logs/text.

---

## 📘 1. IOC Types

- IPv4: `\b\d{1,3}(\.\d{1,3}){3}\b`  
- Domain: `[a-z0-9.-]+\.[a-z]{2,}`  
- URL: `https?://[^\s]+`  
- MD5: `\b[a-fA-F0-9]{32}\b`  
- SHA256: `\b[a-fA-F0-9]{64}\b`

📸 Placeholder: regex match output.

---

## 🧭 2. Tips

- validate matches  
- normalize case  
- deduplicate results

---
