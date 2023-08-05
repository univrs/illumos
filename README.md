---
description: Resources for developers and sys admins
---

# illumos

***

[Distributions](https://illumos.org/docs/about/distro/)\


| Project                                        | Provider                                                         | Focus                | Linux Comparison | Open Source | Packaging                            | x86     | SPARC   | KVM     | LX      |
| ---------------------------------------------- | ---------------------------------------------------------------- | -------------------- | ---------------- | ----------- | ------------------------------------ | ------- | ------- | ------- | ------- |
| [OmniOS CE](https://www.omniosce.org/)         | [OmniOS Community Association](https://omniosce.org/about/about) | Servers              | Debian           | _check_     | IPS                                  | _check_ |         | _check_ | _check_ |
| [OpenIndiana](https://www.openindiana.org/)    | [OpenIndiana](https://www.openindiana.org/)                      | Workstation, Servers | Ubuntu           | _check_     | IPS                                  | _check_ |         | _check_ |         |
| [SmartOS](https://smartos.org/)                | [MNX Solutions](https://mnxsolutions.com/)                       | Hypervisor           | CoreOS           | _check_     | [pkgsrc](https://pkgsrc.joyent.com/) | _check_ |         | _check_ | _check_ |
| [NexenStor](https://community.nexenta.com/s/)  | [Nexenta](https://nexenta.com/)                                  | Storage              |                  |             | APT                                  | _check_ |         |         |         |
| [Tribblix](http://www.tribblix.org/)           | Peter Tribble                                                    | Workstation, Servers | Slackware        | _check_     | SVR4                                 | _check_ | _check_ |         | _check_ |
| [DilOS](http://www.dilos.org/)                 | igork                                                            | Workstation, Servers |                  | _check_     | APT                                  | _check_ | _check_ | _check_ | _check_ |
| [XStreamOS](http://www.sonicle.com/xstreamos/) | [Sonicle](http://www.sonicle.com/)                               | Server               |                  | _check_     |                                      | _check_ |         |         |         |
| [v9os](http://www.milax.fi/v9os.html)          | [MilaX](http://www.milax.fi/)                                    | Server               |                  | _check_     | IPS                                  |         | _check_ |         |         |
| [Danube Cloud](https://danube.cloud/)          | [Danube Cloud Community](https://github.com/erigones/esdc-ce)    | Hypervisor           | Proxmox          | _check_     | [pkgsrc](https://pkgsrc.joyent.com/) | _check_ |         |         |         |

\
\
**Books & Papers:**

* [Updated versions of Sun docbooks for illumos](https://github.com/illumos/illumos-docbooks)
* [illumos: Boot Loader Paper](https://s3.amazonaws.com/dev.univrs.io/books/illumos\_Boot\_Loader.pdf)
* [C Compiler (PCC) to Illumos](https://briancallahan.net/blog/20230705.html)
* [Oxide Guides](https://docs.oxide.computer/guides/introduction)
* [OmniOS-Wiki](https://github.com/omniosorg/omnios-wiki)
* [AWS AMI: Ominos](https://ardeshir.io/omnios)

### [illumos Developer's Guide](https://illumos.org/books/dev/)

This guide covers the basic workflow for developing illumos and then dives into specific detail on everything from the layout of the gate to several HOWTOs. Whether this is your first time working with illumos or you remember back when the code in the gate all referred to something called SunOS, this guide will help you in enhancing and fixing illumos.

### [Dynamic Tracing Guide](https://illumos.org/books/dtrace/)

DTrace is a comprehensive dynamic tracing framework for the illumos Operating System. DTrace provides a powerful infrastructure to permit administrators, developers, and service personnel to concisely answer arbitrary questions about the behavior of the operating system and user programs. The illumos Dynamic Tracing Guide describes how to use DTrace to observe, debug, and tune system behavior. This book also includes a complete reference for bundled DTrace observability tools and the D programming language.

### [Modular Debugger Guide](https://illumos.org/books/mdb/)

The Modular Debugger (MDB) is a highly extensible, general purpose debugging tool for the illumos Operating System. The Modular Debugger Guide describes how to use MDB to debug complex software systems, with a particular emphasis on the facilities available for debugging the illumos kernel and associated device drivers and modules. It also includes a complete reference for and discussion of the MDB language syntax, debugger features, and MDB Module Programming API.

### [Writing Device Drivers](https://illumos.org/books/wdd/)

Writing Device Drivers provides information on developing drivers for character-oriented devices, block-oriented devices, network devices, SCSI target and HBA devices, and USB devices for the illumos Operating System (illumos). This book discusses how to develop multithreaded reentrant device drivers for all architectures that conform to the illumos DDI/DKI (Device Driver Interface, Driver-Kernel Interface). A common driver programming approach is described that enables drivers to be written without concern for platform-specific issues such as endianness and data ordering.

Additional topics include hardening illumos drivers; power management; driver autoconfiguration; programmed I/O; Direct Memory Access (DMA); device context management; compilation, installation, and testing drivers; debugging drivers; and porting illumos drivers to a 64-bit environment.

### [Memory and Thread Placement Optimization Developer's Guide](https://illumos.org/books/lgrps/)

The Memory and Thread Placement Optimization Developer's Guide provides information on locality groups and the technologies that are available to optimize the use of computing resources in the illumos operating system.
