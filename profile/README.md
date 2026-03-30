## Hi there 👋

# Hisense&Ligent - SONiC Community 

## Introduction

Welcome to the Hisense & Ligent SONiC Community. With 23 years of excellence in optical transceiver design and manufacturing, Hisense & Ligent provides industry-leading connectivity solutions. We partner with top-tier cloud and networking giants to drive AI infrastructure forward. Through our deep technical synergy with the SONiC ecosystem, we empower customers to accelerate product deployment and establish stable, monitorable, and highly efficient AI factories.

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
  - `cmisCDB.py` & `cmis.py`: Common Management Interface Specification (CMIS) implementation
  - `qsfp_dd.py`: QSFP-DD module-specific driver enhancements

These contributions ensure consistent behavior and performance of Hisense optical modules across diverse SONiC deployments.

## Getting Started

### Using Hisense-Enabled SONiC Images test

1. [Build SONiC](https://github.com/Hisense-Ligent/SONiC-image) images with Hisense driver enhancements:
2. Install OS via ONIE [How to install SONiC ](https://github.com/Hisense-Ligent/SONiC-image)
3. [Set topology & Run pytest](https://github.com/Hisense-Ligent/SONiC-CICT/tree/main)

## Community Resources

- **[Hisense product datasheet](https://hbmt.hisense.com)**:
- **[Ligent  product datasheet](https://www.ligent.com/#solutions)**

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](https://github.com/sonic-net/SONiC/blob/master/LICENSE) file for details.

## Acknowledgments

- Thanks to the SONiC community for their ongoing collaboration and support
- Special thanks to all contributors who help improve Hisense optical module integration in SONiC
