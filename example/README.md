# ran-profiles

This repository contains 5G DU / CU profiles.
The profiles here can be configured by any toolset (e.g. ACM or cnf-feature-deploy)


## Overview

The [`du`](du) directory contains the Kustomize profiles for of DU integration features configiurations, namely:
- PTP operator Telco profiles
- SR-IOV operator profiles of the DU function, configuring midhaul and fronthaul networks
 
The [`example`](example) directory contains PAO profiles, which are hardware-specific

