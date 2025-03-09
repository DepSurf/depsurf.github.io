# Function: <code>vmf_insert_pfn_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vmf_insert_pfn_pmd(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmd, long unsigned int pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580900048,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:892",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580900048,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int vmf_insert_pfn_pmd(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmd, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581023760,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:662",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581023760,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int vmf_insert_pfn_pmd(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmd, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098512,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:733",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098512,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
int vmf_insert_pfn_pmd(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmd, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145616,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:758",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145616,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int vmf_insert_pfn_pmd(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmd, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267968,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:758",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267968,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmd, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414544,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:755",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414544,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmd, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498288,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:774",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498288,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581607600,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:810",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581607600,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678496,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:816",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678496,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582576914,
      "name": "vmf_insert_pfn_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:64",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault"
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
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582648219,
      "name": "vmf_insert_pfn_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:55",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault"
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
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582674654,
      "name": "vmf_insert_pfn_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:55",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault"
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
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583002009,
      "name": "vmf_insert_pfn_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:55",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_fault_iter"
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
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583472055,
      "name": "vmf_insert_pfn_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:56",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_fault_iter"
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
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584065407,
      "name": "vmf_insert_pfn_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:56",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_fault_iter"
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583508528,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:897",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_fault_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583508528,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 851
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583705552,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1112",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_fault_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583705552,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493122960,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:816",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493122960,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286600480,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:816",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286600480,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1104
    }
  ]
}
```
</details>
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581647232,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:816",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647232,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586864,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:816",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "drivers/dax/device.c:dev_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586864,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581638544,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:816",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581638544,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
```

```json
{
  "name": "vmf_insert_pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581704880,
      "name": "vmf_insert_pfn_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:816",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581704880,
      "name": "vmf_insert_pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int pfn</code> ➡️ <code>pfn_t pfn</code>
</li>
</ul>
</details>
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault * vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>pmd_t * pmd</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, addr, pmd, pfn, write</code> ➡️ <code>vmf, pfn, write</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault * vmf, pfn_t pfn, bool write)
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
