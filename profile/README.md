# SolaraStudio

Open-source tools for the modern web. Our flagship is Solara Browser — a minimal, privacy-first Android browser built from the ground up.

---

## What we build

We are building a complete browser stack from scratch. No Chromium. No system WebView. No compromises.

- Solara — the flagship Android browser. Kotlin, Jetpack Compose, Material 3.
- Solaria — the same experience for older devices. Java, Views, API 21+.
- Optima — the rendering engine. Rust. HTML, CSS, DOM, layout, paint.
- Solarium — the JavaScript engine. Zig. Written from scratch.
- Solarian — search provider API. Kotlin.

Plus the surrounding ecosystem — website, docs, extensions, mods.

---

## Repositories

| Repository | Purpose | Language | License |
|------------|---------|----------|---------|
| [`Solara`](https://github.com/SolaraStudio/Solara) | Flagship Android browser (API 24+) | Kotlin + Compose | MPL-2.0 |
| [`Solaria`](https://github.com/SolaraStudio/Solaria) | Android browser for older devices (API 21+) | Java + Views | MPL-2.0 |
| [`Optima`](https://github.com/SolaraStudio/Optima) | Rendering engine | Rust | MIT OR Apache-2.0 |
| [`Solarium`](https://github.com/SolaraStudio/Solarium) | JavaScript engine | Zig | MPL-2.0 |
| [`Solarian`](https://github.com/SolaraStudio/Solarian) | Search provider API | Kotlin | MPL-2.0 |
| [`web`](https://github.com/SolaraStudio/web) | Official website | HTML + CSS + JS | MPL-2.0 |
| [`docs`](https://github.com/SolaraStudio/docs) | Documentation | Markdown | MPL-2.0 |
| [`extension`](https://github.com/SolaraStudio/extension) | Extension system SDK | TypeScript | MPL-2.0 |
| [`mod`](https://github.com/SolaraStudio/mod) | Mods marketplace | CSS + JSON | MPL-2.0 |

---

## Design principles

- Privacy by default. No telemetry. No tracking. No accounts required.
- Performance first. Rust and Zig engines. Small binary size. Fast startup.
- Own the stack. We build our own rendering and JavaScript engines — no Chromium, no WebView.
- Quiet, beautiful UI. Material You, glass-morphism, no clutter.
- Accessible to all. Support for older devices. No forced obsolescence.

---

## Technology stack

| Layer | Technology |
|-------|------------|
| UI | Jetpack Compose + Material 3 |
| App | Kotlin, Java |
| Rendering | WebVeiw - Rust |
| JavaScript | Runtime - Zig |
| Extensions | TypeScript |
| Search API | Kotlin |
| Build | Gradle (Kotlin DSL), Cargo, Zig |
| CI/CD | GitHub Actions |
|Hosting | GitHub Pages |

---

## Getting started

### Build the flagship browser:

```bash
git clone https://github.com/SolaraStudio/Solara.git
cd Solara/android
./gradlew assembleRelease
```

Build the rendering engine:

```bash
git clone https://github.com/SolaraStudio/Optima.git
cd Optima
cargo build --release
```

Build the JavaScript runtime:

```bash
git clone https://github.com/SolaraStudio/Solarium.git
cd Solarium
zig build
```

---

## Project status

Solara is Under Development. Optima already renders static HTML and CSS; Solarium (JavaScript) is under construction.

Progress is tracked in each repository's issues and milestones. Roadmaps are posted in the individual repos.

---

## Contributing

We welcome contributions of any size. Each repository has its own CONTRIBUTING.md, but the process is the same everywhere:

1. Fork the repository.
2. Create a feature branch.
3. Make your changes with tests.
4. Open a pull request.

For larger changes, open an issue or discussion first so we can align on the approach before you write code.

---

## Community

- GitHub Discussions — questions, ideas, feedback
- GitHub Issues — bug reports and feature requests
- Website — coming soon
- Discord — coming soon

---

## License

Most SolaraStudio repositories are licensed under the Mozilla Public License 2.0.
