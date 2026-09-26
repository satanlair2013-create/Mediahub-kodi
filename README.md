# MediaHub — a streaming-style Kodi skin for movies and TV

`skin.mediahub` gives Kodi's movie and TV library a streaming-app home screen: a rotating **hero slider** across the top, a row of **network cards** under it (Disney, Pixar, Marvel, Star Wars, National Geographic, Star), and rows of your movies and shows below. Each network card opens its own **network hub**, which has its own slider at the top and only shows titles from that studio or network.

**To install**, add `https://satanlair2013-create.github.io/Mediahub-kodi/` as a source in Kodi's file manager and follow [Install](#install).

![Home screen](screenshots/home.jpg)

| Network card focused | Network hub (Pixar) |
| --- | --- |
| ![Network cards](screenshots/cards.jpg) | ![Network hub](screenshots/hub.jpg) |
| **Movie library (poster view)** | **Details page** |
| ![Movies](screenshots/movies.jpg) | ![Info](screenshots/info.jpg) |
| **Network card editor** | **Home row editor** |
| ![Card editor](screenshots/card-editor.jpg) | ![Home rows](screenshots/home-rows.jpg) |
| **Up Next row** | **Up Next card at the end of an episode** |
| ![Up Next row](screenshots/up-next-row.jpg) | ![Up Next card](screenshots/up-next-card.jpg) |
| **Episodes (landscape view)** | **Side menu** |
| ![Episodes](screenshots/episodes.jpg) | ![Side menu](screenshots/rail.jpg) |
| **Player bar: clearart, 4K / Dolby / 5.1 badges, languages** | **Subtitle download** |
| ![OSD](screenshots/osd.jpg) | ![Subtitles](screenshots/subtitles.jpg) |
| **Chapters and bookmarks** | **My List row** |
| ![Chapters](screenshots/chapters.jpg) | ![My List](screenshots/my-list.jpg) |
| **Details page: My List, thumbs up / down / love** | **More Like This** |
| ![Details with thumbs](screenshots/details-thumbs.jpg) | ![More Like This](screenshots/more-like-this.jpg) |
| **TV show page with season tabs** | **Actor page** |
| ![Show page](screenshots/show-page.jpg) | ![Actor page](screenshots/actor-page.jpg) |
| **Search** | **Who's watching? with avatars** |
| ![Search](screenshots/search.jpg) | ![Profiles](screenshots/whos-watching.jpg) |
| **Kids mode** | **Pause screen** |
| ![Kids mode](screenshots/kids-mode.jpg) | ![Pause screen](screenshots/pause-screen.jpg) |
| **Skip Intro** | **Audio & Subtitles** |
| ![Skip Intro](screenshots/skip-intro.jpg) | ![Audio and subtitles](screenshots/audio-subtitles.jpg) |
| **Quality badges on the details page** | **NEW badges** |
| ![Quality badges](screenshots/quality-badges.jpg) | ![NEW badges](screenshots/new-badges.jpg) |
| **Collection page** | **Screensaver** |
| ![Collection](screenshots/collection.jpg) | ![Screensaver](screenshots/screensaver.jpg) |
| **Music: now playing** | **Music: album** |
| ![Now playing](screenshots/music-now-playing.jpg) | ![Album](screenshots/music-album.jpg) |
| **Live TV guide** | **Live TV channels** |
| ![TV guide](screenshots/tv-guide.jpg) | ![TV channels](screenshots/tv-channels.jpg) |
| **Trailer preview in a home row** | **Because You Watched and Coming Soon** |
| ![Row preview](screenshots/row-preview.jpg) | ![Because You Watched](screenshots/because-coming-soon.jpg) |
| **Player bar: Finish by and Night mode** | **Search: people and the mic key** |
| ![Finish by](screenshots/osd-watching.jpg) | ![People search](screenshots/search-people.jpg) |
| **Movies filter chips** | **Your year** |
| ![Filter chips](screenshots/movie-filters.jpg) | ![Your year](screenshots/your-year.jpg) |
| **Christmas theme** | **Halloween theme** |
| ![Christmas](screenshots/season-christmas.jpg) | ![Halloween](screenshots/season-halloween.jpg) |
| **Start-up intro** | **Welcome setup** |
| ![Intro](screenshots/startup-intro.jpg) | ![Welcome](screenshots/welcome.jpg) |
| **Banner trailer, greeting and On now** | **Top 10 row** |
| ![Banner trailer](screenshots/hero-greeting-on-now.jpg) | ![Top 10](screenshots/top10.jpg) |
| **Ratings badges and the Family List button** | **Extras** |
| ![Ratings](screenshots/details-ratings.jpg) | ![Extras](screenshots/extras.jpg) |
| **Season progress and Mark season watched** | **After the movie** |
| ![Season progress](screenshots/season-progress.jpg) | ![After the movie](screenshots/post-play.jpg) |
| **Are you still watching?** | **Kids bedtime** |
| ![Still watching](screenshots/still-watching.jpg) | ![Bedtime](screenshots/bedtime.jpg) |
| **Colour from the artwork** | **Lyrics** |
| ![Colour from the artwork](screenshots/art-colour.jpg) | ![Lyrics](screenshots/lyrics.jpg) |
| **On demand** (IPTV playlist as shows and movies) | **Calendar** |
| ![On demand](screenshots/on-demand.jpg) | ![Calendar](screenshots/calendar.jpg) |
| **My Channels** | **Live TV mini guide** |
| ![My Channels](screenshots/my-channels.jpg) | ![Live TV mini guide](screenshots/live-mini-guide.jpg) |
| **Quick menu** | **Library health** |
| ![Quick menu](screenshots/quick-menu.jpg) | ![Library health](screenshots/library-health.jpg) |

The screenshots come from a real Kodi instance running the skin against a small test library of made-up titles.

## Features

