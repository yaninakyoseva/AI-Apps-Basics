
# 💡 Idea Tracker – IdeaSpark

**Course:** AI Apps Basics – SoftUni AI  
**Exercise:** Database Apps with AI Prompts  
**Project:** 03 – Idea Tracker

## 📌 About the Project

IdeaSpark is an AI-assisted web application for sharing, discovering, and voting on ideas.

Visitors can explore community ideas, while registered users can submit new ideas and participate in voting.

The application is designed to use Supabase for authentication and persistent data storage.

## ✨ Features

- 💡 Browse community ideas
- 📝 Submit new ideas
- 👍 Upvote ideas
- 👎 Downvote ideas
- 🔐 User registration and login
- 👤 User-specific voting
- 🗳️ One active vote per user per idea
- 📊 Display voting scores
- 📱 Responsive interface

## 🛠️ Technologies Used

- Lovable
- React
- TypeScript
- Supabase
- PostgreSQL
- Supabase Authentication
- GitHub

## 🗄️ Database Integration

The application is designed around two main tables:

### Ideas
- `id` – Unique idea identifier
- `title` – Idea title
- `description` – Idea description
- `user_id` – Author identifier
- `created_at` – Creation timestamp

### Votes
- `id` – Unique vote identifier
- `idea_id` – Related idea
- `user_id` – Voting user
- `vote_type` – Upvote (+1) or downvote (-1)

The voting system is designed to prevent duplicate votes from the same user on the same idea.

## 🎯 Learning Objectives

- Developing applications using AI prompts
- Working with Supabase databases
- Implementing user authentication
- Managing relational data
- Building a voting system
- Practicing database security
- Deploying web applications

## 🚀 Live Demo

🔗 [Try Idea Tracker](https://perfect-page-peek.lovable.app/)

## 🎓 Course Information

**Academy:** SoftUni AI  
**Course:** AI Apps Basics  
**Topic:** Database Apps with AI Prompts  
**Project:** 03 – Idea Tracker

---

⭐ Created as part of my SoftUni AI learning journey.
