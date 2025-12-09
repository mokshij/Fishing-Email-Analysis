Phishing Email Analysis – Cybersecurity Internship Task 2

This repository contains my completed work for Task 2: Phishing Email Analysis, assigned during my Cybersecurity Internship.
The objective of this task is to analyze a suspicious email (Amazon Gift Card Scam) and identify phishing indicators using email header analysis and common phishing detection techniques.

📌 Task Overview

Task Name: Analyze a Phishing Email Sample
Goal: Identify phishing characteristics in a suspicious email by examining the sender, header details, message body, and embedded links.
Tools Used:

MXToolbox Header Analyzer

Email Client (for viewing headers)

WHOIS Lookup

Browser Link Hover Inspection

📨 Phishing Email Summary

The suspicious email claimed that the receiver had won an Amazon Gift Card and needed to click a link to claim the reward.
The email contained a spoofed sender address, mismatched domains, authentication failures, and classic social engineering tactics.

🔍 Header Analysis Summary

Key findings from MXToolbox:

DKIM: permerror – No key found for signature

header.i Domain: questionprov717059741207719264.com (not related to Amazon)

Return-Path: Return@tvportal.tiscali.it (fake sender domain)

SPF: Passed only for tiscali.it, not Amazon

Client IP: 45.130.201.129 – Hosting provider, not Amazon

ARC/DomainKey: Missing or improperly configured

These inconsistencies strongly indicate spoofing and unauthorized sending servers.

⚠️ Phishing Indicators Identified

Fake sender domain (tiscali.it instead of amazon.com)

DKIM authentication failed

Suspicious IP address not linked to Amazon

Misleading subject claiming a “free gift card”

Urgent call-to-action (“claim immediately”)

Generic greeting instead of personalized name

Hover link does not lead to an Amazon domain

Social engineering techniques used to trick the user

🛡️ Conclusion

This email is a high-risk phishing attempt designed to steal user credentials or personal information.
The email headers, sender information, and message content all show clear signs of malicious intent.
