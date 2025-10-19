## Case Title
AI Study Buddy

## Background
Students often spend a lot of time reading and processing the syllabus, but lack effective tools to structure and review the material. Notes, slides, and academic texts easily become confusing, and traditional learning methods like manual summaries and flashcards are time-consuming. At the same time, the use of artificial intelligence is becoming increasingly relevant in academic contexts.

## Purpose
Develop an application that helps students learn more effectively by using AI to analyze uploaded documents and generate summaries, flashcards, and quiz questions. The application should function as a personal learning assistant that both provides academic support and teaches the student how AI can be used as a tool for text processing and learning

## Target Users
Students in higher education (university, college)
Course participants and self-learners who use digital notes
Teachers who want to create automatic review sheets for courses

## Core Functionality
Secure sign-up/login; save materials, sessions, and quiz results.

### Must Have (MVP)
User registration and login (storing materials and results)
Document upload (PDF, Word, text)
AI generation of:
Summaries (short, medium, detailed)
Flashcards (question/answer format)
Multiple-choice quiz questions
Language options: Norwegian and English
Saving and downloading results (PDF/text)

### Nice to Have (Optional Extensions)
Speech-to-text from lecture recordings
Sharing notes or quizzes with other users
Personal learning statistics (scores over time)

## Data Requirements
User: ID, email, password (hash), language settings
Uploaded Files: file type, course code, language, upload date
Generated Output: summaries, flashcards, quiz, keywords, references to sources/pages

## User Stories (Optional)
[Brief scenarios describing how users will interact with the system]

As a student, I can upload lecture notes and receive a concise exam-prep summary.
As a student, I can generate flashcards from course materials to practice key terms.
As a student, I can select summary depth (short/medium/detailed) to fit my needs.
As a student, I can take quizzes generated from my own materials to check retention.
As a user, my data is stored securely so I can sign in and access past outputs.

## Technical Constraints
[Any specific requirements or limitations]

Web-first application with mobile support (responsive).
Use managed AI providers Gemini CLI.
Secure, encrypted file upload; max size 10 MB per file.
Employ AI during development for code suggestions, testing, docs.
Human-in-the-loop: all AI outputs require review prior to use.
Privacy: securely store user data; no sharing with AI vendors without explicit consent.

## Success Criteria
[How will you know the application is successful?]

Latency: AI outputs delivered ≤10 seconds after upload.
Usefulness: ≥80% of test users rate outputs as helpful for revision.
Bilingual robustness: No functional errors in Norwegian or English.
Reliability: Stable save & retrieve of prior generated materials.
Usability: First-time users can complete core tasks without training

