# HejBit Upload and Download Animations

A dependency-free Canvas Web Component that visualizes a file being split into chunks and scattered through a network. The animation is illustrative: it makes no network requests and does not claim replication, permanence, or retrieval speed.

The reusable component and runnable demo are in [dist/](dist/). See [dist/README.md](dist/README.md) for integration, progress and state handling, accessibility, reduced motion, and sizing details.

## Run locally

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000.

## Tests

```sh
node --test tests/motion.test.mjs
```

## Project checklist

See [dist/TODO.md](dist/TODO.md).
