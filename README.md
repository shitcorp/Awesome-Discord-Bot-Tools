# Awesome Discord Bot Tools

> A curated collection of tools for developers working on Discord bots

## Table of Contents

- [Alternate Gateways](#alternate-gateways)
- [Libraries](#libraries)

  - [Go](#go)
  - [JavaScript](#javascript)
  - [Multi Lang](#multi-lang)
  - [Python](#python)
  - [Rust](#rust)

- [MISC](#misc)

---

## Alternate Gateways

- [gateway-proxy](https://github.com/Gelbpunkt/gateway-proxy) - Drop-in proxy for Discord gateway connections and sessions allowing for zero downtime deploys
- [rateway](https://github.com/IdleRPGBot/rateway) (maybe dead) - A stateful gateway for Discord Bots. Scaling well, it processes messages from the Discord gateway and puts them in AMQP exchanges

---

## Libraries

### Go

- [arikawa](https://github.com/diamondburned/arikawa) - A Golang library and framework for the Discord API
- [corde](https://github.com/Karitham/corde) - A high level discord interactions wrapper, simple, idiomatic, testable and extensible.
- [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for Discord
  - [dgrs](https://github.com/zekroTJA/dgrs) - A (WIP) DiscordGo state manager using Redis
  - [ken](https://github.com/zekroTJA/ken/) - A cutting edge (haha), object-oriented and highly modular application command handler for Discordgo
- [disgo](https://github.com/disgoorg/disgo) - A modular Golang Discord API Wrapper
- [disgord](https://github.com/andersfylling/disgord) - Go module for interacting with the documented Discord's bot interface

### JavaScript

- [detritusjs](https://github.com/detritusjs) (dead) - A wheels-attached, pure-TypeScript library for the Discord API.

- [discord.js](https://discord.js.org/#/) - The most popular discord bot framework

  - [discord-cross-hosting](https://github.com/meister03/discord-cross-hosting) - Scale discord.js horizontally
  - [discord-hybrid-sharding](https://github.com/meister03/discord-hybrid-sharding) - Allows clustering with discord.js sharding
  - [discord.js-light](https://github.com/timotejroiko/discord.js-light) - All the power of discord.js, zero caching
  - [Kurasuta](https://github.com/DevYukine/Kurasuta) - Discord.js sharder with clustering support

- [Eris](https://abal.moe/Eris/) - A lightweight and flexible library
  - [eris-fleet](https://github.com/danclay/eris-fleet/) - Cluster management for Discord bots using the Eris library
  - [eris-sharder](https://github.com/discordware/eris-sharder) (dead) - Sharding manager for the discord Eris library
  - [megane](https://github.com/brussell98/megane) - A framework for large multi-process Discord bots
  - [redis-sharder](https://github.com/privy-gg/redis-sharder) - Scalable and robust sharding solution for the Eris discord library.
- [Paracord](https://github.com/paracordjs/paracord) (dead) - NodeJS Discord API framework built to scale
- [Weather Stack](https://github.com/DasWolke/CloudStorm) - Ecosystem of tools for microservice Discord bots

### Multi Lang

- [Spectacles](https://github.com/spec-tacles) - A distributed Discord API wrapper

### Python

- [discord.py](https://discordpy.readthedocs.io/en/stable/)

### Rust

- [serenity](https://github.com/serenity-rs/serenity) - A Rust library for the Discord API
- [Twilight](https://twilight.rs/) - **twilight** is a powerful asynchronous, flexible, and scalable ecosystem of Rust libraries for the Discord API

## MISC

- [BotBlock.org](https://botblock.org/) - The single source for all Discord bot lists. Simplify sending your bot's guild count with the BotBlock API.
- [gateway-queue](https://github.com/twilight-rs/gateway-queue) - Ratelimited gateway queue for multiserviced bots.
- [http-proxy](https://github.com/twilight-rs/http-proxy) - A ratelimited HTTP proxy in front of the Discord API

---

## Contributing

Please try to keep your additon in line with the general formating of this document. Some basic guidlines are:

- List in alphanumeric order
- Provide a meanful description (ie. what sets it apart)
- Provide a link to the project
