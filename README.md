# PCI-DSS-Certifications
PCI-specific certifications for [Compliance Masonry](https://github.com/opencontrol/compliance-masonry)

This repository is a Work-In-Progress.  

The goal is to enable applications that must document their PCI DSS compliance to leverage the pattern developed by Compliance Masonry for FedRAMP compliance via NIST-800-53.  

To import these data into a OpenControl project add the follow code to your opencontrol.yaml file.
```yaml
dependencies:
  certifications:
    - url: https://github.com/johnpfield/PCI-DSS-Certifications
      revision: master
```

For more information on the opencontrol.yaml visit the [Compliance Masonry CLI](https://github.com/opencontrol/compliance-masonry#creating-an-opencontrol-project).