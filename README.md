# (Static) Hermes resources
Collection of resourced that I gather across internet about (Static) Hermes JS engine. (engine that powers React Native)

### Official links
- [Hermes Github Repo](https://github.com/facebook/hermes) - all active development is happening in `static_h` branch (Static Hermes)

### Videos
- [Hermes: better performance with runtime bytecode translation — Tzvetan Mikov | RUC 2024](https://www.youtube.com/watch?v=GUM64b-gAGg) - "JIT" for Hermes
- [Neil Dhar - Optimizing With Static Hermes (Chain React 2024)](https://www.youtube.com/watch?v=wflwVQp2zN0_) - deep dive into how Hermes optimizes your code internally
- [Static Hermes: the Next Generation of Hermes - Tzvetan Mikov | React Native EU 2023](https://www.youtube.com/watch?v=q-xKYA0EO-c) - introduction of Static Hermes

### Podcasts
- [RNR 323 - Static Hermes with Tzvetan Mikov (March 2025)](https://www.youtube.com/watch?v=CPyNY79DQuY)


### People to follow

**Tzvetan Mikov** - leader of Hermes team at Meta
  - X: [@tmikov](https://x.com/tmikov)
  - Blog: [tmikov.blogspot.com](https://tmikov.blogspot.com)

### Articles
- [Static Hermes Update, Dec 2024](https://x.com/tmikov/status/1869945330638442651)
- [I made JSON.parse() 2x faster (Radek Pietruszewski)](https://radex.io/react-native/json-parse/) - interesting deep dive into how Hermes JSON parser works


### Code examples + repositories
- [Try Static Hermes in your app](https://github.com/software-mansion-labs/hermes) - Fork and build of Static Hermes from Software Mansion. This repo includes guide how to use Static Hermes in your app today (without typed mode)
- [Repo](https://github.com/tmikov/gpt-scroller) - A simple Static Hermes demo using DearImGUI
- [Gist](https://gist.github.com/tmikov/3e6310abcd77ff8066297cdd4927b44d) - example usage of `NativeState`
- [Repo](https://github.com/tmikov/octane) - Tzvetan fork of `Octane` benchmark lib with some results for (Static) Hermes
- [Repo](https://github.com/tmikov/hermes-jsi-demos) - Small demos of using the Hermes JavaScript engine with JSI without React Native or any other framework
- [Repo](https://github.com/thejustinwalsh/sh-raylib) - raylib bindings for Static Hermes

### Other useful links
- [Github Discussion](https://github.com/facebook/hermes/discussions/1137) - How to try Static Hermes + lot of tips, examples and even some benchmark results
- [Link X](https://x.com/mrousavy/status/1890742572466753808) - make app start significatly faster by disabling bytecode compression for Android apps (should be default RN 0.79+)
- [Link X](https://x.com/piaskowyk/status/1842201000095948860) - introduction of SWM fork of Static Hermes that you can try right now
- [Link X](https://x.com/tmikov/status/1821219997181763956) - small example of how NativeState could be used to define classes backed by a native implementation. [Gist](https://gist.github.com/tmikov/3e6310abcd77ff8066297cdd4927b44d)
- [Link X](https://x.com/tmikov/status/1820266381545468200) - Tzvetan tweets about difference between JSI `NativeState` and `HostObject`
- [Link X](https://x.com/tmikov/status/1757112273783378054) - Tzvetan tweets about Static Hermes generic support with technical details in thread
- [Link X](https://x.com/kzzzf/status/1729312792094675060) - discussion and some benchmark about `NativeState` vs `HostObject` (November 2023)
- [Link X](https://x.com/tmikov/status/1720103356738474060) - Tweet with demo that showcases the Static Hermes native FFI by using bindings for libraries like DearImGui and Sokol, with an “imperative UI” that rebuilds the screen each frame.
- [Github Issue](https://github.com/facebook/hermes/discussions/1634) - Interesting discussion about how Hermes handles strings internally and how Hermes team made it faster
- [Link X](https://x.com/tmikov/status/1837600409386734037) - Tzvetan long tweet why Hermes doesn't support WASM
- [Link X](https://x.com/tmikov/status/1747462584725545049) - `atob` and `btoa` support in Hermes

### Conferences
[React Universe](https://www.reactuniverseconf.com) - Wrocław, Poland - usually you can meet Hermes team there and there is also at least one talk about Hermes
