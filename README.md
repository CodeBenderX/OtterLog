# OtterLog
**Description:**
A minimal, privacy-first daily log app to track your day from start to finish. Start your day, jot your thoughts, select your mood, and mark “Done for today” — all stored locally on your device. No servers, no cloud, just your data. Built with React, Tailwind CSS, and Capacitor for web and mobile.

**Features:**
Start Day / End Day logging
Daily journal entry
Mood selector with emojis
Local notifications for reminders
History view of past entries
Privacy-first: all data stays on device

**Tech Stack:**
React + Vite
Tailwind CSS
Capacitor (for iOS/Android)
IndexedDB for local storage

**Folder Structure**
app/
  layout.tsx          # Root layout with fonts and metadata
  page.tsx            # Main entry point
  globals.css         # Theme colors and Tailwind config
components/
  app-shell.tsx       # Navigation state manager
  bottom-nav.tsx      # Tab navigation (Home, History, Settings)
  mood-selector.tsx   # Emoji mood picker
  journal-input.tsx   # Text area with character count
  screens/
    home-screen.tsx     # Today's logging view
    history-screen.tsx  # Past entries list
    settings-screen.tsx # App preferences
hooks/
  use-daylog-store.ts # SWR-based state management with localStorage
lib/
  types.ts            # TypeScript interfaces

**Goal:**
Fast, lightweight, and zero-cost diary/scheduler app with a simple, friendly UX. Perfect for productivity, reflection, and mindful daily tracking.

**License:** MIT
