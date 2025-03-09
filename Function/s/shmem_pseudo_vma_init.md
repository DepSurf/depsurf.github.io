# Function: <code>shmem_pseudo_vma_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580676444,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1339",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580743564,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1364",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580771788,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1389",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
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
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580859116,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1412",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995968,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1428",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995968,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077216,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1400",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077216,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140608,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1427",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140608,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581198496,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1442",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198496,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581384853,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1447",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
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
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581428453,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1502",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
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
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581449499,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1476",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
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
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581703819,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1499",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582080400,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1464",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_folio",
        "mm/shmem.c:shmem_alloc_hugefolio",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080400,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582558745,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1483",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_alloc_folio"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugefolio",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555840,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582761120,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1495",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_folio",
        "mm/shmem.c:shmem_alloc_hugefolio",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582761120,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492582480,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1442",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492582480,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226446056,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1442",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_swapin"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285891312,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1442",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285891312,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272616488,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1442",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin"
      ],
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
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581167344,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1442",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581167344,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581114192,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1442",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114192,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581158544,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1442",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158544,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```

```json
{
  "name": "shmem_pseudo_vma_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581225104,
      "name": "shmem_pseudo_vma_init",
      "external": false,
      "loc": "mm/shmem.c:1442",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581225104,
      "name": "shmem_pseudo_vma_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
```
</details>
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
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
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
void shmem_pseudo_vma_init(struct vm_area_struct * vma, struct shmem_inode_info * info, long unsigned int index)
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
