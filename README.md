# MovieBox v22.0 — Movie & Web Series Streaming Catalog with 3-Step Animated Welcome, 5-Digit Share Code Redeem & Admin Panel

## What's new in v22.0
- **Removed Old Loading Screen & Added 3-Step Animated Welcome Showcase (`SplashScreen.kt`)**:
  - **Step 1 — New & Recently Updated Movies**: Live TMDB-fetched movie poster wall in the background with the **Recently Updated Movie** highlighted in the center spotlight card, paired with information about new movie releases and a **Next** button.
  - **Step 2 — Trending Web Series**: Animated Web Series poster showcase featuring multi-season Web Series posters and information about complete seasons and episodes, with a **Next** button.
  - **Step 3 — Instant Play, Offline Download & 100% No Ads**: Animated feature showcase highlighting 1080p Full HD Play, Smart Offline Downloads (watch without internet), and a 100% Ad-Free streaming experience, with a **Start Watching Now** button.
- **All v18.0 Features Preserved**:
  - Real Device ID (`Settings.Secure.ANDROID_ID`) & 5-digit Share Code registration in Firebase (`/users/{uid}` and `/shareCodes/{shareCode}`).
  - Strict Firebase 5-digit Share Code verification (only real codes registered in Firebase can be redeemed; random codes are rejected).
  - Admin Panel User Management (click user for full details, set VIP Points to Access) and VIP / Free selector on Movie & Web Series upload pages.
