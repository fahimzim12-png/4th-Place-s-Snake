# The 4th Place - Cravings Chase

Snake game for The 4th Place event (3 November 2026, BUP Campus).

## Files
- index.html - page
- style.css - styles
- game.js - game, music, sounds, leaderboard
- audio/khaichi.wav - the "khaichi" voice played when the snake eats

## Publish on GitHub Pages
1. Create a new repository and upload everything in this folder (keep the audio folder).
2. Settings > Pages > Source: Deploy from a branch > main > / (root) > Save.
3. After a minute the game is live at https://YOUR-USERNAME.github.io/REPO-NAME/

## Notes
- Open through a web server or GitHub Pages. Double-clicking index.html may block the audio file (browsers block fetch from file://). To test locally run: python3 -m http.server
- The leaderboard saves scores on each player's own device only. For a shared top 3, connect the submit step to a Google Form/Sheet or Firebase.
- Music and the death scream are generated in code (Web Audio), no files needed.
