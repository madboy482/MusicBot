# Tesla MusicBot
### A bot that can play music on Telegram Group and Channel Voice Chats

https://user-images.githubusercontent.com/73926361/126453534-7712ed8b-5dfe-48c2-9178-472981a41967.mp4

#### POWERED BY [PYTGCALLS](https://github.com/pytgcalls/pytgcalls)
### Available on telegram as [@TeslaMusicRoBot](https://telegram.me/TeslaMusicRoBot)
### UserBot Helper : [@TeslaMusicPlayer](https://telegram.me/TeslaMusicPlayer)

<p align="center">
  <img src="https://media.giphy.com/media/S7jznj1TlqH9otxZux/giphy.gif">
</p>

<h2> Features 🔥 </h2>

- Thumbnail Support
- Playlist Support
- Current playback support
- Showing track names when skipping
- Zero downtime, Fully Stable
- Deezer,Youtube & Saavn playback support
- Settings panel
- Control with buttons
- Userbot auto join
- Channel Music Play
- Keyboard selection support for youtube play

---
---
---

## 🚀 Deployment

* 🌐 Heroku:

#### Generate String session [IMPORTANT]
- Get it by running this [![GenerateString](https://img.shields.io/badge/repl.it-GenerateString-redblack)](https://replit.com/@madboy482/Pyrogram-Session)

or 

- Run this file [str.py](https://raw.githubusercontent.com/madboy482/MusicBot/Music/str.py) locally.

Then you will get a session string, copy it, then press heroku deploy button.

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2Fmadboy482%2FMusicBot&template=https%3A%2F%2Fgithub.com%2Fmadboy482%2FMusicBot)

---

* ⚔ Self-hosting:
```sh
# Install Git First (apt-install git)
$ git clone https://github.com/madboy482/MusicBot
$ cd MusicBot
# Upgrade sources
# Install All Requirements 
$ pip3 install -r requirements.txt
# Rename example.env to local.env and fill
$ npm i -g npm
# Start Bot 
$ python3 -m MusicBot
```

---
---
---

### Commands for Group 🛠
#### For all in group

- `/play <song name>` - play song you requested
- `/play <reply to audio>` - play replied file
- `/dplay <song name>` - play song you requested via deezer
- `/splay <song name>` - play song you requested via jio saavn
- `/ytplay <song name>`: Directly play song via Youtube Music
- `/playlist` - Show now playing list
- `/current` - Show now playing
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/deezer <song name>` - download songs you want quickly via deezer
- `/saavn <song name>` - download songs you want quickly via saavn
- `/video <song name>` - download videos you want quickly

#### Admins only.
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/userbotjoin` - invite assistant to your chat
- `/userbotleave` - remove assistant from your chat
- `/admincache` - Refresh admin list
- `/musicplayer [on/off]` - Enable/Disable Music Player

### Commands for Channel Music Play 🛠
For linked group admins only:
- `/cplay <song name>` - play song you requested
- `/cplay <reply to link>` - play replied youtube link
- `/cplay <reply to audio>` - play replied file
- `/cdplay <song name>` - play song you requested via deezer
- `/csplay <song name>` - play song you requested via jio saavn
- `/cplaylist` - Show now playing list
- `/cccurrent` - Show now playing
- `/cplayer` - open music player settings panel
- `/cpause` - pause song play
- `/cresume` - resume song play
- `/cskip` - play next song
- `/cend` - stop music play
- `/userbotjoinchannel` - invite assistant to your chat
* channel is also can be used instead of c

If you don't like to play in linked channel:
 1. Get your channel ID.
 2. Rename your group to: Channel Music: your_channel_id
 3. Add @TeslaMusicRoBot as Channel admin with full perms
 4. Add helper to channel (@TeslaMusicPlayer)
 5. Simply send commands in your group.

### Commands for Sudo Users ⚔️
- `/userbotleaveall` - remove assistant from all chats
- `/gcast <reply to message>` - globally brodcast replied message to all chats
- `/pmpermit [on/off]` - enable/disable pmpermit message

#### PmPermit
- `.a` - approove someone to pm you
- `.da` - disapproove someone to pm you
+ Sudo Users can execute any command in any groups

---
---
---

# Credits 😊
## • MADBOY   »»  <a href="https://github.com/madboy482" alt="MadBoy"> <img src="https://img.shields.io/badge/MADBOY-30302f?logo=github" /></a> {DEV}

## • PRANAV  »»  <a href="https://github.com/Pranav18262" alt="Pranav"> <img src="https://img.shields.io/badge/Pranav-625D5D?logo=github" /></a> {DEV}

---
---

### Special Credits --
- [InukaASiTH](https://github.com/InukaAsith)
- [Technical-Hunter](https://github.com/Technical-Hunter)
- [Rojserbest](http://github.com/rojserbes)
- [Wrench](https://github.com/EverythingSuckz/)
- [Bemro](https://github.com/bemroofficial)
- [QueenArzoo](https://github.com/QueenArzoo)
- [lucifeermorningstar](https://github.com/lucifeermorningstar)
- [AuraXNetwork](https://github.com/AuraXNetwork/AuraXMusicBot)
- [Hamker Cat](https://github.com/thehamkercat/)
- [Anjana-Ma](https://github.com/Anjana-Ma)
- [ImJanindu](https://github.com/ImJanindu)
- [Laky](https://github.com/Laky-64) & [Andrew](https://github.com/AndrewLaneX): PyTgCalls
- [Original Repo owners](https://github.com/suprojects/CallsMusic)

---
---

### Special Thanks to :
- [Rojserbest](http://github.com/rojserbest): Callsmusic Developer

>> This bot is based on the original work done by [Rojserbest](http://github.com/rojserbest). Without his hardwork Tesla Music Bot won't exist. 
>>
>> Tesla Music Bot is a modified version of [Callsmusic](https://github.com/callsmusic/callsmusic) that fits the needs of @TeslaMusicRoBot users.
