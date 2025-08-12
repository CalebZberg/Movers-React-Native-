# College Movers – Mobile (React Native)

A mobile app for managing moving jobs, schedules, and status updates.  
Connects directly to the existing Bubble backend.

## Features (planned → shipping)
- Auth (login/logout)
- Jobs list (assigned, upcoming, completed)
- Job detail (address, notes, contact info)
- Clock in/out + status updates
- Offline-friendly UI (caching recent jobs)
- Error/retry & loading states

## Tech Stack
React Native (Expo) · TypeScript  
Navigation (React Navigation) · Zustand (state management)  
HTTP (fetch/axios) · Form validation (Zod/Yup)  
Testing (Jest + React Native Testing Library)

## Quick Start
```bash
git clone https://github.com/<your-username>/college-movers-rn.git
cd college-movers-rn
npm install
npx expo start
# press i (iOS simulator) or a (Android emulator) or scan QR on device

Current Status: Scaffold only
License: MIT
