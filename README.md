# Rust Libvirt

The goal of this project is to create a new libvirtd that is more capabile and provides more sensible defaults from the original libvirt.

## Goals

* Drop in replaceable from libvirtd
* Support Multiple definition formats (XML,YAML,JSON)
* Support Socket connectivity from other libvirt sdks
* Improved behaviors in blockcopy and migrate
* Storage Pool feature set more production worthy ( current design is not)
* Narrow scope to solely KVM based orchestration (no Xen)
* Memory Safety with Rust
* More sensible default xml attributes and settings when not specified by user definition
* Improved Monitoring Telemetry pipeline
* Expand Snapshot capabilities


This project is just beginning but we hope to make rapid progress in 2025
