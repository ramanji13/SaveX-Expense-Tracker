# SaveX - Professional Expense Tracker

SaveX is a Flutter-based mobile application designed to help users track their daily spending with professional analytics and budget reminders.

##  Key Features
* **Spending Analytics:** A dynamic line chart showing the last 5 days of activity.
* **Budget Reminders:** Set a monthly limit and get notified of your status.
* **Authentication:** Secure login and OTP verification.
* **Category Tracking:** Organize spending into Groceries, Food, Shopping, and more.
* **Dashboard:** Real-time balance and category overview.
* **Fixed Expenses:** Manage recurring payments easily.
* **QR Scanner:** Scan and pay or log expenses instantly.
* **Analytics:** Professional line charts (Graph) to track 5-day spending trends.

## 📸 App Screenshots

<table style="width: 100%; border-collapse: collapse;">
  <tr>
    <td align="center"><b>Dashboard</b></td>
    <td align="center"><b>Fixed Amounts</b></td>
    <td align="center"><b>QR Scanner</b></td>
    <td align="center"><b>Spending Graph</b></td>
    <td align="center"><b>Profile</b></td>
  </tr>
  <tr>
    <td><img src="Screenshots/dashboard.png" width="180"></td>
    <td><img src="Screenshots/fixedAmounts.png" width="180"></td>
    <td><img src="Screenshots/scanner.png" width="180"></td>
    <td><img src="Screenshots/graph.png" width="180"></td>
    <td><img src="Screenshots/profile.png" width="180"></td>
  </tr>
</table>


## 🛠️ Tech Stack
* **Frontend:** Flutter & Dart
* **Backend:** Flask (Python)
* **Database:** mongodb
* **State Management:** Provider

## 🏁 How to Run
1. Clone the repository.
2. Run `flutter pub get`.
3. Ensure your Flask server is running at the configured IP.
4. Run `flutter run`.

# SaveX - Professional Expense Tracker 

SaveX is a professional-grade Flutter application designed to help users take control of their financial life. It combines real-time spending analytics with a secure Flask backend and MongoDB database.

[![Download APK](https://img.shields.io/badge/Download-APK-green?style=for-the-badge&logo=android)](https://github.com/BhumulaLakshmiNarayanaReddy/SaveX-Expense-Tracker/releases/download/v1.0.0/SaveX.apk)

## 📥Setup Guide

### Mobile App Connection (Hidden Menu)
* Download and install the SaveX APK by clicking the above download button.
* The 7-Tap Secret: Open the app, go to the Profile page, and tap the Wallet Icon 7 times quickly.
* Configure URL: A hidden configuration field will appear. Enter your backend URL:
Example:[https://savex-backend.vercel.app/]
* Save & Enjoy: Tap Save. The app will now communicate with your own server and database!
