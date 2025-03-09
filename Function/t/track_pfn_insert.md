# Function: <code>track_pfn_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, long unsigned int pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579306640,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:951",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_pfn",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306640,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579306064,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:975",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306064,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579321568,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:989",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321568,
      "name": "track_pfn_insert",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579318864,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:986",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318864,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579341840,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:1008",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vm_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341840,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579352288,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:1024",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vm_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579352288,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579379280,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:1033",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379280,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394752,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:1034",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394752,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398064,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:1034",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398064,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436688,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:1061",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436688,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435920,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:1061",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435920,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438848,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:1063",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438848,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:1068",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592089684,
      "name": "track_pfn_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579503216,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:1076",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593856628,
      "name": "track_pfn_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579585120,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:1029",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595970415,
      "name": "track_pfn_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579695152,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:1029",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596487998,
      "name": "track_pfn_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579708944,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:1029",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597384620,
      "name": "track_pfn_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579743648,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
  "name": "track_pfn_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "track_pfn_insert",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:816",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "track_pfn_insert",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:816",
      "file": "mm/huge_memory.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "track_pfn_insert",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:816",
      "file": "mm/memory.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "track_pfn_insert",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:816",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "track_pfn_insert",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:816",
      "file": "mm/huge_memory.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "track_pfn_insert",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:816",
      "file": "mm/memory.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579393968,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:1034",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393968,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579323696,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:1034",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323696,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579393888,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:1034",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393888,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```

```json
{
  "name": "track_pfn_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402416,
      "name": "track_pfn_insert",
      "external": true,
      "loc": "arch/x86/mm/pat.c:1034",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402416,
      "name": "track_pfn_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void track_pfn_insert(struct vm_area_struct * vma, pgprot_t * prot, pfn_t pfn)
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
