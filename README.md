# Hi, I'm Kamran 👋

Systems Programmer & Kernel Engineer with 10+ years of experience specializing in **OS Internals**, **Windows/Linux Kernel Driver Development**, **Hypervisor Architectures (x86_64 virtualization)**, and **Low-Level Security / Reverse Engineering**.

Focus areas include Second-Level Address Translation (EPT/NPT) memory introspection, custom VMM development, driver-level memory manipulation, and analyzing complex anti-cheat/EDR internal architecture.

---

### 🔬 Technical Specializations

```
  +----------------------------------------------------------------------+
  |                   KERNEL & SYSTEMS ARCHITECTURE                      |
  +----------------------------------------------------------------------+
  |  Windows Kernel     :: WDF / KMDF / WDM, I/O Subsystem, EPROCESS/PTE   |
  |  Linux Kernel       :: LKMs, Netfilter, eBPF, Virtual Memory (mm_struct)|
  |  Virtualization     :: Intel VT-x / AMD-V, EPT/NPT Hooking, Hyper-V VMM|
  |  Reverse Eng.       :: IDA Pro, Ghidra, x64dbg, Windbg Kernel Debugging|
  |  Languages          :: C11, C++20, x86_64 MASM/NASM, Rust (no_std)     |
  +----------------------------------------------------------------------+
```

- **Kernel Development**: Native Windows Kernel Drivers (KMDF/WDM) & Linux Kernel Modules (LKMs). Deep understanding of IRQLs, IRP handling, physical/virtual memory management (PTEs, Page Fault handling, CR3 manipulation), and internal OS dispatching.
- **Hypervisor Introspection (VMM)**: Low-level virtualization leveraging Intel VT-x and AMD-V extensions. Implementation of shadow page tables, EPT/NPT execution-only page manipulation, VMCB/VMCS context management, and Hyper-V attachment detours.
- **Reverse Engineering**: Advanced dynamic & static analysis of kernel drivers, obfuscated binaries, and protection subsystems. Custom IDAPython scripts, symbol reconstruction, and WinDbg kernel-mode triage.
- **Memory Introspection & Security**: Physical/Virtual address space translation, kernel-level stealth hooks, DKOM (Direct Kernel Object Manipulation), and anti-cheat / EDR telemetry analysis.

---

### 🛠 Tech Stack & Tools

- **Languages**: `C` (C99/C11), `C++` (C++17/C++20), `Assembly` (x86_64 MASM/NASM), `Rust` (`no_std` kernel environment), `Python` (Tooling/IDA scripts), `PowerShell`
- **Platforms & APIs**: Windows Driver Kit (WDK), Win32 API, Native API (`Nt`/`Zw`), Linux Kernel API, UEFI EDK-II, USB Host Shield 2.0
- **Debugging & Tools**: WinDbg (Kernel/User), IDA Pro, Ghidra, x64dbg, QEMU/KVM, VMware Workstation, Sysinternals Suite, Process Hacker / System Informer
- **Build Systems**: Visual Studio MSBuild, CMake, Make, vcpkg, NASM, Arduino IDE

---

### 🚀 Highlighted Repositories

- **[hyper-reV](https://github.com/adamvalves/hyper-reV)** — Hypervisor-based memory introspection and kernel reverse engineering framework leveraging Microsoft Hyper-V (Intel EPT & AMD NPT SLAT code hooking, UEFI pre-boot hijack, hypercalls via CPUID, usermode kernel debugging CLI).
- **[easyanticheat-kernel-driver-re](https://github.com/adamvalves/easyanticheat-kernel-driver-re)** — Technical reverse engineering breakdown of EasyAntiCheat kernel driver internals (Import obfuscation decryption, stack unwinding verification, TPM 2.0 hardware attestation, and minifilter I/O monitoring).
- **[arduino-usb-hid-passthrough](https://github.com/adamvalves/arduino-usb-hid-passthrough)** — Embedded C++ firmware for Arduino & MAX3421E USB Host Shield 2.0 implementing USB HID mouse passthrough and CDC serial movement control.

---

### 📌 Core Technical Skillset Summary

| Category | Technologies & Concepts |
| :--- | :--- |
| **Kernel & OS** | Windows Kernel Internals, KMDF, WDM, Linux LKMs, Paging, Virtual Memory Management, IRQLs |
| **Virtualization** | Intel VT-x, AMD-V, EPT / NPT Shadow Paging, Hyper-V VMM Detours, SLAT Cache Synchronization (NMI) |
| **Reverse Engineering** | IDA Pro, Ghidra, WinDbg, Assembly x86_64, Obfuscation Analysis, Kernel Telemetry Bypass Analysis |
| **Embedded & Hardware** | USB HID Protocol, MAX3421E SPI USB Host Shield 2.0, USB CDC Serial, Arduino C++ |
| **Languages** | C, C++, x86_64 Assembly, Rust (`no_std`), Python |
| **Tooling & Environments**| WDK, EDK2 UEFI, Visual Studio, VisualUefi, NASM, CMake, Sysinternals |

---

<div align="center">
  <sub>Discreet Low-Level Systems & Kernel Research • Windows & Linux</sub>
</div>
