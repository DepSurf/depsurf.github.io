# Function: <code>__sysfs_match_string</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588245792,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:668",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245792,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588797216,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:669",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797216,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589175312,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:669",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589175312,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589405232,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:670",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589405232,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589861024,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:712",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861024,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590086512,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:714",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086512,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585084352,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:771",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/acpi/button.c:param_set_lid_init_state",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585084352,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585233520,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:768",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/acpi/button.c:param_set_lid_init_state",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233520,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585116368,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:768",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/acpi/button.c:param_set_lid_init_state",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_lpm_latch_mode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116368,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585565056,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:769",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "mm/memory_hotplug.c:set_online_policy",
        "block/blk-ioprio.c:ioprio_set_prio_policy",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/acpi/button.c:param_set_lid_init_state",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585565056,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586103440,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string_helpers.c:919",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "mm/memory_hotplug.c:set_online_policy",
        "block/blk-ioprio.c:ioprio_set_prio_policy",
        "drivers/gpio/gpiolib-sysfs.c:edge_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/acpi/button.c:param_set_lid_init_state",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_parse",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586103440,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587088480,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string_helpers.c:963",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "mm/memory_hotplug.c:set_online_policy",
        "block/blk-ioprio.c:ioprio_set_prio_policy",
        "drivers/gpio/gpiolib-sysfs.c:edge_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/acpi/button.c:param_set_lid_init_state",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_parse",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587088480,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587348400,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string_helpers.c:963",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "mm/memory_hotplug.c:set_online_policy",
        "block/blk-ioprio.c:ioprio_set_prio_policy",
        "drivers/gpio/gpiolib-sysfs.c:edge_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/acpi/button.c:param_set_lid_init_state",
        "drivers/block/virtio_blk.c:cache_type_store",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_parse",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587348400,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587634528,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string_helpers.c:980",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "mm/memory_hotplug.c:set_online_policy",
        "block/blk-ioprio.c:ioprio_set_prio_policy",
        "drivers/gpio/gpiolib-sysfs.c:edge_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/acpi/button.c:param_set_lid_init_state",
        "drivers/block/virtio_blk.c:cache_type_store",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_parse",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587634528,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503864280,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:714",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503864280,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236492320,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:714",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236492320,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297723488,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:714",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297723488,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279760128,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:714",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279760128,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688768,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:714",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688768,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589414560,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:714",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414560,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590132144,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:714",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132144,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```

```json
{
  "name": "__sysfs_match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590182528,
      "name": "__sysfs_match_string",
      "external": true,
      "loc": "lib/string.c:714",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/scsi/sd.c:zeroing_mode_store",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182528,
      "name": "__sysfs_match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __sysfs_match_string(const const char * * array, size_t n, const char * str)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
