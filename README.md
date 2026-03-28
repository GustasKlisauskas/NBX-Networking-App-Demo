# NBX Connect — Networking App

Interactive React prototype for **NBX Connect**, a networking app designed for [Next Block Expo 2026](https://nextblockexpo.com) in Warsaw, Poland.

## Overview

NBX Connect helps conference attendees discover people, schedule meetings, manage connections, and chat — all from a single mobile interface.

## Screens

- **Home** — Greeting, quick stats (Meetings / Connections / New Requests), upcoming meetings, and full event agenda with Day 1 & Day 2 tabs
- **Connect** — Discover new people, view connected contacts, and manage incoming connection requests across three tabs
- **Meetings** — Day-by-day meeting schedule with confirmed/pending sections, gap indicators, and manage/reschedule/cancel flows
- **Chat** — Connected chats and connection requests with inline meeting request bubbles (Accept / Decline / Reschedule), schedule status icons, and full message history
- **Profile** — Editable profile (name, title, bio, interests, looking for), avatar picker, VIP ticket with QR code

## Features

- Multi-state meeting lifecycle: Schedule → Pending → Booked, with reschedule/cancel at any stage
- Cross-screen state consistency (chat list icons, chat header, message bubbles all reflect the same status)
- Incoming meeting request detection with "Respond" indicators and badge counts
- Connection request flow with Accept/Decline and auto-removal of declined cards
- Editable profile with toggleable interest/skill chips
- Inline VIP event ticket with QR code pointing to [beawhale.io](https://beawhale.io)

## Tech Stack

- React (JSX) with hooks for state management
- Lucide React icons
- Base64-embedded images (built via sharp)
- Tailwind-inspired inline styles
- Mobile-first layout (375×812px)

## Getting Started

This is a single-file React component (`nbx-networking-app.jsx`) designed to run in any React environment that supports JSX.

## Built By

[BeAWhale](https://beawhale.io) — Blockchain Design & Development Agency
