# Music System in BDFD v5.0

An advanced system to play music with your Discord bot using Bot Designer For Discord.

## Configuration

#### You only need to create 2 required variables

| Name     | Value                         |
| :------- | :---------------------------- |
| `TOKEN`  | `Your Discord bot token`      |
| `musicMS` | `No value`                    |

## Commands
- !play
- !stop
- !vol
- !musicIA
- $onInteraction (2)

## Author

- [Edgajuman](https://github.com/edgajuman)

## Support

https://discord.gg/RMSYrQCs2r

## Additions in the previous version
- Improved the premium system to offer more advantages to PREMIUM bots
- NOW YOUR BOT CAN PLAY MUSIC FROM YOUTUBE BY NAME OR URL
- Pause and Resume functionality
- Skip functionality
- Action buttons
- Playlist
- Action loading improved; responses are now faster (except !play, which requires music search)
- Added user voice channel presence checks
- Now shows the names of the currently playing songs
- Volume control system added
- Rewind system added
- Fixed a bug that caused the entire playlist to repeat when loading new music
- Added a Music Card for a visually appealing view during !play
- Implemented additional necessary checks (thanks to this, the "play" variable is no longer required)
- Now when your bot is disconnected from the voice channel without using !stop, the playlist will be automatically deleted (to avoid glitched playback and improve the experience)

## Additions in the new version v5.0
- Buttons will now always appear on the most recently added song
- Greatly reduced the errors that prevented songs from being added
- Fixed issues for NON-PREMIUM bots
- Added AI system (This system will give song recommendations and add them to the playlist automatically)
- Changed search library for better readability and to avoid most common errors
- Added color to buttons and action names
- Added a download system to download the currently playing song (Only for 1 minute, after that it won’t be downloadable)

## Possible Bugs
The system is fully functional, although there are a few bugs that will be fixed over time.
Some known issues:
- Songs not being added to the playlist (rarely happens, mostly depends on YouTube's API and video permissions)

## BotPanel
> A panel has been developed for bots using this music system.  
`Link:` https://edgabot.lucnodes.es/
### Demo video
https://vimeo.com/1077124656
