# ValQuiz

A Real-Time Multiplayer Quiz Platform Powered by Valkey

---

## Attendee/Team Details

**Name:** Vinayak Santosh
**GitHub Username:** Rinzlertron456
**LinkedIn Profile:** [www.linkedin.com/in/vinayak-santhosh-sreeramula](http://www.linkedin.com/in/vinayak-santhosh-sreeramula)
**GitHub Project Repository:** https://github.com/Rinzlertron456/kahoot_valkey

---

## Problem Statement Selected

### Kahoot-like Quiz Game

Build a real-time multiplayer quiz game (Kahoot-style) using Valkey for game state, player scores, leaderboards, and pub/sub for live question broadcasting.

---

## Project Description

ValQuiz is a real-time multiplayer quiz platform inspired by Kahoot, built using Valkey as the core real-time engine. The platform enables hosts to create and conduct interactive quiz sessions while participants join using a game PIN and compete in real time.

The project is designed for educators, trainers, event organizers, students, and communities who need an engaging quiz experience. Beyond replicating traditional quiz platforms, ValQuiz focuses on solving common challenges such as unfair scoring due to network latency, bot participation, limited player scalability, and lack of intelligent quiz creation tools.

The platform leverages AI-powered quiz generation, real-time leaderboards, latency-aware scoring, and a scalable game engine to provide a more inclusive, reliable, and modern quiz experience.

---

## Approach

The project was designed around Valkey's strengths in high-speed data access, pub/sub communication, streams, and sorted sets.

My approach included:

* Building a React-based frontend for hosts and players.
* Using Node.js and Socket.io as the real-time game engine.
* Using Valkey for game state management, scoring, leaderboards, pub/sub communication, and anti-bot protection.
* Introducing an AI microservice using FastAPI and Gemini API to generate quizzes automatically from topics or text.
* Using Supabase for persistent storage, authentication, and quiz management.
* Designing a latency-aware scoring system that compensates for network delays.
* Implementing scalable architecture capable of supporting large multiplayer sessions.

What makes ValQuiz different is its focus on fairness, accessibility, AI-assisted content creation, and solving several limitations commonly found in existing quiz platforms.

---

## Tech Stack and Tools Used

**Frontend:** React 19, TypeScript, Vite, Redux Toolkit, RTK Query, CSS Modules

**Backend:** Node.js, Express.js, Socket.io, FastAPI

**Database:** Supabase PostgreSQL

**AI Tools/API:** Gemini API, FastAPI, Pydantic

**Cloud/Deployment:** Docker, Docker Compose, Supabase

**Other Tools:** Valkey, iovalkey, GitHub, Postman, Socket.io, Docker Desktop

---

## Key Features

1. Real-time multiplayer quiz sessions with live leaderboards.
2. AI-powered quiz generation from topics and custom text.
3. Latency-compensated scoring for fair competition.
4. Valkey-powered pub/sub question broadcasting.
5. Anti-bot protection using rate limiting and device fingerprinting.
6. Host dashboard for managing quiz sessions.
7. Multiple scoring modes (Classic, Balanced, Accuracy).
8. Real-time ranking updates using Valkey Sorted Sets.
9. Persistent quiz storage and management using Supabase.
10. Responsive player experience across devices.

---

## What is Working?

* React frontend setup and navigation.
* Node.js game server architecture.
* Socket.io real-time communication flow.
* Valkey integration for game state and leaderboard management.
* Supabase schema and database design.
* AI quiz generation service architecture using FastAPI and Gemini.
* Docker-based local development environment.
* Real-time multiplayer game lifecycle design.

---

## What is Still in Progress?

* Complete integration of all game screens.
* Advanced leaderboard animations and UI polish.
* AI-generated explanations for quiz answers.
* Additional accessibility improvements.
* End-to-end testing and load testing.
* Production deployment and monitoring.
* Enhanced analytics and game reporting.

---

## Screenshots or Demo

**Deployed Link:** Not yet deployed

**Demo Video Link:** To be added

**Screenshots:**

* Home Page
* Host Dashboard
* Quiz Creation Page
* AI Quiz Generator
* Live Leaderboard
* Player Question Screen

---

## Challenges Faced

Some major challenges encountered during development include:

* Designing a scalable real-time architecture.
* Handling fair scoring despite varying player network latency.
* Structuring Valkey data models efficiently for game state and leaderboards.
* Integrating AI-generated quiz content while maintaining data validation.
* Managing communication between React, Node.js, FastAPI, Valkey, and Supabase services.
* Ensuring resilience against bot joins and duplicate participants.

---

## Learnings

Through this project, I gained hands-on experience with:

* Advanced Valkey features such as Pub/Sub, Streams, Sorted Sets, and Lua scripts.
* Real-time application architecture using Socket.io.
* Designing scalable multiplayer systems.
* FastAPI microservice development.
* AI integration using Gemini API.
* PostgreSQL schema design with Supabase.
* Docker-based multi-service deployment.
* Building latency-aware systems for fair user experiences.

---

## Future Improvements

Given more time, I would like to add:

* Voice-based quiz participation.
* AI-generated images and multimedia questions.
* Team-based game modes.
* Detailed player analytics dashboards.
* Tournament and bracket systems.
* Offline-first support with synchronization.
* Mobile application support.
* Multi-language quiz generation and translation.
* Advanced moderation and classroom management tools.

---

## Final Note

ValQuiz was built to demonstrate how Valkey can power highly interactive, real-time applications beyond traditional caching use cases. The project combines real-time multiplayer gameplay, AI-assisted content creation, and scalable architecture to create a modern learning and engagement platform.

The goal was not only to recreate a Kahoot-like experience but to address many of its limitations through fairness-focused scoring, AI automation, accessibility improvements, and an open, scalable architecture.

This project represents my interest in combining Full Stack Engineering, Real-Time Systems, AI, and Modern Cloud Architecture into a single impactful solution.
