# Hot Ice

Hot Ice is a mobile-first daily sports player guessing game.

## Public Beta v45 Community Stats Foundation

Updates:
- Added optional community stats placeholder under the status/search area
- Added safe community stats hooks:
  - first daily guess = played today
  - solved daily puzzle = solved today
  - reveal answer = revealed today, not solved
- Community stats are disabled by default until Supabase URL + anon key are added
- If community stats are not configured or fail, the stat hides and the game continues normally
- Added `supabase-community-stats.sql` setup script for the database/RPC functions
- Keeps How To Play button/modal, latest-guess card, full ranked list, rank-based heat emoji logic, NFL/MLB position-over-division tuning, daily save/lock, Share Result, Copy Result, expanded player pool, NFL/MLB refresh, mobile layout, streaks, transparent logo, and analytics

Live site:
https://playhotice.com/
