# 🚀 Getting Started with Splunk

**Date:** 2025-06-12

## ✅ Installed Version
- Splunk Enterprise [version number]
- OS: [Windows/Linux/Mac]

## 🖥️ Setup Notes
- Installation was [smooth / encountered issues]
- UI exploration: Navigated to Settings > Data Inputs

## 📥 First Data Ingested
- Source: [e.g., Windows Security Logs]
- Index created: `windows_logs`
- Sourcetype: `WinEventLog:Security`

## 🔍 First Search
```spl
index=* | stats count by sourcetype
```

## 🧠 Reflections
- Splunk’s UI is easy to use after orientation.
- Excited to explore SPL more.
