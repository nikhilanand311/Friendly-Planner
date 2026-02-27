# TaskFlow Pro — Smart Task Management App

<div align="center">

![TaskFlow Pro](https://img.shields.io/badge/TaskFlow%20Pro-Task%20Management-6366f1?style=for-the-badge&logo=checkmarx&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-18%2B-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-Integrated-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**A Premium Full-Stack Task Management Platform with AI, Analytics & Smart Notifications**

</div>

TaskFlow Pro is a comprehensive full-stack task management application built with **Flutter** (mobile frontend) and **Node.js/Express** (backend). It combines powerful task management with AI-powered assistance, detailed productivity analytics, smart notifications, calendar integration, and social sharing — all wrapped in a beautifully designed, theme-customizable UI.

<br>

## 📋 Table of Contents

| Section | Link |
|---------|------|
| About | [About](#-about) |
| Features | [Features](#-features) |
| Tech Stack | [Tech Stack](#-tech-stack) |
| Architecture | [Architecture](#-architecture) |
| Screens & Pages | [Screens & Pages](#-screens--pages) |
| Installation | [Installation](#-installation) |
| Configuration | [Configuration](#-configuration) |
| API Documentation | [API Documentation](#-api-documentation) |
| Usage | [Usage](#-usage) |
| Contributing | [Contributing](#-contributing) |
| License | [License](#-license) |

---

## 📖 About

TaskFlow Pro is a feature-rich, production-ready task management platform designed to maximize personal productivity. Built as a full-stack mobile application, it connects a polished Flutter frontend to a secure, scalable Node.js REST API backed by Firebase.

The platform helps users:
- Create, organize, and prioritize tasks with rich metadata (categories, priorities, due dates, tags)
- Track productivity through in-depth analytics dashboards (daily, weekly, monthly, yearly views)
- Stay on schedule with intelligent smart notifications (overdue alerts, quiet hours, daily summaries)
- Visualize their schedule through an interactive calendar with task overlays
- Get AI-assisted task planning and advice through the built-in AI Board
- Share achievements on social platforms (LinkedIn, Instagram Stories)
- Export task data to CSV/Excel for reporting
- Secure accounts with pattern lock, OTP verification, and JWT authentication

---

## ✨ Features

### Core Task Management
- **Full CRUD** — Create, read, update, and delete tasks with rich fields
- **Priority Levels** — High, Medium, Low priority classification
- **Categories & Tags** — Organize tasks by Work, Personal, Health, Finance, Education, Shopping, and more
- **Due Dates & Times** — Schedule tasks with date/time pickers and voice input
- **Task Status Tracking** — Active, Completed, Overdue views
- **Recently Completed** — Dedicated section for completed task history

### Smart Notifications
- **Overdue Task Alerts** — Real-time alerts when tasks are overdue
- **Today's Reminders** — Daily task reminders with configurable intervals
- **Upcoming Task Reminders** — Heads-up notifications for future tasks
- **Quiet Hours** — Suppress notifications during configurable sleep windows
- **In-App Overlay Banners** — Slide-down banners when the app is in the foreground
- **WorkManager Background Tasks** — Notifications even when the app is killed
- **AlarmManager** — Native Android alarm for MIUI/aggressive OEM support

### Analytics Dashboard
- **Overview Metrics** — Tasks completed, completion rate, best streak, daily average
- **Completion Trend Charts** — Line graphs across daily, weekly, monthly, yearly periods
- **Priority Distribution** — Bar charts comparing total vs. completed by priority
- **Category Breakdown** — Donut charts of task distribution by category
- **Productivity Insights** — Most productive day, peak completion time
- **Achievement Badges** — Task Master, Streak Champion, and more

### AI & Intelligence
- **AI Board** — Built-in AI chat assistant powered by external AI agents
- **Multi-Provider Support** — Connect custom AI agent URLs and API keys
- **AI-powered task suggestions and planning assistance**

### Calendar & Schedule
- **Monthly Calendar View** — Visual task markers (dots) on days with tasks
- **Task Overlay on Date** — Tap any day to see tasks scheduled for that date
- **Calendar Integration** — Sync and visualize all tasks in a date-based layout

### Search & Filtering
- **Full-text Search** — Search by task title, description, and categories
- **Advanced Filters** — Filter by priority level, category, tags, completion status, date range
- **Instant Results** — Real-time filtering as you type

### Customization & Settings
- **Dark / Light Mode** — Full dark mode support
- **Theme Colors** — 6 accent color themes: Blue, Purple, Green, Orange, Red, Teal
- **Language & Region** — App language, date format, currency settings
- **Notification Preferences** — Granular per-category toggles with interval controls
- **Pattern Lock** — Biometric-style pattern authentication
- **Export Data** — Download your task data as CSV or Excel
- **Cloud Sync** — Sync progress to the cloud

### Authentication & Security
- **JWT Authentication** — Secure, token-based user sessions
- **Registration with OTP** — Email verification via 6-digit OTP
- **Forgot Password** — Email/phone-based OTP reset flow
- **Password Strength Meter** — Real-time password strength indicator
- **Pattern Lock** — Local security layer for privacy
- **Bcrypt Password Hashing** — Secure password storage on the backend

### Social Sharing
- **LinkedIn Professional Share** — Share achievements and milestones as LinkedIn posts
- **Instagram Stories Share** — Export achievements as Instagram-ready story cards

---

## 🛠 Tech Stack

### Mobile Frontend (Flutter)
| Technology | Description |
|------------|-------------|
| **Flutter 3.x** | Cross-platform mobile UI framework |
| **Dart** | Programming language |
| **Google Fonts** | Typography (Inter, Roboto, Outfit) |
| **Flutter Local Notifications** | Android/iOS notification delivery |
| **Firebase Auth** | Authentication integration |
| **Firebase Messaging (FCM)** | Push notification support |
| **WorkManager** | Background task scheduling |
| **Dio** | HTTP client for API calls |
| **Shared Preferences** | Local key-value storage |
| **FL Chart** | Analytics charts (line, bar, donut) |
| **Image Picker / Camera** | Profile photo upload |
| **WebView Flutter** | AI board web interface |
| **Permission Handler** | Runtime permissions management |
| **Timezone** | Accurate scheduled notifications |
| **Sizer** | Responsive design system |
| **Google Mobile Ads** | Ad integration |

### Backend (Node.js)
| Technology | Description |
|------------|-------------|
| **Node.js 18+** | JavaScript runtime |
| **Express.js 5** | Web application framework |
| **Firebase Admin SDK** | Server-side Firebase access |
| **JWT (jsonwebtoken)** | Token-based authentication |
| **Bcryptjs** | Password hashing |
| **Multer** | File/image upload handling |
| **Nodemailer** | Email delivery (OTP, notifications) |
| **Twilio** | SMS OTP support |
| **Helmet** | HTTP security headers |
| **Express Rate Limit** | API rate limiting |
| **Winston** | Structured server logging |
| **Morgan** | HTTP request logging |
| **PDFKit** | PDF generation for exports |
| **json2csv** | CSV data export |
| **Moment.js** | Date/time utilities |
| **Compression** | Gzip response compression |

### Development Tools
- **VS Code** — IDE
- **Postman** — API testing
- **Firebase Console** — Auth and push notifications management
- **Git** — Version control
- **Nodemon** — Backend hot-reloading
- **ESLint + Prettier** — Code quality and formatting
- **Jest + Supertest** — Backend unit & integration tests

---

## 🏗 Architecture

The system follows a clean layered architecture:

```
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│         Flutter Frontend             │    │         Node.js Backend              │
│                                      │◄──►│                                      │
├──────────────────────────────────────┤    ├──────────────────────────────────────┤
│ • Presentation (Screens/Widgets)     │    │ • Controllers (Business Logic)       │
│ • Services (API + Notifications)     │    │ • Services (Email, AI, Analytics)    │
│ • Models (Data Layer)                │    │ • Middleware (Auth, Rate Limit)      │
│ • Routes (Navigation)                │    │ • Routes (REST Endpoints)            │
│ • Theme (Design System)              │    │ • Utils (Helpers, Validators)        │
└──────────────────────────────────────┘    └──────────────────────────────────────┘
                                                         │
                                            ┌────────────────────────┐
                                            │   Firebase (Auth/FCM)  │
                                            └────────────────────────┘
```

### Project Structure

```
taskflow_pro/
├── lib/                              # Flutter Frontend
│   ├── main.dart                     # App entry point
│   ├── firebase_options.dart         # Firebase config
│   ├── models/                       # Data models
│   ├── services/                     # notification_service, task_service, etc.
│   ├── routes/                       # Named route definitions
│   ├── theme/                        # Theme, colors, text styles
│   ├── core/                         # Core utilities and constants
│   ├── data/                         # Data sources and repositories
│   ├── widgets/                      # Global reusable widgets
│   ├── ai_platform_manager/          # AI board management
│   └── presentation/
│       ├── splash_screen/            # App launch screen
│       ├── onboarding_flow/          # 4-step onboarding slides
│       ├── login_screen/             # Authentication
│       ├── sign_up_screen/           # Registration
│       ├── otp_verification_screen/  # OTP flow
│       ├── reset_password_screen/    # Password recovery
│       ├── new_password_screen/      # Set new password
│       ├── main_task_dashboard/      # Home / Task list
│       ├── add_edit_task/            # Create / Edit tasks
│       ├── task_detail_view/         # Task detail screen
│       ├── task_list_view/           # All tasks list
│       ├── today_tasks_view/         # Today's tasks
│       ├── upcoming_tasks_view/      # Upcoming tasks
│       ├── calendar_view/            # Monthly calendar
│       ├── analytics_dashboard/      # Charts & insights
│       ├── search_and_filter/        # Search & advanced filters
│       ├── history_screen/           # Task history
│       ├── recently_completed/       # Completed task log
│       ├── ai_board/                 # AI assistant interface
│       ├── achievements_gallery/     # Achievement badges
│       ├── settings_and_preferences/ # App settings
│       ├── profile_edit/             # User profile
│       ├── change_password/          # Password management
│       ├── pattern_authentication/   # Pattern lock
│       ├── payment_interface/        # Premium/payment
│       ├── instagram_stories_share/  # Instagram export
│       ├── linked_in_professional_share/ # LinkedIn sharing
│       └── no_internet_screen/       # Offline screen
│
└── backend/                          # Node.js Backend
    ├── server.js                     # Entry point
    ├── config/                       # Firebase + DB config
    ├── controllers/                  # authController, taskController, etc.
    ├── middleware/                   # auth, rateLimiter, validator, errorHandler
    ├── models/                       # Mongoose/Firebase schemas
    ├── routes/                       # auth, tasks, analytics, AI, calendar, etc.
    ├── services/                     # emailService, notificationService
    └── utils/                        # Helper utilities
```

---

## 📱 Screens & Pages

### Onboarding Flow

| Smart Filtering | Track Progress | Calendar Integration | Task Management |
|-----------------|----------------|----------------------|-----------------|
| ![Onboarding1](assets/images/1772179853980.jpg) | ![Onboarding2](assets/images/1772179853991.jpg) | ![Onboarding3](assets/images/1772179854000.jpg) | ![Onboarding4](assets/images/1772179854010.jpg) |

### Authentication

| Login | Sign Up | Forgot Password | OTP Verification |
|-------|---------|-----------------|-----------------|
| ![Login](assets/images/1772179854066.jpg) | ![SignUp](assets/images/1772179854043.jpg) | ![ForgotPassword](assets/images/1772179854052.jpg) | ![OTP](assets/images/1772179854030.jpg) |

| Email Verified |
|----------------|
| ![EmailVerified](assets/images/1772179854018.jpg) |

### Main Dashboard

| Active Tasks Dashboard | Add New Task | Add Task (with Keyboard) | Task Detail View |
|------------------------|--------------|--------------------------|-----------------|
| ![Dashboard](assets/images/1772179854121.jpg) | ![AddTask](assets/images/1772179854521.jpg) | ![AddTaskKeyboard](assets/images/1772179854530.jpg) | ![TaskDetail](assets/images/1772179854538.jpg) |

### Search & Filter

| Search & Filter (Priority) | Search & Filter (Tags) | Search with Keyboard |
|----------------------------|------------------------|----------------------|
| ![SearchFilter1](assets/images/1772179854292.jpg) | ![SearchFilter2](assets/images/1772179854301.jpg) | ![SearchFilter3](assets/images/1772179854100.jpg) |

| Filter (Status) | Filter (Advanced) |
|-----------------|-------------------|
| ![FilterStatus](assets/images/1772179854320.jpg) | ![FilterAdvanced](assets/images/1772179854110.jpg) |

### Calendar

| Monthly Calendar View | Task Details on Date |
|-----------------------|----------------------|
| ![Calendar](assets/images/1772179854514.jpg) | ![CalendarOverlay](assets/images/1772179854504.jpg) |

### Analytics Dashboard

| Overview Metrics | Monthly Completion Trend | Monthly Stats |
|------------------|--------------------------|---------------|
| ![Analytics Overview](assets/images/1772179854377.jpg) | ![Monthly Trend](assets/images/1772179854412.jpg) | ![Monthly Stats](assets/images/1772179854421.jpg) |

| Weekly View | Weekly Completion Trend | Weekly Progress |
|-------------|-------------------------|-----------------|
| ![WeeklyView](assets/images/1772179854164.jpg) | ![WeeklyTrend](assets/images/1772179854479.jpg) | ![WeeklyProgress](assets/images/1772179854486.jpg) |

| Weekly Stats Cards | Analytics Loading |
|--------------------|-------------------|
| ![WeeklyStats](assets/images/1772179854497.jpg) | ![AnalyticsLoading](assets/images/1772179854145.jpg) |

| Priority Distribution | Category Breakdown (Monthly) | Category Breakdown (Yearly) |
|-----------------------|------------------------------|-----------------------------|
| ![Priority](assets/images/1772179854456.jpg) | ![CategoryMonthly](assets/images/1772179854400.jpg) | ![CategoryYearly](assets/images/1772179854354.jpg) |

| Productivity Insights (Monthly) | Productivity Insights (Weekly) | Yearly Overview & Achievements |
|---------------------------------|-------------------------------|-------------------------------|
| ![InsightsMonthly](assets/images/1772179854342.jpg) | ![InsightsWeekly](assets/images/1772179854446.jpg) | ![YearlyAchievements](assets/images/1772179854332.jpg) |

| Monthly Completion Trend (Full) |
|---------------------------------|
| ![MonthlyTrend](assets/images/1772179854366.jpg) |

| Weekly Achievements |
|---------------------|
| ![WeeklyAchievements](assets/images/1772179854432.jpg) |

### Settings & Preferences

| Notifications Settings | Appearance (Dark Mode & Themes) | Quiet Hours & Account Data |
|-----------------------|---------------------------------|---------------------------|
| ![NotifSettings](assets/images/1772179854220.jpg) | ![Appearance](assets/images/1772179854282.jpg) | ![QuietHours](assets/images/1772179854261.jpg) |

| Privacy & Security | Language & Region / AI Agent | About App |
|-------------------|------------------------------|-----------|
| ![Privacy](assets/images/1772179854232.jpg) | ![Language](assets/images/1772179854241.jpg) | ![About](assets/images/1772179854252.jpg) |

| Help & Support | Export Data (CSV/Excel) | Change Password |
|----------------|-------------------------|-----------------|
| ![HelpSupport](assets/images/1772179854183.jpg) | ![ExportData](assets/images/1772179854079.jpg) | ![ChangePassword](assets/images/1772179854089.jpg) |

| Notification Toggle Details |
|-----------------------------|
| ![NotifToggles](assets/images/1772179854273.jpg) |

### Notifications (System)

| Android Notification Shade |
|---------------------------|
| ![SystemNotification](assets/images/1772179854206.jpg) |

---

## 🚀 Installation

### Prerequisites
- **Flutter SDK** 3.6.0+ with Dart
- **Node.js** 18+ and npm
- **Firebase Project** with Auth and Cloud Messaging enabled
- **Android Studio / Xcode** for mobile emulators
- **Git**

---

### Backend Setup

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd taskflow_pro/backend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Create environment file**
   ```bash
   cp .env.example .env
   ```
   Fill in the values:
   ```env
   PORT=8000
   NODE_ENV=development
   ALLOWED_ORIGINS=http://localhost:3000
   
   # Firebase
   FIREBASE_PROJECT_ID=your_project_id
   FIREBASE_PRIVATE_KEY=your_private_key
   FIREBASE_CLIENT_EMAIL=your_client_email
   
   # JWT
   JWT_SECRET=your_super_secret_jwt_key
   JWT_EXPIRES_IN=7d
   
   # Email (Nodemailer)
   EMAIL_HOST=smtp.gmail.com
   EMAIL_PORT=587
   EMAIL_USER=your_email@gmail.com
   EMAIL_PASS=your_app_password
   
   # Twilio (SMS OTP)
   TWILIO_ACCOUNT_SID=your_sid
   TWILIO_AUTH_TOKEN=your_token
   TWILIO_PHONE_NUMBER=+1234567890
   ```

4. **Run the backend server**
   ```bash
   npm run dev
   ```
   Server starts at: `http://localhost:8000`

---

### Flutter Frontend Setup

1. **Navigate to the project root**
   ```bash
   cd taskflow_pro
   ```

2. **Install Flutter dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**
   - Add your `google-services.json` to `android/app/`
   - Add your `GoogleService-Info.plist` to `ios/Runner/`
   - Update `lib/firebase_options.dart` with your Firebase project settings

4. **Update API Base URL**
   In your environment/config file, set:
   ```dart
   const String apiBaseUrl = 'http://YOUR_LOCAL_IP:8000/api';
   ```
   > ⚠️ Use your machine's **local IP address** (not `localhost`) so the Android emulator/device can connect.

5. **Run the app**
   ```bash
   flutter run
   ```

---

## ⚙️ Configuration

### Backend Environment Variables

| Variable | Description | Default |
|----------|-------------|---------|
| `PORT` | Server port | `8000` |
| `NODE_ENV` | Environment (`development`/`production`) | `development` |
| `ALLOWED_ORIGINS` | Comma-separated allowed CORS origins | `http://localhost:3000` |
| `FIREBASE_PROJECT_ID` | Firebase project ID | — |
| `JWT_SECRET` | Secret key for JWT signing | — |
| `JWT_EXPIRES_IN` | Token expiry duration | `7d` |
| `EMAIL_HOST` | SMTP host for sending emails | — |
| `TWILIO_ACCOUNT_SID` | Twilio SID for SMS | — |

### Flutter Configuration

| Setting | File | Description |
|---------|------|-------------|
| API Base URL | `lib/services/` | Backend endpoint URL |
| Firebase Options | `lib/firebase_options.dart` | Firebase project config |
| Notification Icon | `android/app/src/main/res/drawable/` | `ic_notification.png` |
| App Theme | `lib/theme/` | Color palette and typography |

---

## 📚 API Documentation

### Authentication

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Register a new user (sends OTP) |
| POST | `/api/auth/login` | Login with email + password |
| POST | `/api/auth/verify-otp` | Verify email OTP |
| POST | `/api/auth/forgot-password` | Request password reset OTP |
| POST | `/api/auth/reset-password` | Reset password with OTP |
| GET | `/api/auth/me` | Get current authenticated user |

### Tasks

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/tasks` | Get all tasks for user |
| POST | `/api/tasks` | Create a new task |
| GET | `/api/tasks/:id` | Get single task |
| PUT | `/api/tasks/:id` | Update task |
| DELETE | `/api/tasks/:id` | Delete task |
| PATCH | `/api/tasks/:id/complete` | Mark task as complete |

### Analytics

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/analytics/overview` | Summary metrics |
| GET | `/api/analytics/trends` | Completion trend data |
| GET | `/api/analytics/categories` | Category breakdown |
| GET | `/api/analytics/productivity` | Productivity insights |

### Notifications

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/notifications` | Get notification settings |
| PUT | `/api/notifications/settings` | Update notification preferences |
| POST | `/api/notifications/fcm-token` | Register FCM device token |

### Calendar

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/calendar` | Get tasks for calendar view |
| GET | `/api/calendar/:date` | Get tasks for specific date |

### Search

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/search` | Search tasks with filters |

### User & Settings

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/user/profile` | Get user profile |
| PUT | `/api/user/profile` | Update profile |
| PUT | `/api/user/change-password` | Change password |
| GET | `/api/settings` | Get app settings |
| PUT | `/api/settings` | Update settings |
| GET | `/api/settings/export` | Export data (CSV/Excel) |

### Achievements & Social

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/achievements` | Get user achievement badges |
| POST | `/api/social/share` | Share task/achievement |

### AI Agents

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/ai-agents` | List configured AI agents |
| POST | `/api/ai-agents` | Add new AI agent |
| DELETE | `/api/ai-agents/:id` | Remove AI agent |

### Admin

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/admin/users` | List all users |
| GET | `/api/admin/analytics` | System-wide analytics |

### Health Check

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/health` | Server health status |

---

## 📖 Usage

### Getting Started

1. **Launch the app** — You'll see the onboarding slides explaining key features
2. **Register** — Create an account with your name, email, and password
3. **Verify your email** — Enter the OTP sent to your inbox
4. **Explore the dashboard** — Your main task hub is ready

### Creating Tasks

1. Tap the **➕ FAB** on the dashboard
2. Enter a **title** and optional description
3. Set a **due date & time** (tap the date picker or use voice input)
4. Choose a **priority** (High / Medium / Low)
5. Select a **category** (Work, Personal, Health, etc.)
6. Add **tags** for extra organisation
7. Tap **Save**

### Analytics

- Navigate to the **Analytics** tab in the bottom bar
- Switch between **Daily**, **Weekly**, **Monthly**, **Yearly** views
- Scroll down to see Completion Trend, Priority Distribution, Category Breakdown, and Productivity Insights

### Notifications

- Go to **Settings → Notifications**
- Toggle **Overdue Alerts**, **Today's Reminders**, **Upcoming Reminders** individually
- Set **Quiet Hours** to suppress notifications at night
- Adjust the **reminder interval** (e.g., every 30 minutes, every 1 hour)

### Customization

- Go to **Settings → Appearance**
- Switch between **Light / Dark mode**
- Pick one of the 6 **accent color themes**

### Exporting Data

- Go to **Settings → Account & Data**
- Tap **Export Data**
- Choose **CSV** or **Excel** format

---

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork** the repository
2. **Create a feature branch**
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'feat: add YourFeatureName'
   ```
4. **Push the branch**
   ```bash
   git push origin feature/YourFeatureName
   ```
5. **Open a Pull Request**

### Code Style Guidelines
- Follow **Dart/Flutter** best practices and the [Effective Dart](https://dart.dev/guides/language/effective-dart) guide
- Use **ESLint + Prettier** for backend JavaScript
- Write meaningful, conventional commit messages (`feat:`, `fix:`, `chore:`)
- Add comments for complex business logic
- Write tests for new backend endpoints

---

## 📄 License

This project is licensed under the **MIT License**.

```
MIT License

Copyright (c) 2026 TaskFlow Pro

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

---

## 🚀 Deployment

### Backend Deployment

1. **Set production environment variables**
   ```env
   NODE_ENV=production
   PORT=8000
   ```

2. **Start the server**
   ```bash
   cd backend
   npm install --production
   npm start
   ```

3. **Recommended**: Use a process manager like **PM2**
   ```bash
   pm2 start server.js --name taskflow-api
   ```

4. **Optional**: Configure **Nginx** as a reverse proxy

### Flutter Release Build

1. **Android APK / AAB**
   ```bash
   flutter build apk --release
   # or for Play Store
   flutter build appbundle --release
   ```

2. **iOS (requires macOS + Xcode)**
   ```bash
   flutter build ios --release
   ```

3. Update the **API base URL** in your config to point to your production server before building.

---

<div align="center">

**Built with ❤️ for maximum personal productivity**

</div>
