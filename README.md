# Dragonball: Infinite Chaos

A desktop MUD client for Windows and macOS with an illustrated world atlas, separate channel chat, room and mob panels, combat highlights, and configurable quick actions.

## Download and play

[Get the latest client](https://github.com/narixsu/dragonball-infinite-chaos/releases/latest)

- **Windows:** download `InfiniteChaos-Client-2.2-Windows.zip`, extract the ZIP, and run `InfiniteChaos.exe`.
- **Mac:** download `InfiniteChaos-Client-2.2-macOS.zip`, extract the ZIP, and open `DBIC Client.app`. Supports Apple Silicon (macOS 13+) and Intel (macOS 11+).

Click **Connect** and log in or create a character. The server is preset to **malls-prada.tun.ply.gg**, port **43666**. Player instructions and Godot runtime notices are bundled in both ZIPs.

The Mac app is ad-hoc signed, not Apple-notarized, and may need macOS approval to open. Its bundle, architectures, and permissions have been checked; a native Mac launch has not yet been tested.

## New in 2.2

- Illustrated planet atlas with forests, mountains, coastlines, ocean waves, roads, cities, landmark icons, and a player beacon.
- **Planet** fits the whole world; **Expand** opens a larger map window, and **Dock** returns it. Scroll to zoom, drag to pan, and hover landmarks for their names.
- **Atlas preview** provides an offline Earth map demo.
- Last command stays selected after Enter: Enter repeats, typing replaces. Configurable in Settings. Passwords still clear immediately and are excluded from history.

![Planet atlas](https://github.com/narixsu/dragonball-infinite-chaos/releases/download/v2.2.0/AtlasPreview.png)

## Other features

- Current-room panel with larger descriptions, exits, mobs, players, and aura details. Drag the divider to resize it. It refreshes when you move or use Look and needs the matching server room-panel update.
- All, OOC, Chat, Clan, Tells, and Staff tabs with unread counts.
- Live life, ki, armor, power, focus, and target-life displays; compact battle HUD inside Combat Feed while fighting.
- World Feed retains every server message. Combat highlights use text matching and may not recognize every attack.
- Six configurable quick actions, aliases, font sizing, aura themes, and reduced battle animations.

Life-change indicators show net change between server updates. This repository distributes the client; game server files and player accounts are not included.
