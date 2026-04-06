# librtbit-tracker-comms

HTTP and UDP tracker communication for the rtbit BitTorrent client.

**Version:** 0.1.0 | **Edition:** Rust 2024 | **License:** MIT

## This Is a Shared Library

### Consumed By

| App | Via | Tag |
|-----|-----|-----|
| rustTorrent | git | v0.1.0 |
| Arz | git | v0.1.0 |
| NGMS | git | v0.1.0 |

### Depends On

- **librtbit-buffers** (git, v0.1.0)
- **librtbit-bencode** (git, v0.1.0)
- **librtbit-core** (git, v0.1.0)

## BEP Implementations

- BEP 3 — HTTP tracker protocol (/announce, /scrape)
- BEP 15 — UDP tracker protocol (binary protocol with connection IDs)
- BEP 23 — Compact peer lists
