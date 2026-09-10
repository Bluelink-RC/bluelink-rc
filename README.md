# BlueLink RC

Public documentation website for **BlueLink RC** — drive RC vehicles with an Xbox or Stadia controller over Bluetooth Low Energy.

**Docs (canonical):** [https://bluelink-rc.github.io/bluelink-rc/](https://bluelink-rc.github.io/bluelink-rc/)

This GitHub repository hosts that site (`docs/`) and nothing else of substance. It is not firmware, not the app, and not a map of private systems.

## On the site

- [Overview](https://bluelink-rc.github.io/bluelink-rc/)
- [How it works](https://bluelink-rc.github.io/bluelink-rc/how-it-works.html)
- [Hardware](https://bluelink-rc.github.io/bluelink-rc/hardware.html)
- [Status & boundary](https://bluelink-rc.github.io/bluelink-rc/about.html)

## Local preview

```bash
python3 -m http.server --directory docs 8080
```

Then open `http://127.0.0.1:8080`.

## GitHub Pages

The workflow in `.github/workflows/pages.yml` publishes `docs/` from `main`. If the first deploy fails, enable Pages in the repository settings (Source: **GitHub Actions**), then re-run the workflow.

## Public boundary

Published: product description, high-level architecture, verified board class, project status.

Not published: source, protocols, pinouts, internal repository names, cloud or operations layout, credentials, or build machinery.

See [SECURITY.md](SECURITY.md) and [CONTRIBUTING.md](CONTRIBUTING.md).

## Author

[Lincoln Larson](https://github.com/modernn) · [Bluelink-RC](https://github.com/Bluelink-RC)

## License

**License TBD.** No `LICENSE` file is in this repository. Until one is published, do not treat this documentation (or private implementation) as licensed for reuse.
