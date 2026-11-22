# Cua Driver, as Foundation links it

This branch holds only `libs/cua-driver/rust` of https://github.com/nixiesoftware/cua
(a fork of https://github.com/trycua/cua, MIT), at the same path, so a Cargo git
dependency fetches the driver and not the monorepo.

- Fork branch `foundation` commit: 3861237fa5cd48417ff0cf2acc4535080efce2d1
- Upstream commit it sits on: f4b3a18fcc062e406fb107fbeac8f016e59429f8

Each commit here is the driver tree of one `foundation` commit. Changes are made
on `foundation` and carried here; nothing is edited on this branch.
