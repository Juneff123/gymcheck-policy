---
layout: default
title: GymCheck — privacy-policy-en
permalink: /privacy-policy-en/
---

# GymCheck Privacy Policy

**Effective Date**: May 4, 2026
**Last Updated**: May 4, 2026

GymCheck ("the Service", "we", "us", "our") respects your privacy and is committed to protecting your personal information in compliance with applicable data protection laws, including the GDPR, CCPA, and South Korea's Personal Information Protection Act (PIPA).

---

## 1. Information We Collect

### 1.1 Account Information
| Item | Method | Required |
|---|---|---|
| Email address | Provided during email sign-up | Required |
| Password (encrypted/hashed) | Provided during email sign-up | Required |
| Name, email (provided by Apple) | Automatically collected via Sign in with Apple | Optional |

### 1.2 Service Usage Data (Auto-Collected)
- Workout logs (date, body part)
- InBody composition records (weight, skeletal muscle mass, body fat percentage, and other measurements from your InBody result sheets)
- InBody result sheet photos (stored only on your device, optional)
- Profile information you set (display name, training start date, preferred language)

### 1.3 Device Permissions
| Permission | Purpose | If Declined |
|---|---|---|
| Camera | Capture InBody result sheets | Only photo capture is unavailable; other features work normally |
| Photo Library (Read) | Import InBody result sheet photos | Only photo import is unavailable |
| Photo Library (Write) | Save shareable workout cards as images | Only card saving is unavailable |

---

## 2. How We Use Your Information

We use collected information solely for the following purposes:
1. User identification and authentication
2. Storing and retrieving your workout and body composition records
3. Synchronizing data across your devices
4. Generating statistical analysis screens
5. Sending essential service-related notices

---

## 3. Data Retention

- We retain your information **from sign-up until you delete your account**.
- When you use the **Delete Account** feature in the app, the following are immediately deleted:
  - Firebase Authentication account info (email, auth tokens)
  - All workout records and InBody records stored in Cloud Firestore
  - Local on-device data (when the app is uninstalled)
- Where retention is required by law, the data is stored separately for the legally mandated period only.

---

## 4. Sharing With Third Parties

We do **not** sell, rent, or share your personal information with third parties for marketing purposes. Limited sharing occurs only:
1. With your explicit consent
2. As required by law (e.g., valid legal requests from authorities)

---

## 5. Service Providers (Sub-Processors)

To operate the service, we use the following service providers:

| Provider | Purpose | Data Shared |
|---|---|---|
| Google LLC (Firebase) | Authentication, database (Cloud Firestore), hosting | Email, auth credentials, workout logs, InBody records |
| Google LLC (AdMob) | Ad serving and measurement | Advertising identifier, approximate location (IP), device info |
| Google LLC (Vertex AI in Firebase / Gemini) | Analysis of InBody result sheet photos | Photos you upload (transient, not stored) |
| Apple Inc. (StoreKit) | In-app subscription billing (ad removal) | Payment data handled by Apple; operator receives only transaction tokens |
| Apple Inc. | Sign in with Apple | Email, name (only when you use Apple Sign In) |

> InBody photos are processed once for measurement extraction and immediately discarded — they are not stored or reused.

These providers are contractually bound to protect your data in accordance with applicable laws.

---

## 6. International Data Transfers

Firebase data may be stored on Google's global infrastructure (including the United States and other regions).
- **Items transferred**: All items listed in Section 1
- **Destination countries**: United States, South Korea, and other Google Cloud regions
- **Transfer timing**: In real time, as you sign up and use the service
- **Recipient information**: Google LLC ([https://policies.google.com/privacy](https://policies.google.com/privacy))

We rely on Standard Contractual Clauses (SCCs) and other appropriate safeguards as required under GDPR.

---

## 7. Your Rights

You may exercise the following rights at any time:

| Right | How to Exercise |
|---|---|
| Right of access | View your data on the Profile screen in the app |
| Right of rectification | Use the in-app edit/delete features |
| Right to restrict processing | Contact us using the details below |
| **Right to erasure (account & data deletion)** | Use **Profile → Delete Account** in the app |
| Right to data portability | Use the in-app **Export to JSON** feature |
| Right to lodge a complaint | Contact your local data protection authority |

---

## 8. Data Protection Officer

For privacy-related inquiries:

- **DPO**: June Lee
- **Email**: 106ljune@gmail.com
- **Response time**: Within 7 business days



---

## 9. Data Destruction

Upon account deletion, your data is destroyed as follows:
- **Electronic records**: Permanently deleted from Cloud Firestore and Firebase Authentication (irrecoverable)
- **On-device data**: Removed when you uninstall the app

---

## 10. Security Measures

We protect your information through:
- HTTPS/TLS encryption for all communications
- Firebase Security Rules that isolate user data (you can only access your own data)
- One-way password hashing (bcrypt); plaintext passwords are never stored
- Regular security reviews and patching

---

## 11. Children's Privacy

- The Service is not directed at children under 14.
- We do not knowingly collect data from children under 14. If we learn we have, we will delete that account and data immediately.

---

## 12. Changes to This Policy

We may update this Privacy Policy. Material changes will be announced at least 7 days in advance via in-app notice or email.

---

## Effective

This Privacy Policy is effective as of **May 4, 2026**.
