# QuakeWatch for Android: your first mobile app with Saphan Studio

**Coming soon.** This repository will hold the Android app of QuakeWatch, built by AI coding agents with
[Saphan Studio](https://saphan.ai/) and approved step by step by one person, with a guide that shows how.

## What it will be

A small Android app (Kotlin, Jetpack Compose) for the [QuakeWatch server](https://github.com/saphan-ai/quake-watch-server):

- a **list** of recent earthquakes for your region, from the public USGS feed;
- a **map** of them (OpenStreetMap, no API key needed);
- a **threshold editor**: the weakest magnitude and the greatest depth you care about.

It works offline from the last data it saw, and you will be able to install it on your own phone from this README alone.

## How it will be built

The same way as the server: you tell the agents what you want, they build it in small steps, a reviewer from a different AI
company checks every step, and nothing is accepted without the owner. Every step will be written up here as it happens.

Start with the server, which is already done: [quake-watch-server](https://github.com/saphan-ai/quake-watch-server).

Licence: the code is [Apache-2.0](LICENSE); the guide and the build record are [CC BY 4.0](LICENSE-docs).
