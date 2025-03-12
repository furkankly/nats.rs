This repository is a patched fork of the [async-nats](https://github.com/nats-io/nats.rs/tree/main) crate, with modifications to enable IPC communication with the Fly agent. These changes were made to address immediate needs independently of the upstream project.

The primary modifications include support for IPC communication, which isn't available in the original crate. This fork is published to crates.io under a different name to allow immediate use.

If you're looking for the original implementation, please visit the [official NATS.rs repository](https://github.com/nats-io/nats.rs/tree/main).
