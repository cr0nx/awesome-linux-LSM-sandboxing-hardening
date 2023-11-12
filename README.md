# Awesome-Linux-LSM-Sandboxing-Hardening
This page is a result of the ongoing hands-on research around advanced Linux Hardening, Sandboxing, and Linux Security Modules.

Since I have been practicing the red vs blue approach for years, the material below will allow you to see the scale of the number of projects, techniques, and tactics in the scope of Linux/Kubernetes defensive/protection/hardening options and features.

All these defensive/protection techniques and tools have been tested by myself, offensively targeted by different use case scenarios taken from the Defensive Security Linux Attack and Live Forensics At Scale course (https://edu.defensive-security.com/linux-attack-live-forensics-at-scale)

This is the 2nd step to creating a dynamic workshop program as a framework, where you can play as a Linux Defender, SysOps, and DevSecOps Engineer at once using the full set of custom detection/protection layers. The approach will also allow for the creation of custom defense-in-depth configuration paths, steps needed for restricting/hardening your OS and application stack, and all the stuff needed for secure Linux deployments on-premise and in the cloud.

The more layers, the more chances.


## Linux Security Modules/Security Features/Hardening Patches

| Name                                                              | Description                                                                                                                           |
|-------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| SELinux - Mandatory Access Control   | SELinux aims to enhance the security of Linux systems by implementing mandatory access controls (MAC).                                                                |
| Apparmor - Mandatory Access Control       | Linux security module designed to restrict the capabilities of individual programs or processes                                                                   |                 
| SMACK - Simplified Mandatory Access Control Kernel                | Smack is a kernel-based implementation of mandatory access control that includes simplicity in its primary design goals                   |
| Tomoyo - Name-based MAC extension (LSM module) for the Linux kernel                  | MAC that covers practical requirements for most users and remains usable for most administrators                         |
| LoadPin - Linux Security Module                  | Linux Security Module that ensures all kernel-loaded files (modules, firmware, etc) all originate from the same filesystem                         |
| Lockdown - Security feature                  | Linux kernel lockdown is a security feature that aims at restricting the root's ability to modify the kernel at runtime                         |
| Yama - LSM                  | Yama is a Linux Security Module that collects system-wide DAC security protections that are not handled by the core kernel itself                        |
| Ptags - LSM                  | The Linux Security Module ptags manages for each process a list of tags                        |
| KRSI – Kernel Runtime Security Instrumentation                  | The target of this patch is to allow users to implement LSM hooks by utilizing bpf compiled code                       |
| fs-verity – read-only file-based authenticity protection                  |  a support layer that filesystems can hook into to support transparent integrity and authenticity protection of read-only files     |
| LKRG – Linux Kernel Runtime Guard                  | LKRG performs runtime integrity checking of the Linux kernel and detection of security vulnerability exploits against the kernel     |
| GRSecurity – set of security patches                  | Grsecurity® is an extensive security enhancement to the Linux kernel that defends against a wide range of security threats through intelligent access control, memory corruption-based exploit prevention, and a host of other system hardening that generally require no configuration.     |
| LKRG – Linux Kernel Runtime Guard                  | LKRG performs runtime integrity checking of the Linux kernel and detection of security vulnerability exploits against the kernel     |
| VED-Ebpf                  | VED (Vault Exploit Defense)-eBPF leverages eBPF (extended Berkeley Packet Filter) to implement runtime kernel security monitoring and exploit detection for Linux systems    |


 ## Linux Sandboxes
| Name                                                              | Description                                                                                                                           |
|-------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
|  gVisor   | gVisor intercepts application system calls and acts as the guest kernel, without the need for translation through virtualized hardware                                                          |
|  bpflock   | bpflock - eBPF driven security for locking and auditing Linux machines                                                          |
|  nsjail   | A lightweight process isolation tool that utilizes Linux namespaces, cgroups, rlimits and seccomp-bpf syscall filters, leveraging the Kafel BPF language for enhanced security. |
|  isolate   | Isolate is a sandbox built to safely run untrusted executables, offering them a limited-access environment and preventing them from affecting the host system. |
|  cloudflare/sandbox   | Simple Linux seccomp rules without writing any code |
|  secimport   | Python runtime sandbox with eBPF and seccomp (Blocks RCE). | 
|  bubblewrap   | Low-level unprivileged sandboxing tool used by Flatpak and similar projects | 








