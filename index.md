---
layout: default
title: Afterparty Groovy Music
description: High quality Discord music playback with queue tools, filters, and premium listening features.
---

## Overview

**Afterparty Groovy Music** is the music-focused Discord bot from Afterparty Bot Labs. It is built for quick song playback, clean queue handling, direct link support, and a polished voice experience for both casual listening and always-on community music rooms.

## Features

- High quality audio playback through Lavalink
- Search queries and direct URL playback
- Queue tools for moving, removing, looping, and shuffling songs
- Audio controls for volume, seek, filters, and equalizer changes
- Premium source support for Spotify and Apple Music in supported deployments

## Quick Start

1. Invite the bot to your server.
2. Join the voice channel where you want playback to happen.
3. Use `/play` with a song name or direct link.
4. Open `/queue` to review what is lined up next.

## Commands

### Playback

`/play`, `/search`, `/pause`, `/resume`, `/skip`, `/previous`, `/replay`, `/stop`

### Queue

`/queue`, `/move`, `/remove`, `/clear`, `/shuffle`, `/loop`

### Audio

`/volume`, `/seek`, `/filters filter`, `/equalizers equalizer`, `/audio-output`, `/autoplay`, `/247`

### Utility

`/nowplaying`, `/join`, `/disconnect`, `/help`, `/support`, `/invite`

## Required Permissions

- View Channels
- Connect
- Speak
- Send Messages
- Embed Links
- Read Message History
- Use Slash Commands

## Troubleshooting

- If the bot is not joining, confirm it can view, connect to, and speak in the target voice channel.
- If playback starts but you hear nothing, retry with `/stop` followed by `/play` and confirm the Lavalink node is online.
- If searches fail, try a more specific artist plus track query or use a direct URL.
- If premium sources fail, verify your deployment and entitlement setup first with a standard YouTube search as a control test.

## FAQ

### Does it support direct links?

Yes. You can paste supported track or playlist URLs directly into `/play`.

### What should I check if music stops unexpectedly?

Check the voice connection, Lavalink node health, and whether the current source provider is having issues.

### Are Spotify and Apple Music always available?

Not always. Those sources can depend on premium access and source availability in your deployment.

## Support

Use the Support button above to join the Afterparty support server. For source code and release context, use the GitHub button in the header.
