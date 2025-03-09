# Function: <code>unuse_pte_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580762244,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1195",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580884673,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1185",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
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
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580952753,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1205",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
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
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580998114,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1617",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
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
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581109138,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1829",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
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
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581245795,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1829",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581329315,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1801",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446128,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1909",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446128,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510352,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1909",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510352,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718528,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1935",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718528,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1034
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581766432,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1951",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581766432,
      "name": "unuse_pte_range",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793952,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1951",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793952,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1043
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582077856,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1938",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582077856,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1077
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582517584,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1843",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582517584,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1115
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583035984,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1839",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583035984,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 923
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583244656,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1825",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244656,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583479136,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1833",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583479136,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492932416,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1909",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492932416,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1508
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
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226719752,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1909",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286341888,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1909",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286341888,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2160
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272851272,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1909",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272851272,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581479088,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1909",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479088,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581420496,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1909",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420496,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1857
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581470400,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1909",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470400,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
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
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581535184,
      "name": "unuse_pte_range",
      "external": false,
      "loc": "mm/swapfile.c:1909",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535184,
      "name": "unuse_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool frontswap</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * fs_pages_to_unuse</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int unuse_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```
</details>
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
