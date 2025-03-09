# Function: <code>map_madt_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583574169,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:111",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_core.c:acpi_get_phys_id"
      ],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583896175,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:111",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583896175,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id, bool ignore_disabled)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584035681,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:114",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:__acpi_get_phys_id",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584035681,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584092512,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:111",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092512,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584363920,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:111",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584363920,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584584960,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:111",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584960,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584682368,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:111",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584682368,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584882656,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:112",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584882656,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585018560,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:112",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585018560,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585720400,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:112",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585720400,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585842464,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:109",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585842464,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585720992,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:109",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585720992,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586202800,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:109",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586202800,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587439968,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:109",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587439968,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588699632,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:109",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588699632,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588987728,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:135",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588987728,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589291792,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:159",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589291792,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497428760,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:112",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497428760,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584961024,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:112",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584961024,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584869824,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:112",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584869824,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584970144,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:112",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970144,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```

```json
{
  "name": "map_madt_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585076320,
      "name": "map_madt_entry",
      "external": false,
      "loc": "drivers/acpi/processor_core.c:112",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_core.c:acpi_map_madt_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076320,
      "name": "map_madt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool ignore_disabled</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool ignore_disabled</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt * madt, int type, u32 acpi_id)
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
