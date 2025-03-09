# Function: <code>__split_huge_pmd_locked</code>

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
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581032148,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:1505",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
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
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581107443,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:1629",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146112,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:1951",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146112,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1750
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581280373,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2070",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
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
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581428839,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2058",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581500624,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2078",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500624,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2479
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581610272,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2135",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581610272,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2506
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681184,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2140",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681184,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2506
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899696,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2013",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899696,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2415
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581945232,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2028",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945232,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2296
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581971152,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2035",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971152,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2548
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582273792,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:1958",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582273792,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2519
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582756656,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:1984",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582756656,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3313
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2078",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290672,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2826
    },
    {
      "addr": 18446744071596047108,
      "name": "__split_huge_pmd_locked.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2074",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583509408,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3356
    },
    {
      "addr": 18446744071596569648,
      "name": "__split_huge_pmd_locked.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2409",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699968,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2675
    },
    {
      "addr": 18446744071597473987,
      "name": "__split_huge_pmd_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493128688,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2140",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493128688,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1800
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286603504,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2140",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286603504,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3112
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581649920,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2140",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649920,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2506
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588720,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2140",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588720,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2140
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581641232,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2140",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581641232,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2506
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```

```json
{
  "name": "__split_huge_pmd_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581707616,
      "name": "__split_huge_pmd_locked",
      "external": false,
      "loc": "mm/huge_memory.c:2140",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707616,
      "name": "__split_huge_pmd_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2506
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
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
void __split_huge_pmd_locked(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int haddr, bool freeze)
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
