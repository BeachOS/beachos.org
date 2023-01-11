---
title: Security FAQ
description: Frequently asked questions about BeachOS security
toc: true
---

### How secure is the signing infrastructure for the OS builds?

Signing is a cryptographic process where we take the factory image of BeachOS and apply a digital signature that allows your device to attest that the image actually came from Beach and no one else.

BeachOS factory images and OTA updates are signed off-line by one person with sole custody of the signing keys.

### Could a rogue developer compromise the over-the-air updates?

As an open source project, BeachOS depends on the contributions from many developers and many other projects. Changes go through stringent review process. Ultimately, there are a small number of people who have (separate) trusted roles, such as creating or signing the factory images.

### What are the security implications of the extended permissions for F-Droid

{% include_page f-droid/security %}

### What are the security implications of the extended permissions for Aurora Store?

{% include_page aurora-store/security %}

### Is it possible to root BeachOS?

BeachOS does not support running in rooted mode, nor do we recommend this. Running any Android device with root permissions severely undermines the security of the device.
