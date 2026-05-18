# MO$EAN Platform

Full-stack artist/community platform combining music, merch, memberships, rewards, locked downloads, live rooms, and payments.

> Source code is private. This repo is a public technical showcase for hiring/portfolio review.

## What I Built

- React/TypeScript frontend with pages for marketplace, music, merch, community, updates, profile, downloads, auth/payment flows, and member dashboard.
- Express/TypeScript backend with route modules for auth, music, merch, community, vault, streams, rewards, notifications, support, memberships, playlists, checkout, badges, challenges, token store, activity tracking, and account management.
- Membership and rewards system with badges, challenges, leaderboards, downloads, billing invoices, and activity history.
- Vault/download system for locked and unlocked content, purchase history, re-download tracking, and member-only access.
- Realtime features using Socket.io and LiveKit-style voice/video/live room infrastructure.
- Payment and Web3 integrations with Stripe, Solana Pay, wallet adapters, and token-store style purchase/exchange flows.
- Media handling with Cloudinary/Multer and player/UI features for tracks, playlists, playback history, and content updates.

## Technical Scope

- **Frontend:** React, TypeScript, Tailwind, Zustand, React Router, Three.js/react-three/fiber, Framer Motion, GSAP
- **Backend:** Node.js, Express, TypeScript, MongoDB/Mongoose, Passport, JWT, sessions
- **Realtime/media:** Socket.io, LiveKit, Stream Chat-style UI, Cloudinary
- **Payments/Web3:** Stripe, Solana Pay, Solana web3.js, wallet adapters
- **Security/ops:** helmet, CORS, rate limiting, validators, Winston, Jest

## Engineering Notes

- Built as a real product surface rather than a static artist site: auth, billing, vault access, rewards, and community state are all modeled.
- Combined traditional SaaS patterns with music/product/community features.
- Used realtime infrastructure for member chat, streams, and live interactions.

