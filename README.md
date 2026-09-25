## Hi, I'm Marwan

I'm a software engineer at METI (Micro Engineering Tech), and I finish my Computer Engineering degree at the American University in Cairo in December 2026. I live in Cairo, hold UAE residency, and work in English and Arabic.

At work I build full-stack products with Laravel, Next.js and Angular. On my own time I build real-time things: browser games with their own netcode, a native iPhone and Apple Watch app, and firmware for a Cortex-M4. The bugs I enjoy most only show up under load.

[Portfolio](https://marwanmoh11.github.io) · [CV (PDF)](https://marwanmoh11.github.io/cv.pdf) · [LinkedIn](https://www.linkedin.com/in/marwan-abudaif-088567283/) · marwanabudaif5@gmail.com

### Selected work

**[GeoFighters 2.0](https://github.com/MarwanMoh11/Geo-FightersV2)** ([play it](https://marwanmoh11.github.io/Geo-FightersV2/))
A co-op 3D survival shooter that runs in the browser, about 45k lines of TypeScript. Players connect host-star over WebRTC, and 30 Hz snapshots travel on unreliable, unordered data channels so a lost packet never holds up a newer one. When ICE fails, that player falls back to a socket.io relay.
`TypeScript` `Three.js` `Svelte 5` `Rapier` `miniplex ECS` `WebRTC`

**[GymTrack](https://github.com/MarwanMoh11/Gymtrack)**
A strength tracker for iPhone and Apple Watch. The phone owns the data and the watch mirrors it, so a set logged on the wrist is saved on the phone and the two screens stay in sync. Live workouts run through HealthKit. It also has widgets, a Live Activity for the rest timer and Siri shortcuts, with no third-party dependencies.
`Swift` `SwiftUI` `SwiftData` `HealthKit` `WatchConnectivity`

**[Emberhold](https://github.com/MarwanMoh11/emberhold)** ([play it](https://marwanmoh11.github.io/emberhold/))
Horde survival on top of a settlement-building loop, playable on desktop and phone. All of the art, sound and terrain is generated in code at boot, so the repository has no asset files.
`TypeScript` `Phaser 3` `Vite`

**[smart-redlight-tm4c123](https://github.com/MarwanMoh11/smart-redlight-tm4c123)**
A red-light violation detector on a TI Tiva C board (ARM Cortex-M4). Six FreeRTOS tasks communicate only through queues, and a dwell-time filter on the ultrasonic sensor ignores fast swipes and parked objects. Built with a hand-written Makefile.
`C` `FreeRTOS` `arm-none-eabi-gcc` `TivaWare`

**[Pixel-Perfect](https://github.com/MarwanMoh11/Pixel-Perfect)**
4x super-resolution for pixel art, built with one teammate. I wrote the ESRGAN model, the training loop and the losses. Training pairs are downsampled with nearest-neighbour and an edge-aware loss penalises blur, so upscaled sprites keep their hard edges.
`Python` `PyTorch`

**[Digital_Design_I](https://github.com/MarwanMoh11/Digital_Design_I)**
An event-driven gate-level logic simulator from a course group project. It reads per-gate propagation delays from a cell library and schedules each output change on a time-ordered priority queue.
`C++`

### At work

At METI I've shipped four products back to back since June 2025:

- **MVS Client Portal:** sole engineer on a multi-tenant Laravel 12 and Next.js 16 portal with nine features across three roles, backed by 49 test classes.
- **GuloGulo:** a geospatial AI platform built by a team of seven. I owned chat, datasets and settings, including a resumable multipart upload engine and a hand-written SSE client that falls back to polling.
- **Aqtar:** a Saudi B2B geospatial services marketplace built by about ten engineers. I owned ratings and reviews, content moderation, admin user management and the English/Arabic localisation layer.
- **AI Author Tool:** an Angular platform that turns uploaded documents into structured courses.

That code is private. The portfolio has the details.

### Right now

I'm leading a seven-person senior thesis, TELOS II, which tests whether a recommender can adapt to evidence while holding its position under conversational pressure. A versioned, SHA-256-pinned deterministic policy makes every decision, and the language model only writes the response.

### Tools

**Languages:** TypeScript, Python, PHP, Swift, C, C++, SQL
**Web:** React, Next.js, Angular, Svelte, Tailwind, Laravel, FastAPI, Node.js
**Data:** PostgreSQL with PostGIS, MySQL, SwiftData, Firebase
**Real-time and graphics:** Three.js, WebRTC, Server-Sent Events, Phaser
**Mobile and embedded:** SwiftUI, Capacitor, FreeRTOS on ARM Cortex-M4
