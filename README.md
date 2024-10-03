# 📚 WiseBridge - A Networking and Learning Platform for Students and Experts

**WiseBridge** is a comprehensive online platform designed to bridge the gap between students and senior students/alumni (experts). It allows students to access verified educational content while providing experts an opportunity to monetize their resources. The platform encourages networking, knowledge sharing, and mentorship among students and alumni of the **Master of Applied Computing (MAC)** program at the University of Windsor.

## 🛠️ Project Overview

WiseBridge provides a networking platform for students and alumni, where experts can upload verified content (videos, notes, etc.) that students can access for a fee or for free. It creates a niche environment focused on specific academic content and practical experiences related to the MAC program.

Key features include:
- **Verified content** provided by alumni and senior students.
- **Monetization options** for experts.
- A **subscription model** for students to access paid content.
- **User-friendly dashboard** for students and experts.
- Secure, scalable, and reliable backend infrastructure using **Firebase**.

## 🎯 Objective

The main goal of WiseBridge is to facilitate access to niche educational resources while providing students an opportunity to connect with alumni and senior students. It also allows experts to monetize their content, creating a mutually beneficial ecosystem.

## 👥 Target Users

- **Students**: Freshmen and seniors in the MAC program at the University of Windsor.
- **Experts**: Senior students and alumni from the MAC program who wish to share educational resources.

## 📊 Features

### For Students:
- **Access to Verified Content**: View, download, and subscribe to content uploaded by experts.
- **Rating and Reviewing**: Provide feedback on content to help improve the learning experience.
- **Subscription Model**: Subscribe to paid content uploaded by experts.

### For Experts:
- **Upload Educational Content**: Share resources like videos, notes, etc., and monetize the content.
- **View Subscriber List**: See who has subscribed to your content.
- **Receive Payments**: Handle payments for your content through a secure payment gateway.

## 🛠️ Tech Stack & Tools

- **Programming Language**: Java
- **Development Environment**: Android Studio
- **Backend**: Firebase (for real-time data synchronization and cloud storage)
- **Version Control**: GitHub
- **Project Management**: Jira
- **Methodology**: Scrum (Agile)

## 🖥️ System Design

The system includes multiple user types with different privileges and functionalities:

- **Admin**: Approves expert and student registrations and content uploads.
- **Experts**: Can upload content, view subscribers, and manage their profiles.
- **Students**: Can access content, subscribe to paid material, and post reviews.

## ⚙️ Functionalities

1. **User Registration**: Both students and experts can register and are verified by the admin.
2. **Login System**: Users can log in using their credentials based on their role (student, expert, or admin).
3. **Expert Features**:
   - Upload videos, notes, and other educational content.
   - Manage content, including viewing subscribers.
   - Verify payments from students.
4. **Student Features**:
   - Access and subscribe to expert content.
   - Provide reviews and ratings for content.
   - Download educational material.
5. **Admin Features**:
   - Approve or reject content uploaded by experts.
   - Manage and verify user registrations.
