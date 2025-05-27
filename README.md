# 📧 Phishing Email Analysis Report

## 📂 Task Overview

This task involves identifying phishing indicators in a suspicious email. It includes email address analysis, header examination, link inspection, and spotting social engineering techniques.

---

## 📨 Sample Email Used

See the file: `sample-email.txt`

---

## 🔍 Phishing Indicators Found

### 1. **Sender Spoofing**

* Display name: **Amazon Support**
* Actual email: `support@amazzon.com` (misspelled domain)
* Legit Amazon emails come from `@amazon.com`

### 2. **Suspicious Link**

* Displayed link: `https://amazzon-security-check.com/login`
* Not a valid Amazon domain; designed to look similar
* Likely a phishing website to steal credentials

### 3. **Urgent Language**

* "Your account has been locked"
* "Failure to do so within 24 hours will result in permanent suspension"
* These phrases create pressure and fear

### 4. **Spelling/Grammar Errors**

* "unusual activity in your account" — vague and generic
* Common trick used in phishing to scare all users

---

## 🛠 Tools Used

* Gmail + “Show original” (to view headers)
* [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
* Hover inspection for links
* Manual analysis for tone and language

---

## ✅ Summary

This email displays **clear phishing traits**:

* Spoofed email address
* Fake login link
* Urgent tone
* Minor language issues

**Conclusion**: This is a phishing attempt and should be reported and deleted immediately.

---

## 📎 Key Concepts

* Phishing
* Email Spoofing
* Header Analysis
* Social Engineering
* Threat Detection
