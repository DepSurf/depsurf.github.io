# Function: <code>of_find_node_by_type</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_find_node_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_node_by_type",
      "external": false,
      "loc": "include/linux/of.h:615",
      "file": "drivers/firmware/efi/sysfb_efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_find_node_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_node_by_type",
      "external": false,
      "loc": "include/linux/of.h:483",
      "file": "drivers/firmware/efi/sysfb_efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_find_node_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_node_by_type",
      "external": false,
      "loc": "include/linux/of.h:481",
      "file": "drivers/firmware/efi/sysfb_efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_find_node_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_node_by_type",
      "external": false,
      "loc": "include/linux/of.h:493",
      "file": "drivers/firmware/efi/sysfb_efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_find_node_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_node_by_type",
      "external": false,
      "loc": "include/linux/of.h:492",
      "file": "drivers/firmware/efi/sysfb_efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct device_node * of_find_node_by_type(struct device_node * from, const char * type)
```

```json
{
  "name": "of_find_node_by_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501598280,
      "name": "of_find_node_by_type",
      "external": true,
      "loc": "drivers/of/base.c:1025",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/altera_edac.c:altr_sdram_probe",
        "drivers/edac/altera_edac.c:altr_sdram_probe",
        "drivers/of/of_numa.c:of_numa_init",
        "drivers/of/of_numa.c:of_numa_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501598280,
      "name": "of_find_node_by_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct device_node * of_find_node_by_type(struct device_node * from, const char * type)
```

```json
{
  "name": "of_find_node_by_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234125372,
      "name": "of_find_node_by_type",
      "external": true,
      "loc": "drivers/of/base.c:1025",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234125372,
      "name": "of_find_node_by_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct device_node * of_find_node_by_type(struct device_node * from, const char * type)
```

```json
{
  "name": "of_find_node_by_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295021312,
      "name": "of_find_node_by_type",
      "external": true,
      "loc": "drivers/of/base.c:1025",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/time.c:get_freq",
        "arch/powerpc/kernel/time.c:time_init",
        "arch/powerpc/kernel/setup-common.c:check_legacy_ioport",
        "arch/powerpc/kernel/setup-common.c:check_legacy_ioport",
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps",
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps",
        "arch/powerpc/kernel/setup_64.c:initialize_cache_info",
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports",
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports",
        "arch/powerpc/kernel/isa-bridge.c:isa_bridge_find_early",
        "arch/powerpc/kernel/isa-bridge.c:isa_bridge_find_early",
        "arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec_prepare",
        "arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec_prepare",
        "arch/powerpc/mm/numa.c:hot_add_scn_to_nid",
        "arch/powerpc/mm/numa.c:hot_add_scn_to_nid",
        "arch/powerpc/mm/numa.c:parse_numa_properties",
        "arch/powerpc/mm/numa.c:parse_numa_properties",
        "arch/powerpc/mm/numa.c:parse_numa_properties",
        "arch/powerpc/sysdev/xics/icp-native.c:icp_native_init",
        "arch/powerpc/sysdev/xics/icp-native.c:icp_native_init",
        "arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_init",
        "arch/powerpc/platforms/pseries/nvram.c:pSeries_nvram_init",
        "arch/powerpc/platforms/pseries/setup.c:pseries_init_irq",
        "arch/powerpc/platforms/pseries/setup.c:pseries_init_irq",
        "arch/powerpc/platforms/pseries/iommu.c:enable_ddw",
        "arch/powerpc/platforms/pseries/iommu.c:enable_ddw",
        "arch/powerpc/platforms/pseries/iommu.c:pci_dma_bus_setup_pSeries",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove_by_index",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove_by_index",
        "arch/powerpc/platforms/pseries/pmem.c:__machine_initcall_pseries_pseries_pmem_init",
        "arch/powerpc/platforms/pseries/pmem.c:dlpar_hp_pmem",
        "drivers/video/fbdev/offb.c:offb_init",
        "drivers/video/fbdev/offb.c:offb_init",
        "drivers/video/fbdev/offb.c:offb_init",
        "drivers/video/fbdev/offb.c:offb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295021312,
      "name": "of_find_node_by_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct device_node * of_find_node_by_type(struct device_node * from, const char * type)
```

```json
{
  "name": "of_find_node_by_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278067230,
      "name": "of_find_node_by_type",
      "external": true,
      "loc": "drivers/of/base.c:1025",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/perf_event.c:init_hw_perf_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278067230,
      "name": "of_find_node_by_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct device_node * of_find_node_by_type(struct device_node * from, const char * type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct device_node * of_find_node_by_type(struct device_node * from, const char * type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct device_node * of_find_node_by_type(struct device_node * from, const char * type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct device_node * of_find_node_by_type(struct device_node * from, const char * type)
```
</details>
</li>
</ul>
