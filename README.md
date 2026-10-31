# Dragonball: Infinite Chaos

A desktop MUD client with a detailed world atlas, miniature area landscapes, separate channel chat, pinned room details and animated combat effects.

## Download and play

[Get the latest client](https://github.com/narixsu/dragonball-infinite-chaos/releases/latest)

- **Windows:** download `InfiniteChaos-Client-2.3-Windows.zip`, extract it, and run the new `InfiniteChaos.exe`. Close the older client first.
- **Mac preview:** `InfiniteChaos-Client-2.3-macOS-Preview.zip` is experimental. Supports Apple Silicon (macOS 13+) and Intel (macOS 11+), but has not been launched on a native Mac. The reported damaged/cannot-open issue is **not confirmed fixed**. It is ad-hoc signed, not Apple-notarized; see the bundled START_HERE.txt.

Click **Connect** and log in or create a character. The server is preset to **malls-prada.tun.ply.gg**, port **43666**. Player instructions, checksums and Godot notices accompany the downloads.

## New in 2.3

- Detailed atlas with smooth ocean-depth shading, textured terrain, mountain relief, forest canopies, miniature buildings, distinct landmark icons, coordinate guides and readable labels.
- Raised local room tiles show forests, buildings, water and mountains, with clearer paths, doors and stairs. Double-click routes avoid closed and locked doors.
- Nearby mob badges show counts, hostile/trainer colors and hover names. **Requires the matching server update and hotboot.** Live mob snapshots respect visibility, darkness, local range and hidden/closed exits.
- Combat Feed includes ki beams, impact rings and defense effects, based on game text. **Reduce animations** keeps the display static.
- Command and chat input remain in typing mode after Enter. The last command stays selected: typing replaces it, Enter repeats it. Passwords clear immediately and stay out of history.

![World atlas](https://github.com/narixsu/dragonball-infinite-chaos/releases/download/v2.3.0/AtlasPreview.png)

![Area landscapes](https://github.com/narixsu/dragonball-infinite-chaos/releases/download/v2.3.0/AreaPreview.png)

Scroll to zoom, drag to pan, **Expand** for a larger map, **Dock** to return it, and **Planet** to fit the world. **Atlas preview** shows an offline Earth demo.

## Other features

- Pinned room descriptions, exits, occupants and aura details, refreshed on movement or Look with the matching server update.
- All, OOC, Chat, Clan, Tells and Staff tabs with unread counts.
- Life, ki, armor, power, focus and target-life displays; combat HUD appears in Combat Feed while fighting.
- World Feed preserves every server message. Combat highlights use text matching and may not recognize every attack. Life-change indicators show net changes between server updates, not per-hit damage.
- Quick actions, aliases, font sizing and aura themes.

Interaction tests, mob-visibility tests, a full server candidate build and exported Windows startup passed. Mac checks verify packaging, permissions and signature hashes only; Mac launch and Gatekeeper acceptance remain unverified. The game server has not been hotbooted by this release. This repository distributes the client; game server files and player accounts are not included.
