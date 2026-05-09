# 🍜 `miso`

> [!IMPORTANT]
> We're solving frontend and native mobile for [Haskell](https://haskell.org) using the [miso](https://github.com/dmjio/miso) 🍜 web framework.

## 🏆 Goal

The [Haskell](https://haskell.org) `miso` organization provides a first-class frontend experience (in the spirit of [React](https://react.dev) / [React Native](https://reactnative.dev/) 
) for the Haskell ecosystem. We do this by combining a "simple Haskell" philosophy with industry standard techniques such as [Virtual DOM](https://en.wikipedia.org/wiki/Virtual_DOM), components, event delegation, [SSR](https://developer.mozilla.org/en-US/docs/Glossary/SSR), [TypeScript](https://www.typescriptlang.org/) and extensive browser API integration. We use native libraries like [LynxJS](https://lynxjs.org) to target [iOS](https://www.apple.com/ios), [Android](https://www.android.com/) and [HarmonyOS](https://device.harmonyos.com/en/) devices. We support the [latest web standards](https://webassembly.org/) like [Web Assembly](https://ghc.gitlab.haskell.org/ghc/doc/users_guide/wasm.html) via the [Haskell WASM project](https://github.com/haskell-wasm) and JavaScript via the [GHC JS](https://ghc.gitlab.haskell.org/ghc/doc/users_guide/javascript.html#) backend.

## 🍜 `miso`

-  [miso](https://github.com/dmjio/miso)

## 📚 Docs

- [Miso](https://haddocks.haskell-miso.org/miso/Miso.html)

## 🌎 Website 

- [haskell-miso.org](https://haskell-miso.org)

## 🥢 Quick start

-  [miso-sampler](https://github.com/dmjio/miso-sampler)

```bash
# Install nix 
curl -L https://nixos.org/nix/install | sh

# Enable flakes
echo 'experimental-features = nix-command flakes' >> ~/.config/nix/nix.conf

# Clone, build and host
git clone https://github.com/haskell-miso/miso-sampler && cd miso-sampler
nix develop .#wasm --command bash -c 'make && make serve'
```

## 💅 Styles

-  [miso-ui](https://ui.haskell-miso.org)

## 📦 npm

- [haskell-miso](https://www.npmjs.com/package/haskell-miso)

## 🧊 3D

- [three.hs](https://github.com/haskell-miso/three-miso)

## :octocat: Community 

- [Matrix](https://matrix.to/#/#haskell-miso:matrix.org) 
- [Discord](https://discord.gg/QVDtfYNSxq)
- [Slack](https://haskell-miso.slack.com/join/shared_invite_confirmed/zt-37vusrcdw-HH6~hY0DGT7MLCjNWZvLDQ#/email-invite/credentials)
- [IRC](https://www.irccloud.com/invite?channel=%23haskell-miso&hostname=irc.libera.chat&port=6697&ssl=1)

## ⚙️ Compilers
  - [Web Assembly](https://github.com/haskell-wasm)
  - [GHCJS](https://github.com/ghcjs)
  - [GHC](https://www.github.com/ghc/)

## 🍱 Index

| 📚 Learn | 🎮 Games | 📦 Libs / Utils ⚙️ | 💫 Apps | 🔌 APIs | 📱 Native | 💅 UI | ⚡ 3rd-party |
| ----------- | ------- | -------- | ------- | ------- | ------ | ------ | ------ |
| Blog | [2048](https://github.com/haskell-miso/miso-2048) |[miso-from-html](https://github.com/haskell-miso/miso-from-html)|[TodoMVC](https://github.com/haskell-miso/miso-todomvc) | [Audio](https://github.com/haskell-miso/miso-audio)|[miso-lynx](https://github.com/haskell-miso/miso-lynx)|[Tailwind / ShadCN](https://github.com/haskell-miso/miso-ui)|[three.js](https://github.com/three-hs/three-miso-example)
| [README.md](https://github.com/dmjio/miso/blob/master/README.md) | [Space Invaders](https://github.com/haskell-miso/miso-invaders) |[miso-aeson](https://github.com/haskell-miso/miso-aeson)|[Haskell-Miso.org](https://github.com/haskell-miso/haskell-miso.org)|[Video](https://github.com/haskell-miso/miso-video)|[miso-lynx Haddocks](https://lynx-haddocks.haskell-miso.org)|[Dashi](https://github.com/ners/dashi)|[AFrame.io](https://github.com/haskell-miso/miso-aframe)
| [Presentation](https://github.com/haskell-miso/miso-presentation) | [Tetris](https://github.com/haskell-miso/miso-flatris) |[miso-optics](https://github.com/haskell-miso/miso-optics)|[Router](https://github.com/haskell-miso/miso-router)|[Camera](https://github.com/haskell-miso/miso-camera)|[miso-lynx Docs](https://lynxjs.haskell-miso.org)|[Bulma](https://github.com/noinia/miso-bulma/)|[c3.js](https://github.com/haskell-miso/miso-c3js)|
|[Haddocks](https://haddocks.haskell-miso.org)|[Snake](https://github.com/haskell-miso/miso-snake)|[miso-diagrams](https://github.com/haskell-miso/miso-diagrams)|[SVG](https://github.com/haskell-miso/miso-svg)|[Canvas 2D](https://github.com/haskell-miso/miso-canvas2d)|[Sphynx](https://github.com/dmjio/sphynx)||[Supabase](https://github.com/haskell-miso/supabase-miso)
|[Awesome miso](https://github.com/haskell-miso/awesome-miso)|[Flappy Bird](https://github.com/haskell-miso/miso-plane)|[servant-miso-html](https://github.com/haskell-miso/servant-miso-html)|[PubSub](https://github.com/haskell-miso/miso-pubsub)|[WebSocket](https://github.com/haskell-miso/miso-websocket)|||[TipTap](https://github.com/haskell-miso/miso-tiptap)|
|[Coverage](https://coverage.haskell-miso.org)|[Mario](https://github.com/haskell-miso/miso-mario)|[servant-miso-router](https://github.com/haskell-miso/servant-miso-router)|[Counter](https://github.com/haskell-miso/miso-counter)|[MathML](https://github.com/haskell-miso/miso-mathml)|||[highlight.js](https://github.com/haskell-miso/miso-highlightjs)|
||[Minesweeper](https://github.com/haskell-miso/miso-minesweeper)|[servant-miso-client](https://github.com/haskell-miso/servant-miso-client)|[Reactivity](https://github.com/haskell-miso/miso-reactive)|[SSE](https://github.com/haskell-miso/miso-sse)|||[chart.js](https://github.com/haskell-miso/miso-chartjs)|
||[Card Game](https://github.com/smelc/miso-darkcraw)|[servant-miso-json](https://github.com/haskell-miso/servant-miso-json)|[Currency Converter](https://functora.github.io/apps/currency-converter)|[Fetch](https://github.com/haskell-miso/miso-fetch)|||[GraphQL](https://github.com/haskell-miso/miso-graphql)
||[Tic-Tac-Toe](https://github.com/haskell-miso/tic-tac-miso)|[Markdown](https://github.com/juliendehos/misodoc2)|[File Upload](https://github.com/haskell-miso/miso-fileupload)|[Drag and Drop](https://github.com/haskell-miso/miso-drag-and-drop)|||[MathJAX](https://github.com/haskell-miso/miso-mathjax)|
||[Multiplayer Maze](https://github.com/juliendehos/miso-maze-iso)|[bun-wasm](https://github.com/haskell-miso/bun-wasm)|[VPN Router](https://github.com/yaitskov/vpn-router)|[Geolocation](https://github.com/haskell-miso/miso-geolocation)||
||[Sokoban](https://juliendehos.github.io/misokoban/)|[miso-tagsoup](https://github.com/haskell-miso/miso-tagsoup)|[NixCon 2026](https://github.com/nixcon/2026.nixcon.org)|[File Reader](https://github.com/haskell-miso/miso-filereader)||
||[Numeron](https://github.com/kiwamizamurai/miso-numeron)||[Proof Assisstant](https://github.com/Reijix/finch)|[Storage](https://github.com/haskell-miso/miso-storage)||
