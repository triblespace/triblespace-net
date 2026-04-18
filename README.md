# triblespace-net

> **This repository has moved.**
>
> `triblespace-net` now lives inside the
> [`triblespace-rs`](https://github.com/triblespace/triblespace-rs) workspace
> as a first-class member crate. Further development, issue tracking, and
> releases happen there.

## Where to go

- **Source:** [`triblespace-rs/triblespace-net`](https://github.com/triblespace/triblespace-rs/tree/main/triblespace-net)
- **Issues & PRs:** [triblespace-rs/issues](https://github.com/triblespace/triblespace-rs/issues)
- **Distributed-sync book chapter (mental model + transports + API):**
  [triblespace book](https://docs.rs/triblespace/)

Most users should enable `triblespace-net` via the facade crate's `net`
feature rather than depending on this crate directly:

```toml
[dependencies]
triblespace = { version = "0.36", features = ["net"] }
```

```rust,ignore
use triblespace::net::peer::{Peer, PeerConfig};
```

## History

Full commit history was preserved when this crate was subtree-merged
into `triblespace-rs`. Anything you need to browse or blame is
available there under `triblespace-net/`.
