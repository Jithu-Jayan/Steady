# Steady — Exam Stress & Study Tracker

> A private, browser-based tool designed to help students understand how exam pressure affects their mood, stress, sleep, and study habits.

## Overview

**Steady** is a private and easy-to-use exam stress and study tracker designed for students. Exam stress is common, but many students never track how their stress levels relate to their study habits, sleep, and mood.

Steady makes self-reflection simple through a daily check-in that takes approximately two minutes.

Users can record their **mood, stress level, study hours, sleep hours, and a short personal note**. The application then transforms this information into trends and plain-language insights that help users understand their recent patterns.

> **Note:** Steady is designed for self-reflection and general wellbeing support. It is not a medical or diagnostic tool.

---

## Features

### 📝 Daily Check-In

Users can record their daily wellbeing and study information through a simple check-in.

- Rate mood using five simple faces
- Rate stress using a five-step meter
- Record study hours
- Record sleep hours
- Add a short personal note
- Add or edit previous days
- Continue tracking even after missing a day

---

## 📊 Trends

The Trends page provides an interactive view of the user's recent data.

It allows users to explore:

- Study hours
- Mood levels
- Stress levels
- Weekly averages
- Recent changes and patterns

### Available Time Ranges

- 7 days
- 14 days
- 30 days

The charts help users understand whether their mood, stress, and study habits are improving or changing over time.

---

## 💡 Insights

Steady converts recent tracking data into simple, easy-to-understand observations.

For example, the application may identify patterns such as:

- Long study hours coinciding with lower mood
- Reduced sleep occurring alongside increased stress
- Changes in stress levels during periods of intensive studying
- Improvements in mood after maintaining healthier study habits

The goal is to make personal data easier to understand without requiring users to interpret complicated statistics.

---

## 📚 History

The History page provides a complete record of previous check-ins.

Users can:

- View past entries
- Review their mood and stress levels
- Check study and sleep hours
- Read previous notes
- Edit existing entries

This ensures that users can maintain an accurate record even when they miss or need to correct a check-in.

---

## 🧘 Support

The Support page provides practical resources for managing exam pressure.

It includes:

- Guided breathing exercises
- Practical study habits
- General stress-management suggestions
- Guidance on when to reach out to a counsellor, doctor, or trusted person

Steady encourages users to seek professional support when stress becomes overwhelming.

---

## 🔒 Privacy First

Privacy is a core part of Steady's design.

All user data is stored locally in the browser using **`localStorage`**.

This means:

- No account is required
- No server is required
- No personal data is uploaded
- No data is shared with third parties
- Users have complete control over their information

Users can also:

- **Export their data** as a file
- **Delete all stored data** at any time

Because the data is stored locally, the application is designed to provide a private tracking experience.

---

## 🎨 Design

Steady uses a calm and minimal interface designed to make daily tracking feel simple rather than overwhelming.

### Design Features

- Clean and modern interface
- Smooth transitions
- Light and dark themes
- Responsive layout
- Mobile-friendly design
- Tablet support
- Desktop support
- Simple navigation

The interface is designed to make the application comfortable to use regularly, especially during stressful examination periods.

---

## 🗂️ Application Structure

The application is organized into five main sections:

```text
Steady
│
├── Today
│   ├── Daily check-in
│   ├── Greeting
│   ├── 7-day mood overview
│   └── Latest insight
│
├── Trends
│   ├── Study hours
│   ├── Mood
│   ├── Stress
│   ├── Weekly averages
│   └── 7 / 14 / 30-day views
│
├── Insights
│   └── Plain-language observations
│
├── History
│   ├── Previous entries
│   └── Edit entries
│
└── Support
    ├── Breathing exercise
    ├── Study habits
    └── Professional support guidance
