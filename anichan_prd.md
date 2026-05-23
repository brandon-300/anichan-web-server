# AniChan Product Requirements Document (PRD)

## Project Overview
AniChan is a complete anime social platform featuring real-time chat, profile management, and an anime discovery engine. Built with vanilla JS and Supabase v2.

## Core Tech Stack
- Frontend: Pure HTML, CSS, Vanilla JavaScript (Tailwind CSS for utility-first styling).
- Backend: Supabase v2 (Auth, DB, Storage, Realtime).
- API: Jikan API (MyAnimeList wrapper) for anime metadata.

## Global Requirements
- Multi-lingual support (i18n.js) for EN, JA, ZH, DE, FR.
- Dark mode primary theme with premium UI.
- Real-time updates for chat, presence, and site settings.
- Admin-only English-only dashboard for site management.

## Screen List
1. **user_login.html**: Sliding login/signup, age calculation, validation.
2. **forgot_password.html**: Username lookup and reset trigger.
3. **reset_password.html**: Secure password update.
4. **index.html**: Homepage with Jikan integration, search, and real-time banners.
5. **find_friends.html**: User discovery and DM shortcuts.
6. **profile.html**: Editable personal profile and read-only visitor view.
7. **chat.html**: Real-time DM system with typing indicators and message management.
8. **admin_login.html**: Secure gateway for staff.
9. **admin.html**: CRUD for anime, user management, and site-wide broadcast control.
