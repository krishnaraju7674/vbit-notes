Project Overview
Name: VBIT NoteShare
Purpose: Web app for VBIT students to upload, share, and download study notes (PDFs/images) with metadata like branch, year, semester, subject.
Type: Single-page static HTML app (no server needed).
Tech: HTML/CSS/JS frontend, Supabase backend (auth, database, storage).
Files
index.html: Main app file (~1200 lines, includes all code).
README.md: Project documentation (created earlier).
Features
User signup/login with email/password.
Upload notes with drag-drop, preview, and required fields.
Browse notes with search/filter by branch/year/etc.
Download files, like/rate notes.
Profile page for user's uploads.
Mobile-responsive design.
Logout button (desktop/mobile).
Supabase Setup
URL: https://gsufmznjaphalkyyrwcf.supabase.co
Anon Key: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6ImdzdWZtem5qYXBoYWxreXlyd2NmIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NzYwMDA3OTQsImV4cCI6MjA5MTU3Njc5NH0.tNYQuPxPYjpE5RglBUCl1lg7EhEsc9v6mYaIzDD0bMQ
Tables: notes (id, title, uploader, branch, year, semester, subject, topic, type, file_url, likes, ratings).
Storage: Bucket for uploaded files.
Deployment
Static hosting: GitHub Pages, Netlify, Vercel.
Steps: Upload index.html to repo root, enable Pages from main branch.
URL: https://yourusername.github.io/repo-name
Curriculum Data
Subject lists for 1st-4th year, all branches (CSE, ECE, etc.), semesters 1-8.
Hardcoded in JS for offline use.
Troubleshooting Blank Screen
Test locally: Open index.html in browser.
Check console for JS errors (F12 > Console).
Ensure repo is public, file in root, Pages enabled.
