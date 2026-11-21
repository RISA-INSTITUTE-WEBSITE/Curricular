# CS222 — Operating Systems

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Computer Science  
**Module code:** CS222  
**Module title:** Operating Systems  
**Level:** Second-year / 200-level  
**Document:** Proposed module learning outcomes  
**Status:** Draft — pending academic review  
**Version:** 0.1  
**Date:** 21 November 2026

## 1. Module purpose

This module develops students’ understanding of how an operating system manages processes, memory, files, devices and shared resources. Students use an accessible operating-system environment and simulators to observe behaviour, solve common resource-management problems and apply basic system-administration practices.

**Curriculum alignment:** The original RISA outline identifies processes, threads, CPU scheduling, memory management and file systems. Process synchronization, command-line investigation, access permissions and device management are suggested developments to make the module teachable and assessable.

## 2. Proposed module learning outcomes

**Upon successful completion of CS222, students should be able to:**

| Code | Learning outcome |
| --- | --- |
| **LO1** | Explain the purpose, structure and major services of an operating system, distinguishing user applications, the kernel and system calls. |
| **LO2** | Describe the process lifecycle and examine how processes are created, scheduled, suspended and terminated. |
| **LO3** | Distinguish processes from threads and explain common benefits and risks of concurrent execution. |
| **LO4** | Trace and compare introductory CPU scheduling algorithms using waiting, turnaround and response time measures. |
| **LO5** | Explain race conditions, critical sections, synchronization primitives and deadlock through simple concurrent scenarios. |
| **LO6** | Explain the role of memory allocation, address spaces, paging and virtual memory in process execution. |
| **LO7** | Describe file-system structures and apply basic file and directory operations, paths, permissions and access controls. |
| **LO8** | Explain how operating systems coordinate input/output devices through device drivers, interrupts and buffering at an introductory level. |
| **LO9** | Use safe system utilities or simulations to inspect processes, memory and files, and diagnose basic resource or permission problems. |
| **LO10** | Analyse and document a small operating-system case study or experiment, justifying configuration or resource-management choices using observed results. |

## 3. Learning outcomes by teaching section

### Section A — OS Services, Processes and CPU Scheduling

**Mapped outcomes:** LO1, LO2, LO3, LO4

**Content focus:**
- Operating system services, kernel/user space and system calls
- Process states, process control and threads
- Context switching and CPU scheduling
- Scheduling measures and small scheduling traces

### Section B — Concurrency, Memory, Files and I/O

**Mapped outcomes:** LO5, LO6, LO7, LO8

**Content focus:**
- Critical sections, races, locks and deadlocks
- Memory allocation, paging, virtual memory and address spaces
- Files, directories, paths, metadata and permissions
- Device drivers, interrupts, buffering and I/O flow

### Section C — System Investigation and Practical Work

**Mapped outcomes:** LO9, LO10; integrates LO1–LO8

**Content focus:**
- Authorized process, memory and file inspection
- Scheduling/concurrency simulation and measurements
- Documented troubleshooting and operating-system case study

## 4. Suggested practical learning and assessment activities

These activities are **proposals**, not a finalized assessment specification.

| Practical activity | Outcomes assessed |
| --- | --- |
| Identify kernel services and observe a system call using a controlled example. | LO1 |
| Inspect process states and identify running processes on a lab system. | LO2, LO9 |
| Compare process and thread behaviour in a provided demonstration. | LO3 |
| Calculate waiting and turnaround times for simple scheduling scenarios. | LO4 |
| Demonstrate and explain a controlled race condition and a locking solution. | LO5 |
| Use a simulator to trace page references and page faults. | LO6 |
| Create files and directories and verify file permissions in an approved environment. | LO7, LO9 |
| Trace an illustrative input/output request from application to device. | LO8 |
| Submit a short troubleshooting and resource-monitoring report with evidence. | LO9, LO10 |

## 5. Recommended teaching boundaries

- **Foundation:** Build on CS101 architecture and CS102 programming concepts; any practical code should be short and scaffolded.
- **Platforms:** A supervised Linux virtual machine, WSL or lab image may support exercises; ensure alternatives for low-resource hardware.
- **Safety:** Use unprivileged accounts and isolated lab resources; do not ask students to modify production systems or disable protections.
- **Depth:** Introduce scheduling, memory and synchronization concepts without expecting kernel development, advanced driver programming or deep distributed operating-system internals.

## 6. Curriculum development and approval notes

The curriculum team should determine and approve:

- Specify supported operating-system image, commands, simulation tools and lab privileges.
- Decide which scheduling and memory algorithms students must calculate.
- Define assessments and practical access for students without local virtualization.
- Approve credits, prerequisites, teaching hours and academic standards.
- Assessment weightings, contact hours, prerequisites and institutional approval status.

**Source and development basis:** Original RISA outline includes processes, threads, CPU scheduling, memory management and file systems. Other detailed outcomes and activities are additional curriculum proposals.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
