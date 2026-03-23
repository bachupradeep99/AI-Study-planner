# AI Study Planner

A smart, offline, browser-based **personalized study scheduler** built with HTML, CSS (Tailwind), and vanilla JavaScript.

It helps students create optimized daily study timetables based on subjects, topics, deadlines, priorities, and available daily study hours — with automatic revision time allocation, dynamic rescheduling, progress tracking, and Pomodoro-style break suggestions.

![AI Study Planner Screenshot](https://via.placeholder.com/1200x600/4f46e5/ffffff?text=AI+Study+Planner+Screenshot)  
*(Replace this placeholder with a real screenshot later)*

## Features

- Add subjects/topics with estimated hours, deadline & priority
- Automatically adds 20% revision time per subject (lower priority)
- Greedy scheduling algorithm (earliest deadline first → highest priority)
- Dynamic rescheduling when you mark sessions as complete
- Daily study hours limit + balanced workload distribution
- Today's Focus section + full schedule view
- Progress analytics (percentage, completed/remaining hours, days left)
- Edit/delete tasks, clear all data
- Export / Import JSON backup
- Dark mode + responsive design (mobile-friendly)
- 100% offline – uses browser **localStorage**
- No backend, no login, no installation required

## Tech Stack

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript (no frameworks)
- localStorage for persistence
- Date API for deadlines & scheduling

## Project Structure
