
---
## 🚀 LockedIn (Co-Developer)

**Repo:** [GymSnap](https://github.com/ukkandi/Gymsnap)  
**Tech:** React, JavaScript, TailwindCSS, Vite  

A real-time, browser-only gym-tracking and behavior-matching app that uses on-device pose estimation, custom analytics, and dynamic embeddings to understand training style and match users based on consistency, intensity, and behavior patterns.

**My Contributions:**  
- Designed and implemented the Profile + Analytics interface with embedding visualization, training category breakdowns, and activity summaries
- Built the frontend data-flow pipeline connecting rep events → embedding updates → streak engine → UI components
- Developed reusable React components that consume AI-layer and core-logic outputs with consistent state synchronization
- Created UI logic for calendar activity, heatmap data, streak summaries, and training-style analytics with real-time updates
- Contributed to overall interaction design to keep the app cohesive and responsive without a backend

---

## 🚀 PatriotGo (Co-Developer)

**Repo:** [PatriotGo](https://github.com/saumitg26/PatriotGo)  
**Tech:** React Native, Expo, Supabase, Amazon DynamoDB, Amazon Redshift  

A high-performance carpooling platform built for students at George Mason University that enables real-time ride coordination, secure peer-to-peer messaging, and large-scale commute analytics through a hybrid-cloud architecture.

**My Contributions:**  
- Engineered the real-time messaging system using Supabase Realtime (WebSockets), implementing optimistic UI updates and custom message-consistency logic for low-latency communication  
- Architected a hybrid-cloud data pipeline separating operational data (PostgreSQL), high-speed session state (DynamoDB), and long-term analytics workloads (Redshift)  
- Designed and implemented core mobile UI systems including the Live Driver Feed, Floating Island navigation, and safe-area aware layouts  
- Developed authentication flows and enforced Row Level Security (RLS) policies to ensure secure, isolated student data access  
- Built the ride-matching “Pinging” workflow with state-driven UI updates and haptic feedback for high-fidelity interaction  
