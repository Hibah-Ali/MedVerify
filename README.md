
# MedVerify

**MedVerify** is a public health prototype app designed to combat the distribution of counterfeit and substandard medicines in Pakistan and other LMICs. Built with React Native and integrated with barcode scanning technology, the app allows users to scan medicine packaging and verify its authenticity in real-time.

---

## 📱 Features

- 📷 **Barcode Scanner** using device camera
- ✅ **Verification Result Screen** showing medicine status
- ☁️ **Mock Google Sheets Backend** (replaceable with real health authority database)
- 🔒 Future plans for API integration with official regulatory bodies

---

## 🚀 Getting Started

### Prerequisites

- Node.js
- Expo CLI
- Git

### Install

```bash
git clone https://github.com/Hibah-Ali/MedVerify.git
cd MedVerify
npm install
npx expo start
```

---

## 🧪 How It Works

1. User opens the app and scans the barcode on medicine packaging.
2. The app checks the barcode against a Google Sheet (mock backend).
3. It returns a message indicating whether the medicine is verified and safe.

---

## 🌍 Vision

MedVerify is part of a broader public health effort to:

- Regulate antibiotic sales
- Strengthen supply chain transparency
- Enable community reporting of fake/substandard drugs

---

## 📦 Tech Stack

- React Native (Expo)
- Google Sheets API (mock database)
- Expo Barcode Scanner

---

## 🧑‍⚕️ Use Case Scenarios

- Pharmacists verifying stock
- Public awareness campaigns
- Regulatory field officers
- Community health workers

---

## 🛡️ Future Enhancements

- Integration with official Drug Regulatory Authority API
- Offline caching for remote areas
- Geo-logging of counterfeit detections
- Admin dashboard for reports

---

## 📫 Contact

Built by [Hibah Ali](https://github.com/Hibah-Ali)  
For inquiries, collaboration, or demo: **medverify.app@gmail.com**

---

> ⚠️ *This is a prototype for demonstration purposes only.*
