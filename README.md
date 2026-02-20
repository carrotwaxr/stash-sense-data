# stash-sense-data

Face recognition database releases for [Stash Sense](https://github.com/carrotwaxr/stash-sense).

Contains performer metadata and face embeddings from StashDB, FansDB, ThePornDB, PMVStash, and JAVStash — currently **108,000+ performers** and **366,000+ face embeddings**.

Releases are built from [stash-sense-trainer](https://github.com/carrotwaxr/stash-sense-trainer) and consumed by the Stash Sense sidecar.

## Download

Grab the latest release zip (~1.5 GB) from the [releases page](https://github.com/carrotwaxr/stash-sense-data/releases/latest), then follow the [installation guide](https://carrotwaxr.github.io/stash-sense/installation/) to set up the sidecar.

## Updating

The Stash Sense plugin can check for and install database updates automatically from Settings. You can also update manually or via the API — see [Database & Updates](https://carrotwaxr.github.io/stash-sense/database/).

## What's Inside

| File | Purpose |
|------|---------|
| `performers.db` | SQLite database with performer metadata and stash-box IDs |
| `face_facenet.voy` | FaceNet512 embedding index |
| `face_arcface.voy` | ArcFace embedding index |
| `face_adaface.voy` | AdaFace IR-101 embedding index |
| `tattoo_embeddings.voy` | Tattoo embedding index |
| `faces.json` | Face-to-performer mapping |
| `performers.json` | Performer lookup data |
| `tattoo_embeddings.json` | Tattoo-to-performer mapping |
| `manifest.json` | Version, checksums, and build metadata |

## Documentation

Full documentation is at [carrotwaxr.github.io/stash-sense](https://carrotwaxr.github.io/stash-sense/).
