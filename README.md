# Mono "hello world" snappy package: monocurl

[![CI status](https://github.com/nblockchain/mono-hello-world-snap/workflows/ubuntu/badge.svg)](https://github.com/nblockchain/mono-hello-world-snap/commits/master)

This is a snappy package for a simple C# application that simply works like curl, based on Jonathan Van der Cruysse's [repo](https://github.com/jonathanvdc/mono-hello-world-snap) (which is based on David Paskevic's [Pinta snap](https://github.com/casept/snap-pinta) ).

To create a snap, install snapcraft (you might want to check how it's done in CI by looking at the install_snapcraft.sh file) first, and then run the `build_snap.sh` script. The resulting file will be a .snap file which you can install via `sudo snap install --dangerous monocurl_0.1_amd64.snap`.
