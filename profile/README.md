## Hi there 👋

# Hisense&Ligent - SONiC Community 

## Introduction

Welcome to the Hisense Optoelectronics contribution repository for SONiC (Software for Open Networking in the Cloud). As a leading manufacturer of optical transceivers,
Hisense is committed to enhancing the SONiC ecosystem by providing seamless integration and optimal performance for our optical modules across various networking environments, including OTT, Cloud, SDN, and Telcom.
This repository focuses on addressing optical module exceptions caused by peripheral driver issues through collaborative development with the SONiC community. 
-We aim to assist SONiC ecosystem users in efficiently connecting Scale-up and Scale-out networks for AI infrastructure development. 
-We provide optical module compatibility test reports based on various white-box hardware platforms, 
-We will share our technical expertise in the optical module domain, and enable stable firmware upgrades for optical modules while maintaining continuous service traffic in SONiC cloud environments

## Our Contributions

- Contributing platform and device driver enhancements
- Providing test topologies and validation frameworks
- Offering comprehensive troubleshooting resources
- Maintaining an active support channel for community issues

### 1. Driver Development & Integration

We actively contribute to the following code paths in the https://github.com/Hisense-Ligent/SONiC-image:

- **Platform Drivers**: Enhancements to platform-agnostic base classes and interfaces
  - `sfp_base.py`: Base class for SFP interface management
  - `xcvr.py`: Transceiver module management framework

- **Device-Specific Drivers**: Optimizations for Hisense optical modules across different ASIC platforms
  - `cmisCDB.py` & `cmis.py`: Common Management Interface Specification (CMIS) implementation
  - `qsfp_dd.py`: QSFP-DD module-specific driver enhancements

These contributions ensure consistent behavior and performance of Hisense optical modules across diverse SONiC deployments.

### 2. Testing & Validation

We provide resources in the [sonic-mgmt repository](https://github.com/sonic-net/sonic-mgmt) to facilitate rigorous testing of optical modules:

- **Test Topologies**: Pre-configured test environments for validating optical module functionality
- **Automated Test Cases**: Scripts for verifying compliance with SONiC standards
- **Test Reports**: Regularly updated validation results for Hisense optical modules in SONiC environments

### 3. Documentation & Support

Our [Wiki] contains comprehensive resources for SONiC users:

- **Troubleshooting Guides**: Step-by-step instructions for resolving common optical module issues
- **Debug SOPs**: Standard operating procedures for advanced debugging scenarios
- **FAQs**: Answers to frequently asked questions about Hisense optical modules in SONiC

## Getting Started

### Using Hisense-Enabled SONiC Images test

1. Build SONiC images with Hisense driver enhancements:
   ```bash
   git clone https://github.com/sonic-net/sonic-buildimage.git
   cd sonic-buildimage
   # Apply Hisense patches cmis.py cmisCDB
  
   ```
2.Install OS via ONIE
  

3.Set T0 topology & run pytest 

### Contributing to Our Efforts

We welcome contributions from the community! To contribute:

1. Fork this repository and create a feature branch
2. Submit pull requests for code reviews
3. Participate in issue resolution and testing efforts

Please adhere to the [SONiC Contribution Guidelines](https://github.com/sonic-net/SONiC/blob/master/CONTRIBUTING.md) when submitting changes.

### Reporting Issues

If you encounter issues with Hisense optical modules in your SONiC environment, please:

1. Check the [existing issues](https://github.com/hisense-optoelectronics/sonic/issues)
2. Use the [issue template](https://github.com/hisense-optoelectronics/sonic/issues/new) to submit detailed information
3. Include relevant logs and configuration details

Our team monitors these issues and provides timely responses and resolutions.

## Community Resources

- **Hisense optical module datasheet**: [https://sonic-net.github.io/SONiC/](https://sonic-net.github.io/SONiC/)
- **SONiC Community Support**: 
- **Hisense Optoelectronics**: [https://www.hisense-opto.com/](https://www.hisense-opto.com/)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](https://github.com/sonic-net/SONiC/blob/master/LICENSE) file for details.

## Acknowledgments

- Thanks to the SONiC community for their ongoing collaboration and support
- Special thanks to all contributors who help improve Hisense optical module integration in SONiC
