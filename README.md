# 🔁 BounceBack — Reclaim Your Time, Reconnect Your Life

> "Because it’s never too late to bounce back."

BounceBack is a full-stack social reintegration app designed to support individuals—like Melissa—who are ready to reclaim the time they lost to early responsibilities or life challenges. This project merges personalization, community, and gamification into a single platform that encourages users to pursue goals and make new connections.

---

## 🌟 Overview

Millions of adults face social isolation after experiencing major life responsibilities early on—such as single parenting, illness, or caregiving. BounceBack helps these individuals restart with confidence through:

- Curated and customizable bucket lists
- Small group matching for shared goals
- Gamified progress tracking
- Personalized community support

---

## 💡 Key Features

### ✅ Bucket List Builder
Users can add up to **3 activities** to their personal list in the free version, or unlock **unlimited options** with Premium. Each activity is broken into **achievable subtasks** (milestones) that users can complete and check off over time.

### ✅ Group Matching
Each activity links users to a **dedicated group** of others working toward the same goal, promoting mutual encouragement and accountability.

### ✅ Gamified Roadmap
A **level-based system** tracks a user’s progress through their activities and milestones. Completing levels unlocks:
- Badges
- Progress stats
- Premium perks (with optional upgrades)

### ✅ Event Calendar & RSVP System
Users can view **local and online events** tied to their interests and RSVP to attend. This helps them transition from planning to action.

### ✅ In-App Messaging
Each group has a **chatroom** where users can:
- Share tips
- Plan group activities
- Build community

---

## 🛠️ Technical Architecture

### 🔐 User Onboarding
- Authentication via Firebase Auth
- User input collected includes:
  - Basic info (name, email)
  - Demographic & group preferences
  - Bucket list activity selection

### 🧠 Backend & Data Management
- **Firestore** for real-time syncing of user data, group activities, messages, and event updates
- **Firebase Cloud Functions** for:
  - Group matchmaking
  - Progress level updates
  - Notification triggers

### 📱 Frontend (React)
- Component-based UI
- Western-themed interface using custom CSS
- Responsive design optimized for mobile and desktop

### 📲 Notifications & Engagement
- Real-time activity and milestone tracking
- Event reminders & level-up notifications
- Chat functionality with Firestore listeners

### 💬 Messaging
- Group chat using Firestore's real-time database
- Syncs across devices instantly
- Enables threaded conversations in future expansion

---

## 📌 Tech Stack

| Component       | Tech Used                     |
|----------------|-------------------------------|
| Frontend        | React, HTML/CSS               |
| Backend         | Firebase Firestore, Cloud Functions |
| Authentication  | Firebase Auth                 |
| Messaging       | Firestore (real-time chat)    |
| Notifications   | Firebase & In-App Prompts     |
| Payment         | (Future) Stripe Integration   |

