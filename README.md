# 🌐 SocialApp

A full-featured **social media platform** built with Django. Users can sign up, create profiles, post content, follow other users, and interact through likes and comments.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Django](https://img.shields.io/badge/Django-4.x-green)
![Python](https://img.shields.io/badge/Python-3.10+-yellow)



## 📌 Features

- 🔐 User registration, login, logout (JWT-based or session-based)
- 👤 Profile creation with avatar, bio, and social links
- 📝 Create/edit/delete posts with media (images/videos)
- ❤️ Like, comment, and follow/unfollow users
- 🔎 Explore feed with trending/public posts
- 📱 Mobile-responsive UI (Django Templates or React Frontend)
- 🛠 Admin panel for user/content moderation

---

## 🏗️ Tech Stack

| Layer        | Technology            |
|--------------|------------------------|
| Backend      | Django, Django REST Framework |
| Auth         | Django Auth / JWT (via djangorestframework-simplejwt) |
| Database     | PostgreSQL / SQLite (dev) |
| Media Upload | Cloudinary / local file storage |
| Frontend     | Django Templates / React (optional) |
| Hosting      | Render / Vercel / Heroku / Railway |
| Analytics    | Google Analytics / PostHog |

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/socialapp.git
cd socialapp

