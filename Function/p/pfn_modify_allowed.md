# Function: <code>pfn_modify_allowed</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579348080,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:251",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vm_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348080,
      "name": "pfn_modify_allowed",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579375024,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:251",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579375024,
      "name": "pfn_modify_allowed",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390512,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390512,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579393824,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393824,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579408000,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408000,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579408480,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408480,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411792,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411792,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592087668,
      "name": "pfn_modify_allowed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579474624,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593854547,
      "name": "pfn_modify_allowed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579552288,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595969332,
      "name": "pfn_modify_allowed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579658992,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_p4d_range",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596486974,
      "name": "pfn_modify_allowed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579673216,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597383596,
      "name": "pfn_modify_allowed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579707104,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
  "name": "pfn_modify_allowed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1131",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1131",
      "file": "mm/mprotect.c",
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
  "name": "pfn_modify_allowed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1131",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1131",
      "file": "mm/mprotect.c",
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
  "name": "pfn_modify_allowed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1131",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1131",
      "file": "mm/mprotect.c",
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
  "name": "pfn_modify_allowed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1131",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pfn_modify_allowed",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1131",
      "file": "mm/mprotect.c",
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389728,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389728,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579319280,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319280,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389648,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389648,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```

```json
{
  "name": "pfn_modify_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398176,
      "name": "pfn_modify_allowed",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398176,
      "name": "pfn_modify_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```
</details>
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot)
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
