# ThreatView Alert Rules

These are basic rules to raise alerts on suspicious behavior.

## 🔐 Rule 1: Brute Force Login Attempt
If a user fails to log in 3+ times in under 1 minute → trigger "Brute Force Alert"

## 📁 Rule 2: Suspicious File Access
If a user logs in and immediately opens a sensitive file → trigger "Suspicious File Access Alert"

## 🚩 Rule 3: After-Hours Login
If login occurs between 12:00 AM and 5:00 AM → trigger "Unusual Login Time Alert"