# ran-profiles

This repository contains 5G DU / CU profiles.
The profiles here can be configured by any toolset (e.g. [`ACM`](https://github.com/open-cluster-management) or [`cnf-feature-deploy`](https://github.com/openshift-kni/cnf-features-deploy))


## Overview

The [`du`](du) directory contains the Kustomize profiles for of DU integration features configiurations, namely:
- PTP operator Telco profiles
- SR-IOV operator profiles of the DU function, configuring midhaul and fronthaul networks

 
The [`example`](example) directory contains hardware-specific configurations:
- PAO profiles
- SR-IOV network node policies
  - the interface names must be changed for a specific HW

