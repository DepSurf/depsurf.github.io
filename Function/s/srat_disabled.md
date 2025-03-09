# Function: <code>srat_disabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "srat_disabled",
      "external": false,
      "loc": "arch/x86/mm/srat.c:40",
      "file": "arch/x86/mm/srat.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595419771,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:221",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595419771,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 15
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595670588,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:221",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595670588,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 15
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596594188,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:221",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596594188,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602922349,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:223",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602922349,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603094671,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:223",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603094418,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604896805,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:222",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604896552,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605002970,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:209",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/hmat/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605002720,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605040335,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:209",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/hmat/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605040085,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609333555,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:169",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609333305,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612404526,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:204",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612404250,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614546974,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:204",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614546698,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615499229,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:204",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615498884,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617302366,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:204",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617301983,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628020757,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:204",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628020192,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619786213,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:204",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619785648,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622093429,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:204",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622092864,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511120812,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:209",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/arm64/kernel/acpi_numa.c:arm64_acpi_numa_init",
        "arch/arm64/kernel/acpi_numa.c:acpi_numa_gicc_affinity_init",
        "arch/arm64/kernel/acpi_numa.c:acpi_parse_gicc_pxm",
        "drivers/acpi/hmat/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511120408,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604945251,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:209",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/hmat/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604945001,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604912650,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:209",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/hmat/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604912400,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605022923,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:209",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605022673,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int srat_disabled()
```

```json
{
  "name": "srat_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605044515,
      "name": "srat_disabled",
      "external": true,
      "loc": "drivers/acpi/numa.c:209",
      "file": "drivers/acpi/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:x86_acpi_numa_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/hmat/hmat.c:hmat_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605044265,
      "name": "srat_disabled",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int srat_disabled()
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int srat_disabled()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int srat_disabled()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int srat_disabled()
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
