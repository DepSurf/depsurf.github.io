# Function: <code>bus_get_dev_root</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct device * bus_get_dev_root(const struct bus_type * bus)
```

```json
{
  "name": "bus_get_dev_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590602384,
      "name": "bus_get_dev_root",
      "external": true,
      "loc": "drivers/base/bus.c:1360",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/workqueue.c:wq_sysfs_init",
        "drivers/acpi/acpi_lpit.c:lpit_update_residency",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590602384,
      "name": "bus_get_dev_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct device * bus_get_dev_root(const struct bus_type * bus)
```

```json
{
  "name": "bus_get_dev_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590961328,
      "name": "bus_get_dev_root",
      "external": true,
      "loc": "drivers/base/bus.c:1360",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/cpu.c:cpuhp_sysfs_init",
        "kernel/workqueue.c:wq_sysfs_init",
        "drivers/acpi/acpi_lpit.c:lpit_update_residency",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/cpu.c:cpu_dev_init",
        "drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/cpuidle/sysfs.c:cpuidle_add_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590961328,
      "name": "bus_get_dev_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct device * bus_get_dev_root(const struct bus_type * bus)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
