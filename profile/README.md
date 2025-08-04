## Hi there 👋

# Hisense&Ligent - SONiC Community 

## Introduction

Welcome to the [Hisense&Ligent](https://www.ligent.com/) contribution repository for [SONiC (Software for Open Networking in the Cloud)](https://github.com/sonic-net). As a leading manufacturer of optical transceivers,
Hisense is committed to enhancing the SONiC ecosystem by providing seamless integration and optimal performance for our optical modules across various networking environments, including Cloud, OTT, SDN, and Telcom.
This repository focuses on addressing optical module exceptions caused by peripheral driver issues through collaborative development with the SONiC community. 
- We will share our technical support in the optical module domain, and enable stable firmware upgrades for optical modules while maintaining continuous service traffic in SONiC cloud environments.
- We provide optical module compatibility test reports based on various white-box hardware platforms.
- We aim to assist SONiC ecosystem users in efficiently connecting Scale-up and Scale-out networks for AI infrastructure development. 


## Our Contributions


### 1.Technical Support

- Technical Support is available under the [discussion section（Q&A）](https://github.com/orgs/Hisense-Ligent/discussions).

- when submitting a bug ticket please use the [announcement template](https://github.com/orgs/Hisense-Ligent/discussions/1) to help us quickly identify and resolve the issue.
  
- We'll share [optical networks-related technical materials](https://github.com/Hisense-Ligent/SONiC-OCP-OFC-Summit-Related-Highlight) from the AI Data Center Open Source Summit in this community. You can access tech sharing from this top summit here. If interested in optical module tech, 
  feel free to contact us.

### 2. Testing & Validation

We are verifying the stability of Hisense optical modules on various platforms based on the [SONiC-MGMT project](https://github.com/Hisense-Ligent/SONiC-MGMT). The related test topology, test code, and reports will be shared in the [Hisense SONiC automation test case](https://github.com/Hisense-Ligent/SONiC-CICT):

- **Test Topologies**: Pre-configured test environments for validating optical module functionality
- **Automated Test Cases**: Scripts for verifying compliance with SONiC standards
- **Test Reports**: Regularly updated validation results for Hisense optical modules in SONiC environments

### 3. Driver Development & Integration

We actively contribute to the following code paths in the https://github.com/Hisense-Ligent/SONiC-image:

- **Platform Drivers**: Enhancements to platform-agnostic base classes and interfaces
  - `sfp_base.py`: Base class for SFP interface management
  - `xcvr.py`: Transceiver module management framework

- **Device-Specific Drivers**: Optimizations for Hisense optical modules across different ASIC platforms
  - `cmisCDB.py` & `cmis.py`: Common Management Interface Specification (CMIS) implementation
  - `qsfp_dd.py`: QSFP-DD module-specific driver enhancements

These contributions ensure consistent behavior and performance of Hisense optical modules across diverse SONiC deployments.

## Getting Started

### Using Hisense-Enabled SONiC Images test

1. Build SONiC images with Hisense driver enhancements:
   ```bash
   git clone https://github.com/sonic-net/sonic-buildimage.git
   cd sonic-buildimage
   # Apply Hisense patches cmis.py cmisCDB
  
   ```
2.Install OS via ONIE [How to install SONiC ](https://github.com/hisense-optoelectronics/sonic/issues)
  

3.[Set topology & run pytest](https://github.com/Hisense-Ligent/SONiC-CICT/tree/main)

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
- **SONiC Community Support**: [https://www.ligent.com/](https://www.ligent.com/)
- **Hisense Optoelectronics**: [https://www.ligent.com/](https://www.ligent.com/)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](https://github.com/sonic-net/SONiC/blob/master/LICENSE) file for details.

## Acknowledgments

- Thanks to the SONiC community for their ongoing collaboration and support
- Special thanks to all contributors who help improve Hisense optical module integration in SONiC
