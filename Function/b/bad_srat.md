# Function: <code>bad_srat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595070347,
      "name": "bad_srat",
      "external": false,
      "loc": "arch/x86/mm/srat.c:34",
      "file": "arch/x86/mm/srat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595070347,
      "name": "bad_srat",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595419743,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:215",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595419743,
      "name": "bad_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595670560,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:215",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595670560,
      "name": "bad_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596594155,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:215",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596594155,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602922316,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:217",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602922316,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603094385,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:217",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603094385,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604896519,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:216",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604896519,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605002687,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:203",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605002687,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605040052,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:203",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605040052,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609333272,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:163",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609333272,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612404217,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:198",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612404217,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614546665,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:198",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614546665,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615498851,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:198",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615498851,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617301942,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:198",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617301942,
      "name": "bad_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628021123,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:198",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628020128,
      "name": "bad_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619786579,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:198",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619785584,
      "name": "bad_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622093795,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:198",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622092800,
      "name": "bad_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511120360,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:203",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/acpi_numa.c:acpi_numa_gicc_affinity_init",
        "arch/arm64/kernel/acpi_numa.c:acpi_numa_gicc_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511120360,
      "name": "bad_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604944968,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:203",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604944968,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604912367,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:203",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604912367,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605022640,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:203",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605022640,
      "name": "bad_srat",
      "section": ".init.text",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void bad_srat()
```

```json
{
  "name": "bad_srat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605044232,
      "name": "bad_srat",
      "external": true,
      "loc": "drivers/acpi/numa.c:203",
      "file": "drivers/acpi/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/srat.c:acpi_numa_processor_affinity_init",
        "arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init",
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605044232,
      "name": "bad_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void bad_srat()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void bad_srat()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void bad_srat()
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