- **Welcome setup**: the first time the home screen opens, five quick steps set your colour, what you watch (which picks the home rows), the network cards and profiles (see [Welcome setup](#welcome-setup)).
- **Start-up intro**: while Kodi loads you see a MediaHub splash, and then it comes alive: the logo pops with a burst of light in your accent colour and a short intro sound, and the home screen opens (see [Start-up intro](#start-up-intro)).
- **Hero slider**: a full-width banner with backdrop, clear logo (or the title if there's no logo), year, genre, runtime, rating and plot. It rotates every 9 seconds and shows page dots. Stay on it and the title's **trailer plays silently** on its right. A **greeting** with your avatar sits on top (*Good evening*, *Up late*). Pressing Select opens the details page. In Skin Settings you can make it show random movies, recently added movies, random TV shows or, with [MediaHub IPTV](#mediahub-iptv-xtream-codes), your IPTV service's newest films and series.
- **Network cards**: a slider of cards under the hero, with 38 built-in networks and studios plus 20 custom slots. A card only appears when your library has movies or shows from it. Each card matches items whose *studio* (for movies) or *network* (for TV shows) contains one of two filter words. On the focused card, a light sweeps across every few seconds and the logo gently "breathes".
- **Network hub**: selecting a card opens a page with the network's logo, its own hero slider, *All movies* and *All TV shows* buttons, a "New & Noteworthy" row, and rows for movies and TV shows.
- **Home rows you choose**: up to 12 rows, each set to one of 60 row types and put in any order (see [Home rows](#home-rows)), including **Top 10** rows with big rank numbers, **Because You Watched**, **Coming Soon**, **New This Week**, **Directed By …**, **Marvel in Story Order**, the **Family List**, mood rows like *Feel-Good Movies* and *Short on Time*, and rows from **any add-on's folder**. Hold OK on a row's card to **move or hide the row**. With Live TV there are also **My Channels** (the channels you pick), **On now** and two rows of a **channel group** you choose (Sports, News). **Continue Watching: On Demand** has what you're part-way through from an IPTV catalogue. After time away, a **New since you were last here** banner lists what was added. By default they are Continue Watching, Up Next, My List, Recommended For You, New Movies, New Episodes, TV Shows For You, Collections and Top Rated Movies. A row is hidden when it has nothing in it.
- **Trailer previews**: stay on a movie in a home row for a few seconds and its trailer plays in a small panel at the top right, like Disney+ and Netflix. Moving on stops it (see [Trailer previews](#trailer-previews)).
- **My List and thumbs**: add any movie or show to My List from its details page or the long-press menu, and rate it *Not for me*, *I like this* or *Love this!* (see [My List, thumbs and recommendations](#my-list-thumbs-and-recommendations)). **Recommended For You** learns from your thumbs.
- **Up Next**: a row with the next episode of every show you're part-way through, most recently watched first. Selecting one plays it with the following episodes queued. In the last 30 seconds of an episode, a card in the corner shows which episode plays next.
- **Side menu**: icons down the left edge that open up with labels when you focus them. It has Search, Home, **Surprise me**, Movies, TV Shows, **Calendar**, Music, Live TV, **On demand**, Networks, Favourites, Add-ons, Files, **Your year**, Settings and Power (Music and Live TV appear once you have music or TV channels, **Now playing** appears while music plays, and **Downloads** once you've downloaded something).
- **Search page**: a letter grid you can use with a TV remote (or the normal keyboard), with movies, TV shows, episodes, **people** (actors and directors), **On demand** shows and films and **Live TV channels** from your IPTV playlist appearing as you type. The **mic key** opens the keyboard so you can talk instead: on Apple TV, hold the Siri Remote's mic button (see [Finding something](#finding-something)).
- **Surprise me**: picks something you haven't watched, leaning towards what you like, and opens it.
- **Filter chips on the Movies page**: All, Unwatched, 4K, Under 2 hours, Kids, and the 2020s, 2010s, 2000s, 1990s and older.
- **TV show page**: opening a show gives a Disney+-style page with the backdrop and logo, a *Play* / *Continue S2 E1* button, My List and thumbs, season tabs with a bar showing how much of each season you've watched (*Season 2 • 7 of 10 watched*), a **Mark season watched** button, and the season's episodes with thumbnails and plots.
- **Library views**: Posters, Landscape (good for episodes) and List with a details panel. A toolbar at the top has view, sort, order, watched filter, filter, search and update library.
- **Details page**: backdrop, logo, **ratings badges** (IMDb, Rotten Tomatoes, Metacritic and TMDB, from your scraper), a Play button (or **Resume** and **Restart** for something you've started), trailer, My List and thumbs, extras/versions (Kodi 21+), set, director, choose art and refresh buttons, the plot, details, a cast row an **Extras** row (featurettes and deleted scenes in an *extras* folder next to the movie) and **More Like This**. After a few seconds the trailer starts playing behind the page (turn this off in Skin Settings). Selecting a cast member opens their **actor page**: every movie and show they're in, and what they directed. Selecting a movie in a home row opens its details page; a movie you're part-way through resumes straight away, and an episode plays from where you stopped with the next ones queued.
- **Playback**: a player bar in your accent colour. On the left is the title's **clearart** (the picture with the characters and logo), or its logo, or the poster. Next to it: *Now playing*, the title, **badges** for the picture and sound (4K, HDR10 / Dolby Vision, Dolby Digital / Atmos / DTS, 5.1) and the audio and subtitle language, the progress bar you can scrub, and round buttons. There's also a seek bar, bookmarks, a subtitle download screen that works with any subtitle add-on (OpenSubtitles, Subdl and others from Kodi's repository), and:
  - **Audio & Subtitles**: a Disney+-style panel (the speech-bubble button) listing every audio track (*English — Dolby Digital 5.1*) and subtitle, so you switch language in one press;
  - a **pause screen**: pause for a moment and the picture dims behind "You're watching", the title's logo, the episode and the plot, like Netflix;
  - **Skip Intro**, **Skip Recap** and **Skip Credits** buttons while a chapter named *Intro* / *Opening*, *Recap* / *Previously on* or *Credits* / *Outro* / *Ending* plays. They need chapter markers in the file (many rips have them). Skip Credits plays the next episode if one is queued. The button hides itself after 10 seconds, and Back dismisses it. Once you've skipped a show's intro, its later episodes **skip it by themselves**;
  - **Finish by**: tell it when you want to stop ("11:30 PM", or "after this episode") and the next episode only starts if it will end in time;
  - **Chapters**: a button that shows the file's chapters with a picture of each, and your bookmarks;
  - **Sound modes**: *Night* (quieter, with quiet speech lifted) and *Dialogue boost* (clearer speech);
  - **each show remembers its languages**: switch a show to French audio or turn its subtitles off once, and its next episodes start the same way;
  - a **sleep timer** that fades the sound out, **subtitle styles** (Large, Extra large, Yellow, Boxed), **Are you still watching?** after a few episodes on their own, and an **after the movie** page with thumbs and More Like This. See [While you watch](#while-you-watch).
- **Badges**: **NEW** on movies and episodes added in the last two weeks, **NEW EPISODES** on a show you've started when more arrive, **4K** on cards, and the full set (4K, HDR, Dolby, 5.1) on the details page. The first scan of a library doesn't count, so a fresh library isn't all marked new.
- **Collections**: Marvel, Star Wars, Harry Potter and other movie sets get a page with the backdrop and logo, how many films and the years, a **Play** button (it starts at the first one you haven't seen) and the films in release order. Open it from the **Collection** button on a movie's details page, the Collections home row, or a set in the movie library.
- **Screensaver**: slowly zooming fanart with each title's logo, name, year and genre, or a **big clock**, both with **today's weather** (see [Screensaver](#screensaver)).
- **Music**: an album-art grid, album pages with the track list, a queue, and a **now playing** screen with big album art on a soft colour wash of it (or the artist's fanart), the song, artist and album, progress, what's up next and the song's **lyrics**. Press OK for the controls: previous, play/pause, next, stop, shuffle, repeat, lyrics and the queue.
- **Live TV**: **My Channels** on the home screen, a **mini guide** (channel, now with progress, next) when you press Info while watching, a TV guide with channel logos, a "now" line and the focused programme's details at the top; a channel list with what's on now; recordings, timers and search; programme details; and, while watching, a channel list and the channel's guide over the picture (the guide button in the player bar). A **last channel** button in the player bar flips back to the channel you watched before, and two home rows can each show a **channel group** such as Sports or News. It works with any PVR add-on, for example IPTV Simple Client, including Xtream Codes services (see [Live TV extras](#live-tv-extras)).
- **MediaHub IPTV** (a separate add-on in the MediaHub repository): sign in to your **Xtream Codes** IPTV service and get Live TV with what's on now and next, catch-up, and films and series with their posters and plots, resume and the next episode, with its own side-menu entry and home rows. It has a **TV guide** page, a **Channels** panel and mini guide while you watch, **last channel** and **channel numbers**, programme **reminders**, **catch-up search**, **My List**, **downloads** and **more than one account** (see [MediaHub IPTV](#mediahub-iptv-xtream-codes)).
- **More MediaHub add-ons** (also in the MediaHub repository, each on its own): **MediaHub Radio** (thousands of internet radio stations), **MediaHub Podcasts** (find, follow and listen), **MediaHub Web Remote** (your phone's web browser as the remote, a second screen, and Listen on this phone), **MediaHub Sync** (what you've watched and your lists, the same on every Kodi in the house, and Watch together in two rooms), **MediaHub Cinema**, **MediaHub Import**, **MediaHub Audiobooks**, **MediaHub Classics**, **MediaHub Weather**, **MediaHub Scores** (your teams' fixtures and results), **MediaHub News** (headlines, bulletins and a news ticker) and **MediaHub Space** (NASA's picture of the day). See [More MediaHub add-ons](#more-mediahub-add-ons).
- **Games night**: [Movie quiz](#movie-quiz-night), [Name that tune](#name-that-tune) and [Movie match](#movie-match), played on your phones.
- **On demand**: an IPTV video-on-demand playlist as **TV shows (by season) and movies**, A-Z with search, read straight from the playlist instead of loading it into Live TV, with **posters and plots**, **resume** and the **next episode**, and groups you'd rather not see hidden behind the Kids mode PIN (see [On demand](#on-demand)).
- **Calendar**: the next two weeks of episodes for the shows in your library, day by day (see [Calendar](#calendar)).
- **Quick menu**: holding OK (the context menu) shows what it's for at the top, with Play, Play trailer, Mark as watched, My List and the rest.
- **Profiles**: a "Who's watching?" screen at start-up where every profile has a colourful **avatar** (pick your own in Skin settings), and a Profiles settings page. Each Kodi profile has its own watched progress, My List and settings (see [Profiles](#profiles)).
- **Your year**: hours watched, movies, episodes, your most-watched show, your longest binge, top genres, busiest month and favourite movie of the year (see [Your year](#your-year)).
- **Downloads** (not on Apple TV): save a movie or episode to watch without the network, for a laptop or tablet on the road (see [Downloads](#downloads)).
- **Seasonal themes**: Christmas lights and snow in December, a Halloween garland in late October and summer sunshine, all by themselves (see [Seasonal themes](#seasonal-themes)).
- **Kids mode**: only family-rated titles everywhere, protected by a PIN, with a **bedtime** that locks the screen until morning (see [Kids mode](#kids-mode)).
- **Family List**: a watch-together list every profile shares (see [Family List](#family-list)).
- **Backup and restore**: your settings, rows, network cards, My List and thumbs in one file (see [Backup and restore](#backup-and-restore)).
- **Accent colours**: Disney+ blue, Netflix red, Prime cyan, slate, purple, gold or green, in **Skin settings → Accent colour**. **Colour from the artwork** tints the background with the colours of whatever you're on.
- **Lite mode** for Apple TV and other boxes short of memory: six home rows and no trailers or moving effects, with a memory reading; it turns itself on if memory runs low (see [Lite mode](#lite-mode)).
- **Pure black background** for OLED screens, with any accent colour.
- **Free up space**: Kodi's picture cache size, and clearing the pictures not used for a month (see [Storage](#storage)).
- **Library health**: what's missing artwork, in the library twice, or wasn't identified (see [Library health](#library-health)).
- **Trakt**: set up the Trakt add-on and sync from Skin settings (see [Trakt](#trakt)).
- **Languages**: English, German, Spanish, French, Italian and Brazilian Portuguese, following Kodi's language setting.
- **Accessibility**: large text, a high-contrast theme and reduce motion (see [Accessibility](#accessibility)).
- **The rest of Kodi's screens are skinned too**: settings, skin settings, add-on browser and add-on settings, file browser, add-source dialog, keyboard, number pad, select, confirm/progress, context menu, notifications, volume and the power menu.

## Requirements

- **Kodi 21 "Omega" or newer** (the skin needs `xbmc.gui` 5.17.0, so it also works on Kodi 22 "Piers").
- A video library: add your movie/TV folders as sources, set their content type and scan them. Until you do, the home screen shows a welcome card with an **Add videos** button.

## Install

Works on Apple TV, Fire TV, Android TV, Windows, Mac, Linux and any other Kodi box.

1. In Kodi, turn on **Settings → System → Add-ons → Unknown sources**.
2. Go to **Settings → File manager → Add source**. Type the address below exactly, including `https://` and the final `/`, and name the source `mediahub`:
   ```
   https://satanlair2013-create.github.io/Mediahub-kodi/
   ```
3. Go to **Settings → Add-ons → Install from zip file → mediahub** and pick **`repository.mediahub-1.0.1.zip`**.
4. Go to **Install from repository → MediaHub Repository → Look and feel → Skin → MediaHub → Install**. Say **Yes** to switching skins.
5. For an Xtream Codes IPTV service, also install **Install from repository → MediaHub Repository → Video add-ons → MediaHub IPTV** (see [MediaHub IPTV](#mediahub-iptv-xtream-codes)).

Installing through the repository means Kodi also installs the **MediaHub Helper** add-on the skin needs, and keeps both up to date (see [Updates](#updates)). To install once without the repository, pick `script.mediahub.helper-<version>.zip` in step 3, then do step 3 again with `skin.mediahub-<version>.zip`.

## Updates

MediaHub checks for a new version a minute after Kodi starts and every 6 hours after that. When there is one, a banner appears at the top of the home screen with what's new and two buttons:

- **Update now** installs it straight away through Kodi's own add-on installer. That works even if Kodi is set to only notify you about updates. If other add-ons have updates waiting too, it opens Kodi's **Available updates** list instead, so nothing else gets updated without you choosing it.
- **Later** hides the banner until the next version comes out.

If an update ever says it failed (MediaHub 1.6.0 and older could, see below), close Kodi completely, open it again and go to **Settings → Add-ons → My add-ons → Look and feel → Skin → MediaHub → Update**. Kodi's own add-on screen always works.

**1.6.1 fixes "Update failed".** Before 1.6.1, **Update now** kept the helper busy watching the install while Kodi was replacing that same helper. Kodi then had to force-stop it, and the update failed or Kodi crashed. Now the button hands the update to Kodi and steps aside, and the new helper finishes up after Kodi restarts it. Updating *to* 1.6.1 from an older version opens Kodi's **Available updates** list (choose MediaHub or **Update all** there).

You can also check any time in **Skin settings → Check for updates**, which shows the version you have. (Before helper 1.6.2 it always said *Couldn't check - are you online?* on the public site, which sends its list of versions compressed; Kodi's own update check was not affected.) The check reads the MediaHub repository, so it needs `repository.mediahub` installed (the Apple TV / web install above) or falls back to the public site.

## Title logos

Wherever a title would be written out, the skin shows the movie's or show's **logo art** (Kodi calls it `clearlogo`) if it has one. That includes the hero slider, the Continue Watching and other 16:9 cards, episode cards (which use the show's logo), under the focused poster, the details page and the playback screens. If an item has no logo, the skin shows its name as text.

To get logos for your library:

1. Go to **Settings → Media → Videos** (set the settings level to *Advanced* or *Expert*) and set **Artwork level** to **Maximum**. That makes the scraper download logos along with posters and fanart.
2. The default scrapers (*The Movie Database* for movies and TV) get logos from TMDB and, if it's turned on in their settings, from fanart.tv.
3. For items you've already scanned: open an item's details page and choose **Refresh**, or remove the source from the library and scan it again.
4. Or save a `clearlogo.png` next to a movie file (or in a TV show's folder), or name it `<movie file name>-clearlogo.png`, and Kodi picks it up as local artwork.

## Network cards

The card row under the hero slider is a slider: arrows show when there are more cards off-screen, and the next card peeks in at the right edge. It has **38 built-in networks and studios** plus **20 custom slots**. A card only appears when your library has something from it. Behind each card are two tiny hidden lists that check for a matching movie and a matching TV show. If neither finds anything, the card stays hidden, and if no card has any titles, the whole row hides. This works the same on the **Networks** page, which is in the side menu.

Built-in cards: Disney, Pixar, Marvel, Star Wars, National Geographic, Star, Netflix, HBO, Apple TV+, Prime Video, Hulu, Paramount+, Peacock, Warner Bros., Universal, Sony Pictures, DreamWorks, Illumination, Studio Ghibli, Lionsgate, A24, Legendary, New Line Cinema, MGM, Blumhouse, BBC, AMC, Showtime, Starz, ABC, NBC, CBS, FOX, The CW, Syfy, Discovery, Cartoon Network and Nickelodeon.

A card matches movies whose **studio**, or TV shows whose **network**, contains either of its two filter words. For example, Star matches `20th Century` or `FX`, and Star Wars matches `Lucasfilm` or `Star Wars`. The studio and network names come from your scraper, e.g. TMDB.

### Editing cards

Go to **Settings → Skin settings → Edit network cards**. Pick a card on the left; its settings show on the right:

| Setting | What it does |
| --- | --- |
| Name | The name on the card and at the top of its hub. If you change it, the built-in logo is swapped for the name in text. |
| Studio / network filter | The card matches items whose studio or network contains this text. |
| Second filter (optional) | A second word to match. |
| Logo image | Pick any PNG. White logos with a transparent background look best. |
| Show name instead of logo / Hide this card / Reset this card | These do what they say. |

The list also shows each card's status: *In your library*, *Nothing in your library*, *Hidden* or *Empty slot*. To add a network that isn't built in, give one of the **Custom slots** at the bottom a name and a filter.

Skin Settings has two related options. **Show every network card, even empty ones** turns off the auto-hiding, and **Hide network cards** removes the row completely.

The built-in card art is plain typography, not the studios' official logos. For real logos, the `resource.images.studios.white` add-on in Kodi's repository has them, and you can point a card's *Logo image* at one of its files.

## Home rows

Go to **Settings → Skin settings → Customise home rows**. The left column lists the 12 row positions and what each one shows. Pick a position, then choose a row type in the middle column. **Move row up** and **Move row down** reorder the selected row, and **Reset rows to default** puts everything back. Set a position to **None** to leave it out.

Row types:

- Continue Watching (movies), Continue Watching: TV, Up Next, My List, Recommended For You, New Movies, New Episodes, TV Shows For You, Collections
- Top Rated Movies, Top Rated TV Shows, Watch Again (movies you've seen, most recent first), Movies You Haven't Seen, Random Movies
- 16 movie genres (Action, Adventure, Animation, Comedy, Crime, Documentary, Drama, Family, Fantasy, Horror, Mystery, Romance, Science Fiction, Thriller, War, Western)
- 10 TV genres (Action, Animation, Comedy, Crime, Documentary, Drama, Kids, Mystery, Reality, Sci-Fi)
- **Because You Watched …**: titles like the last thing you finished (sharing its genres, studio or director) that you haven't seen. The row's name says what it's based on.
- **Coming Soon**: episodes in your library whose air date hasn't come yet (Sonarr and some scrapers add upcoming episodes), and what [TVmaze](https://www.tvmaze.com) says airs next this week for your other shows, one per show with the day it airs: *S2 E4 • Sunday*.
- Mood rows: **Feel-Good Movies**, **Edge of Your Seat**, **Short on Time (Under 90 Minutes)** and **Watch Together**
- **Top 10 Movies** and **Top 10 TV Shows**: the ten with the most votes on TMDB / IMDb, with big rank numbers beside the posters
- **Family List**: the titles on the shared [Family List](#family-list)
- With [MediaHub Radio](#mediahub-radio) and [MediaHub Podcasts](#mediahub-podcasts): **Radio: Your Stations**, **Radio: Recently Played**, **Podcasts: New Episodes** (the newest unplayed episode of each podcast you follow) and **Podcasts: Continue Listening**. Their cards show the station's logo or the podcast's cover.
- **New This Week**: episodes in your library that aired in the last seven days, newest first, one per show.
- **Directed By …**: a director with three or more of your movies (favouring ones you've watched or liked) and their films. A different director each day.
- **Marvel in Story Order**: the Marvel Cinematic Universe films you have, in the order the story happens, starting from the first one you haven't watched (*4 / 12*), so the row is where your marathon is up to.
- 3 **custom rows**: give one a name and pick a playlist or smart playlist, **or a folder of any video add-on** (**Or pick a folder of an add-on** browses your add-ons' folders), and choose poster or wide cards. Make smart playlists in **Videos → Playlists**.

Rows that have nothing in them stay hidden, so a genre row only shows once your library has something in it.

**On the home screen itself**, hold OK on a card (the long-press menu) and choose **Move or hide this row**: *Move up* and *Move down* swap it with the next row that's showing, and *Hide this row* sets it to None (Customise home rows brings it back). Kodi only opens that menu on rows of library or add-on content, so rows the helper fills (Up Next, My List, Recommended, Because You Watched, Coming Soon, New This Week, Directed By, Marvel, Family List) are moved in Customise home rows.

More on the home screen:

- **Banner trailer**: stay on the hero slider for 5 seconds and the title's trailer plays, muted, on the right of the banner, and the slider stops turning. The sound is turned back on when it ends (and when Kodi starts, if Kodi was closed while one played). **Skin settings → Play the trailer in the banner** turns it off.
- **Greeting**: *Good morning*, *Good afternoon*, *Good evening* or *Up late*, with your avatar, above the banner. **Skin settings → Say good morning / evening on the home screen** turns it off.
- **New since you were last here**: when you come back (Kodi started again, or six hours or more without a button press), a banner under the hero counts the movies and episodes added while you were away, with buttons that open them. **Dismiss** hides it.
- **My Channels**: in Live TV, hold OK on a channel and choose **My channels: add / remove**. Your channels appear in a row under the network cards with what's on now (and how far in) and next; select one to watch.
- **On now**: with Live TV set up, a row under the network cards shows each channel's programme, with its logo and a progress bar. Select one to watch. It's hidden in Kids mode, and **Skin settings → Show On now (Live TV) on the home screen** turns it off.
- **Remove from Continue Watching**: long-press a movie you've started or a show you're part-way through (in the library, or a movie in Continue Watching) and choose **Remove from Continue Watching**. A movie loses its resume point; a show leaves Up Next until you watch another of its episodes. (Kodi doesn't open the long-press menu on Up Next's own cards, so for a show use its entry in the TV library.)

### Trailer previews

Stay on a movie in a home row for 4 seconds and its trailer plays in a panel at the top right, with the title's logo and a *Preview* tag. Moving on, opening something or pressing Back stops it, and a trailer that has finished doesn't start again for the same card. **Skin settings → Trailer previews in home rows** has three choices:

- **Local trailers** (the default): trailers saved next to your movies (`<movie>-trailer.mkv`) or downloaded by your scraper as files.
- **All trailers**: also YouTube trailers from the TMDB scraper. They need the YouTube add-on, and Kodi shows its busy spinner while one loads, which holds up the remote for a moment.

YouTube trailers need Kodi's **YouTube** add-on. When it isn't installed, previews simply skip those trailers, and the **Trailer** button on a details page (or **Play trailer** in the long-press menu) offers to install it from Kodi's own repository. (YouTube may then ask you to set up its own API key: see its settings.)
- **Off**.

## MediaHub Helper

Up Next, My List, thumbs, Recommended For You, More Like This and the show page's Play button come from **MediaHub Helper** (`script.mediahub.helper`), a small add-on the skin installs alongside itself. It runs quietly in the background: the skin asks it for things and it fills them in. It also adds **Add to My List** and **Rate: thumbs up / down** to the long-press (context) menu on movies, shows and episodes.

## Up Next

For each TV show you've started, the helper finds the episode you stopped part-way through, or else the first unwatched episode after the last one you watched. Selecting a card plays that episode, resuming if you'd started it, with the next few episodes queued. Near the end of each episode, the **Up next** card shows the next one and counts down. Kodi then moves on to it by itself. To turn the card off, go to **Skin settings → Show an "Up next" card at the end of an episode**.

The card only shows when another video is queued after the one playing. That's always the case when you start from Up Next. When you play an episode from the library, it depends on Kodi's **Settings → Player → Videos → Play next video automatically** option. The row refreshes whenever you come back to the home screen.

## My List, thumbs and recommendations

- **My List**: press **+** on a details page or the show page (or use the long-press menu) and the title goes to the top of the My List row. Press it again (it shows a tick) to take it off. My List is stored as a library tag called *My List*, so you can also filter by it in the library.
- **Thumbs**: three buttons on the details page and show page, *Not for me*, *I like this* and *Love this!*. They're saved as the library's own *My rating* (2, 8 and 10 out of 10), so other skins and add-ons see them too. Pressing the same one again clears it.
- **Recommended For You** ranks the movies you haven't watched by how well their genres, studios and directors match what you loved, liked and watched, and leaves out anything you gave a thumbs down. It reshuffles once a day.
- **More Like This** on a details page lists titles that share genres, studio or director with it.

## Profiles

Kodi's profiles give each person their own watched status, Continue Watching, Up Next, My List, thumbs and settings.

1. Go to **Settings → Profiles** and choose **Add profile…**. Give it a name and a picture, and pick whether it shares the library or has its own.
2. On the same page, turn on **Show "Who's watching?" when Kodi starts**.
3. To switch profile later, use **Power → Log off** in the side menu.

Every profile gets an **avatar** on "Who's watching?": a colourful picture that goes with its place in the list, or one you pick in **Skin settings → Profile avatar** (there are 12). A profile picture set in Kodi's own profile settings is used if you haven't picked an avatar. Your avatar also shows on the **Your year** page. (Kodi only lets the "Who's watching?" screen read the main profile's skin settings, so MediaHub keeps every profile's pick there.)

If a new profile keeps its own add-ons, turn on **MediaHub Helper** in it too (**Settings → Add-ons → My add-ons → Services**).

## Kids mode

Turn it on in **Skin settings → Kids mode**. While it's on:

- the hero slider, home rows, network cards and hubs, search, actor pages and the side menu's **Movies** and **TV Shows** only show titles rated **G, PG, U, TV-Y, TV-Y7, TV-G or TV-PG**. The rating comes from your scraper; titles without one are left out.
- Continue Watching: TV, New Episodes and Collections are hidden (Up Next still shows kids' shows).
- **Settings**, **Add-ons** and **Files** disappear from the side menu, and **Exit Kids mode** appears.

Set a **Kids mode PIN** first (in Skin settings, while Kids mode is off) and leaving Kids mode asks for it.

**Bedtime**: in **Skin settings → Kids bedtime**, set a bedtime and a wake-up time. In Kids mode, a note says *Bedtime in 10 minutes*; at bedtime, whatever is playing gets ten more minutes (or stops at its end, if that's sooner), then a **Time for bed** screen covers everything until the wake-up time. It comes back if someone closes it. **Grown-ups** on that screen asks for the Kids mode PIN and unlocks it for the rest of the night. Leaving Kids mode ends it too.

**Screen time**: **Skin settings → Kids screen time** gives Kids mode a daily allowance of video (30 minutes to 3 hours). Time counts while something plays; the home screen's greeting says how much is left (*45 min of TV left today*), a note comes ten minutes before the end, and then an hourglass screen (*That's all the TV for today*) covers everything until tomorrow. **Grown-ups** on it asks for the PIN and adds 15, 30 or 60 minutes, or lifts the limit for the day. It starts again each morning.

## Family List

A watch-together list for the whole house. The people button on a movie's or show's details page adds it (it fills in once it's on the list; press it again to take it off). Every profile sees the same list: it's kept in the main profile's data, and each title is matched to your own library by its IMDb / TMDB / TVDB id, or its title and year. Show it on the home screen with the **Family List** row type ([Home rows](#home-rows)); the Kids and family choice in the welcome setup includes it.

## Backup and restore

**Skin settings → Back up MediaHub to a file** saves your skin settings (home rows, network cards, colours and every switch), My List and thumbs to `MediaHub backup <date>.json` in a folder you pick. Pick a network folder and you can take it to another device. **Restore from a backup** puts it all back: settings the backup doesn't have go back to their defaults, and My List and thumbs are matched to the library by id or title and year, so they carry across to a device with the same films. The helper's own lists (the order of My List, shows hidden from Up Next, remembered intros) are restored only to the same library.

## Screensaver

Turn it on in **Skin settings → MediaHub screensaver**, and pick when it starts (2, 5, 10, 15 or 30 minutes without a button press). It shows your movies and shows while nothing is playing, and any button wakes it up. Turning it on switches Kodi's own screensaver off (turning it off puts Kodi's *Dim* back), so the two don't overlap. In Kids mode it only shows family titles.

- **Screensaver style**: *Pictures from your library*, *Photo frame*, *Space pictures* (NASA's pictures of the day, with [MediaHub Space](#mediahub-space)) or *Big clock*: a large clock, the date and the weather on black, drifting slowly so nothing marks the screen. (A library with no backdrops yet gets the clock too.)
- **Photo frame** shows your own photos: every picture in the **Photo folder** you pick (and the folders in it; a network share works too) and the ones sent from a phone with [MediaHub Web Remote](#mediahub-web-remote), in a random order, whole on a dimmed copy of themselves, with the folder's name, the clock and the weather.
- With [MediaHub Radio](#mediahub-radio)'s alarm clock, the clock also shows the next alarm.
- **Weather**: set **Skin settings → Weather for** to your town (*Leeds*, or *Leeds, UK* when there are several) and both styles show the temperature, what it's like and today's high and low, from [Open-Meteo](https://open-meteo.com) (free, no account), in °C or °F following Kodi's region setting. It's only looked up while the screensaver shows, at most every half hour. If Kodi has a weather add-on set up (**Settings → Services → Weather**), that one is used instead and the town setting hides.

## Cinema mode (Home Assistant)

**Skin settings → Cinema mode (Home Assistant)** sets the room when a film plays: Home Assistant turns on a scene or script (`scene.film_night`, `script.dim_lights`, an automation...) **when a film starts** full screen (and again when it carries on after a pause), another **when it's paused**, and another **at the end credits** (the last few minutes) or when it stops. **Episodes too** does the same for TV. Give it your Home Assistant's address (`http://homeassistant.local:8123`) and a long-lived access token (Home Assistant → your profile → Security); **Test cinema mode** turns on the first scene, then the end one ten seconds later, and says whether Home Assistant answered. Trailers on the home screen don't count, and a Home Assistant that's slow or off never holds up the film.

**Lights that take the film's colours**: name one or more lights (`light.tv_strip, light.lamp`) and, when a film starts or carries on, they take the main colour of its poster. MediaHub works the colour out itself from Kodi's copy of the poster; for a web poster it can't read, it asks Home Assistant's **Color Extractor** integration, if you've added it.

### Doorbell

**Skin settings → Cinema mode (Home Assistant) → Doorbell: pause and show who's at the door** watches a doorbell in Home Assistant (with the same address and token): an event entity such as `event.front_door` (every press), or a binary sensor, input boolean or switch (`binary_sensor.doorbell`, when it turns on). When it rings, what's playing pauses and a pop-up shows the picture from a **Camera** (`camera.front_door`), fresh every few seconds, with **Resume** and **Dismiss**. **Test the doorbell** shows it straight away. Home Assistant is asked every two seconds, in the background.

## Movie quiz night

**Movie quiz** in the side menu plays ten questions about the films in your library: a still from a film slowly zooming out, which film stars these actors, which film this plot is (its title blanked out), and when a film came out, with four answers each and 20 seconds. A faster right answer scores more (500 to 1000).

Up to four people play on their phones: the lobby shows a QR code that opens [MediaHub Web Remote](#mediahub-web-remote) and pairs the phone, they type their name, and their phone becomes four big coloured answer buttons (it shows the question too, except for the stills). The TV shows who has answered, then the answer and everyone's points, and the winner at the end. With nobody on a phone, **Play with the remote** is a game for one. In Kids mode it only asks about family films.

## Movie match

**Movie match** in the side menu is for deciding what to watch together. Everyone scans the lobby's QR code with their phone ([MediaHub Web Remote](#mediahub-web-remote)) and swipes through the same pile of films from your library (up to 40, the ones nobody's watched first): right or **Yes** for one they'd watch, left or **Nope** for one they wouldn't. The first film everyone says yes to is **a match**, shown on the TV with **Play it** and **Keep swiping**. If the pile runs out first, the most liked film is offered. With nobody on a phone, **Swipe with the remote** plays it on the TV.

## Name that tune

**Name that tune** in the side menu is the movie quiz with music: each question plays the theme tune of one of your shows or films (a `theme.mp3`, `theme.flac` or `theme.m4a` in its folder, as saved by tools like TV Tunes) and asks where it's from, with four answers. Bars bounce while it plays; the answer shows the poster. It's played on phones or with the remote like [the quiz](#movie-quiz-night), and the phones and the TV never show what's playing. It needs at least three shows or films with theme music.

## Trailer night

**Trailer night** in the side menu plays the trailers of the films you haven't watched yet, one after another, like the trailers before a film at the cinema, with the film's logo, year, genre, running time and plot over the trailer. **Watch the film** plays it, **Next trailer** skips on, and **Add to My List** keeps it for later. In Kids mode it keeps to the films kids may see.

## While you watch

The player bar has four new round buttons: **Audio & Subtitles**, **Chapters**, **Finish by** and **Sound mode**. What's on shows under the clock (*Finish by: 11:30 PM • Sound: Night*).

- **Finish by**: pick *After this episode* or a time (every half hour for the next 5 hours). Up Next leaves out episodes that wouldn't finish in time, and when an episode ends, the next one only plays if it fits; otherwise playback stops and a message says so. It switches itself off once the time has passed.
- **Chapters**: every chapter in the file with a picture from it and its time, plus your bookmarks. Select one to jump there.
- **Intro memory**: press **Skip Intro** once in a show and from then on its intros are skipped for you (a short message says so). To turn this off, go to **Skin settings → Skip intros automatically in shows where you've skipped one**; **Offer Skip Intro again in every show** forgets the shows it remembers.
- **Sleep timer** (the timer button): *Stop after this one*, *TV off after this one* or *Sleep in* 15 to 90 minutes. On live TV (Kodi's Live TV or MediaHub IPTV) *Stop after this one* stops when the programme on now ends, so Kids bedtime works for live channels too. In the last minute the sound fades out and the picture dims, then it stops and the volume goes back to where it was. Pressing any button during the fade cancels it. **Finish by** is in the same menu.
- **The TV goes off too**: *TV off after this one* stops at the end and turns the TV off, and **Skin settings → Turn the TV off too when the sleep timer or bedtime stops what's playing** does the same for every sleep timer and for Kids bedtime. It uses HDMI-CEC (Kodi's own *CECStandby*: the box has to be plugged into the TV with CEC on), or, when **The TV in Home Assistant** is set (`media_player.living_room_tv`, `switch.tv` or `remote.tv`, with the Home Assistant address and token from [Cinema mode](#cinema-mode-home-assistant)), Home Assistant turns it off.
- **Watch together** (a player bar button, with [MediaHub Sync](#mediahub-sync)): play the same film or episode with another room.
- **Subtitle style** (in Audio & Subtitles): *Standard*, *Large*, *Extra large*, *Yellow* or *Boxed* (white on a dark box, the easiest to read). It sets Kodi's own subtitle settings, so it sticks.
- **Are you still watching?**: after three episodes in a row with no button pressed, the next one pauses and asks. *Continue watching* carries on; *Stop* stops. **Skin settings → Ask "Are you still watching?" after 3 in a row** turns it off.
- **After the movie**: when a film ends (or you stop it near the end), a page shows its logo, asks *How was it?* with the thumbs, and lists More Like This. **Skin settings → Show rating and More Like This after a movie** turns it off.
- **Each show remembers its languages**: change the audio language or the subtitles (in Audio & Subtitles, or Kodi's own menu) and the show's next episodes start with the same audio language and the same subtitles, or none. Only a change you make is kept, so shows you never touch follow Kodi's language settings. **Skin settings → Each show remembers its audio language and subtitles** turns it off.
- **Stream info** (a button in the player bar, for films and shows as well as IPTV): a small box in the top corner with the video (size, frame rate, codec, decoder, pixel format), the audio (codec, channels, sample rate) and how full the buffer is. Press it again to hide it. Useful when a stream stutters.
- **Theme music**: open a show's page and its theme tune plays quietly while you look around, if there's a `theme.mp3` (or `theme.flac`, `theme.m4a`) in the show's folder, as saved by tools like TV Tunes. It stops when you leave the page or play something. **Skin settings → Play a show's theme music on its page** turns it off.
- **Instant mix** (a music player button, and **Instant mix** in the context menu of a song, artist, album or genre): fills the music queue with songs from your library that go with it (the same genres and moods first, from around the same years, the artists taking turns), the song itself first, and adds more before it runs out. Playing something else ends it.
- **Sound modes**: **Night** lowers the volume and adds some of Kodi's volume amplification, so quiet speech stays clear while explosions don't wake anyone. **Dialogue boost** only adds the amplification. **Normal** puts everything back. Amplification doesn't work when your receiver decodes the sound itself (passthrough), so on those setups Night just lowers the volume. Picture presets aren't possible: Kodi doesn't let skins change the TV's picture.

## Finding something

- **People search**: the search page's **People** row lists the actors and directors whose names contain what you typed, from your movies and TV shows. Select one to see everything they're in and what they directed.
- **Mic key**: the first key under the letter grid opens the keyboard with a hint to talk. On Apple TV, hold the mic button on the Siri Remote and say a title (it needs Kodi's Apple TV keyboard, the default, and dictation turned on in the Apple TV's settings). Phones and other remotes with voice typing work the same way.
- **Surprise me**: in the side menu. It picks a movie or show you haven't watched (skipping thumbs-down titles, and only family titles in Kids mode). What you like makes a title more likely, but it's still a surprise.
- **On demand and Live TV in search**: with an [On demand](#on-demand) playlist, the search page also has rows of its **shows and films** and its **live channels** whose names match. A show opens its seasons; a film or channel plays.
- **Filter chips**: above the Movies page. *All*, *Unwatched*, *4K*, *Under 2 hours*, *Kids*, *2020s*, *2010s*, *2000s*, *1990s* and *Older*. The one you're on is lit, and **..** goes back up as usual.

## Details page extras

- **Ratings badges**: IMDb (7.8), Rotten Tomatoes (92%, a tomato or a green splat), Metacritic (76, green, yellow or red like theirs) and TMDB (78%). They come from the ratings your scraper saved; the TMDb scraper gets Rotten Tomatoes and Metacritic when its *OMDb* option is on (it needs a free OMDb key).
- **Extras**: put featurettes, deleted scenes or interviews in a folder called `extras` (or `featurettes`, `behind the scenes`, `deleted scenes`, `interviews`, `scenes`, `shorts`, `trailers`, `other`) next to the movie, or in the show's folder. They appear in an **Extras** row; a picture with the same name as the video (or `name-thumb.jpg`) is its thumbnail, otherwise the movie's backdrop is used.
- **Season progress**: on a show page every season tab has a bar showing how much of it you've watched, and *Season 2 • 7 of 10 watched* shows next to the round buttons. The tick button marks the whole season watched, or unwatched if it all is.

## Your year

**Your year** in the side menu (or in Skin settings) looks back at this year: hours watched, how many movies, episodes and shows, your most-watched show, your longest binge (*5 episodes of Outer Rim • 24 September*), your top genres, your busiest month and your favourite movie (the one you rated highest). It's worked out from when you last watched each thing, so a movie you watched twice counts once.

## Downloads

On Mac, Windows, Linux and Android (not Apple TV, where the system can delete big files at any time), movie and episode details pages have a **Download** button. It copies the file to your downloads folder with a progress bar in the corner, so you can watch it without the network. **Downloads** then appears in the side menu. To remove one, long-press it there and choose **Remove download**. Pick the folder in **Skin settings → Downloads folder** (by default it's in Kodi's own data folder). Streams from add-ons can't be downloaded, except MediaHub IPTV's films and episodes: long-press one and choose **Download** (live channels can't be).

## Seasonal themes

The home screen and "Who's watching?" dress up by themselves:

- **Christmas** (1–26 December): twinkling lights along the top and falling snow.
- **Halloween** (15–31 October): a garland of pumpkins and bats, and a cobweb in the corner.
- **Summer** (21 June – 31 August): a warm sun with slowly turning rays in the corner.

**Skin settings → Seasonal themes** turns them off, or picks one to use all year.

## On demand

Some IPTV playlists are really catalogues: every episode and every film is an entry, hundreds of thousands of them. Loaded into Live TV as "channels" they use up the memory of a box like Apple TV. **On demand** (in the side menu) reads the playlist itself instead and shows it as **TV Shows** (A-Z → show → season → episodes) and **Movies** (A-Z), a page at a time, with **Search**. Select an episode or film to play it.

- It uses **Skin settings → On demand → Playlist address** (a web address or a file), or else IPTV Simple Client's own playlist, **whether or not that add-on is on**. So with a big catalogue you can turn IPTV Simple Client off (**Add-ons → My add-ons → PVR clients**) to free the memory, and still watch through On demand.
- **Update the list now** reads the playlist again (it takes a minute for a big one); the list also refreshes by itself once a day while nothing is playing. Skin settings shows how many shows, episodes and movies it found.
- An entry named like *Show S01 E02* (or *S01E02*, *1x02*) is an episode; one whose address is a video file or an Xtream `/movie/` address is a film; everything else is a live channel and is left to Live TV. Language tags in front (*EN - …*, *|UK| …*) are ignored.
- **Resume and next episode**: what you've watched gets a tick and what you've started resumes (or *Play from beginning*, holding OK). Playing an episode queues the next few, so the Up Next card offers the next one, and the home row **Continue Watching: On Demand** has what you're part-way through and the next episode of shows you're following. Progress is kept by address, so it survives the daily refresh.
- **Posters and plots**: shows are looked up on [TVmaze](https://www.tvmaze.com) (free, no account) for a poster, a backdrop and the plot; films on [TMDB](https://www.themoviedb.org) once you put a free TMDB API key in **Skin settings → On demand → TMDB API key**. It happens in the background a page at a time; a show's own page looks it up straight away.
- **Hide playlist groups**: **Skin settings → On demand → Hide playlist groups** ticks the playlist's groups (categories) to leave out of On demand and search. Groups that look like adult ones are hidden to start with, and with a Kids mode PIN set, changing the list asks for it.

## Calendar

**Calendar** (in the side menu, under TV Shows) lists the next two weeks of episodes for the shows in your library, day by day, with the time they air. Select one to open the show. The helper looks each show up on [TVmaze](https://www.tvmaze.com) (free, no account) by its TVDB or IMDb id, or its exact name, once a day in the background; a show that has ended, or that TVmaze doesn't know, is asked about again after a month. What's next this week also appears in the **Coming Soon** row.

## Live TV extras

- **My Channels**: hold OK on a channel in Live TV and choose **My channels: add / remove**. The home screen gets a row of your channels with what's on now, a progress bar and what's next. To take one off, do the same in Live TV (Kodi doesn't open the long-press menu on the row's own cards).
- **Mini guide**: press Info while watching a channel for its logo and number, what's on now (with the times and how far in) and what's next. Up / Down change channel.
- **Last channel**: while watching Live TV, the back-arrow button in the player bar goes to the channel you watched before, and pressing it again comes back.
- **Channel group rows**: **Skin settings → Live TV → Home row of a channel group** (and a second one) puts a group from your channel list, like *Sports* or *News*, on the home screen with what's on now and next. *All channels* isn't offered, and a group of more than 1000 channels is refused, so a huge IPTV list can't be loaded onto the home screen.
- **Reminders**: in the TV guide, open a programme and choose **Set reminder**; when it starts, Kodi asks whether to switch to it.
- **Catch-up**: if your IPTV service offers it, turn **Catchup** on in IPTV Simple Client's settings (**Skin settings → Live TV → Catch-up and IPTV settings** opens them). Past programmes in the guide then play with **Play programme**.

### Xtream Codes services

The easiest way is **[MediaHub IPTV](#mediahub-iptv-xtream-codes)**. To have the same service in Kodi's own Live TV as well (its TV guide, reminders and recording), **IPTV Simple Client** reads it through the playlist and guide addresses every Xtream service gives out (MediaHub IPTV's **Use with Kodi's Live TV** shows yours). With your provider's server address, username and password:

1. **Add-ons → Install from repository → PVR clients → PVR IPTV Simple Client**, install and enable it.
2. In its settings (**Skin settings → Live TV → Catch-up and IPTV settings**), **General → M3U playlist URL**: `http://SERVER:PORT/get.php?username=USER&password=PASS&type=m3u_plus&output=ts`
3. **EPG → XMLTV URL**: `http://SERVER:PORT/xmltv.php?username=USER&password=PASS`
4. **Catchup → Enable catchup** if your service has it (Xtream catch-up is recognised from the playlist by itself).
5. Restart Kodi. Channels are in Live TV; films and series from the same playlist are easiest in **On demand**, which reads that playlist without loading it all into Live TV. If the playlist is huge (hundreds of thousands of entries) and Kodi struggles, turn IPTV Simple Client off (**Add-ons → My add-ons → PVR clients**): On demand keeps reading its playlist address.

Only use a service you are licensed to watch.

## MediaHub IPTV (Xtream Codes)

**MediaHub IPTV** (`plugin.video.mediahub.xtream`) is a video add-on for Xtream Codes IPTV services, made to go with MediaHub (it works with any skin). It talks to your service's own Xtream API rather than loading a giant playlist, so even a service with hundreds of thousands of films stays quick on an Apple TV.

**Get it**: **Skin settings → IPTV (Xtream Codes) → Get MediaHub IPTV** (or **Add-ons → Install from repository → MediaHub Repository → Video add-ons → MediaHub IPTV**). Then **Sign in to your IPTV service** with the server address, username and password your provider gave you (a pasted playlist address works too: the server is taken from it). **IPTV** appears in the side menu.

- **Live TV**: your service's categories, each channel with what's on now (and its times) and next. Hold OK on a channel for its **programme guide** and, where your service keeps them, **catch-up**. MPEG-TS or HLS streams (**MediaHub IPTV settings**).
- **Start over**: on a channel with catch-up, start the programme that's on now from its beginning: from the channel's long-press menu, the guide, or the **Start over** button in the player bar while you watch. **Back to live** (in the same place) returns to the live picture.
- **My channels**: hold OK on a channel and choose **Add to My channels**. They get their own page at the top of MediaHub IPTV and an **IPTV: My Channels** row on the home screen (under My Channels), with what's on now, a progress bar and what's next, brought up to date every minute.
- **TV guide**: a guide page with your lists on the left (My channels, Recent channels and each category) and, on the right, every channel with what's on now (with its time and a progress bar), next and later. Select a channel to watch it. It's the first entry in MediaHub IPTV.
- **Channels while you watch**: the **Channels** button in the player bar opens a panel down the right of the picture with the channels of the list you came from, the one playing highlighted, and what's on each. Up and down go through them, OK switches. **1 2 3** at the top jumps to a channel number. Press Info while watching for the **mini guide**: the channel, what's on now with a progress bar and what's next.
- **Last channel**: the **Last channel** button in the player bar (and in MediaHub IPTV) goes back to the channel you watched before; press it again to swap back. **Recent channels** lists the ones you watched last.
- **Go to channel number**: type a channel's number (from your service's own numbering) to watch it.
- **Reminders**: in a channel's guide, hold OK on a programme that hasn't started and choose **Remind me**. A minute before it starts, a message asks whether to watch it; *Yes* switches to the channel. **Reminders** lists them, and **Cancel reminder** takes one off.
- **Record**: hold OK on a programme (in a channel's guide, or OK in the timeline guide) and choose **Record**. On a channel with catch-up it's saved from catch-up a few minutes after it ends (so a programme that's already over can be saved straight away); on any other it's saved from the live stream while it's on, joining again if the stream drops. Recordings go to MediaHub's Downloads folder, and **Recordings** lists what's waiting, recording, recorded or didn't record: recorded ones play, and **Delete recording** removes one. Kodi needs to be on while a live programme records, and a service that allows one connection at a time can't record one channel while you watch another.
- **TV guide: timeline**: eight channels by four hours, each programme as wide as it is long, with a line at the time now. Left and right go from programme to programme (and on by an hour at the edges), up and down from channel to channel; the programme in focus is lit up with its details above. OK watches it live, from the start or from catch-up, or offers **Remind me** and **Record**; a red dot marks a recording and a yellow one a reminder. It's in MediaHub IPTV and behind **Timeline** on the TV guide page.
- **Catch-up**: the channels your service records, by day (today, yesterday and back as far as it keeps), then the programme. **Search catch-up** at the top finds past programmes by title or description on all of them (your channels first).
- **Movies** and **Series**: by category, with the service's own posters, backdrops, plots, cast, ratings and trailers (a film's details arrive a moment after the page opens). A series opens its seasons and episodes.
- **Continue Watching**: what you're part-way through resumes (or *Play from beginning*), watched titles get a tick, and playing an episode queues the next ones, so Up Next offers them. A finished episode puts the next one here.
- **New episodes**: when a series you've caught up with gets more episodes, the next one appears in Continue Watching and the series gets a **NEW EPISODES** badge (the list is checked once a day).
- **Record every episode**: next to **Record** in the guide, the timeline and search. Every showing of that title on that channel is lined up for recording, now and every half hour as the guide fills in, leaving out repeats (the same description as one already recorded or lined up).
- **Search the guide**: what's on now or coming up on any channel, by title, from your service's whole TV guide (downloaded in one go and kept for six hours). Each result offers **Watch**, **Remind me**, **Record** and **Record every episode**.
- **Recently added** films and series, and **Search** across channels, films and series. These use a list of everything on your service, which the add-on reads once a day in the background, a category at a time.
- **My List**: long-press a film or series and choose **Add to My List**. It has its own page, and MediaHub's **My List** row shows it after your library's titles.
- **Downloads**: long-press a film or episode and choose **Download** to copy it to MediaHub's downloads folder (see [Downloads](#downloads); not on Apple TV).
- **Account**: status, expiry date and connections in use, and **Sign out**. **Switch account** holds more than one service or login (**Add another account**): each keeps its own channels, progress, My List and reminders, and switching is instant. Signing out forgets only the one in use.
- **Use with Kodi's Live TV**: the playlist and guide addresses for IPTV Simple Client (see [Xtream Codes services](#xtream-codes-services)).
- **Hide categories** (at the end of each category list): leave out the ones you don't want. Adult-looking categories are hidden until you choose, and with a Kids mode PIN set, changing the list asks for it. In **Kids mode** only children's categories show (Kids, Family, Cartoons, Animation, Disney…), in the pages, search and home rows.
- **Home rows** (**Customise home rows**): **Continue Watching: IPTV**, **IPTV: New Movies** and **IPTV: New Series**; and **IPTV: My Channels** by itself once you add a channel.
- **Banner**: **Skin settings → Slider shows → IPTV: new movies and series** fills the home banner with your service's newest films and series, with their backdrops and plots.

The add-on doesn't come with any channels, films or series: it plays what your own service offers. Only use a service you are licensed to watch.

## More MediaHub add-ons

Twelve more add-ons go with MediaHub (each works with any skin). Get them from **Skin settings → More from MediaHub** (or **Add-ons → Install from repository → MediaHub Repository**). Radio, Podcasts and Cinema then appear in the side menu, and Weather once MediaHub Weather is set up.

### MediaHub Radio

**MediaHub Radio** (`plugin.audio.mediahub.radio`) plays internet radio stations from [radio-browser.info](https://www.radio-browser.info), a free, community-run list (no account).

- **Your stations**: hold OK on a station and choose **Add to Your stations**; *Move up* and *Move down* put them in your order. **Recently played** has the last 30.
- **Popular in** your country (from Kodi's region; **Your country** or the long-press menu changes it), **Most listened**, **Most voted** and **Listened to right now**.
- **Genres**, **Countries** and **Languages**, each with the ones with the most stations first, and **Search** by name (or a genre or place).
- The player shows the song playing when the station sends it, and the station's logo. Next and Previous in the player go through the list you started from.
- **Alarm clock**: wake up to a station. **Add an alarm** asks the time, the days (or once) and the station (from Your stations or Recently played); select an alarm to change its volume, how long it **fades in** (up to 15 minutes), turn it off, **Try it now** or delete it. At the time, Kodi wakes the TV over HDMI-CEC where the TV allows it, starts the station quietly and turns it up, and asks **Stop** or **Snooze** (nine minutes). It doesn't ring over a film playing full screen (a note says so instead). Kodi has to be running (asleep with the screen off is fine).

### MediaHub Podcasts

**MediaHub Podcasts** (`plugin.audio.mediahub.podcasts`) finds podcasts with Apple's free podcast search and plays them straight from their own feeds.

- **Search**, **Top podcasts** in your country, or **Add a podcast by its feed address** (any RSS feed).
- **Follow** a podcast (on its page, or hold OK). **Your podcasts** lists them, and **Latest episodes** has their newest episodes, unplayed first, with **NEW** on the ones that came out since you last opened the podcast.
- Episodes **resume** where you stopped (or *Play from beginning*), get a tick once played, and **Continue listening** has the ones you're part-way through. Hold OK for *Mark as played* or *Mark all as played*.
- Every three hours, the feeds of the podcasts you follow are checked, and a message says when a new episode comes out (**MediaHub Podcasts settings** turns it off). Video podcasts play too.
- **Download** an episode (hold OK) to have it without the internet: it plays from the file, and **Downloads** lists them. On a podcast you follow, **Download new episodes automatically** brings down its newest episode as it comes out and keeps the number set in the settings (older ones go once played). The settings also choose the downloads folder.

### MediaHub Web Remote

**MediaHub Web Remote** (`service.mediahub.webremote`) turns a phone's web browser into Kodi's remote. There's nothing to install on the phone.

1. **Skin settings → More from MediaHub → MediaHub Web Remote: connect a phone** shows a QR code and the remote's address (for example `http://192.168.1.20:8585`).
2. Scan the QR code with the phone's camera: the remote opens and is paired straight away. Or type the address into the phone's browser and enter the code the TV shows.
3. Add the page to the phone's home screen to open it like an app.

The remote has a pad (tap the arrows, or swipe; tap OK), Back, Home, Info and Menu, what's playing with its picture and a seek bar, play / pause, skip and ±10 / 30 seconds, volume and mute, **Type on the TV** (for Kodi's keyboard), **Search** across your films, shows and MediaHub IPTV, and **Channels**: your MediaHub IPTV channels and MediaHub Radio stations, one tap to start. While a MediaHub IPTV channel plays it adds **Channel −**, **Last channel** and **Channel +**.

**Send to TV**: paste a link and **Play on TV**: a YouTube video (with the YouTube add-on; if Kodi doesn't have it, it offers to install it), a video, song or stream address, or a picture. Or **Choose photos or videos** on the phone: they're sent to Kodi and shown as a slideshow (or the video plays), and they also appear in the [Photo frame](#screensaver) screensaver. **Clear** removes what's been sent.

**Voice search**: the microphone next to Search uses the browser's speech recognition where the page is allowed to (browsers only allow it on a secure `https` page, which a remote on your home network isn't), and otherwise puts you in the search box with a tip to use the microphone on the phone's keyboard, which works everywhere. For the same reason, the phone's **Share** menu can't send to the remote: sharing to a web page needs it installed from an `https` address.

**Movie quiz night**, **Name that tune** and **Movie match**: while [the quiz](#movie-quiz-night), [Name that tune](#name-that-tune) or [Movie match](#movie-match) is on the TV, the Remote page offers to join it; in Movie match the phone shows the film cards to swipe.

**Second screen**: while a film or an episode from your library plays, the Remote page shows its year, genres, rating and director, its story (tap to read it all), its **Cast** (tap someone: what else they're in, in your library, to play or queue) and, for an episode, the **Next episode** with **Play next**.

**Out of sync?** (under what's playing, for videos): **Subtitles** and **Sound**, each **Too early** or **Too late**, a tenth of a second at a time, with the offset now; **Back in step** puts both back. It's Kodi's own subtitle and audio offset, so the TV shows its slider and Kodi remembers the offset for that video.

**Browse**: a tab with Continue watching (films and episodes), Recently added films and episodes, My List and your Collections (a collection opens its films, with **Show on the TV**), as posters. Tap to play, or, while something plays, **Play now**, **Play next** or **Add to the queue**.

**Listen on this phone**: while the TV plays something to listen to (a book from MediaHub Audiobooks, a podcast, a radio station or your music), **Listen on this phone** carries on in the phone's browser from the same second, with the rest of the book's chapters or the queue after it, and the TV stops. **Back to the TV** hands it back from where the phone got to. Files only Kodi can reach (your music library, a downloaded episode) come to the phone through the remote. A browser may need a tap on play the first time.

**Play-next queue**: while something plays, picking a search result offers **Play now**, **Play next** or **Add to the queue** (a TV show: its next episode you haven't watched). The Remote page shows what's **up next**, with move up, move down and remove. It's Kodi's own playlist, so the TV plays through it as usual.

It works on your home network only, and each phone needs the code from the TV once (the quiz's code works for every phone until the quiz closes). **MediaHub Web Remote settings** change the port (8585) or turn it off, and **Forget paired phones** makes every phone pair again.

### MediaHub Sync

**MediaHub Sync** (`service.mediahub.sync`) keeps several Kodi devices in step through a folder they can all reach: a network share, a NAS, or a folder a cloud drive keeps in step on each device. There's no MediaHub account or server.

1. Install it on each Kodi, then **Skin settings → More from MediaHub → MediaHub Sync: sync now** and pick the folder (the same one on every device).
2. It syncs a little after Kodi starts, every 15 minutes (**MediaHub Sync settings**: 5, 15 or 60) and shortly after something stops playing. **Sync now** does it straight away, and the Skin settings row says when it last synced and with which devices.

What it keeps in step (each can be turned off in its settings):

- **Films, shows and episodes**: watched, where you stopped, when you last watched, thumbs and **My List**. They're matched by their IMDb, TMDB or TVDB id (or title and year; episodes by their show and number), so the libraries don't have to be the same.
- **MediaHub's Family List**.
- **MediaHub IPTV**: where you are in films and episodes, My channels, My List, reminders and hidden categories, per account.
- **MediaHub Radio**: Your stations. **MediaHub Podcasts**: the podcasts you follow and where you are in each episode.

Each Kodi writes only its own file in the folder's `MediaHub Sync` folder and reads the others', so two devices never write over each other. When the same thing was changed on two devices, the latest change wins. The first time, lists (your stations, podcasts, channels) are put together rather than replaced.

**Carry on watching**: stop a film or episode on one Kodi and, within twelve hours, the next Kodi's home screen shows a **Carry on watching** banner (*From Living room: Night Shift, at 0:51*). **Carry on watching** plays it from there; **Dismiss** hides it.

**Watch together**: while a film or an episode from the library plays, the player bar's **Watch together** button asks the other Kodis in the house (with MediaHub Sync) who's there, and you pick a room. That Kodi asks *Living room would like to watch Night Shift together. Start it here?* and plays the same film from its own library, from the same moment. From then on a pause, a play or a skip on either one does the same on the other, and the one that started it says where it is every few seconds, so the other catches up if it drifts. Stopping on either one ends it (the button again asks to stop). The Kodis talk directly over the home network (UDP port 8586; the device names come from **MediaHub Sync settings**); the sync folder isn't needed for it, but helps find the others on networks that block broadcasts. **Watch together** in MediaHub Sync's settings turns it off.

### MediaHub Cinema

**MediaHub Cinema** (`plugin.video.mediahub.cinema`) shows what's at the cinema, from [TMDB](https://www.themoviedb.org).

- **Now showing** and **Coming soon** at cinemas in your country (from Kodi's language, or **MediaHub Cinema settings**), and **Search**, with posters, backdrops and what each film is about. Selecting a film plays its **trailer** (with the YouTube add-on); **About this film** has its cast and when it comes out at home.
- **Tell me when it's out at home**: twice a day it checks the films you picked, and says when one can be bought or rented (or is out on disc) in your country, or turns up in your library. **Waiting for** and **Out at home** list them.
- **Home rows**: **Cinema: Now Showing** and **Cinema: Coming Soon**; a card offers the trailer, Tell me and About.
- **Where to watch** (a film's context menu, or its card's menu): the streaming services that have it in your country, and where it's free, to rent or to buy, with their logos (from JustWatch, through TMDB). **About this film** lists them too.
- It needs a free TMDB API key (themoviedb.org → Settings → API): its own setting, or the one [On demand](#on-demand) already uses. Cinema times near you aren't included: there's no free, open listing of them.

### MediaHub Import

**MediaHub Import** (`script.mediahub.import`) brings your IMDb and Letterboxd history into Kodi. Export it first (**How to get the files** explains): IMDb gives a `.csv` of your ratings, your watchlist or a list; Letterboxd gives a `.zip` of everything. **Import a file**, pick it, and for the films and shows you have:

- your **watchlist** or list goes into **My List**, in its order;
- your **ratings** become MediaHub's thumbs (9–10 love, 6–8 up, 1–4 down; Letterboxd's out of five counts double) and Letterboxd's **likes** become love; thumbs you've already given stay unless you choose **Replace thumbs you've already given**;
- what you've **rated or watched** is marked watched, on the day you did.

IMDb titles are found by their IMDb id (so they match even when the title's spelled differently), Letterboxd's by title and year. It asks which of these to do, and ends with what isn't in your library.

### MediaHub Audiobooks

**MediaHub Audiobooks** (`plugin.audio.mediahub.audiobooks`) plays LibriVox's free audiobooks (classics out of copyright, read by volunteers), through the Internet Archive; no account needed.

- **Popular**, **Newest**, **Genres** and **Search** by title or author; **MediaHub Audiobooks settings** can keep to books read in one language.
- A book plays chapter after chapter and **carries on where you stopped**, next time too: its page starts with *Carry on: Chapter 5*, and **Continue listening** (and MediaHub's **Audiobooks: Continue Listening** home row) has the books you're part-way through, with the time left.
- **My books** keeps the ones you want (hold OK); **Mark as finished** takes a book off Continue listening.

### MediaHub Classics

**MediaHub Classics** (`plugin.video.mediahub.classics`) has old films and TV that are free to watch because they're out of copyright, from the Internet Archive; no account needed.

- **Feature films**, **Film noir**, **Science fiction and horror**, **Comedy**, **Westerns**, **Silent films**, **Cartoons** and **Classic TV**, most watched first, and **Search**. In Kids mode only Cartoons show.
- A film **resumes** where you stopped (or starts again), gets a tick once watched, and **Continue watching** has the ones you're part-way through. **My List** keeps films for later.
- **Home rows**: **Classics: Continue Watching**, and **Classic Films** (a different handful of well-liked films each day).

### MediaHub Weather

**MediaHub Weather** (`weather.mediahub`) is a Kodi weather add-on using [Open-Meteo](https://open-meteo.com) (free, no account or key), for up to three towns: now, the next 24 hours and the next 7 days, in your region's units. **Skin settings → More from MediaHub → MediaHub Weather** installs it, makes it Kodi's weather and asks for your town. Then the **Weather** page (side menu) shows now, the next 12 hours and 7 days (**Next town** switches between the towns set), the home screen's greeting has the temperature, and the clock screensaver uses it. It works with any skin.

### MediaHub Scores

**MediaHub Scores** (`plugin.video.mediahub.scores`) follows your teams, in any sport [TheSportsDB](https://www.thesportsdb.com) knows (football, rugby, basketball, ice hockey, American football, cricket and more; free, no account).

- **Add a team** (search by name), then each team shows its **Next matches**, its **Results** and its league's **Table**.
- **On match days**: a notification a quarter of an hour before your team kicks off, and **Full time: Liverpool 1 – 2 Arsenal** when the result comes in. It looks every half hour, and every few minutes while your team is playing.
- **Home row**: **Scores: Your Teams**: today's matches, the latest results, then what's coming.
- It's scores only: there's no free, legal stream of the matches to watch in Kodi. TheSportsDB's free key only gives each team's next and last five matches and live scores need its paid key (**MediaHub Scores settings** takes your own key).

### MediaHub News

**MediaHub News** (`plugin.video.mediahub.news`) has the headlines from the news sites you choose.

- **Choose news sites** from a list (BBC News, The Guardian, Sky News, NPR, Al Jazeera, DW, France 24, CBC, ABC, The Verge, tagesschau, El País, Le Monde, ANSA, g1 and news bulletins such as NPR News Now and the BBC Global News Podcast; the ones in Kodi's language first), or **Add a news feed** by its address (any RSS or Atom feed).
- **Top stories** puts them all together, newest first, and each site has its own list: the headline, its picture, a few lines and how long ago. A bulletin (a news podcast or video) plays. The whole article is on the web: Kodi can't show web pages, so the story shows its few lines and its address.
- **Home row**: **News: Headlines**. **Skin settings → More from MediaHub → News ticker** runs the latest headlines along the bottom of the home screen while you're at the top (it moves out of the way in the rows). It looks for news every quarter of an hour.

### MediaHub Space

**MediaHub Space** (`plugin.image.mediahub.space`) has NASA's [Astronomy Picture of the Day](https://apod.nasa.gov): a picture of space every day with an astronomer's explanation.

- **Today's picture** fills the screen with its explanation over the bottom (OK hides or shows it; some days it's a video, which plays). **The last few weeks**, and **A surprise from the archive** (any day since 1995).
- **NASA live**: NASA's live stream on YouTube (with the YouTube add-on). **Where is the space station?**: how high the ISS is, what it's above, how fast it's going and whether it's in sunlight (from [wheretheiss.at](https://wheretheiss.at)).
- **For MediaHub**: the **Space: Picture of the Day** home row, **Skin settings → More from MediaHub → Today's space picture as the background** (darkened behind the menus), and the screensaver's **Space pictures** style.
- No account needed: it uses NASA's DEMO_KEY, which allows a few dozen requests an hour (it asks a few times a day); a free key from [api.nasa.gov](https://api.nasa.gov) can go in its settings.

## Storage

**Skin settings → Storage → Picture cache** shows how much room Kodi's saved pictures (and old add-on downloads) take, and how many pictures there are. Kodi keeps a copy of every poster, backdrop and logo it has ever shown and never lets go of them, which adds up on a box with little storage like Apple TV. **Clear pictures not used for a month** removes those (through Kodi, so its picture list stays right) and the old add-on download zips; anything still in use is simply fetched again the next time it's shown.

## Lite mode

**Skin settings → Lite mode** is for Apple TV and other boxes short of memory: the home screen shows six rows instead of twelve (the others aren't loaded at all), and trailer previews, the banner trailer, backdrops, the artwork colour and moving effects are off. Turning it off puts those settings back the way they were. **Memory in use** shows how much memory Kodi is using and how much is free.

If free memory stays under 250 MB for a minute and a half while nothing plays, Lite mode turns itself on (once) and says so. **Turn on by itself when memory is low** stops that.

## Library health

**Skin settings → Library → Library health** shows what in your library needs a look:

- **Missing artwork**: movies and shows without a poster or a backdrop. **Look for missing artwork** asks Kodi to look them up again (50 at a time).
- **Duplicates**: the same movie twice (same IMDb / TMDB id, or same title and year), with the other file's name.
- **Not identified**: movies and shows the scraper didn't recognise (no plot and no artwork), usually a file or folder name it couldn't make sense of.

- **What's missing** (**Look for what's missing**): episodes that have been on TV but aren't in your library (from TVmaze; not the specials, nor what hasn't aired), shown per show as *3 missing: S03E01 · S03E02 · S03E03* (a whole season as *S01 (all 10)*), and the films of a collection you have part of that are out but not in your library (from TMDB, with the key from [On demand](#on-demand) or MediaHub Cinema). Select a collection's entry to see where each missing film can be watched in your country (streaming, free, rent or buy, from JustWatch through TMDB); with MediaHub Cinema, picking one offers its trailer and Tell me when it's out. It takes a while, so it runs when you ask, and the answer is kept for next time.

**Clean library** runs Kodi's own clean, which removes what's no longer on disk. Select an entry to open it.

## Trakt

[Trakt](https://trakt.tv) keeps what you've watched, your ratings and your watchlist the same on every device and app. **Skin settings → Trakt → Set up Trakt** installs the Trakt add-on from Kodi's repository; it then shows a code to enter at trakt.tv/activate. After that, **Trakt settings** opens its settings and **Sync with Trakt now** syncs straight away (it also syncs by itself).

## Welcome setup

The first time the home screen opens (in each profile), MediaHub asks five quick things: your colour; what you watch most (*A bit of everything*, *Mostly movies*, *Mostly TV shows* or *Kids and family*, which sets the home rows); whether to show network cards and which; and a shortcut to Kodi's profiles. **Skip** leaves everything as it is. Run it again from **Skin settings → Run the welcome setup again**.

## Accessibility

In **Skin settings → Accessibility**:

- **Text size**: *Large* makes everyday text (descriptions, details, buttons and labels) about a fifth bigger and headings a little bigger. It's Kodi's font setting, so it's also in **Settings → Interface → Skin → Fonts**.
- **High contrast**: black backgrounds, brighter text and edges and a stronger blue. It's a colour theme, so it takes the place of the accent colour.
- **Reduce motion**: no falling snow or twinkling lights, no light sweeping across network cards, no breathing logos, no zoom on the focused card and no slowly moving backgrounds.

**Colour from the artwork** (in the Look section) tints the background of the library, home screen and other pages with the colours of the focused title's backdrop, blown up until only its colours are left.

## Lyrics

On the music now-playing screen, press OK and choose the **Lyrics** button. The song's lyrics (from its tags) take the lower half of the screen and scroll by themselves; press it again to hide them. If a song has no lyrics and the **CU LRC Lyrics** add-on (`script.cu.lrclyrics`) is installed, the button opens it instead, to find them online.

## Start-up intro

When Kodi starts it first shows its loading splash. MediaHub replaces Kodi's with its own: the logo on a glow in the accent blue. When the skin takes over, the same picture comes alive in time with a short sound (a swoosh into a warm chord): the logo pops, a ring of light spreads out and rays burst behind it, then the home screen opens. It takes about 4 seconds, and any button skips it.

- **Skin settings → Intro when Kodi starts** turns it off (and puts Kodi's own splash back). **Intro sound** keeps the pictures but drops the sound.
- The sound goes through Kodi's interface sounds, so it's silent if **Settings → Interface → Sounds** is off, and it never shows as "now playing".
- The MediaHub splash is shown from the second start after installing, because the helper copies it into Kodi's folder (`special://home/media/splash.png`) once it runs. If you switch to another skin it takes it away again. If you've put a splash of your own there (`splash.jpg`, or your own `splash.png`), it's left alone.
- With **Show "Who's watching?"** on, Kodi goes straight to that screen and the intro doesn't play.
- Without the helper, the intro still plays after a moment, just silently.

## If Kodi closes by itself

**1.9.2 fixes another: a huge Live TV channel list.** The On now row asked Kodi for every TV channel and kept the 20 watched last, so Kodi built the whole list first. With an IPTV playlist of hundreds of thousands of entries (a video-on-demand list where every episode is a "channel") that used up the memory a little after start-up, whatever screen you were on, and Apple TV closed Kodi. The row now asks only for the channels you watched last, and hides until you've watched one. Such a playlist still makes Kodi's Live TV itself use a lot of memory. From 1.10.0, [On demand](#on-demand) reads it without Live TV, so you can turn IPTV Simple Client off, and [Lite mode](#lite-mode) saves memory elsewhere.

**1.9.1 fixes one cause.** When the MediaHub Helper was stopped while the banner trailer was playing (Kodi installing a helper update in the background just after start-up, or Kodi closing), the helper hung for 5 seconds. Kodi then force-stopped it, and that can make Kodi close by itself. The helper now stops straight away.

The MediaHub Helper (1.6.1 and newer) also keeps a note of where you are while you use Kodi. If Kodi closes on its own (a crash, or Apple TV closing it), the next time Kodi starts MediaHub tells you where it happened, for example *Home, The Last Orbit, as a trailer preview started*. If you were moving around the menus, it also offers **Safe mode** (in the skin's own window, so it never holds up the helper):

- **Safe mode** turns off trailer previews (home rows and the banner) and moving effects (**Reduce motion**). You can turn each back on in Skin Settings.
- If Kodi closes again with Safe mode already on, the cause is something else. Please send the log: install **Kodi Logfile Uploader** (**Add-ons → Install from repository → Kodi Add-on repository → Program add-ons**), run it and send the address it shows. After a crash the useful part is in `kodi.old.log`, which it uploads too. The helper also writes the last few places it saw into the log (`MediaHub Helper: Kodi closed unexpectedly last time`), with the screen, view, number of items and memory in use at each, and (from helper 1.6.3) copies the last 150 lines of the log of the session that closed (`MediaHub Helper: before the close | ...`). So the log to send is the one from the first start after the close: Kodi keeps only one older log, and it's replaced at the next start.

Closing Kodi normally, updating the helper or turning it off removes the note, so none of those count as a crash.
