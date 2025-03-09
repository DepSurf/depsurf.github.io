# Function: <code>disable_srat</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_srat()
```

```json
{
  "name": "disable_srat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612404238,
      "name": "disable_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:32",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:bad_srat"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/mm/numa.c:numa_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612404196,
      "name": "disable_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void disable_srat()
```

```json
{
  "name": "disable_srat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614546686,
      "name": "disable_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:32",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:bad_srat"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/mm/numa.c:numa_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614546644,
      "name": "disable_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void disable_srat()
```

```json
{
  "name": "disable_srat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615498872,
      "name": "disable_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:32",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:bad_srat"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/mm/numa.c:numa_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615498830,
      "name": "disable_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void disable_srat()
```

```json
{
  "name": "disable_srat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617301963,
      "name": "disable_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:32",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:bad_srat"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/mm/numa.c:numa_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617301917,
      "name": "disable_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void disable_srat()
```

```json
{
  "name": "disable_srat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628021135,
      "name": "disable_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:32",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/mm/numa.c:numa_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628020080,
      "name": "disable_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void disable_srat()
```

```json
{
  "name": "disable_srat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619786591,
      "name": "disable_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:32",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/mm/numa.c:numa_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619785536,
      "name": "disable_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void disable_srat()
```

```json
{
  "name": "disable_srat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622093807,
      "name": "disable_srat",
      "external": true,
      "loc": "drivers/acpi/numa/srat.c:32",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/mm/numa.c:numa_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622092752,
      "name": "disable_srat",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void disable_srat()
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
