# Function: <code>__kernel_is_locked_down</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool __kernel_is_locked_down(const char * what, bool first)
```

```json
{
  "name": "__kernel_is_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583191168,
      "name": "__kernel_is_locked_down",
      "external": true,
      "loc": "security/lock_down.c:60",
      "file": "security/lock_down.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:SyS_iopl",
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "kernel/power/hibernate.c:hibernation_available",
        "kernel/power/user.c:snapshot_open",
        "kernel/module.c:load_module",
        "kernel/kexec.c:compat_SyS_kexec_load",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:open_proxy_open",
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/char/mem.c:open_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191168,
      "name": "__kernel_is_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
bool __kernel_is_locked_down(const char * what, bool first)
```

```json
{
  "name": "__kernel_is_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kernel_is_locked_down",
      "external": true,
      "loc": "security/lock_down.c:69",
      "file": "security/lock_down.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/power/hibernate.c:hibernation_available",
        "kernel/power/user.c:snapshot_open",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/bpf/syscall.c:__ia32_sys_bpf",
        "kernel/bpf/syscall.c:__x64_sys_bpf",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/char/mem.c:open_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583399624,
      "name": "__kernel_is_locked_down.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071583399552,
      "name": "__kernel_is_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
bool __kernel_is_locked_down(const char * what, bool first)
```

```json
{
  "name": "__kernel_is_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kernel_is_locked_down",
      "external": true,
      "loc": "security/lock_down.c:69",
      "file": "security/lock_down.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/power/hibernate.c:hibernation_available",
        "kernel/power/user.c:snapshot_open",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info_user",
        "drivers/char/mem.c:open_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583519672,
      "name": "__kernel_is_locked_down.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071583519600,
      "name": "__kernel_is_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
bool __kernel_is_locked_down(const char * what, bool first)
```

```json
{
  "name": "__kernel_is_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kernel_is_locked_down",
      "external": true,
      "loc": "security/lock_down.c:71",
      "file": "security/lock_down.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/power/hibernate.c:hibernation_available",
        "kernel/power/user.c:snapshot_open",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kprobes.c:register_kprobe",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/proc/kcore.c:open_kcore",
        "fs/debugfs/inode.c:debugfs_setattr",
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/char/mem.c:open_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583707336,
      "name": "__kernel_is_locked_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071583707264,
      "name": "__kernel_is_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool __kernel_is_locked_down(const char * what, bool first)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
bool __kernel_is_locked_down(const char * what, bool first)
```
</details>
</li>
</ul>
