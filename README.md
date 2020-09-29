# Arty Z7 Hardware Repository

This repository contains Vivado projects for all demos for the Arty Z7.

For more information about the Arty Z7, visit its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/arty-z7/start) on the Digilent Wiki.

Each demo contained in this repository is documented on the Digilent Wiki, links in the table below.

| Wiki Link | Description |
|-----------|-------------|
| [Arty Z7 HDMI Input Demo](https://reference.digilentinc.com/reference/programmable-logic/arty-z7/demos/hdmi-input) | Implements input and output video streaming, with some processor-side video processing. |
| [Arty Z7 HDMI Output Demo](https://reference.digilentinc.com/reference/programmable-logic/arty-z7/demos/hdmi-output) | Output-only video streaming, prints test patterns and implements some processor-side video processing functionality. |
| [Arty Z7 XADC Analog to Digital Converter Demo](https://reference.digilentinc.com/reference/programmable-logic/arty-z7/demos/xadc) | Simple hardware-only project that uses the XADC analog-to-digital functionality of the board. |
| [Arty Z7 Out-of-Box Demo](https://reference.digilentinc.com/reference/programmable-logic/arty-z7/demos/oob) | The project originally used to program the board during manufacturing. Includes audio output, an HDMI passthrough, USB-UART communication, and uses the LEDs and buttons. |

## Repository Description

This repository contains the Vivado projects and hardware designs for all of the demos that we provide for the Arty Z7. As some demos also require software sources contained in Vitis workspaces, this repository should not be used directly. The [Arty-Z7](https://github.com/Digilent/Arty-Z7) repository contains all sources for these demos across all tools, and pulls in all of this repository's sources by using it as a submodule.

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked in the table of demos, above.

Demos were moved into this repository during 2020.1 updates. History of these demos prior to these updates can be found in their old repositories, linked below:
* https://github.com/Digilent/Arty-Z7-10-HDMI-In
* https://github.com/Digilent/Arty-Z7-20-HDMI-In
* https://github.com/Digilent/Arty-Z7-10-HDMI-Out
* https://github.com/Digilent/Arty-Z7-20-HDMI-Out
* https://github.com/Digilent/Arty-Z7-10-XADC
* https://github.com/Digilent/Arty-Z7-20-XADC
* https://github.com/Digilent/Arty-Z7-10-OOB
* https://github.com/Digilent/Arty-Z7-20-OOB