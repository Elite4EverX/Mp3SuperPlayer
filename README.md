# Mp3SuperPlayer
A web music player that’s got all the vibes: the slick Spotify polish, buttery Apple Music UX, stacked with gamification, achievements, playlists, streaks, mini-games, visualizer, and a sick leaderboard. Custom PNG button set for that real shiny look. Browser stats/profile saving—ready for Vercel deploy, runs everywhere.



🚀 Features

🔥 Killer Spotify + Apple UI DNA
🕹️ MP3 playback with playlists, shuffle, repeat, like
🍕 Gamification: XP, levels, streaks, trophies, daily quests, stats
🏆 Achievement gallery (with PNG trophies)
🥇 Leaderboard: see your stats vs others
🎨 Audio visualizer (animated)
🛠️ Playlist builder and track liking
🧠 Mini quiz game
💾 In-browser save game/profile, fast load
☁️ Cloud sync stubs—just wire it to Firebase/Supabase to go global
🔥 PNG buttons ripped off Apple/Spotify style


📦 Dependencies

Make sure you have these node modules installed (comes with npm install):

next (React framework)
react / react-dom (library base)
typescript (typing)
uuid (for IDs)
idb (for IndexedDB if you wanna expand to real cloud saves)
eslint + @types for lint/type safety
All shipped in the bundled package.json.



🛠️ Setup

Clone or extract the ZIP
git clone https://github.com/YourUser/Mp3SuperPlayer.git
# OR
unzip Mp3SuperPlayer.zip
cd Mp3SuperPlayer

Copy
Drop your PNG buttons and MP3 files in /public/buttons/ and /public/music/
Install all dependencies
npm install

Copy
Run it locally
npm run dev
# open http://localhost:3000

Copy


🌍 Deploy to Vercel

One-click deploy:
button.svg
OR

Manual:
Log into Vercel and hit “New Project”
Point it at your GitHub repo or upload ZIP
Hit “Deploy”
🎉 Listen and flex


🧠 FAQ

Where are my stats saved?
Browser localStorage—streaks, likes, playlists, achievements reload whenever you return.
Can I add real cloud sync?
Hell yeah—just hook the /utils/cloudSync.ts to Firebase/Supabase.
How do I add new features?
Add new components or ask Personal Bot for upgraded code.


🤘 Credits

Student^2 and Personal Bot: Built by a dude  in school and bot with zero chill and infinite code hustle.
