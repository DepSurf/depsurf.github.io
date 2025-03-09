# Function: <code>iommu_flush_dte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584275136,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:915",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584275136,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618016,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1011",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618016,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584806656,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1100",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584806656,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584897152,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1159",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584897152,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585317984,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1100",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585317984,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585560978,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1106",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585685170,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1121",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585912336,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1109",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586055424,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1116",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055648,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586801678,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1060",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586799744,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586860846,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1150",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586859104,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586738419,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1082",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586738000,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587291667,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1094",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587291248,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588606897,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1116",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588605008,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590069515,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1185",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590382720,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1202",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590382720,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590722432,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1291",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590722432,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585816400,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1116",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585816624,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585675584,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1116",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585675808,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586005440,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1116",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586005664,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_dte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586113728,
      "name": "iommu_flush_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1116",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586113952,
      "name": "iommu_flush_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```
</details>
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
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int iommu_flush_dte(struct amd_iommu * iommu, u16 devid)
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
