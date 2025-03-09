# Function: <code>get_irq_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_remap_table * get_irq_table(u16 devid, bool ioapic)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290288,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3551",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290288,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
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
struct irq_remap_table * get_irq_table(u16 devid, bool ioapic)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584621168,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3565",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621168,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 869
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
struct irq_remap_table * get_irq_table(u16 devid, bool ioapic)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584806752,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3659",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584806752,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
struct irq_remap_table * get_irq_table(u16 devid, bool ioapic)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584897264,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3799",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584897264,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 767
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
struct irq_remap_table * get_irq_table(u16 devid, bool ioapic)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585318096,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3585",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585318096,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585554400,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3612",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585554400,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585679504,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3677",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679504,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585906144,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3658",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585906144,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586049136,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3694",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586049136,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586797120,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3110",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797120,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586855664,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3201",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855664,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586735280,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2567",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735280,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2635",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288272,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071592467552,
      "name": "get_irq_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2661",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588600976,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071594337638,
      "name": "get_irq_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2826",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590061968,
      "name": "get_irq_table.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071596240146,
      "name": "get_irq_table.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2872",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590373872,
      "name": "get_irq_table.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071596768242,
      "name": "get_irq_table.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2911",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:free_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590715360,
      "name": "get_irq_table.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071597676863,
      "name": "get_irq_table.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585810112,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3694",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810112,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585669296,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3694",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669296,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585999152,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3694",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585999152,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct irq_remap_table * get_irq_table(u16 devid)
```

```json
{
  "name": "get_irq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586107344,
      "name": "get_irq_table",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3694",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586107344,
      "name": "get_irq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool ioapic</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct irq_remap_table * get_irq_table(u16 devid)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct irq_remap_table * get_irq_table(u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct irq_remap_table * get_irq_table(u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct irq_remap_table * get_irq_table(u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct irq_remap_table * get_irq_table(u16 devid)
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
