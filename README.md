# Learn Ngspice with Python
## Why Ngspice
Since 1972, analog simulation of electrical circuits has been dominated by Spice simulation. Several commercial spawned from original Spice are in wide use today ([HSPICE](https://www.synopsys.com/implementation-and-signoff/ams-simulation/primesim-hspice.html), [Spectre](https://www.cadence.com/en_US/home/tools/custom-ic-analog-rf-design/circuit-simulation/spectre-x-simulator.html), [QSPICE](https://www.qorvo.com/design-hub/design-tools/interactive/qspice)). [Ngspice](https://ngspice.sourceforge.io/) is the only FOSS (Free and Open-Source Software) version available today. Understanding Ngspice will give you a solid understanding of Spice-level circuit simulation.

## Cloning the Repository
This respository can be cloned and run on a local computer. Ngspice and the py4spice package must be installed.

## Running with Codespace
This example is set up to use GitHub Codespaces,enabling you to run the example remotely on GitHub. Simply select *Codespace* instead of *clone*. A ready-to-use VS Code IDE will be created, ready to run the script and Ngspice simulation. Basic knowledge of VS Code and Linux is required.

## Local Installation

### Install Ngspice
Ngspice must be [installed](https://ngspice.sourceforge.io/download.html). For most Linux distributions, Ngspice can be installed with a package manager. As an example, for Debian use the following commands:

```bash
sudo apt update
sudo apt install ngspice
ngspice -v
```
For Microsoft Windows and macOS see the [Ngspice](https://ngspice.sourceforge.io/download.html) repo for instructions.

### Install py4spice
py4spice is installed in the customary way for a PyPI package.
```bash
pip install py4spice
```
