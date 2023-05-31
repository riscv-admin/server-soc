# RISC-V Server SoC Specification TG Charter 

The RISC-V Server SoC specification TG shall define a specification for a standardized set of hardware capabilities that portable system software such as operating systems and hypervisors can rely on being present in a RISC-V server SoC. A server is a computing system that is designed to manage and distribute resources, services, and data to other computers or devices on a network. It is often referred to as a "server" because it serves or provides information or resources upon request. Such computing systems are designed to operate continually and have a higher degree of requirements on RAS, security, performance, quality of service, etc. Examples of servers include web servers, file servers, database servers, mail servers, game servers, etc. The focus of this specification is to define requirements for general purpose server computing systems that may be used for one or more of these purposes.

The specification standardizes the requirements for the hardware interfaces and capabilities (e.g., harts, timers, interrupt controllers, PCIe root complexes, RAS, QoS, in-band management, out-of-band (OOB) management, etc.) provided by the SoC to software executing at privilege level less than M, and enables OS and hypervisor vendors to support such SoC with a single binary OS image distribution that can be installed and used across implementations compliant with this specification.

The specification shall reference the relevant industry standards (e.g., PCIe, CXL, DMTF, etc.) and RISC-V standards (e.g., BRS-I, ISA profiles) where applicable. Where existing specifications provide options, this specification may impose constraints on those options.

The RISC-V server SoC specification complements the following specifications (among others):
 - ISA profiles
 - Boot and runtime services
 - Platform security model

The RISC-V server SoC specification is expected to be updated periodically to stay up to date with evolution of related RISC-V specifications (e.g., profiles, BRS-I, etc.) and related standards defined by the industry (e.g., PCIe, CXL, DMTF, OCP, etc.).

The RISC-V server SoC specification TG shall define a coverage plan and approach to determine compliance to the requirements defined by the specification.

This specification shall be a component of a future RISC-V server platform specification along with the ISA profiles, BRS specification, and the platform security model. The coverage plan defined by the TG shall be an input to a future RISC-V server platform compatibility/compliance test suite.

The TG shall be governed by the SoC Infrastructure HC directly and dotted line to the Privileged Software HC.
