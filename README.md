# FIRST Rust Competition

A monorepo for `wpilib` for programming FRC robots and `cargo-frc` for deploying said code. Currently a pre-alpha WIP.

## Getting started
Parts of this repository is designed to be compiled for a [RoboRIO](http://sine.ni.com/nips/cds/view/p/lang/en/nid/213308), the
processor used in the FIRST Robotics Competition. To cross compile for RoboRIO, you have to do a few things.
Detailed instructions can be found in [WPIlib's README](wpilib/README.md).

Examples can be found in [wpilib-examples](wpilib-examples).

To deploy code you write using `wpilib`, use [cargo-frc](cargo-frc).

## Building

Verify you can build `wpilib`, then run `make all`. `cargo-frc` should build out of the box, but you should `cargo install` it 
to [use it properly](cargo-frc/README.md).

## License

The contents of this repo are released under the GPLv3.
By contributing, you license your contribution under the GPLv3.
You also agree to have your contribution included in a future
version of this library licensed under a future version of the GPL
as released by the Free Software Foundation.
