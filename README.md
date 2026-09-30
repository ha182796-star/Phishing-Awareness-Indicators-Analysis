# Phishing Email Examples for Security Awareness

![Cyber Security](https://img.shields.io/badge/Domain-Cyber%20Security-blue.svg)
![Type](https://img.shields.io/badge/Report-Educational%20Simulation-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

## 📌 Project Overview
Phishing remains one of the primary entry points for threat actors aiming to compromise organizational networks. Because phishing targets human psychology rather than technical controls, raising security awareness is vital.

This repository contains an educational report and analysis evaluating two realistic, simulated phishing email scenarios built around distinct social engineering vectors:
1. **Urgency & Fear**: Fake IT Help Desk Password Expiration.
2. **Curiosity & Reward**: Fake Customer Gift Card Offer.

Each scenario includes the full email template, social engineering mechanics, red flag indicators, and actionable guidance on how to detect the attack.

---

## ⚠️ Educational Disclaimer
The phishing scenarios described in this repository are fictional simulations created strictly for educational, security awareness, and training purposes. They utilize fictitious names, companies, and domains. These templates **must not** be used for malicious activities, unauthorized testing, or spamming.

---

## 🔍 Case Studies & Indicator Analysis

### Scenario 1: Fake IT Help Desk Email
* **Target Audience**: Corporate employees with network/email credentials.
* **Social Engineering Vector**: Urgency and Fear.
* **Subject Line**: `Urgent: Immediate Action Required - Your Password Expires Today`
* **Sender**: `IT Help Desk <ithelpdesk@corp-secure-support.com>`

> **Simulated Email Content:**
> **Dear Employee,**  
> Our system indicates that your network password will expire in the next 3 hours. To avoid losing access to your email, shared drives, and internal applications, you must reset your password immediately using the secure link below).  
> 
> `[Reset My Password Now]`  
> 
> If you do not update your credentials before the deadline, your account will be locked and you will need to submit a help desk ticket, which may take up to 5 business days to resolve.  
> *This is an automated message. Please do not reply.*

#### Phishing Indicators & Red Flags:
* **Artificial Time Pressure**: A 3-hour deadline induces panic to bypass critical reasoning.
* **Generic Greeting**: Addressed as "Dear Employee" rather than the recipient's name.
* **Mismatched Domain**: Sent from `corp-secure-support.com` instead of the official internal company domain.
* **Exaggerated Consequences**: Threatens a 5-day lockout to make clicking the link feel like the only safe option.
* **"Do Not Reply" Instruction**: Prevents verification through the same communication channel.
* **Single Call to Action**: Forces the recipient through an unverified link rather than directing them to a secure, known portal.

---

### Scenario 2: Fake Gift Card Offer
* **Target Audience**: General consumers (mass untargeted campaign).
* **Social Engineering Vector**: Curiosity and Reward.
* **Subject Line**: `You've Won! Claim Your Free $100 Gift Card Today`
* **Sender**: `Customer Rewards <rewards@shopper-perks-bonus.com>`

> **Simulated Email Content:**
> **Congratulations!**  
> Your email has been selected to receive a FREE $100 gift card as a thank-you for being a loyal customer. This exclusive reward is only available to the first 100 people who respond.  
> 
> To claim your gift card, click the link below and complete a short verification form with your name, address, and payment details for shipping confirmation.  
> 
> `[Claim Your Free Gift Card 🎉]` 
> *Hurry, this offer expires in 60 minutes!*

#### Phishing Indicators & Red Flags:
* **Unsolicited Reward**: Unrealistic prize without prior participation or purchase history.
* **Artificial Scarcity & Urgency**: "First 100 people" and "60-minute expiration" prevent rational evaluation.
* **Sensitive Data Harvesting**: Requests payment details disguised as "shipping verification.
* **Emotional Language**: Emojis and celebratory tone trigger excitement over scrutiny.
* **Unrelated Sender Domain**: Address bears no connection to a recognizable organization.

---

## 🛡️ Key Detection Strategies

| Indicator | Legitimate Email | Phishing Email |
| :--- | :--- | :--- |
| **Sender Domain** | Matches the official company/brand domain. | Uses lookalike or completely unrelated domains. |
| **Salutation** | Personalized with full or official account name. | Generic terms ("Dear Employee", "Valued Customer"). |
| **Time Frame** | Standard operational notices with reasonable windows. | Extreme urgency (e.g., 60 minutes, 3 hours). |
| **Action Route** | Directs user to log in independently via known portal. | Forces navigation through a single embedded hyperlink(end_span). |
| **Data Requested** | Standard workflows; never asks for payment for free gifts). | Requests credentials, personal info, or payment details |

---

## 👤 Author & Acknowledgments

* **Author**: Hasnain Ali
* **Program**: GLAXIT Internship Program — Advanced Cyber Security
* **Supervisor**: Sir Saifullah
* **Submission Date**: August 9, 2026
