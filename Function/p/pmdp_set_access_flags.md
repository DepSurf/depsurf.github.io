# Function: <code>pmdp_set_access_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579307904,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:424",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307904,
      "name": "pmdp_set_access_flags",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579307712,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:428",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307712,
      "name": "pmdp_set_access_flags",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322944,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:428",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322944,
      "name": "pmdp_set_access_flags",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320208,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:438",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320208,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579343296,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:438",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343296,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579354512,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:443",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354512,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579381632,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:509",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381632,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579397104,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:496",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397104,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400416,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:492",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400416,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409664,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:499",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409664,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410304,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:499",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410304,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413472,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:499",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:follow_devmap_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413472,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579476352,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:499",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476352,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554432,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:499",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554432,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661120,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:503",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661120,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675280,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:503",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675280,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579709408,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:515",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709408,
      "name": "pmdp_set_access_flags",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493140600,
      "name": "pmdp_set_access_flags",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:681",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282755872,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/powerpc/mm/book3s64/pgtable.c:35",
      "file": "arch/powerpc/mm/book3s64/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282755872,
      "name": "pmdp_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396320,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:492",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396320,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579325872,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:492",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325872,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396240,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:492",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396240,
      "name": "pmdp_set_access_flags",
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```

```json
{
  "name": "pmdp_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404736,
      "name": "pmdp_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:492",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404736,
      "name": "pmdp_set_access_flags",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
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
int pmdp_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp, pmd_t entry, int dirty)
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
