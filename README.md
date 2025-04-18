# Music System in BDFD v4.0

A system for playing music with your Discord bot in Bot Designer For Discord.

## Configuration

#### You only need to create 1 variable

| name | value |
| :-------- | :------- |
| `TOKEN` | `Your Discord bot token` |

## Commands
- !play
- !stop
- !vol
- $onInteraction (2)

## Author

- [Edgajuman](https://github.com/edgajuman)

## Support

https://discord.gg/RMSYrQCs2r

## New Stuff and Updates
- Improved the premium system to give more advantages to PREMIUM bots
- Pause and Resume Functionality
- Skip Functionality
- Action Buttons
- Playlist
- Fixed loading actions; they now respond faster, except for !play, since it searches for music
- Added checks to determine whether the user is in a channel or not
- Added names of currently playing music
- Added a volume system
- Added a rewind system
- Fixed a bug that caused the entire playlist to repeat when loading new music
- Added a Music Card for an attractive music view in !play
- More necessary checks have been implemented (thanks to this, the "play" variable will no longer be needed)
- Now, when your bot is disconnected from the voice channel without the !stop, the playlist will be automatically deleted (this improves the experience and prevents bugged playback)

## Possible Bugs
The system is fully functional, although it has some bugs that will be fixed later.
Some bugs may include:
- Not adding music to the playlist (rarely, this depends more on the music download API)

## Coming Soon
- A user panel is being developed so you can control your bot's music system from a web-based dashboard
