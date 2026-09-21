# CRYPTO-5140

Single-technology IP library.

- doc/     : user documentation
- dependencies/ : sub-cells and blocks
- release/v.1.0.0 : immutable versioned deliveries

## Overview and origin

AES-128 (Advanced Encryption Standard) is the most popular and widely used symmetric-key block cipher algorithm standardized by NIST. It encrypts fixed-size 128-bit data blocks using a 128-bit secret key through 10 encryption rounds. AES-128 is widely adopted in secure communication and embedded systems due to its strong security, efficiency, and suitability for both software and hardware implementations.

This IP is derived form the Apache-2.0-licensed https://github.com/vijayank88/AES128_GFMPW0. It provides an implementation of this algorithm in GF180mcuC PDK. 

The resulting IP package was produced through a reproducible digital design flow based on LibreLane. All files included in the package are the outcome of executing the complete design, implementation, and validation flow within LibreLane. Additionally, the design was validated using the provided testbenches.

The current release targets the GF 180nm CMOS process design kit using the gf180mcu_fd_sc_mcu7t5v0 standard-cell library. In addition to the synthesizable RTL implementation, the release includes a placed-and-routed hard macro and the associated logical, physical, timing, and verification views required for integration into a larger design.
