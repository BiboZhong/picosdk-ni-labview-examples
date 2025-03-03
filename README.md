# picosdk-ni-labview-examples

*picosdk-ni-labview-examples* is a set of National Instruments LabVIEW examples for PicoScope<sup>®</sup> oscilloscope and PicoLog<sup>®</sup> data logger products.

Examples are provided as a set of LabVIEW vi and llb files grouped by driver name, with sub-folders for 32-bit and 64-bit examples.

## Getting started

### Prerequisites

#### Microsoft Windows

* National Instruments LabVIEW Base Development System 9.0 or later (32-bit or 64-bit)

**Notes:** 

* Most examples can be opened with LabVIEW Base Development System 8.5 versions.

### Example dependencies

Some example vi files require common sub-vi files (e.g. PicoScopeAdcToVolts.vi for conversion of ADC counts to volts) which can be located in the shared/PicoScope.llb file.
If downloading files or the repository zip file you will need to download the contents of the shared folder directly from https://github.com/picotech/picosdk-ni-labview-shared. As this is a sub module.

### Installing drivers

Drivers are available via a separate driver package installer.

#### Windows

* Download the PicoSDK (32-bit or 64-bit) driver package installer from our [Downloads page](https://www.picotech.com/downloads).

### Programmer's Guides

You can download Programmer's Guides providing a description of the API functions for the relevant PicoScope or PicoLog driver from our [Documentation page](https://www.picotech.com/library/documentation).

## Obtaining support

Please visit our [Support page](https://www.picotech.com/tech-support) to contact us directly or visit our [Test and Measurement Forum](https://www.picotech.com/support/forum20.html) to post questions.

## Contributing

Contributions are welcome. Please refer to our [guidelines for contributing](.github/CONTRIBUTING.md) for further information.

## Copyright and licensing 

See [LICENSE.md](LICENSE.md) for license terms.

*PicoScope* and *PicoLog* are registered trademarks of Pico Technology Ltd. 

*Windows* is a registered trademark of Microsoft Corporation.

*LabVIEW* is a registered trademark of National Instruments Corporation.

Copyright © 2005-2021 Pico Technology Ltd. All rights reserved.

