# lib_concurrency

This repository owns two narrow targets: `p101_thread` for thread lifecycle
and `p101_sync` for synchronization primitives. They remain separate link
libraries so thread users do not acquire synchronization APIs unnecessarily.
