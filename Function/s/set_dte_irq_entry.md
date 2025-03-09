# Function: <code>set_dte_irq_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584290445,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3535",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table"
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
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584621325,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3549",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table"
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
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584806909,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3645",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584897421,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3785",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
```

```json
{
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585311184,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3571",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:get_irq_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311184,
      "name": "set_dte_irq_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585560886,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3598",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry"
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
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585685078,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3663",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry"
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
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585912247,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3644",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
```

```json
{
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586046640,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3680",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046640,
      "name": "set_dte_irq_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586797792,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3096",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797792,
      "name": "set_dte_irq_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586856544,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3187",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586856544,
      "name": "set_dte_irq_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586735856,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2553",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735856,
      "name": "set_dte_irq_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587289024,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2621",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587289024,
      "name": "set_dte_irq_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588602096,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2647",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588602096,
      "name": "set_dte_irq_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590062224,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2810",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590062224,
      "name": "set_dte_irq_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590374096,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2856",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590374096,
      "name": "set_dte_irq_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590715936,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2895",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590715936,
      "name": "set_dte_irq_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
```

```json
{
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585807616,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3680",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585807616,
      "name": "set_dte_irq_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
```

```json
{
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585666800,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3680",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585666800,
      "name": "set_dte_irq_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
```

```json
{
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585996656,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3680",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585996656,
      "name": "set_dte_irq_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
```

```json
{
  "name": "set_dte_irq_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586104688,
      "name": "set_dte_irq_entry",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3680",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586104688,
      "name": "set_dte_irq_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
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
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table * table)
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
