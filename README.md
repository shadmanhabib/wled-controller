# WLED-Controller

## Table of Contents
- [Automated Fuel Card Processing](#automated-fuel-card-processing)
  - [Table of Contents](#table-of-contents)
  - [About The Project](#about-the-project)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Changelog](#changelog)

## About The Project
PCB design and fabrication of ESP8266 based controller for WLED.

This project contains multiple branches, each with its own unique use case and form factor. This is the main branch which contains the smallest controller with the least number of additional features.

## Getting Started
To get a build this project (or parts thereof), these steps may be followed.

### Prerequisites
1. A download of either the WLED binary or source code that can be compile for upload onto the ESP8266.
2. If you want to make changes to the PCB design or would like to generate new fabrication files, an installation of KiCAD is required.

### Installation
1. Manufacture a PCB.
2. Upload WLED using ESPHomeFlasher or other programs.

## Usage
Examples will be given in future iterations of this file.

_For more examples, please refer to the [Documentation](https://)_

## Changelog
All notable changes to this project will be documented in this section.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project attempts to adhere to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

### [v2.0.0]
#### Changed
- New compact form factor.
- Multiple changes to component selection.
- Removed micro USB port. Replaced with 2.54mm pin header.

#### Added
- Power switching between LiPo and 5V external with external priority.

#### Removed
- Boost converter.

### [v1.0.0]
#### Initial design
- ESP8266 based design.
- Single-cell LiPo charge circuit.
- Boost converter for 5V output.
- Logic level converter (bi-directional 3.3-5V).
