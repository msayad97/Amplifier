# Radio-Frequency Power Amplifier with 1kW peak power

## System specifications

Class A 12MHz pulse amplifier; for details please see the [RFPA_12MHz-details](/doc/RFPA_12MHz-details.pdf) document

- max. load power = 1kW
- max. duty cycle = 10%
- max. pulse duration = 20ms
- input signal frequency = 0.5…12MHz
- 5V 1% enable signal
- gain @ 4MHz = 54.3dB
- R<sub>out</sub> @ 4MHz = 48.2&ohm
- R<sub>in</sub> = 50Ω
- blanking delay ≤ 500ns

## Repository Overview

The repository follows a Unixish directory structure, inspired by the [Minimal OSH Repository Template](https://gitlab.fabcity.hamburg/software/template-osh-repo-structure-minimal/-/blob/main/mod/unixish/README.md):

- [doc](/doc/): documentation
	- xxx
- [res](/res/): additional resources used and referenced throughout the repository
	- xxx
- [src](/src/): source files

## Contributing

### Proprietary Native Files

The design has been created with Altium, files are saved in the native, proprietary format.

### Get in Touch

To join the development, feel free to

- join us on [Matrix](https://matrix.to/#/#osii:matrix.org),
- drop us an [issue](https://gitlab.com/osii/rf-system/rf-power-amplifier/1kw-peak-rfpa/-/issues) or
- file a merge request directly.

## Contributors (alphabetical order)

Original design by Danny de Gans (D.H.deGans@tudelft.nl) from [TU Delft](https://www.tudelft.nl/en/), Netherlands.

## License and Liability

This is an open source hardware project licensed under the CERN Open Hardware Licence Version 2 - Weakly Reciprocal. For more information please check [LICENSE](LICENSE) and [DISCLAIMER](DISCLAIMER.pdf).
