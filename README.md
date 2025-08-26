# OnlyBuns — Social Network for Bunny Lovers 🐇

> Central repository for the **OnlyBuns** project.  
> A social media platform where users can create posts, follow each other, like and comment on posts.

[➡️ Frontend repository](https://github.com/MilanUD/isa-onlybuns-fe)  
[➡️ Backend repository](https://github.com/MilanUD/isa-onlybuns-be)

---

## 🎯 About
OnlyBuns is a social network built for rabbit enthusiasts.  
Users can:
- Create posts (text + images)
- Follow/unfollow other users
- Like posts
- Comment on posts

---

## ✨ Key Features
- News feed with posts from followed users  
- User profiles with followers/following lists  
- Likes and comments system  
- Authentication & authorization (JWT/OAuth)  
- Image uploads

---

## 🧱 Technologies
- **Frontend:** Vue 3  
- **Backend:** Spring boot 
- **Database:** PostgreSQL 

---

## 🧭 Architecture
- Separate frontend and backend repositories  
- REST API backend with endpoints for posts, users, follows, likes, comments  
## 🛠 Technical Highlights

- **Rate Limiting**
  - *Custom implementation* — built my own middleware for API rate limiting.  
  - *Library-based solution* — integrated an external rate limiting library. 
- **Database Transactions (@Transactional)** — used to ensure consistency when liking a post.  
- **Inactive User Email Notifications** — scheduled background job that sends reminder emails to inactive users.  
- **Daily Image Compression** — background job that compresses uploaded images once per day to optimize storage.  
- **Image Upload** — implemented file upload.  

