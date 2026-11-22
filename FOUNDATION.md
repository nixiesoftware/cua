# Cua Driver, as Foundation links it

This branch holds only `libs/cua-driver/rust` of https://github.com/nixiesoftware/cua
(a fork of https://github.com/trycua/cua, MIT), at the same path, so a Cargo git
dependency fetches the driver and not the monorepo.

- Fork branch `foundation` commit: 9c2e4ecd23460ae0c078fef83eb1f50757c0058f
- Upstream commit it sits on: f4b3a18fcc062e406fb107fbeac8f016e59429f8

Each commit here is the driver tree of one `foundation` commit. Changes are made
on `foundation` and carried here; nothing is edited on this branch.
