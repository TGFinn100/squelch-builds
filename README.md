# Squelch Builds

This is an early test build of Squelch, a multiplayer prototype using Steam's networking and voice systems. Host a lobby and invite a friend through Steam to connect, then talk to each other over a live voice channel — each player has a quality slider to distort and degrade how clearly they hear the other person's voice in real time, from clear to heavily corrupted. This build exists purely to test the lobby, connection, and voice systems; there's no gameplay yet.

## Download

Two ways to get a build:

- **Releases** (recommended, smallest download): grab the latest zip from the [Releases](../../releases) page and unzip it.
- **Clone via GitHub Desktop**: clone this repo, then run `Squelch.exe` from the version folder (e.g. `0.0.1/Squelch.exe`).

**Requirements:** Steam must be running and you must be logged in. This build includes debug-console access for testing.

## How to test with a friend

1. One person runs the build and clicks **Host**.
2. Invite your friend via the in-game friends list (the Steam overlay invite dialog doesn't work in this build).
3. Once your friend joins, voice chat starts automatically — talk normally.
4. Use the quality slider to hear how the connection degrades your friend's voice in real time.
