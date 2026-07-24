# NayePankh Student Portal

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/UI-XML-4285F4?style=for-the-badge&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-Authentication-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Database-Firestore-FF6F00?style=for-the-badge&logo=firebase&logoColor=white" />
</p>

A modern Android Student Portal application developed using **Java**, **XML**, **Firebase Authentication**, and **Firebase Firestore**. The application provides students with a centralized platform to access academic resources, register for events, view notices, manage certificates, and maintain their profile through a secure and user-friendly mobile experience.

---

## 📱 APK

Download the latest APK from the **Releases** section of this repository.

---

# 📖 Overview

NayePankh Student Portal is an Android application designed to simplify communication and resource sharing between an organization and its students. The application allows students to securely register, log in, access study materials, view notices, register for events, manage certificates, and maintain their profile from a single mobile platform.

---

# ✨ Features

## 🔐 Authentication

- User Registration
- Secure Login
- Email Verification
- Forgot Password
- Password Reset
- User Session Management
- Firebase Authentication Integration

---

## 🏠 Dashboard

- Personalized Welcome Message
- Dynamic Date Display
- Quick Access Cards
- Navigation Drawer
- Bottom Navigation
- Modern Responsive UI

---

## 📅 Events

- View Upcoming Events
- Event Details
- Event Registration
- Registration Status
- Automatic Expired Event Hiding

---

## 📚 Study Materials

- Learning Resources
- Educational Content
- Student Reference Materials

---

## 📢 Notices

- Academic Notices
- Latest Announcements
- Notice Details

---

## 🏆 Certificates

- Student Certificate Information
- Achievement Records

---

## 👤 Profile

- User Information
- Dynamic Avatar Initials
- Update Profile
- Change Password
- Registered Events
- Cross-Device Synchronization

---

# 🔥 Firebase Services

## Firebase Authentication

Used for:

- User Registration
- Secure Login
- Email Verification
- Forgot Password
- Password Reset
- Session Management

### Firebase Firestore

Used for:

- User Profile Storage
- Event Registration Data
- User Information Management
- Cross Device Synchronization

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Java | Application Logic |
| XML | User Interface |
| Android Studio | Development Environment |
| Firebase Authentication | User Authentication |
| Firebase Firestore | Cloud Database |

---

# 📂 Main Modules

### 🚀 Splash Screen

- Application Branding
- Automatic Login Check
- Email Verification Check
- Smart Navigation

### 📝 Registration

- Full Name Registration
- Email Registration
- Password Validation
- Email Verification
- Firebase Authentication Integration

### 🔑 Login

- Secure Authentication
- Password Visibility Toggle
- Loading Indicator
- Multiple Click Prevention
- Error Handling

### 🔒 Forgot Password

- Password Reset via Email
- Internet Connectivity Validation
- User Feedback Messages

### 🏠 Home Dashboard

- Personalized Welcome Message
- Dynamic Date Display
- Navigation Drawer
- Bottom Navigation
- Quick Access Dashboard Cards

Dashboard Cards:

- 📅 Events
- 📚 Study Materials
- 📢 Notices
- 🏆 Certificates

- ### 📅 Events Module

Features

- Upcoming Events Display
- Event Details Screen
- Event Registration
- Registration Status Tracking
- Automatic Expired Event Hiding

---

# 🔄 Event Registration Workflow

1. Open the Event Details screen.
2. Tap the **Register** button.
3. Registration details are securely stored in Firebase Firestore.
4. Registration is confirmed successfully.
5. The registered event appears in the user's Profile.
6. Registration data is synchronized across devices.

---

# ☁️ Firestore Database

## Collections

```text
users
event_registrations
password_reset_limits
```

### Event Registration Data

- User ID
- Event Title
- Event Date
- Registration Timestamp

---

# 🔒 Security Features

## Authentication Security

- Firebase Authentication
- Email Verification
- Secure Password Reset
- User Session Management

### Data Security

- Firebase Security Rules
- User-Specific Firestore Access
- Authenticated User Validation

### Application Security

- Signed Release APK
- SHA-1 Configuration
- ProGuard Enabled
- Firebase Project Protection

---

# 🎨 User Experience

The application focuses on delivering a modern, responsive, and user-friendly Android experience.

### Loading Management

Implemented in

- Login
- Registration
- Profile Update
- Password Update
- Event Registration

Features

- Loading Indicators
- Multiple Click Prevention
- Error Handling

### Connectivity

- Internet Connectivity Validation
- Offline User Feedback Messages

### UI Features

- Modern Gradient Design
- Material Design Components
- Responsive Layouts
- Dynamic Avatar Initials
- Navigation Drawer
- Bottom Navigation
- Professional Dashboard Interface

---

# 📁 Project Structure

## Activities

```text
SplashActivity
LoginActivity
RegisterActivity
ForgotPasswordActivity
HomeDashboardActivity
EventDetailsActivity
NoticesActivity
StudyMaterialActivity
CertificatesActivity
HelpSupportActivity
DonateUsActivity
AboutNayePankhActivity
PrivacyPolicyActivity
TermsConditionsActivity
```

## Fragments

```text
HomeFragment
EventsFragment
ProfileFragment
```

---

# 🔑 Authentication Flow

```text
Splash Screen
      │
      ▼
Auto Login Check
      │
      ├── Logged In + Verified
      │          │
      │          ▼
      │    Home Dashboard
      │
      └── Not Logged In
                 │
                 ▼
         Login / Register
```

---

# 🚀 Future Enhancements

- Push Notifications
- Admin Dashboard
- Event Attendance Tracking
- Study Material Downloads
- Certificate Generation
- Real-Time Announcements
- Student Chat Support
- Multi-Language Support

---

# 👨‍💻 Developer

**Ravi Thakur**

Android Developer

**LinkedIn**

https://www.linkedin.com/in/ravi-thakur-0994502a2/

---

# 📄 License

This project is intended for educational, learning, and portfolio purposes only.

---

## ⭐ Support

If you found this project helpful, consider giving this repository a **Star ⭐**.

Thank you for visiting this repository!
