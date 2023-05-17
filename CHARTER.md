# RISC-V Server SoC Specification TG Charter 

The RISC-V Server SoC specification TG shall define a specification for a standardized set of hardware capabilities that portable system software such as operating systems and hypervisors can rely on being present in a RISC-V server SoC. The specification standardizes the requirements for the hardware interfaces and capabilities (e.g., harts, timers, interrupt controllers, PCie root ports, RAS, QOS, in-band management, out-of-band (OOB) management, etc.) provided by the SoC to software executing at privilege level less than M, and enables OS and hypervisor vendors to support such SoC/SiP with a single binary OS image distribution model.

The specification shall reference the relevant industry standards (e.g., PCIe, CXL, DMTF, etc.) and RISC-V standards (e.g., BRS, ISA profiles) where applicable. Where existing specifications provide options, this specification may impose constraints on those options.

The RISC-V server SoC specification complements the following specifications (among others):

 - ISA profiles
 - Boot and runtime services
 - Platform security model

This specification shall be a component of a future RISC-V server platform specification along with the ISA profiles, BRS specification, and the platform security model. The TG shall be governed by the SoC infrastructure HC directly and dotted line to the privileged software HC.
