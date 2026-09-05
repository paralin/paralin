# Hi, I'm Christian Stewart

I'm the founder of [Aperture Robotics]. I build open-source software for
distributed systems, embedded Linux, and collaborative computing.

[LinkedIn](https://linkedin.com/in/paralin) · [X](https://twitter.com/paralinq) · [Stack Overflow](https://stackoverflow.com/users/431369/christian-stewart) · [Instagram](https://instagram.com/paralinq/) · [SkiffOS Discord](https://discord.gg/EKVkdVmvwT)

## Spacewave

**A shared workspace for people, agents, and their tools.**

I'm building Spacewave to bring files, conversations, applications, and
computers into shared Spaces. The goal is to make it easy to work together,
follow what an agent is doing, and continue across devices.

Spacewave is in active development. Its foundations combine local storage,
peer-to-peer networking, and plugins, with components built in Go,
TypeScript, and WebAssembly.

[Explore Spacewave][spacewave] · [Browse the source][spacewave-code]

[Aperture Robotics]: https://github.com/aperturerobotics
[spacewave]: https://spacewave.app
[spacewave-code]: https://github.com/s4wave/spacewave

## Selected projects

- [SkiffOS]: a lightweight Linux distribution for running containers across different hardware, including Raspberry Pi and other single-board computers. Read the [paper][arxiv] and its use in the [CNS Flight Stack].
- [QuickJS WASI Reactor][quickjs-wasi]: run [QuickJS-NG] in Go and TypeScript through the WASI reactor model.
- [ocpipe]: SDK for LLM pipelines with [OpenCode] and [Zod].
- [GoScript][goscript]: compile Go to TypeScript.
- [Bifrost][bifrost]: configurable peer-to-peer networking for Go and TypeScript.
- [flex-layout]: interactive drag-and-drop layouts for React.
- [StaRPC][starpc], [protobuf-go-lite], and [protobuf-es-lite]: lightweight, reflection-free Protobuf and RPC implementations for browsers, WebAssembly, and embedded systems.

[SkiffOS]: https://github.com/skiffos/skiffos
[arxiv]: https://arxiv.org/pdf/2104.00048
[CNS Flight Stack]: https://ieeexplore.ieee.org/document/9849131
[quickjs-wasi]: https://github.com/aperturerobotics/js-quickjs-wasi-reactor
[QuickJS-NG]: https://github.com/quickjs-ng/quickjs
[goscript]: https://github.com/paralin/goscript
[bifrost]: https://github.com/aperturerobotics/bifrost
[flex-layout]: https://github.com/aperturerobotics/flex-layout
[ocpipe]: https://github.com/s4wave/ocpipe
[OpenCode]: https://github.com/sst/opencode
[Zod]: https://zod.dev
[protobuf-es-lite]: https://github.com/aperturerobotics/protobuf-es-lite
[protobuf-go-lite]: https://github.com/aperturerobotics/protobuf-go-lite
[starpc]: https://github.com/aperturerobotics/starpc

## Background

**Buildroot.** I've [contributed][contributor] packages for container runtimes,
Go development, networking, and hardware support to [Buildroot], which SkiffOS
uses to build its Linux systems.

**NASA / Jet Propulsion Laboratory.** I interned during the summers of
2013-2017, applying cell-phone processors to visual navigation for small flying
robots on the [Mars Helicopter Ingenuity] team. [Read the story][ingenuity-story].

**FACEIT.** I built matchmaking infrastructure and algorithms, WebSocket
messaging, and the [go-dota2] bot network at [FACEIT]. I also created the FPro
in-house system, which later became the FACEIT Pro League (FPL).

[contributor]: https://patchwork.ozlabs.org/project/buildroot/list/?state=*&submitter=66856
[Buildroot]: https://buildroot.org
[ingenuity-story]: https://github.com/readme/featured/nasa-ingenuity-helicopter
[Mars Helicopter Ingenuity]: https://mars.nasa.gov/technology/helicopter/
[FACEIT]: https://faceit.com
[go-dota2]: https://github.com/paralin/go-dota2

## Earlier work

[rgraphql] streams changes to GraphQL queries so user interfaces can stay up to
date. The client combines component queries into one session query.

[D2Moddin] brought Dota 2 custom games to the public in May-June 2014, before
Valve released Dota 2 Reborn with the Source 2 engine.

[rgraphql]: https://github.com/rgraphql/magellan
[D2Moddin]: https://www.youtube.com/watch?v=BqJ1Z_uGBVY

<details>
  <summary>Old archived projects</summary>

- [AirNet]: gossip based p2p networking
- [AwesomiumCE3]: rendering a web browser inside CryEngine to textures.
- [D2Moddin source][d2moddin-code]: the first DOTA 2 custom game modes platform & website.
- [Dota2]: C# implementation of the DOTA2 game coordinator client.
- [EagleEye]: an Arma 2 DayZ in-browser map of players & items
- [EveFleet]: real-time UI for managing EVE Online fleets
- [EveWaitlist]: real-time UI for managing EVE Online incursions
- [Hackatron]: connect teams with questions at Hackathons.
- [LivingPlanet]: hackathon project of a beautiful informational site.
- [SubGames]: a site for Twitch streamers to host Dota lobbies w/ bots.
- [charlie]: a dynamic networked module loader in C++
- [diskutil]: Go library to access raw disks on windows
- [evexmap]: a force-directed graph visualization of the EVE Online world.
- [go-libp2p-grpc]: GRPC proxying over libp2p.
- [go-p2pd]: a daemon for libp2p
- [gogame]: cross-platform games written in Go.
- [grpc-bus]: call GRPC services from the browser over WebSocket.
- [historian-view-window-js]: remote-state-stream to a browser
- [inca-go]: inca implementation in Go
- [inca-js]: javascript implementation: [inca-counter-example-js]
- [inca]: blockchain framework for Proof of Authority
- [kvgossip]: gossip key/value store on top of Serf using RSA keys.
- [matrixserver]: peer-to-peer networking library for C#
- [metric-stream]: stream of time-series data to the browser.
- [mutate]: Go library for generating mutations in JSON.
- [netproto]: abstract KCP and quic into a single api in Go
- [obd-reporter]: report OBD data from cars to Prometheus
- [objectenc-js]: object encrypt for binary blobs in Js
- [objectenc]: object encrypt for binary blobs in Go
- [objectsig-js]: object signatures implemented in js
- [objectsig]: object signatures for binary blobs in Go
- [objstore-js]: object storage in js
- [objstore]: object storage in Go
- [p2p-storageref]: common storage ref to multiple locations
- [pbobject-js]: js implementation of pbobject
- [pbobject]: protobuf object wrapper and table decoder
- [PlayLethalLeague]: neural network to play a real-time fighting game.
- PlayLLBlaze: openAI gym for Lethal League Blaze
- [pstream]: packet stream for Go
- [quic-channel]: prototype of mesh networking with Quic channels
- [webleague]: a DOTA 2 in-house league system (for FPL) with bots.
- [xbee-netdev]: Linux TAP network interface over Xbee radios.

[AirNet]: https://github.com/airnet/airnet/
[AwesomiumCE3]: https://github.com/paralin/AwesomiumCE3
[d2moddin-code]: https://github.com/paralin/D2Moddin
[Dota2]: https://github.com/paralin/Dota2
[EagleEye]: https://github.com/paralin/eagleeye
[EveFleet]: https://github.com/paralin/evefleet
[EveWaitlist]: https://github.com/paralin/evewaitlist
[Hackatron]: https://github.com/TheWashingtonRedskins/Hackatron
[LivingPlanet]: https://github.com/TheWashingtonRedskins/LivingPlanet
[PlayLethalLeague]: https://github.com/paralin/PlayLethalLeague
[SubGames]: https://github.com/paralin/SubGamesWeb
[charlie]: https://github.com/paralin/charlie
[diskutil]: https://github.com/paralin/diskutil
[evexmap]: https://github.com/paralin/evexmap
[go-libp2p-grpc]: https://github.com/paralin/go-libp2p-grpc
[go-p2pd]: https://github.com/paralin/go-p2pd
[gogame]: https://github.com/paralin/gogame
[grpc-bus]: https://github.com/paralin/grpc-bus
[historian-view-window-js]: https://github.com/paralin/historian-view-window-js
[inca-counter-example-js]: https://github.com/paralin/inca-counter-example-js
[inca-go]: https://github.com/paralin/inca-go
[inca-js]: https://github.com/paralin/inca-js
[inca]: https://github.com/paralin/inca
[kvgossip]: https://github.com/paralin/kvgossip
[matrixserver]: https://github.com/paralin/matrixserver
[metric-stream]: https://github.com/paralin/metric-stream
[mutate]: https://github.com/paralin/mutate
[netproto]: https://github.com/paralin/netproto
[obd-reporter]: https://github.com/paralin/obd-reporter
[objectenc-js]: https://github.com/paralin/objectenc-js
[objectenc]: https://github.com/paralin/objectenc
[objectsig-js]: https://github.com/paralin/objectsig-js
[objectsig]: https://github.com/paralin/objectsig
[objstore-js]: https://github.com/paralin/objstore-js
[objstore]: https://github.com/paralin/objstore
[p2p-storageref]: https://github.com/paralin/p2p-storageref
[pbobject-js]: https://github.com/paralin/pbobject-js
[pbobject]: https://github.com/paralin/pbobject
[pstream]: https://github.com/paralin/pstream
[quic-channel]: https://github.com/paralin/quic-channel
[webleague]: https://github.com/paralin/webleagueweb
[xbee-netdev]: https://github.com/paralin/xbee-netdev

</details>

<!-- Note: special thanks to [Gapur](https://github.com/gapur) for the original GitHub profile inspiration. -->
