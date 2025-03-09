# Function: <code>dax_iomap_pmd_fault</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int dax_iomap_pmd_fault(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, unsigned int flags, struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581583600,
      "name": "dax_iomap_pmd_fault",
      "external": true,
      "loc": "fs/dax.c:1324",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/file.c:ext4_dax_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581583600,
      "name": "dax_iomap_pmd_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1918
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581642400,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1306",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581787863,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1317",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581961437,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1542",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582047312,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1445",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582047312,
      "name": "dax_iomap_pmd_fault.isra.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2490
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582211696,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1462",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211696,
      "name": "dax_iomap_pmd_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1854
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582292592,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1466",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582292592,
      "name": "dax_iomap_pmd_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1854
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
vm_fault_t dax_iomap_pmd_fault(struct vm_fault * vmf, pfn_t * pfnp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582577120,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1454",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582577120,
      "name": "dax_iomap_pmd_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1974
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
vm_fault_t dax_iomap_pmd_fault(struct vm_fault * vmf, pfn_t * pfnp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582648432,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1469",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582648432,
      "name": "dax_iomap_pmd_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1784
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
vm_fault_t dax_iomap_pmd_fault(struct vm_fault * vmf, pfn_t * pfnp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582677568,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1481",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582677568,
      "name": "dax_iomap_pmd_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1723
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
vm_fault_t dax_iomap_pmd_fault(struct vm_fault * vmf, pfn_t * pfnp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583003664,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1534",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583003664,
      "name": "dax_iomap_pmd_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1064
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
vm_fault_t dax_iomap_pmd_fault(struct vm_fault * vmf, pfn_t * pfnp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583474144,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1494",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474144,
      "name": "dax_iomap_pmd_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
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
vm_fault_t dax_iomap_pmd_fault(struct vm_fault * vmf, pfn_t * pfnp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584066704,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1778",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584066704,
      "name": "dax_iomap_pmd_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
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
vm_fault_t dax_iomap_pmd_fault(struct vm_fault * vmf, pfn_t * pfnp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584293088,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1821",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293088,
      "name": "dax_iomap_pmd_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1149
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
vm_fault_t dax_iomap_pmd_fault(struct vm_fault * vmf, pfn_t * pfnp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584509904,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1807",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584509904,
      "name": "dax_iomap_pmd_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1149
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1626",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287498384,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1466",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287498384,
      "name": "dax_iomap_pmd_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1626",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582261328,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1466",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261328,
      "name": "dax_iomap_pmd_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1854
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582198352,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1466",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582198352,
      "name": "dax_iomap_pmd_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2594
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582251808,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1466",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582251808,
      "name": "dax_iomap_pmd_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1854
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pmd_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582327024,
      "name": "dax_iomap_pmd_fault",
      "external": false,
      "loc": "fs/dax.c:1466",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582327024,
      "name": "dax_iomap_pmd_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2657
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int dax_iomap_pmd_fault(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, unsigned int flags, struct iomap_ops * ops)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int dax_iomap_pmd_fault(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, unsigned int flags, struct iomap_ops * ops)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
vm_fault_t dax_iomap_pmd_fault(struct vm_fault * vmf, pfn_t * pfnp, const struct iomap_ops * ops)
```
</details>
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
