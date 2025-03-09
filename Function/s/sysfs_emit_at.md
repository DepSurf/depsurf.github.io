# Function: <code>sysfs_emit_at</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int sysfs_emit_at(char * buf, int at, const char * fmt, void (anon))
```

```json
{
  "name": "sysfs_emit_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582921904,
      "name": "sysfs_emit_at",
      "external": true,
      "loc": "fs/sysfs/file.c:749",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_enabled_show",
        "mm/shmem.c:shmem_enabled_show",
        "mm/shmem.c:shmem_enabled_show",
        "mm/hugetlb.c:hugetlb_report_node_meminfo",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "drivers/base/core.c:uevent_show",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582921904,
      "name": "sysfs_emit_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int sysfs_emit_at(char * buf, int at, const char * fmt, void (anon))
```

```json
{
  "name": "sysfs_emit_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582949616,
      "name": "sysfs_emit_at",
      "external": true,
      "loc": "fs/sysfs/file.c:760",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_enabled_show",
        "mm/shmem.c:shmem_enabled_show",
        "mm/shmem.c:shmem_enabled_show",
        "mm/hugetlb.c:hugetlb_report_node_meminfo",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "drivers/pci/pci-sysfs.c:resource_show",
        "drivers/base/core.c:uevent_show",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949616,
      "name": "sysfs_emit_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int sysfs_emit_at(char * buf, int at, const char * fmt, void (anon))
```

```json
{
  "name": "sysfs_emit_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583284848,
      "name": "sysfs_emit_at",
      "external": true,
      "loc": "fs/sysfs/file.c:760",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_show_wakelocks",
        "kernel/power/wakelock.c:pm_show_wakelocks",
        "mm/shmem.c:shmem_enabled_show",
        "mm/shmem.c:shmem_enabled_show",
        "mm/shmem.c:shmem_enabled_show",
        "mm/hugetlb.c:hugetlb_report_node_meminfo",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "drivers/pci/pci.c:reset_method_show",
        "drivers/pci/pci.c:reset_method_show",
        "drivers/pci/pci-sysfs.c:resource_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/base/core.c:uevent_show",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_available_governors_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284848,
      "name": "sysfs_emit_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int sysfs_emit_at(char * buf, int at, const char * fmt, void (anon))
```

```json
{
  "name": "sysfs_emit_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583789840,
      "name": "sysfs_emit_at",
      "external": true,
      "loc": "fs/sysfs/file.c:757",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_show_wakelocks",
        "kernel/power/wakelock.c:pm_show_wakelocks",
        "mm/shmem.c:shmem_enabled_show",
        "mm/shmem.c:shmem_enabled_show",
        "mm/hugetlb.c:hugetlb_report_node_meminfo",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "drivers/pci/pci.c:reset_method_show",
        "drivers/pci/pci.c:reset_method_show",
        "drivers/pci/pci-sysfs.c:resource_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/base/core.c:uevent_show",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show",
        "drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_available_governors_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583789840,
      "name": "sysfs_emit_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int sysfs_emit_at(char * buf, int at, const char * fmt, void (anon))
```

```json
{
  "name": "sysfs_emit_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584409184,
      "name": "sysfs_emit_at",
      "external": true,
      "loc": "fs/sysfs/file.c:757",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_show_wakelocks",
        "kernel/power/wakelock.c:pm_show_wakelocks",
        "mm/shmem.c:shmem_enabled_show",
        "mm/shmem.c:shmem_enabled_show",
        "mm/hugetlb.c:hugetlb_report_node_meminfo",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "drivers/pci/pci.c:reset_method_show",
        "drivers/pci/pci.c:reset_method_show",
        "drivers/pci/pci-sysfs.c:resource_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/virtio/virtio.c:features_show",
        "drivers/virtio/virtio.c:features_show",
        "drivers/base/core.c:uevent_show",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show",
        "drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_available_governors_get",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584409184,
      "name": "sysfs_emit_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int sysfs_emit_at(char * buf, int at, const char * fmt, void (anon))
```

```json
{
  "name": "sysfs_emit_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584637728,
      "name": "sysfs_emit_at",
      "external": true,
      "loc": "fs/sysfs/file.c:757",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_show_wakelocks",
        "kernel/power/wakelock.c:pm_show_wakelocks",
        "mm/shmem.c:shmem_enabled_show",
        "mm/shmem.c:shmem_enabled_show",
        "mm/shmem.c:shmem_enabled_show",
        "mm/dmapool.c:pools_show",
        "mm/hugetlb.c:hugetlb_report_node_meminfo",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "drivers/pci/pci.c:reset_method_show",
        "drivers/pci/pci.c:reset_method_show",
        "drivers/pci/pci-sysfs.c:resource_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/virtio/virtio.c:features_show",
        "drivers/virtio/virtio.c:features_show",
        "drivers/iommu/iommu.c:iommu_group_show_resv_regions",
        "drivers/base/core.c:uevent_show",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/thermal/thermal_core.c:thermal_build_list_of_policies",
        "drivers/thermal/thermal_core.c:thermal_build_list_of_policies",
        "drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_available_governors_get",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/amd-pstate.c:show_energy_performance_available_preferences",
        "drivers/cpufreq/amd-pstate.c:show_energy_performance_available_preferences",
        "drivers/extcon/extcon.c:state_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637728,
      "name": "sysfs_emit_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int sysfs_emit_at(char * buf, int at, const char * fmt, void (anon))
```

```json
{
  "name": "sysfs_emit_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584869888,
      "name": "sysfs_emit_at",
      "external": true,
      "loc": "fs/sysfs/file.c:770",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_show_wakelocks",
        "kernel/power/wakelock.c:pm_show_wakelocks",
        "mm/shmem.c:shmem_enabled_show",
        "mm/shmem.c:shmem_enabled_show",
        "mm/shmem.c:shmem_enabled_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:slabs_cpu_partial_show",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "mm/slub.c:show_slab_objects",
        "mm/dmapool.c:pools_show",
        "mm/hugetlb.c:hugetlb_report_node_meminfo",
        "drivers/pci/pci.c:reset_method_show",
        "drivers/pci/pci.c:reset_method_show",
        "drivers/pci/pci-sysfs.c:resource_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_nonfatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_fatal_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/pcie/aer.c:aer_dev_correctable_show",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/acpi/fan_attr.c:show_state",
        "drivers/virtio/virtio.c:features_show",
        "drivers/virtio/virtio.c:features_show",
        "drivers/iommu/iommu.c:iommu_group_show_resv_regions",
        "drivers/base/core.c:uevent_show",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpu_modalias",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_distance",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/input/vivaldi-fmap.c:vivaldi_function_row_physmap_show",
        "drivers/input/vivaldi-fmap.c:vivaldi_function_row_physmap_show",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/thermal/thermal_core.c:thermal_build_list_of_policies",
        "drivers/thermal/thermal_core.c:thermal_build_list_of_policies",
        "drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_available_governors_get",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/cpufreq/cpufreq_stats.c:show_trans_table",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "drivers/extcon/extcon.c:state_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584869888,
      "name": "sysfs_emit_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int sysfs_emit_at(char * buf, int at, const char * fmt, void (anon))
```
</details>
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
