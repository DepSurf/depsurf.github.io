# Function: <code>dax_iomap_pte_fault</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581642739,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1075",
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
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581788253,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1098",
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
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581961869,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1335",
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
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582044976,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1238",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044976,
      "name": "dax_iomap_pte_fault.isra.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2334
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
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582209328,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1241",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209328,
      "name": "dax_iomap_pte_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2367
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
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582290224,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1245",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582290224,
      "name": "dax_iomap_pte_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2367
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
vm_fault_t dax_iomap_pte_fault(struct vm_fault * vmf, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573744,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1232",
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
      "addr": 18446744071582573744,
      "name": "dax_iomap_pte_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1954
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
vm_fault_t dax_iomap_pte_fault(struct vm_fault * vmf, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582645248,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1247",
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
      "addr": 18446744071582645248,
      "name": "dax_iomap_pte_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1865
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
vm_fault_t dax_iomap_pte_fault(struct vm_fault * vmf, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582675408,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1259",
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
      "addr": 18446744071582675408,
      "name": "dax_iomap_pte_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2151
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
vm_fault_t dax_iomap_pte_fault(struct vm_fault * vmf, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002768,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1424",
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
      "addr": 18446744071583002768,
      "name": "dax_iomap_pte_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
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
vm_fault_t dax_iomap_pte_fault(struct vm_fault * vmf, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583473104,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1384",
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
      "addr": 18446744071583473104,
      "name": "dax_iomap_pte_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1031
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
vm_fault_t dax_iomap_pte_fault(struct vm_fault * vmf, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584065648,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1668",
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
      "addr": 18446744071584065648,
      "name": "dax_iomap_pte_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1028
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
vm_fault_t dax_iomap_pte_fault(struct vm_fault * vmf, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584292032,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1711",
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
      "addr": 18446744071584292032,
      "name": "dax_iomap_pte_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1040
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
vm_fault_t dax_iomap_pte_fault(struct vm_fault * vmf, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584508848,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1697",
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
      "addr": 18446744071584508848,
      "name": "dax_iomap_pte_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1040
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
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493865496,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1245",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493865496,
      "name": "dax_iomap_pte_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2828
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287495840,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1245",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287495840,
      "name": "dax_iomap_pte_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2536
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
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273430222,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1245",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273430222,
      "name": "dax_iomap_pte_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2406
    }
  ]
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
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582258960,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1245",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258960,
      "name": "dax_iomap_pte_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2367
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
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582195904,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1245",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582195904,
      "name": "dax_iomap_pte_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2435
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
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582249440,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1245",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249440,
      "name": "dax_iomap_pte_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2367
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
  "name": "dax_iomap_pte_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582329696,
      "name": "dax_iomap_pte_fault",
      "external": false,
      "loc": "fs/dax.c:1245",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329696,
      "name": "dax_iomap_pte_fault.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2556
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
vm_fault_t dax_iomap_pte_fault(struct vm_fault * vmf, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
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
