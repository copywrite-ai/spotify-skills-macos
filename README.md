# Spotify Control Skills for OpenClaw (macOS)

A dedicated OpenClaw Skill to control Spotify playback and retrieve track metadata on macOS via AppleScript.

## Features

- **Playback Controls**: Play, pause, toggle (play/pause), next, and previous.
- **Volume Management**: Adjust Spotify's internal volume independently of system volume.
- **Track Navigation**: Seek to specific positions in a song.
- **Metadata Retrieval**: Get real-time info about the current song, artist, album, and Spotify URL.
- **Playback Logic**: Toggle shuffle and repeat modes.

## Requirements

- **OS**: macOS
- **App**: Spotify Desktop
- **Environment**: Python 3 (for the wrapper script)

## Installation

Clone this repository into your OpenClaw or workspace:

```sh
git clone https://github.com/copywrite-ai/spotify-skills-macos
```

The OpenClaw agent will automatically detect the skill in `.agents/skills/spotify-control/`.

## Usage Examples

```sh
# Toggle playback
./scripts/spotify-control playpause

# Get what's playing right now
./scripts/spotify-control get-info

# Set volume to 75%
./scripts/spotify-control set-volume 75
```

## Contributing

Feel free to open issues or PRs to support more features or apps!
