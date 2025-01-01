# StudyBuddy

**StudyBuddy** is a collaborative learning platform built with Django, designed to foster knowledge sharing and interaction among students, developers, and professionals. Users can create and join virtual study rooms, engage in discussions, and explore topics tailored to their interests.

---

## 🚀 Project Overview

StudyBuddy provides an intuitive interface for users to:

- **Create and manage study rooms** focused on specific topics.
- **Participate in discussions** by sharing ideas, asking questions, and responding to others.
- **Follow recent activities** and stay updated with ongoing conversations.
- **Build personal profiles** to showcase their engagement in study rooms.

---

## ✨ Key Features

### 1. **Authentication System**
- User authentication includes **login, registration, and logout functionalities**.
- Role-based access to specific features (e.g., creating or managing rooms is restricted to logged-in users).

### 2. **Dynamic Study Rooms**
- Create study rooms with a **topic, name, and description**.
- Join existing rooms and participate in discussions.
- Track participants in each room.

### 3. **Topic Management**
- Browse, search, and filter topics to find relevant study rooms.
- Dynamic topic creation when creating a study room.

### 4. **Message and Discussion System**
- Post and delete messages within study rooms.
- Track recent activities from room messages.

### 5. **User Profiles**
- View personalized profiles displaying **user-specific rooms, messages, and activities**.
- Update profile details, including profile images.

### 6. **Admin-like Controls**
- Room and message management with permissions to update or delete by respective owners.

---

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: Django Templates, HTML, CSS, Bootstrap
- **Database**: SQLite (default)
- **Authentication**: Django's built-in user authentication system

---

## 👥 User Roles

- **Host**: A user who creates a study room and manages its content.
- **Participant**: Users who join rooms and participate in discussions.

---

## 🔄 Workflow

### 1. **Login and Registration**
- Users register with their details or log in with existing credentials.
- Upon successful login, users are redirected to the home page.

### 2. **Home Page**
- Lists available study rooms based on topics or search queries.
- Displays recent activities from discussions.

### 3. **Room Management**
- Hosts can **create, update, or delete rooms**.
- Participants can **post messages and interact** within the rooms.

### 4. **Profile and User Updates**
- Users can view their engagement (rooms joined, messages posted).
- Profiles are customizable with updated details and profile pictures.

---


