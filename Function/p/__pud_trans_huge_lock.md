# Function: <code>__pud_trans_huge_lock</code>

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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581156768,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1852",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:zap_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156768,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279392,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1959",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:zap_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279392,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581427904,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1947",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:zap_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581427904,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513680,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1967",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/huge_memory.c:zap_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513680,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581623264,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2025",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/huge_memory.c:zap_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623264,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694128,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2030",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/huge_memory.c:zap_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694128,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911664,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1903",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:zap_huge_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911664,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956864,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1918",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:zap_huge_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956864,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581982896,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1925",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:zap_huge_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581982896,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582284880,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1848",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:zap_huge_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284880,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582769344,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1874",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:zap_huge_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582769344,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583303920,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1973",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:zap_huge_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583303920,
      "name": "__pud_trans_huge_lock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583523232,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1962",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:zap_huge_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583523232,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583717968,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2301",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:zap_huge_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583717968,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493138808,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2030",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493138808,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286623200,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2030",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286623200,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581662864,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2030",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/huge_memory.c:zap_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662864,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581602672,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2030",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/huge_memory.c:zap_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602672,
      "name": "__pud_trans_huge_lock",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581654176,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2030",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/huge_memory.c:zap_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654176,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
```

```json
{
  "name": "__pud_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581720576,
      "name": "__pud_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2030",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/huge_memory.c:zap_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581720576,
      "name": "__pud_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
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
spinlock_t * __pud_trans_huge_lock(pud_t * pud, struct vm_area_struct * vma)
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
