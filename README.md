# 🔬 LabLink — Smart Laboratory Equipment Booking & Management Platform

**A Smart Campus & Student Life Project | Project 4**

LabLink is a web-based laboratory equipment booking and management platform designed to simplify how students access laboratory resources and how administrators manage equipment, bookings, and maintenance activities.

The platform provides a centralized interface for browsing equipment, checking availability, submitting booking requests, managing maintenance reports, and monitoring laboratory operations through an interactive analytics dashboard.

> **Project Type:** Frontend-only demonstration  
> **Technology:** HTML5, CSS3, JavaScript  
> **Data Storage:** Browser LocalStorage

---

## ✨ Features

### 1. Dashboard
- Overview of laboratory statistics.
- Real-time statistics calculated from stored application data.
- Quick access to important platform sections.

### 2. Equipment Management
- Browse the laboratory equipment catalogue.
- Search, filter, and sort equipment.
- Add, edit, and delete equipment records.
- Handle equipment with existing active bookings.

### 3. Equipment Booking
- Submit equipment booking requests.
- Check equipment availability before booking.
- Overlap-aware availability calculation.
- Considers peak concurrent quantities across Approved and Active bookings.

### 4. My Bookings
- View personal booking history.
- Filter bookings by status.
- Cancel eligible bookings.
- Track booking request progress.

### 5. Admin Mode
- Demonstration Admin Mode for managing booking requests.
- Approve or reject booking requests.
- Manage booking-related activities.

### 6. Maintenance Management
- Report equipment faults.
- Track maintenance reports.
- Block equipment from being booked during maintenance.
- Flag future reservations that may be affected by maintenance.

### 7. Analytics Dashboard
Includes five interactive Chart.js visualizations with appropriate empty states to display laboratory usage and booking-related insights.

### 8. Notifications
- View application notifications.
- Receive updates about relevant booking and maintenance activities.

### 9. Profile & Settings
- Manage demonstration profile settings.
- Switch between light and dark themes.
- Export application data as JSON.
- Import previously exported JSON data.
- Restore demo data or clear stored application data.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling and responsive interface |
| Vanilla JavaScript | Application logic and interactions |
| Chart.js | Analytics and data visualization |
| Lucide Icons | Interface icons |
| LocalStorage | Browser-based data persistence |

**External libraries:** Chart.js and Lucide are loaded through CDN links. The application is designed to remain usable if these libraries fail to load, although their associated visual enhancements may be unavailable.

---

## 📁 Project Structure

```text
LabLink/
│
├── index.html
│
├── css/
│   └── style.css
│
└── js/
    ├── app.js
    ├── storage.js
    ├── equipment.js
    ├── bookings.js
    ├── maintenance.js
    ├── analytics.js
    └── notifications.js
```

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Google Chrome recommended).
- No additional software installation or build tools required.

### Run Locally

**Option 1: Open directly**

1. Download or clone the repository.
2. Open the project folder.
3. Double-click `index.html`.
4. The application will open in your browser.

**Option 2: Using VS Code**

1. Open the project folder in Visual Studio Code.
2. Install the Live Server extension if it is not already installed.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

---

## 📊 Demo Data

LabLink comes with preloaded demonstration data to make the application immediately usable.

| Data | Quantity |
|---|---:|
| Equipment Items | 18 |
| Bookings | 9 |
| Maintenance Reports | 3 |
| Notifications | 5 |
| Sample Student Profiles | 1 |

All preloaded records are demonstration data and do not represent actual laboratory inventory or student information.

To restore the original demonstration environment:

**Profile & Settings → Restore Demo Data**

---

## 💾 Data Storage

LabLink uses browser LocalStorage to persist application data.

**Storage Key:**

```javascript
lablink_data_v1
```

Data remains available across browser sessions on the same browser and origin unless it is cleared or reset.

The application also supports JSON export and import for data backup and restoration.

---

## 🌐 Deployment

LabLink can be deployed as a static website without a backend or build process.

### GitHub Pages

1. Push the project folder to a GitHub repository.
2. Open repository **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder.
5. Save the settings.
6. Access the deployed application using the generated GitHub Pages URL.

### Vercel

1. Import the GitHub repository into Vercel.
2. Configure the project as a static website.
3. Leave the build command empty.
4. Set the output directory to the project root.
5. Deploy the application.

---

## ⚠️ Current Limitations

LabLink is currently a frontend-only demonstration. It does not include:

- Backend database or server-side processing.
- Multi-user data synchronization.
- Secure user authentication or authorization.
- Actual administrator verification (Admin Mode is a demonstration toggle).
- Integration with physical laboratory inventory.
- Real email or SMS notifications.

All application data is stored locally in the user's browser.

---

## 🔮 Future Enhancements

Potential improvements for future versions include:

- Backend integration with a database.
- Secure authentication and role-based access control.
- Real-time synchronization between students and administrators.
- Automated email notifications for booking updates.
- Interactive calendar-based booking system.
- QR-code-based equipment check-in and check-out.
- Automatic transitions between Active and Completed booking statuses.
- Integration with actual laboratory inventory systems.
- Advanced usage reports and analytics.

---

## 🎯 Project Objective

The primary objective of LabLink is to demonstrate how a centralized digital platform can improve laboratory resource accessibility, equipment utilization, booking management, and maintenance tracking within a smart campus environment.

By bringing these operations together, LabLink aims to make laboratory management more organized, transparent, and efficient.

---

**LabLink — Making Laboratory Resource Management Smarter.** 🔬

*Part of the Smart Campus & Student Life Project Series.*
