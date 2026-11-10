# Awesome Discord [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for the Discord API, Gateway WebSockets, bot frameworks, Embedded App Activities SDK, Slash Commands, interaction UI components, and community moderation tooling.

Discord is a real-time voice, video, and text communication platform structured around community servers, channels, and interactive application integrations. Programmatic development on Discord involves Gateway WebSocket connections, REST APIs, Slash Commands, UI components (buttons, select menus, modals), embedded client Activities, and OAuth2 authentication. This list is intended for bot developers, Discord application architects, community managers, systems integration engineers, and server automation leads.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Official APIs & Platform Documentation](#official-apis--platform-documentation)
- [API Wrappers & SDKs](#api-wrappers--sdks)
  - [JavaScript & TypeScript](#javascript--typescript)
  - [Python & Other Languages](#python--other-languages)
- [Embedded App Activities & Rich Presence](#embedded-app-activities--rich-presence)
- [Bot Frameworks & Self-Hosted Automation](#bot-frameworks--self-hosted-automation)
- [Developer Tooling & Testing](#developer-tooling--testing)
- [Related Awesome Lists](#related-awesome-lists)

## Official APIs & Platform Documentation

Official platform APIs, Gateway event specifications, OAuth2 flows, and interaction component guides.

- [Discord Developer Portal](https://docs.discord.com/developers/intro) — Official hub providing documentation for Discord REST APIs, Gateway events, application registration, and bot tokens.
- [Discord Interactions API](https://docs.discord.com/developers/platform/bots) — Specification for handling application slash commands, context menus, buttons, select menus, and modal dialogs.
- [Discord Gateway WebSockets](https://docs.discord.com/developers/reference) — Real-time bidirectional event stream protocol connecting bots to guild events, voice states, and message streams.
- [Discord OAuth2 Portal](https://docs.discord.com/developers/intro) — OAuth2 authentication framework for third-party logins, bot authorization scopes, and user identity retrieval.

## API Wrappers & SDKs

Language-native libraries handling Gateway connections, rate-limit bucketing, command routing, and object modeling.

### JavaScript & TypeScript

- [discord.js](https://github.com/discordjs/discord.js) — The most popular object-oriented Node.js module for interacting with the Discord API and Gateway.
- [oceanic.js](https://github.com/OceanicJS/Oceanic) — Lightweight, fast TypeScript wrapper designed as a modern successor to Eris for Node.js runtimes.
- [discord-api-types](https://github.com/discordjs/discord-api-types) — Up-to-date TypeScript type definitions for the Discord API and Gateway payloads.

### Python & Other Languages

- [discord.py](https://github.com/Rapptz/discord.py) — Modern, async-ready Python wrapper for the Discord API featuring built-in command handling and rate-limit safety.
- [hikari](https://github.com/hikari-py/hikari) — Opinionated, type-safe Python micro-framework for building high-performance Discord bots.
- [Serenity (Rust)](https://github.com/serenity-rs/serenity) — Fast and modular Rust library for managing Discord Gateway connections and REST endpoints.
- [Disgord (Go)](https://github.com/andersfylling/disgord) — Go library providing concurrency control and strong typing for Discord API interactions.

## Embedded App Activities & Rich Presence

SDKs and frameworks for hosting interactive HTML5 games and apps directly within Discord channels.

- [Discord Embedded App SDK](https://github.com/discord/embedded-app-sdk) — Official SDK for building iframe-based Activities that run natively inside Discord client windows.
- [Discord Rich Presence (RPC)](https://docs.discord.com/developers/intro) — Local IPC protocol allowing desktop games and applications to display real-time status and party invites.
- [discord-activity-starter](https://github.com/discord/embedded-app-sdk) — Official starter repository for building React and Vite applications for Discord Activities.

## Bot Frameworks & Self-Hosted Automation

Turnkey bot applications, modular command frameworks, and open-source moderation suites.

- [Red-DiscordBot](https://github.com/Cog-Creators/Red-DiscordBot) — Self-hosted, modular Python bot framework supporting custom cog plugins, audio playback, and moderation.
- [JMusicBot](https://github.com/jagrosh/MusicBot) — Self-hosted Java music bot designed to stream high-quality audio into voice channels.
- [Carl-bot Ecosystem](https://carl.gg/) — Automated server management tools for reaction roles, custom logging, and auto-moderation.

## Developer Tooling & Testing

Local proxies, payload inspectors, mock gateways, and permissions calculators for Discord engineers.

- [Discord Permissions Calculator](https://discordapi.com/permissions.html) — Visual utility for generating custom OAuth2 invite links with precise bitwise permission integer flags.
- [Discord Component Builder](https://discord.com/developers) — Interactive web builder for designing message layouts, action rows, and interactive buttons.
- [Discohook](https://discohook.org/) — Visual web application for crafting, testing, and sending rich JSON embeds via Discord Webhooks.

## Related Awesome Lists

- [Awesome Twitch](https://github.com/brandonhimpfen/awesome-twitch) — Twitch Helix API, EventSub WebSockets, chat bots, and stream overlays.
- [Awesome Reddit](https://github.com/brandonhimpfen/awesome-reddit) — Reddit Data API, Devvit platform, PRAW, and community moderation bots.
- [Awesome JavaScript](https://github.com/brandonhimpfen/awesome-javascript) — Web runtimes, Node automation libraries, and asynchronous event pipelines.
- [Awesome Python](https://github.com/brandonhimpfen/awesome-python) — Data scraping frameworks, media processing, and machine learning toolkits.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
