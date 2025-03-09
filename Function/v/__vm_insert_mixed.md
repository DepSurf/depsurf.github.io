# Function: <code>__vm_insert_mixed</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580910208,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1797",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_mixed_mkwrite",
        "mm/memory.c:vm_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910208,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581008896,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1914",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_mixed_mkwrite",
        "mm/memory.c:vm_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008896,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581137760,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1928",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vm_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137760,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222304,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1664",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222304,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295968,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1717",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295968,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581354736,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1722",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581354736,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t pgprot, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543792,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1888",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed",
        "mm/memory.c:vmf_insert_mixed_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543792,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t pgprot, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586960,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:2062",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed",
        "mm/memory.c:vmf_insert_mixed_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586960,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t pgprot, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581609024,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:2080",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed",
        "mm/memory.c:vmf_insert_mixed_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581609024,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t pgprot, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581884592,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:2175",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed",
        "mm/memory.c:vmf_insert_mixed_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581884592,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t pgprot, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275248,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:2268",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed",
        "mm/memory.c:vmf_insert_mixed_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275248,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, pgprot_t pgprot, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582767616,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:2239",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed",
        "mm/memory.c:vmf_insert_mixed_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582767616,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582983936,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:2272",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983936,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583159360,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:2295",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583159360,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492758952,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1722",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492758952,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226574764,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1722",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226574764,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286122496,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1722",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286122496,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272739936,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1722",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272739936,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323584,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1722",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323584,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267360,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1722",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267360,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314784,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1722",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314784,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
```

```json
{
  "name": "__vm_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581378736,
      "name": "__vm_insert_mixed",
      "external": false,
      "loc": "mm/memory.c:1722",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vmf_insert_mixed_mkwrite",
        "mm/memory.c:vmf_insert_mixed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378736,
      "name": "__vm_insert_mixed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int __vm_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn, bool mkwrite)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgprot_t pgprot</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, addr, pfn, mkwrite</code> ➡️ <code>vma, addr, pfn, pgprot, mkwrite</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pgprot_t pgprot</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, addr, pfn, pgprot, mkwrite</code> ➡️ <code>vma, addr, pfn, mkwrite</code>
</li>
</ul>
</details>
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
