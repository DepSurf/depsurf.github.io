# Function: <code>build_inv_dte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584275142,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:707",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_flush_dte"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584618022,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:803",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_flush_dte"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584806662,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:873",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_flush_dte"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584890672,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:931",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584890672,
      "name": "build_inv_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585311872,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:872",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311872,
      "name": "build_inv_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585552544,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:878",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585552544,
      "name": "build_inv_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585678096,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:893",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585678096,
      "name": "build_inv_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585904768,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:881",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585904768,
      "name": "build_inv_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586047760,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:888",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047760,
      "name": "build_inv_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586801678,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:832",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586860846,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:923",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586738419,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:847",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587291667,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:859",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588606897,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:881",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590069515,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:950",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590382771,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:967",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:iommu_flush_dte"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590722483,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1080",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:iommu_flush_dte"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585808736,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:888",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808736,
      "name": "build_inv_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667920,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:888",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667920,
      "name": "build_inv_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585997776,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:888",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585997776,
      "name": "build_inv_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_dte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586105872,
      "name": "build_inv_dte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:888",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586105872,
      "name": "build_inv_dte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
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
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void build_inv_dte(struct iommu_cmd * cmd, u16 devid)
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
