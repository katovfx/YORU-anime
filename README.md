# Yoru+

**Yoru+ is a desktop anime app for Windows that keeps your watching in one place.** Sign in with AniList and your lists come with you: Planning becomes My List, Watching becomes Continue Watching, and finishing an episode updates your progress. Episodes play in a custom player with intro and outro skipping, GPU upscaling, styled subtitles, screenshots and clips. Watching earns XP and ranks on a Yoru+ leaderboard, with daily and weekly goals. Your settings and profile sync to the Yoru+ web app on your phone.

> Personal project. Yoru+ links to video hosted on third-party services and stores no video files on its server.

## Features

### Watching
- **Home, Browse, Schedule and Search**: banners and rows built from AniList, with high-res backdrops and title logos, trailers, and the airing schedule.
- **Show pages**: every episode with its thumbnail and your progress, other seasons, related shows and recommendations.
- **The player**:
  - **Controls and navigation**: a dark control panel along the bottom, sub/dub, server picker, previous/next episode, theater mode, fullscreen, picture-in-picture and a mini player.
  - **Auto skip**: skips intros and outros automatically.
  - **Upscaler**: Anime4K upscaling on the GPU.
  - **Subtitles**: drawn in Yoru+'s own style (SRT, WebVTT and ASS).
  - **Captures**: screenshots and clips.
  - **Markers and notes**: bookmarks on an episode, each with a note.
- **Resume**: every episode picks up where you left off. The next one starts when this one ends.
- **"Are you still watching?"**: after 3.5 hours of playing with no one touching the window, the episode pauses and asks.
- **Library**: download episodes and watch them offline.
- **Manga**: a reader for manga, in its own tab.

### Your account
- **AniList is your account.** Yoru+ has no accounts or passwords of its own. AniList checks your password in its own sign-in window, and the app keeps the sign-in key on your PC.
- **Profile**: a Yoru+ display name, bio, picture and banner shown over your AniList ones.
- **Settings sync**:
  - **What syncs**: theme, layout, language, playback choices and profile, kept the same on the PC app and the phone web app.
  - **How it works**: sync is on by default, under a private random sync key; the server keeps only a hash of it. To share one profile, pair another device once with a 6-character code.
- **Ratings**: rate a show (saved as your AniList score) or an episode (Yoru+'s own ratings, with everyone's average). 5 stars, with half stars.

### XP, ranks and the leaderboard
- **Earning XP**: 60 XP a minute of real watching, 300 for an episode once you've watched at least 15 minutes of it, and 740 for finishing a whole series (once per series). Skipping through doesn't count.
- **Double XP**: on holidays and during events.
- **Goals**: daily goals (watch 30 minutes, finish 2 episodes) and weekly goals (watch 5 hours, 10 episodes, finish a series, rate 3 episodes) pay bonus XP.
- **Ranks** (7, themed on Black Clover's devil system, each with its own badge): Devil Contract → Hybrid Devil → Low-Rank Devil → Mid-Rank Devil → High-Rank Devil → Supreme Devil → Underworld King.
- **Leaderboard**:
  - **What it shows**: this week or all time, sorted by XP, watch time or episodes, with the top 3 on a 3D podium of slowly turning columns.
  - **Privacy**: showing up on the board, with your name and picture, is your choice.
- **Cheating**: the server checks every XP report, so it can't be faked.

### The app
- **Looks**: themes and two layouts, with an optional tint that matches the show you're on.
- **Languages**: the app comes in several languages.
- **Updates**: in-app updates, signed, installed from the app.
- **Crash reports**: sent automatically, with no names, keys or files. You can turn them off in Settings.

## The phone web app

Open **https://watch.yoruplus.dev** on your phone and add it to the Home Screen. It has the same account, profile, XP, goals, ratings and leaderboard as the PC app; pair it with your PC once under Settings → Sync.

## Building

You need Windows
