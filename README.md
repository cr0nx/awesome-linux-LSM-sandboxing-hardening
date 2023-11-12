# awesome-linux-LSM-sandboxing-hardening
This page is a result of the ongoing hands-on research around advanced Linux Hardening, Sandboxing, and Linux Security Modules.

Since I have been practicing the red vs blue approach for years, the material below will allow you to see the scale of the number of projects, techniques, and tactics in the scope of Linux/Kubernetes defensive/protection/hardening options and features.

All these defensive/protection techniques and tools have been tested by myself, offensively targeted by different use case scenarios taken from the Defensive Security Linux Attack and Live Forensics At Scale course (https://edu.defensive-security.com/linux-attack-live-forensics-at-scale)

This is the 2nd step to creating a dynamic workshop program as a framework, where you can play as a Linux Defender, SysOps, and DevSecOps Engineer at once using the full set of custom detection/protection layers. The approach will also allow for the creation of custom defense-in-depth configuration paths, steps needed for restricting/hardening your OS and application stack, and all the stuff needed for secure Linux deployments on-premise and in the cloud.

The more layers, the more chances.


## Linux Security Modules 

| File                                                              | Description                                                                                                                                |
|-------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| [SELinux - Mandatory Access Control]  | SELinux aims to enhance the security of Linux systems by implementing mandatory access controls (MAC).                                                                |
| [Apparmor - Mandatory Access Control]      | Linux security module designed to restrict the capabilities of individual programs or processes                                                                   |                 
| [SMACK - Simplified Mandatory Access Control Kernel]               | Smack is a kernel-based implementation of mandatory access control that includes simplicity in its primary design goals                   |
| [Tomoyo - Name-based MAC extension (LSM module) for the Linux kernel]                 | MAC that covers practical requirements for most users and remains usable for most administrators                         |
