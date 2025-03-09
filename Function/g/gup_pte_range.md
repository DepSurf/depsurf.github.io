# Function: <code>gup_pte_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309200,
      "name": "gup_pte_range",
      "external": false,
      "loc": "arch/x86/mm/gup.c:71",
      "file": "arch/x86/mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309200,
      "name": "gup_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309888,
      "name": "gup_pte_range",
      "external": false,
      "loc": "arch/x86/mm/gup.c:105",
      "file": "arch/x86/mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309888,
      "name": "gup_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579325136,
      "name": "gup_pte_range",
      "external": false,
      "loc": "arch/x86/mm/gup.c:105",
      "file": "arch/x86/mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325136,
      "name": "gup_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580878993,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1279",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast"
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
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580963776,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1368",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
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
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581100643,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1372",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
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
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581178720,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1397",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581248927,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1818",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581307535,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1821",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581499216,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:2219",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581499216,
      "name": "gup_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
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
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581539376,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1997",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581539376,
      "name": "gup_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
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
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581562704,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:2063",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562704,
      "name": "gup_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
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
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827344,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:2151",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827344,
      "name": "gup_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 851
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
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582220288,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:2281",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582220288,
      "name": "gup_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1013
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
int gup_pte_range(pmd_t pmd, pmd_t * pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582709664,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:2328",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582709664,
      "name": "gup_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
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
int gup_pte_range(pmd_t pmd, pmd_t * pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582924608,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:2549",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924608,
      "name": "gup_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
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
int gup_pte_range(pmd_t pmd, pmd_t * pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583098784,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:2567",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583098784,
      "name": "gup_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 869
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
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492716296,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1821",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286057452,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1821",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581276383,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1821",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581222835,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1821",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581267583,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1821",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581331439,
      "name": "gup_pte_range",
      "external": false,
      "loc": "mm/gup.c:1821",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int gup_pte_range(pmd_t pmd, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>pmd_t * pmdp</code>
</li>
<li>
<b>Param reordered. </b>
<code>pmd, addr, end, flags, pages, nr</code> ➡️ <code>pmd, pmdp, addr, end, flags, pages, nr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
