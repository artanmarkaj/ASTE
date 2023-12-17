# Autonomous Systems Training Environment (ASTE) Framework

## Overview

Welcome to the Autonomous Systems Training Environment (ASTE) Framework repository! This framework is designed to provide a comprehensive platform for training and testing autonomous systems, with a focus on applications and intelligent control algorithms in autonomous process plant operations. The repository includes information on preliminaries (autonomy, autonomous systems, autonomous operations), the ASTE framework's architecture, implementation details, an exemplary use case featuring a Continuous Stirred Tank Reactor (CSTR), and instructions for deploying the framework and exemplay use case in MATLAB/Simulink.

## Table of Contents

1. [Introduction](#introduction)
2. [Architecture](#architecture)
3. [Implementation](#implementation)
   - [Exemplary Use Case: CSTR](#exemplary-use-case-cstr)
   - [Deployment in MATLAB/Simulink](#deployment-in-matlab-simulink)
4. [Contributing](#contributing)
5. [License](#license)

## Introduction

Autonomy in the sense of technical systems represents a system property characterized by *absence of human intervention, goal orientation* and *consideration of uncertainty*. Autonomous systems are a crucial aspect of modern technology, enabling technical systems to operate independently and make decisions without human intervention. In the context of process plants, autonomy plays a significant role in optimizing operations, enhancing safety, and improving efficiency. But most importantly, future shortage of skilled plant operators can be compensated by a higher degree of automation and autonomy of the plant. This repository introduces the Autonomous Systems Training Environment (ASTE) Framework, a tool designed for training and testing autonomous systems (especially intelligent process control algorithms) with a specific focus on process plant operations.

## Architecture

The ASTE Framework is built on a robust and flexible architecture that allows for seamless integration with various autonomous systems. The logical architecture is illustrated in the figure below:

![ASTE Framework Architecture](figures/ASTE_Architecture.pdf)

The framework is designed to support a modular and extensible structure, making it adaptable to different autonomous applications. The architecture comprises key components for sensor integration, decision-making algorithms, and actuators, facilitating the autonomous operation of process plants.

## Implementation

### Exemplary Use Case: CSTR

To demonstrate the capabilities of the ASTE Framework, an exemplary use case involving a Continuous Stirred Tank Reactor (CSTR) is provided. The figure below illustrates the CSTR use case within the ASTE Framework:

![CSTR Use Case](figures/CSTR_FlowDiagram.pdf)

This section details the implementation specifics, including code snippets and configurations, to showcase how the ASTE Framework can be utilized in a real-world application.

### Deployment in MATLAB/Simulink

The ASTE Framework is seamlessly deployable in MATLAB/Simulink environments. The deployment process is outlined in the documentation, providing step-by-step instructions for integrating the framework into your MATLAB/Simulink projects.

## Contributing

We welcome contributions from the community to enhance and expand the capabilities of the ASTE Framework. If you have ideas, bug reports, or feature requests, please open an issue or submit a pull request. Check out the [CONTRIBUTING.md](CONTRIBUTING.md) file for more information on how to contribute.

## License

This project is licensed under the [MIT License](LICENSE), granting you the freedom to use, modify, and distribute the software.

Feel free to explore the repository and leverage the ASTE Framework for your autonomous systems development and training needs!
