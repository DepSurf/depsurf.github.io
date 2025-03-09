# Function: <code>pudp_set_access_flags</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320272,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:459",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320272,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579343360,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:459",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343360,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579354576,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:464",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354576,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579381712,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:530",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381712,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579397184,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:517",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397184,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400496,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:513",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400496,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409760,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:520",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409760,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410400,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:520",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410400,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413568,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:520",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413568,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579476448,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:520",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476448,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554560,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:520",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554560,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661280,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:524",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661280,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675440,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:524",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675440,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579709568,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:536",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709568,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396400,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:513",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396400,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579325920,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:513",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325920,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396320,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:513",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396320,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```

```json
{
  "name": "pudp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404816,
      "name": "pudp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:513",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404816,
      "name": "pudp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pudp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, pud_t entry, int dirty)
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
