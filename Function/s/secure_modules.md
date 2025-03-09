# Function: <code>secure_modules</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool secure_modules()
```

```json
{
  "name": "secure_modules",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579912464,
      "name": "secure_modules",
      "external": true,
      "loc": "kernel/module.c:4119",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "arch/x86/kernel/ioport.c:SyS_iopl",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/kexec.c:compat_SyS_kexec_load",
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/char/mem.c:write_port",
        "drivers/char/mem.c:write_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912464,
      "name": "secure_modules",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool secure_modules()
```

```json
{
  "name": "secure_modules",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942352,
      "name": "secure_modules",
      "external": true,
      "loc": "kernel/module.c:4290",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:SyS_iopl",
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/kexec.c:compat_SyS_kexec_load",
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/char/mem.c:write_port",
        "drivers/char/mem.c:write_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942352,
      "name": "secure_modules",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool secure_modules()
```

```json
{
  "name": "secure_modules",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579973568,
      "name": "secure_modules",
      "external": true,
      "loc": "kernel/module.c:4311",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:SyS_iopl",
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/kexec.c:compat_SyS_kexec_load",
        "kernel/bpf/syscall.c:SyS_bpf",
        "drivers/pci/pci-sysfs.c:pci_write_resource_io",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/char/mem.c:write_port",
        "drivers/char/mem.c:write_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973568,
      "name": "secure_modules",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool secure_modules()
```
</details>
</li>
</ul>
