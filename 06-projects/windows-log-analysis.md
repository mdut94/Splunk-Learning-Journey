# 📊 Windows Log Analysis (Mini Project)

**Date:** 2025-06-13  
**Objective:** Ingest and analyze local Windows Event Logs using Splunk

## 💾 Data Source
- Local machine Event Logs
- Source: `C:\Windows\System32\winevt\Logs`

## 🛠️ Steps
1. Configured data input via Splunk Web
2. Created index: `windows_logs`
3. Used sourcetype: `WinEventLog:Security`

## 🔍 Useful Queries
```spl
index=windows_logs sourcetype="WinEventLog:Security" EventCode=4625
| stats count by user, host, _time
```

## 📈 Insights
- Found repeated login failures from a test account
- Identified missing log categories

## 📸 Screenshot
_Add screenshot path here_

✅ **Skill tags:** `#SIEM`, `#SPL`, `#WindowsSecurity`, `#DetectionEngineering`
