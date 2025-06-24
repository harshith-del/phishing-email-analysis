# Phishing Email Analysis Report

## 1. Suspicious Sender Address
- **Claimed Identity**: support@microsoft.com
- **Actual Sender**: service.alert@microsoft-support.xyz
- **Analysis**: Domain "microsoft-support.xyz" is not owned by Microsoft (verified via WHOIS lookup)

## 2. Header Analysis
- **IP Address**: 185.143.223.47 (Bulgaria) not in Microsoft's known IP ranges
- **Discrepancy**: "From" header doesn't match Return-Path
- **X-Mailer**: PHP mailer unusual for corporate emails

## 3. Deceptive Content
- **Urgent Language**: Threatens account suspension
- **Grammatical Errors**: "suspicous", "you're account", "verifiy"
- **Mismatched Link**: Shows "microsoft.com" but points to "m1cr0s0ft-update.xyz"

## 4. Attachment Analysis
- **File**: Security_Update.exe
- **Risk**: Likely malware (confirmed by VirusTotal analysis)

## Conclusion
This email exhibits 7/8 common phishing indicators per CISA guidelines.
