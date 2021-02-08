---
layout: layout.pug
navigationTitle: Version Support Policy
title: Version Support Policy
menuWeight: 5
excerpt: Kaptain's supported version policy
beta: false
enterprise: false
---

D2iQ supports `N-2` of the latest `MAJOR.MINOR` release of Kaptain.
With the GA release of Kaptain 1.0.0, support continues for Kaptain 1.0, 0.6, and 0.5, including all patch releases.
Support for Kaptain 0.4.0 expires.

Users should upgrade their Kaptain installations clusters with every new release to stay up to date with the latest features and bug fixes.

## Supported Konvoy Versions

Kaptain 1.0.0 runs on Konvoy 1.7.

## Supported Kommander Versions

Kaptain 1.0.0 is not yet supported on Kommander.

Note that it is possible to use [Kommander's Dex instance](../custom-configuration/external-dex) for authenticating users in Kaptain.

## Experimental Status
"Experimental" means software, features, functionality, sample configurations, or other speculative content that is still under exploration, development, or testing by D2iQ. Experimental components carry no guarantee of eventual release as GA and therefore must not be used in Production Environments. Experimental components qualify for limited, Severity 4 support only and may be discontinued at any time, with or without notice.

Since Experimental components are not intended for Production Environment use, D2iQ cannot assume any responsibility for errors occurring during their use in Production. We can offer only these services in a commercially-reasonable manner, based on the availability of relevant subject matter experts (SMEs):

General operational guidance for the Experimental component.
Identifying and diagnosing of errors in configuration or implementation, if possible.
Advice on preventing and recovering from failures and troubleshooting, as available.
Support for Experimental components is provided on a Standard level, Severity 4 basis only.