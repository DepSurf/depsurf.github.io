# Function: <code>arch_register_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579065248,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579065248,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579061648,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061648,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579060896,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579060896,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579052752,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052752,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579061760,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061760,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579066240,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066240,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579070832,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579070832,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579079552,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579079552,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579081552,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081552,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579092720,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:97",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092720,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579093904,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:99",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579093904,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100288,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:99",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100288,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579124048,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:99",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579124048,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579157248,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:99",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579157248,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206720,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:99",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206720,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int arch_register_cpu(int cpu)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619325851,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:41",
      "file": "arch/x86/kernel/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211232,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int arch_register_cpu(int cpu)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590995088,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "drivers/base/cpu.c:535",
      "file": "drivers/base/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/base/cpu.c:cpu_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590995088,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 101
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
int arch_register_cpu(int cpu)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "drivers/acpi/acpi_processor.c:176",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497426824,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579081904,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081904,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579014592,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579014592,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579081488,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081488,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int arch_register_cpu(int num)
```

```json
{
  "name": "arch_register_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085584,
      "name": "arch_register_cpu",
      "external": true,
      "loc": "arch/x86/kernel/topology.c:107",
      "file": "arch/x86/kernel/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_arch_register_cpu",
        "arch/x86/kernel/topology.c:topology_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085584,
      "name": "arch_register_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>int num</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>int num</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int arch_register_cpu(int num)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int arch_register_cpu(int num)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int arch_register_cpu(int num)
```
</details>
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
