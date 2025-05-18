# Project-

# KidSmart – Adaptive Learning Platform for Children with Learning Disabilities

KidSmart is a mobile and web-based learning platform designed to support children (ages 4–9, PP2 to Grade 4) with learning disabilities such as dyslexia and ADHD. It focuses on improving English language skills through multisensory, interactive learning aligned with Kenya's Competency-Based Curriculum (CBC).

## Features

- **Structured English Lessons**: Aligned with Kenya's CBC from PP2 to Grade 4
- **Multisensory Learning**: Combines audio, visual, and interactive activities
- **Non-AI Adaptive Logic**: Lessons adjust based on rule-based performance tracking
- **Progress Tracking**: Enables parents and teachers to monitor learner progress
- **Offline Access**: Lessons and data are accessible without internet
- **Parent Dashboard**: For monitoring and managing child accounts
- **Subscription Model**: Affordable plans with MPESA integration

## Target Users

- Children aged 4–9 years (PP2–Grade 4) with learning challenges
- Parents of children with dyslexia, ADHD, or slow learning
- Schools and integrated learning centers

## Technology Stack

- **Frontend**: React Native (mobile), React.js (web)
- **Backend**: Node.js, Express.js
- **Database**: Firebase or MongoDB
- **Design**: Figma, Adobe XD
- **Authentication**: Firebase Auth
- **Payment Integration**: MPESA Daraja API
- **Notification**: SMS API via Africa's Talking

## Folder Structure

```bash
kidsmart/
├── client/                  # React/React Native UI
├── server/                  # Node.js + Express API
├── database/                # MongoDB schema or Firebase rules
├── assets/                  # Audio, images, animations
├── docs/                    # Design and curriculum reference
└── README.md
```

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/kidsmart.git
cd kidsmart
```
2. Install dependencies:
```bash
npm install
```
3. Set up environment variables for Firebase, MPESA, and SMS APIs
4. Start development servers:
```bash
npm run dev
```

## Curriculum Alignment

KidSmart follows Kenya's CBC for English Language, covering:
- Phonemic awareness
- Reading and writing fundamentals
- Vocabulary building
- Comprehension and fluency

## Milestones
- **Phase 1**: Curriculum mapping and design (PP2–Grade 4)
- **Phase 2**: Prototype with English learning modules
- **Phase 3**: Offline features and parental dashboard
- **Phase 4**: Pilot testing and feedback in integrated schools

## License
MIT License

## Contributors
- Developer Name (Your Name)
- Supervisor Name (Project Supervisor)

---
KidSmart is designed to ensure every child, regardless of learning speed or challenges, has the opportunity to succeed.
