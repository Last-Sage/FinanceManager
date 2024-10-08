# Financial Management System

A comprehensive web and mobile solution designed for small and medium-sized enterprises in the construction industry, which can be easily adapted to any sector. This system helps track financial transactions, manage staff, and oversee projects effectively through a **Web Dashboard** for admins and managers, and an **Android App** for field staff and managers.

---

## Features

### Web Dashboard (Admin and Manager Portal)
- **Financial Overview**: View real-time expenses and income across projects.
- **Staff Management**: Add, remove, or update staff profiles. Assign staff to projects and managers.
- **Expense Ledger**: Track and categorize all financial transactions entered by field staff.
- **Task Assignment**: Assign tasks to staff members and track task completion.
- **Transaction Approval**: Managers approve or decline transactions submitted by staff, and admins finalize the approvals.
- **Project Management**: Assign staff to specific projects and view project-specific financials.

### Android App (Staff and Manager Portal)
- **Transaction Entry**: Field staff can easily log their financial transactions.
- **Project View**: View assigned projects, tasks, and associated deadlines.
- **Task Completion**: Mark tasks as complete and submit supporting documentation (e.g., photos, receipts).
- **Transaction Approval**: Managers can approve or decline transactions and submit them for admin approval.
- **Offline Support**: Enter transactions offline and sync when online.

---

## Technology Stack

### Backend
- **Firebase**: Secure, scalable backend for authentication, real-time database, and cloud storage.

### Web Dashboard (Frontend)
- **Next.js**: React framework for server-side rendering and fast, SEO-friendly pages.
- **Firebase**: Integrated with Firebase for data fetching and authentication.

### Mobile (Android)
- **Flutter**: Cross-platform development for building the Android app with responsive UI.
- **Firebase**: Used for backend services like authentication and real-time database sync.

---

## Getting Started

### Web Dashboard
The web dashboard is hosted and accessible via the following link:

[**Access Web Dashboard**](https://conifer-admin-test.netlify.app/)
Note: web dashboard needs to be refreshed once after logging in for the first time.

### Android App
The Android APK can be downloaded and installed on your device:

[**Download APK**](https://github.com/Last-Sage/FinanceManager/releases/tag/v0.5.0-alpha)

---

## Security and Privacy

- **Authentication**: Both the web dashboard and Android app use Firebase Authentication to ensure secure login for admins, managers, and staff.
- **Data Protection**: Financial and sensitive data is securely stored using Firebase Realtime Database and Firestore, ensuring data encryption and integrity.
- **Error Handling**: Comprehensive error handling and logging are implemented to provide secure, efficient operations.

---

## Demo Credentials for testing

- **Web Dashboard**

Admin credentials :
- User ID : ccptestservice@gmail.com
- Password : demoadmin

- **Android App**

Credentials Project Manager:
- User ID: EID01@conifer.app
- Password: password@conifer

Credentials staff:
- User ID: EID03@conifer.app 
- Password: password@conifer

 Note:
1. Username and password are case sensitive.
