# Function: <code>device_offline</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387328,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:1518",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387328,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584722224,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:1518",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584722224,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912016,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2109",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912016,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584997280,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2107",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584997280,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585419168,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2242",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585419168,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585661920,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2289",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661920,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585791600,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2364",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585791600,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586022880,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2618",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586022880,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586170592,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2655",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586170592,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586930688,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:3156",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:remove_cpu",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/core.c:online_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586930688,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587017840,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:3568",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:remove_cpu",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/core.c:online_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587017840,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586901472,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:3795",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:remove_cpu",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/core.c:online_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586901472,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587463152,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:3860",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:remove_cpu",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/core.c:online_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587463152,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588782896,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:3894",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:remove_cpu",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/core.c:online_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588782896,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590277488,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:4113",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:remove_cpu",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/core.c:online_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590277488,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590598048,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:4122",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:remove_cpu",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/core.c:online_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590598048,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590956992,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:4135",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:remove_cpu",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/base/core.c:online_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590956992,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498966640,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2655",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498966640,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231536728,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2655",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231536728,
      "name": "device_offline",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292113344,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2655",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292113344,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276347052,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2655",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276347052,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585930960,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2655",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585930960,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585780096,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2655",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585780096,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586120608,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2655",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586120608,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int device_offline(struct device * dev)
```

```json
{
  "name": "device_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586229216,
      "name": "device_offline",
      "external": true,
      "loc": "drivers/base/core.c:2655",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/core.c:online_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586229216,
      "name": "device_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
