## Hi there 👋

# Hisense&Ligent - SONiC Community 

## Introduction

Welcome to the Hisense & Ligent SONiC Community. With 23 years of excellence in optical transceiver design and manufacturing, Hisense & Ligent provides industry-leading connectivity solutions. We partner with top-tier cloud and networking giants to drive AI infrastructure forward. Through our deep technical synergy with the SONiC ecosystem, we empower customers to accelerate product deployment and establish stable, monitorable, and highly efficient AI factories.

## Our Contributions

### 1. Testing & Validation

Proven Performance: We provide real-world test reports for our full product line (100G to 3.2T), verified within live AI factory network environments to ensure maximum reliability.
Universal testing benchmarks：Focused on client requirements, we go beyond internal data; we partner with leading cloud and networking vendors to define industry-standard testing benchmarks, ensuring our test reports are transparent, reliable, and client-trusted."
Complete AI Factory Interconnect Ecosystem: Our solutions cover every AI connectivity scenario, including Scale-Up, Scale-Out, and Scale-Across, supported by a full-spectrum product line spanning transceiver modules, breakout cables, AOCs, and DACs.


- Technical Support is available under the [discussion section（Q&A）](https://github.com/orgs/Hisense-Ligent/discussions).

- when submitting a bug ticket please use the [announcement template](https://github.com/orgs/Hisense-Ligent/discussions/1) to help us quickly identify and resolve the issue.
  
- We'll share [optical networks-related technical materials](https://github.com/Hisense-Ligent/SONiC-OCP-OFC-Summit-Related-Highlight) from the AI Data Center Open Source Summit in this community. You can access tech sharing from this top summit here. If interested in optical module tech, 
  feel free to contact us.



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
