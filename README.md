# Hot Ice

Hot Ice is a mobile-first daily sports player guessing game.

## Public Beta v51 No Soccer + Roster Refresh + Share Fix

Updates:
- Removed soccer/Premier League players from the player pool and daily answer pool
- Game now focuses on NFL, MLB, and NBA
- Preserved compact match details under each guess
- Kept Reddit-style clean list UI
- Improved roster refresh:
  - MLB refresh still uses the MLB 40-man roster API
  - NFL refresh now updates current team/conference/division/position details from Sleeper player data
  - NBA refresh now pulls current team rosters from ESPN’s public team roster endpoints
- Isolated v51 community stats from older puzzle versions because the answer pool changed
- Fixed native Share so it does not show two “Play Hot Ice” links
  - Native share uses one URL field
  - Copy Result still includes the link text for texting/pasting
- Keeps live community stats, How To Play, daily save/lock, Share Result, Copy Result, mobile layout, streaks, transparent logo, and analytics

Player pool change:
- Removed 241 soccer/Premier League players from the embedded pool

Live site:
https://playhotice.com/
