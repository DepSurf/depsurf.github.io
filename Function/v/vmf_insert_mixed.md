# Function: <code>vmf_insert_mixed</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581964703,
      "name": "vmf_insert_mixed",
      "external": false,
      "loc": "include/linux/mm.h:2534",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222544,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:1710",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222544,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296208,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:1763",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296208,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581354976,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:1768",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581354976,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581544048,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:1967",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_load_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544048,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581587216,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:2141",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_load_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587216,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581609280,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:2159",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581609280,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581884848,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:2254",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581884848,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275552,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:2347",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275552,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582767952,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:2318",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582767952,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582984208,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:2318",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984208,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583159632,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:2341",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583159632,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492759136,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:1768",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492759136,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226575024,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:1768",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226575024,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286122656,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:1768",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286122656,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272740076,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:1768",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272740076,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323824,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:1768",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323824,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267600,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:1768",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/device.c:dev_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267600,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581315024,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:1768",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581315024,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```

```json
{
  "name": "vmf_insert_mixed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581378976,
      "name": "vmf_insert_mixed",
      "external": true,
      "loc": "mm/memory.c:1768",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378976,
      "name": "vmf_insert_mixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct * vma, long unsigned int addr, pfn_t pfn)
```
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
