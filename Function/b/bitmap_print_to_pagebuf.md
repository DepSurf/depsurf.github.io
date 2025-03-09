# Function: <code>bitmap_print_to_pagebuf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583012288,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:471",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/rapl.c:rapl_get_attr_cpumask",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012288,
      "name": "bitmap_print_to_pagebuf",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583303152,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:473",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583303152,
      "name": "bitmap_print_to_pagebuf",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583422192,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:473",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422192,
      "name": "bitmap_print_to_pagebuf",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583444160,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:473",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444160,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583624144,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:475",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpumap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583624144,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583839216,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:472",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpumap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583839216,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583923840,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:470",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpumap",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583923840,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584102976,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:470",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:package_cpus_list_show",
        "drivers/base/topology.c:package_cpus_show",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:core_cpus_list_show",
        "drivers/base/topology.c:core_cpus_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpumap",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584102976,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225760,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:490",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:package_cpus_list_show",
        "drivers/base/topology.c:package_cpus_show",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:core_cpus_list_show",
        "drivers/base/topology.c:core_cpus_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpumap",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225760,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584631584,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:478",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpumap",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631584,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584750624,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:478",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/node.c:node_read_cpumap",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584750624,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584778800,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:480",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/node.c:node_read_cpumap",
        "net/core/net-sysfs.c:xps_queue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778800,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585209312,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:480",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "net/core/net-sysfs.c:xps_queue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585209312,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586045520,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:480",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show",
        "net/core/net-sysfs.c:xps_queue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045520,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587028464,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:491",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show",
        "net/core/net-sysfs.c:xps_queue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587028464,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587283616,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:491",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/iommu/intel/perfmon.c:cpumask_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show",
        "net/core/net-sysfs.c:xps_queue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587283616,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587632192,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap-str.c:58",
      "file": "lib/bitmap-str.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/iommu/intel/perfmon.c:cpumask_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show",
        "net/core/net-sysfs.c:xps_queue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587632192,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496099568,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:490",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask",
        "drivers/perf/arm-cci.c:pmu_cpumask_attr_show",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_cpumask_show",
        "drivers/perf/arm_pmu.c:armpmu_cpumask_show",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_cpumask_show",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_cpumask_show",
        "drivers/perf/xgene_pmu.c:xgene_pmu_cpumask_show",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496099568,
      "name": "bitmap_print_to_pagebuf",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229426740,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:490",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_cpumask_show",
        "arch/arm/mach-imx/mmdc.c:mmdc_pmu_cpumask_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/perf/arm-cci.c:pmu_cpumask_attr_show",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_cpumask_show",
        "drivers/perf/arm_pmu.c:armpmu_cpumask_show",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229426740,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290345168,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:490",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/perf/imc-pmu.c:imc_pmu_cpumask_get_attr",
        "arch/powerpc/perf/imc-pmu.c:imc_pmu_cpumask_get_attr",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:package_cpus_list_show",
        "drivers/base/topology.c:package_cpus_show",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:core_cpus_list_show",
        "drivers/base/topology.c:core_cpus_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpumap",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290345168,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275168392,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:490",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275168392,
      "name": "bitmap_print_to_pagebuf",
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194496,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:490",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:package_cpus_list_show",
        "drivers/base/topology.c:package_cpus_show",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:core_cpus_list_show",
        "drivers/base/topology.c:core_cpus_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpumap",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194496,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584129712,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:490",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:package_cpus_list_show",
        "drivers/base/topology.c:package_cpus_show",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:core_cpus_list_show",
        "drivers/base/topology.c:core_cpus_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpumap",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584129712,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584178256,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:490",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:package_cpus_list_show",
        "drivers/base/topology.c:package_cpus_show",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:core_cpus_list_show",
        "drivers/base/topology.c:core_cpus_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpumap",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178256,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int bitmap_print_to_pagebuf(bool list, char * buf, const long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_print_to_pagebuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584282592,
      "name": "bitmap_print_to_pagebuf",
      "external": true,
      "loc": "lib/bitmap.c:490",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask",
        "arch/x86/events/amd/iommu.c:_iommu_cpumask_show",
        "arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask",
        "drivers/pci/pci-sysfs.c:cpulistaffinity_show",
        "drivers/pci/pci-sysfs.c:cpuaffinity_show",
        "drivers/pci/pci-sysfs.c:local_cpulist_show",
        "drivers/pci/pci-sysfs.c:local_cpus_show",
        "drivers/base/cpu.c:show_cpus_attr",
        "drivers/base/topology.c:package_cpus_list_show",
        "drivers/base/topology.c:package_cpus_show",
        "drivers/base/topology.c:die_cpus_list_show",
        "drivers/base/topology.c:die_cpus_show",
        "drivers/base/topology.c:core_siblings_list_show",
        "drivers/base/topology.c:core_siblings_show",
        "drivers/base/topology.c:core_cpus_list_show",
        "drivers/base/topology.c:core_cpus_show",
        "drivers/base/topology.c:thread_siblings_list_show",
        "drivers/base/topology.c:thread_siblings_show",
        "drivers/base/cacheinfo.c:shared_cpu_list_show",
        "drivers/base/cacheinfo.c:shared_cpu_map_show",
        "drivers/base/node.c:node_read_cpumap",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282592,
      "name": "bitmap_print_to_pagebuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
