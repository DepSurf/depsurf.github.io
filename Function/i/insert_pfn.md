# Function: <code>insert_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580687072,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1519",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687072,
      "name": "insert_pfn.isra.66",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580800480,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1552",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800480,
      "name": "insert_pfn.isra.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580864720,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1548",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864720,
      "name": "insert_pfn.isra.66",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909552,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1678",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909552,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581008224,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1781",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vm_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008224,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
int insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136960,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1792",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vm_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136960,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581221424,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1524",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581221424,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295072,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1577",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295072,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581353840,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1582",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581353840,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581542880,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1745",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542880,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586192,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1919",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586192,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581608400,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1937",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581608400,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883936,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:2032",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883936,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582274560,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:2125",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274560,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582766736,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:2096",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582766736,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582983024,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:2116",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983024,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583158272,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:2139",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158272,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492758280,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1582",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492758280,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226574120,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1582",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226574120,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286121424,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1582",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286121424,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272739362,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1582",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272739362,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322688,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1582",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322688,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266560,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1582",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266560,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581313888,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1582",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581313888,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
vm_fault_t insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
```

```json
{
  "name": "insert_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581377840,
      "name": "insert_pfn",
      "external": false,
      "loc": "mm/memory.c:1582",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377840,
      "name": "insert_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
int insert_pfn(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
