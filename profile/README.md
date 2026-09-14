# 🍜 `miso`

The `miso` organization provides a first-class frontend experience (in the spirit of [React](https://react.dev) / [React Native](https://reactnative.dev/) 
). We do this by combining a "simple Haskell" programming philosophy with industry standard techniques such as [Virtual DOM](https://en.wikipedia.org/wiki/Virtual_DOM), components, event delegation, [SSR](https://developer.mozilla.org/en-US/docs/Glossary/SSR), [TypeScript](https://www.typescriptlang.org/) and extensive browser API integration. We use native libraries like [LynxJS](https://lynxjs.org) to target [iOS](https://www.apple.com/ios), [Android](https://www.android.com/) and [HarmonyOS](https://device.harmonyos.com/en/) devices. We support the [latest web standards](https://webassembly.org/) like [Web Assembly](https://ghc.gitlab.haskell.org/ghc/doc/users_guide/wasm.html) via the [WASM project](https://github.com/haskell-wasm) and JavaScript via the [GHC JS](https://ghc.gitlab.haskell.org/ghc/doc/users_guide/javascript.html#) backend. `miso` works well w/ [Claude code](https://claude.com/product/claude-code) and other LLMs for application generation (see the [chess](https://github.com/haskell-miso/miso-chess) example).

## 🍜 `miso`

- [miso](https://github.com/dmjio/miso)
- [Docs](https://haddocks.haskell-miso.org/miso/Miso.html)

## 📱 Native

-  [Gallery](https://github.com/haskell-miso/miso-lynx-gallery), [Misogram](https://github.com/haskell-miso/misogram)
-  [Docs](https://haddocks.haskell-miso.org/miso/Miso-Native.html)

## 🥡 Try it

-  [Try miso](https://try.haskell-miso.org)

## 🌎 Website 

- [haskell-miso.org](https://haskell-miso.org)

## 🥢 Quick start

-  [sampler](https://github.com/dmjio/miso-sampler)

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

-  [miso.ui](https://ui.haskell-miso.org)

## 📦 npm

- [haskell-miso](https://www.npmjs.com/package/haskell-miso)

## 🧊 3D

- [three.hs](https://github.com/haskell-miso/three-miso)

## :octocat: Community 

- [Matrix](https://matrix.to/#/#haskell-miso:matrix.org) 
- [Discord](https://discord.gg/QVDtfYNSxq)

## ⚙️ Compilers
  - [Web Assembly](https://github.com/haskell-wasm)
  - [GHCJS](https://github.com/ghcjs)
  - [GHC](https://www.github.com/ghc/)

## 🍱 Index

| 📚 Learn | 🎮 Games | 📦 Libs / Utils ⚙️ | 💫 Apps | 🔌 APIs | 📱 Native | 💅 UI | ⚡ 3rd-party |
| ----------- | ------- | -------- | ------- | ------- | ------ | ------ | ------ |
|[Blog](https://haskell-miso.org/blog)|[2048](https://github.com/haskell-miso/miso-2048)|[miso-from-html](https://github.com/haskell-miso/miso-from-html)|[TodoMVC](https://github.com/haskell-miso/miso-todomvc)|[Audio](https://github.com/haskell-miso/miso-audio)|[miso-lynx](https://github.com/haskell-miso/miso-lynx)|[miso.ui](https://github.com/haskell-miso/miso-ui)|[three.js](https://github.com/three-hs/three-miso-example)|
|[README.md](https://github.com/dmjio/miso/blob/master/README.md)|[Sudoku](https://github.com/haskell-miso/sudoku)|[servant-miso-html](https://github.com/haskell-miso/servant-miso-html)|[Haskell-Miso.org](https://github.com/haskell-miso/haskell-miso.org)|[Video](https://github.com/haskell-miso/miso-video)|[Sphynx](https://github.com/dmjio/sphynx)|[Dashi](https://github.com/ners/dashi)|[AFrame.io](https://github.com/haskell-miso/miso-aframe)|
|[Presentation](https://github.com/haskell-miso/miso-presentation)|[Tetris](https://github.com/haskell-miso/miso-tetris)|[servant-miso-router](https://github.com/haskell-miso/servant-miso-router)|[Router](https://github.com/haskell-miso/miso-router)|[Camera](https://github.com/haskell-miso/miso-camera)|[miso-lynx haddocks](https://haddocks.haskell-miso.org/miso/Miso-Native.html)|[miso-css](https://github.com/yaitskov/miso-css)|[c3.js](https://github.com/haskell-miso/miso-c3js)|
|[Haddocks](https://haddocks.haskell-miso.org)|[Snake](https://github.com/haskell-miso/miso-snake)|[servant-miso-client](https://github.com/haskell-miso/servant-miso-client)|[SVG](https://github.com/haskell-miso/miso-svg)|[Canvas 2D](https://github.com/haskell-miso/miso-canvas2d)|[Gallery](https://github.com/haskell-miso/miso-lynx-gallery)||[Supabase](https://github.com/haskell-miso/supabase-miso)|
|[Awesome miso](https://github.com/haskell-miso/awesome-miso)|[Flappy Bird](https://github.com/haskell-miso/miso-plane)|[servant-miso-json](https://github.com/haskell-miso/servant-miso-json)|[Calculator](https://github.com/haskell-miso/miso-calculator)|[WebSocket](https://github.com/haskell-miso/miso-websocket)|[Misogram](https://github.com/haskell-miso/misogram)||[TipTap](https://github.com/haskell-miso/miso-tiptap)|
|[Coverage](https://coverage.haskell-miso.org)|[Mario](https://github.com/haskell-miso/miso-mario)|[Markdown](https://github.com/juliendehos/misodoc2)|[Props](https://github.com/haskell-miso/miso-props)|[MathML](https://github.com/haskell-miso/miso-mathml)|||[highlight.js](https://github.com/haskell-miso/miso-highlightjs)|
||[Minesweeper](https://github.com/haskell-miso/miso-minesweeper)|[bun-wasm](https://github.com/haskell-miso/bun-wasm)|[Currency Converter](https://functora.github.io/apps/currency-converter)|[SSE](https://github.com/haskell-miso/miso-sse)|||[chart.js](https://github.com/haskell-miso/miso-chartjs)|
||[Texas Hold Em'](https://github.com/haskell-miso/texasholdem)|[miso-tagsoup](https://github.com/haskell-miso/miso-tagsoup)|[File Upload](https://github.com/haskell-miso/miso-fileupload)|[Fetch](https://github.com/haskell-miso/miso-fetch)|||[MathJAX](https://github.com/haskell-miso/miso-mathjax)|
||[Tic-Tac-Toe](https://github.com/haskell-miso/tic-tac-miso)||[VPN Router](https://github.com/yaitskov/vpn-router)|[Drag and Drop](https://github.com/haskell-miso/miso-drag-and-drop)|||[XYFlow](https://github.com/haskell-miso/miso-flow)|
||[Mahjong](https://github.com/haskell-miso/mahjong)||[NixCon 2026](https://github.com/nixcon/2026.nixcon.org)|[Geolocation](https://github.com/haskell-miso/miso-geolocation)||||
||[Sokoban](https://juliendehos.github.io/misokoban/)||[Finch](https://github.com/Reijix/finch)|[File Reader](https://github.com/haskell-miso/miso-filereader)||||
||[Numeron](https://github.com/kiwamizamurai/miso-numeron)||[Rzk](https://github.com/rzk-lang/rzk-game)|[Storage](https://github.com/haskell-miso/miso-storage)||||
||[Asteroid](https://github.com/haskell-miso/miso-asteroid)||[Taflhouse](https://github.com/taflhouse/game)|[CookieStore](https://github.com/haskell-miso/cookies)||||
||[Solitaire](https://github.com/haskell-miso/miso-solitaire)||[Context](https://github.com/haskell-miso/context)|||||
||[Chess](https://github.com/haskell-miso/miso-chess)|||||||
||[Blockout](https://github.com/jhrcek/miso-blockout)|||||||

