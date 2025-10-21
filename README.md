# Mp3SuperPlayer
A web music player that’s got all the vibes: the slick Spotify polish, buttery Apple Music UX, stacked with gamification, achievements, playlists, streaks, mini-games, visualizer, and a sick leaderboard. Custom PNG button set for that real shiny look. Browser stats/profile saving—ready for Vercel deploy, runs everywhere.



🚀 Features
--------------------------------------------------------------------------------------
-🔥 Killer Spotify + Apple UI DNA

-🕹️ MP3 playback with playlists, shuffle, repeat, like

-🍕 Gamification: XP, levels, streaks, trophies, daily quests, stats

-🏆 Achievement gallery (with PNG trophies)

-🥇 Leaderboard: see your stats vs others

-🎨 Audio visualizer (animated)

-🛠️ Playlist builder and track liking

-🧠 Mini quiz game

-💾 In-browser save game/profile, fast load

-☁️ Cloud sync stubs—just wire it to Firebase/Supabase to go global

-🔥 PNG buttons ripped off Apple/Spotify style


--------------------------------------------------------------------------------------


📦 Dependencies

Make sure you have these node modules installed (comes with npm install):

next (React framework)
react / react-dom (library base)
typescript (typing)
uuid (for IDs)
idb (for IndexedDB if you wanna expand to real cloud saves)
eslint + @types for lint/type safety
All shipped in the bundled package.json.

--------------------------------------------------------------------------------------

🛠️ Setup

1. Clone or extract the ZIP
git clone https://github.com/YourUser/Mp3SuperPlayer.git
# OR 
(idk how to do this one if you do feel free to do it)
1. unzip Mp3SuperPlayer.zip
2. cd Mp3SuperPlayer

3. Drop your PNG buttons and MP3 files in /public/buttons/ and /public/music/
4. Install all dependencies
5. npm install

# OR

-Run it locally (or however you do it idk)

1. npm install

2. npm run dev or npm start

3. open http://localhost:3000

--------------------------------------------------------------------------------------

🌍 Deploy to Vercel
-One-click deploy:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FElite4EverX%2FMp3SuperPlayer)


# OR

-Manual:

1. Log into Vercel and hit “New Project”

2. Point it at your GitHub repo or upload ZIP

3. Hit “Deploy”

4. 🎉 Listen and flex

--------------------------------------------------------------------------------------

🧠 FAQ

Q: Where are my stats saved?
---------------------------- 
  A: Browser localStorage—streaks, likes, playlists, achievements reload whenever you return.

Q: Can I add real cloud sync?
 ----------------------------
  A: Hell yeah—just hook the /utils/cloudSync.ts to Firebase/Supabase.

Q: How do I add new features?
 ----------------------------
  A: Add new components yourself or ask Personal Bot for upgraded code.

--------------------------------------------------------------------------------------

🤘 Credits

Student^2 and Personal Bot: Built by a dude in school and a bot with zero chill and infinite code hustle.
