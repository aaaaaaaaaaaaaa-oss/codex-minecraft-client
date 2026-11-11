Codex Minecraft Client

Codex Minecraft Client is an experimental, personal-use project for operating Minecraft: Java Edition as a player from an Ubuntu command-line environment. It uses the Minecraft Java client and Forge, with a low-resolution display and local keyboard and mouse input. It is not affiliated with or endorsed by Mojang, Microsoft, or OpenAI.

The project aims to let an AI assistant observe the game, communicate with other players, and perform ordinary in-game actions while following server rules and respecting other players. A client-side Forge extension provides inventory information and records limited terrain observations from the player's view. The system does not use teleportation to move the player.

## Development status

- Minecraft 1.20.1 with Forge has been tested in a local single-player world with mods.
- Command-line controls, limited observations, and preliminary automation components are implemented.
- Autonomous play and chat with an AI model have not yet been verified end to end.
- Microsoft account authentication and connection to an online-mode Forge server are under development and have not yet been verified.
- This is an experimental project, not a publicly released service.

## Why Minecraft API access is requested

The application requests Minecraft authentication access so its owner can sign in with a Microsoft account that owns Minecraft: Java Edition and join compatible servers as a normal authenticated player. The device-code flow lets the user sign in on Microsoft's website; the application does not ask the user to disclose their Microsoft password to it. The application stores credentials locally for subsequent launches.

Minecraft is a trademark of Mojang AB. This project is independent and is not an official Minecraft product.
