# NayePankh Student Portal

A modern Android Student Portal application developed using **Java, XML, Firebase Authentication, and Firebase Firestore**. The application provides students with a centralized platform to access academic resources, register for events, view notices, manage certificates, and maintain their profile through a secure and user-friendly mobile experience. :contentReference[oaicite:0]{index=0}

## 📱 APK

The latest APK is available in the **Releases** section of this repository.

---

# Overview

NayePankh Student Portal is an Android-based mobile application developed to provide students with a centralized platform for accessing academic and organizational resources. The application enables students to register, log in securely, access study materials, view notices, register for events, manage certificates, and maintain their profile information. The primary objective is to simplify communication and resource distribution through a modern Android platform. :contentReference[oaicite:1]{index=1}

---

# Features

## User Authentication

- User Registration (Sign Up)
- Secure Login
- Email Verification
- Forgot Password
- Password Reset
- User Session Management
- Firebase Authentication Integration

---

## Student Dashboard

- Personalized Welcome Message
- Dynamic Date Display
- Quick Access Cards
- Navigation Drawer
- Bottom Navigation
- Responsive Dashboard Layout

---

## Events Module

- Upcoming Events
- Event Details
- Event Registration
- Registration Status
- Automatic Expired Event Hiding

---

## Study Materials

- Learning Resources
- Educational Content
- Student Reference Materials

---

## Notices

- Academic Notices
- Latest Announcements
- Notice Details

---

## Certificates

- Certificate Information
- Student Achievement Records

---

## Profile Management

- User Information
- Dynamic Avatar Initials
- Update Full Name
- Change Password
- Registered Events
- Firebase Data Synchronization

---

# Firebase Services

## Firebase Authentication

Used for:

- User Registration
- User Login
- Email Verification
- Forgot Password
- Password Reset
- Session Management

---

## Firebase Firestore

Used for:

- User Profile Storage
- Event Registration
- User Information Management
- Cross Device Data Synchronization

---

# Technologies Used

## Programming Language

- Java

## User Interface

- XML

## IDE

- Android Studio

## Backend

- Firebase Authentication
- Firebase Firestore

## Cloud Services

- Firebase

---

# Main Modules

### Splash Screen

- Application Branding
- Automatic Login Check
- Email Verification Check
- Navigation to Login or Dashboard

### User Registration

- Full Name Registration
- Email Registration
- Password Validation
- Email Verification
- Firebase Authentication Integration

### Login

- Secure Authentication
- Password Visibility Toggle
- Loading Indicator
- Multiple Click Prevention
- Error Handling

### Forgot Password

- Email-Based Password Reset
- Firebase Password Reset Email
- Internet Connectivity Validation
- User Feedback Messages

### Home Dashboard

- Personalized Welcome
- Dynamic Date
- Navigation Drawer
- Bottom Navigation
- Quick Access Cards

Dashboard Cards:

- Events
- Study Material
- Notices
- Certificates

### Events Module

Features:

- Upcoming Events Display
- Event Details Screen
- Event Registration
- Registration Status Tracking
- Automatic Expired Event Hiding

---

# Event Registration Workflow

1. User opens the Event Details screen.
2. User taps the **Register** button.
3. Registration data is stored in **Firebase Firestore**.
4. User receives confirmation.
5. Registered event appears in the Profile section.
6. Registration data is synchronized across devices. :contentReference[oaicite:0]{index=0}

---

# Firestore Database

## Collections

```text
users
event_registrations
password_reset_limits
```

### Stored Registration Data

- User ID
- Event Title
- Event Date
- Registration Timestamp :contentReference[oaicite:1]{index=1}

---

# Security Features

## Authentication Security

- Firebase Authentication
- Email Verification
- Secure Password Reset

## Data Security

- Firebase Security Rules
- User-Specific Firestore Access
- Authenticated User Validation

## Application Security

- Signed Release APK
- Release SHA-1 Certificate
- Debug SHA-1 Certificate
- ProGuard Configuration
- Firebase Project Protection :contentReference[oaicite:2]{index=2}

---

# User Experience

The application focuses on providing a smooth and modern Android experience with optimized performance and responsive UI.

### Loading Management

Implemented on:

- Login
- Registration
- Profile Update
- Password Update
- Event Registration

Features:

- Loading Indicators
- Multiple Click Prevention
- Error Handling

### Connectivity Handling

- Internet Connectivity Validation
- Offline User Feedback Messages

### UI Features

- Modern Gradient Design
- Material Design Components
- Responsive Layouts
- Custom Avatars
- Dynamic Welcome Section
- Navigation Drawer
- Bottom Navigation
- Professional Dashboard Design :contentReference[oaicite:3]{index=3}

---

# Project Structure

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

# Authentication

- Email & Password Authentication
- Email Verification
- Forgot Password
- Secure Session Management
- Firebase Authentication Integration :contentReference[oaicite:4]{index=4}

---

# Future Enhancements

Planned improvements include:

- Push Notifications
- Admin Dashboard
- Event Attendance Tracking
- Study Material Downloads
- Certificate Generation
- Real-Time Announcements
- Student Chat Support
- Multi-Language Support :contentReference[oaicite:5]{index=5}

---

# Author

**Ravi Thakur**

- LinkedIn: https://www.linkedin.com/in/ravi-thakur-0994502a2/

---

# License

This project is intended for educational and portfolio purposes.

---

## ⭐ Support

If you found this project helpful, consider giving it a **Star ⭐** on GitHub.

Thank you for visiting this repository!
