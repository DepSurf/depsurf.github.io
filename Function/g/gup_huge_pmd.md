# Function: <code>gup_huge_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gup_huge_pmd(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309856,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "arch/x86/mm/gup.c:117",
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
      "addr": 18446744071579309856,
      "name": "gup_huge_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int gup_huge_pmd(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309088,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "arch/x86/mm/gup.c:183",
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
      "addr": 18446744071579309088,
      "name": "gup_huge_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
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
int gup_huge_pmd(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579324320,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "arch/x86/mm/gup.c:187",
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
      "addr": 18446744071579324320,
      "name": "gup_huge_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
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
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580880306,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:1413",
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
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580965176,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:1502",
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
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581101534,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:1525",
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
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581179491,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:1550",
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
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581249702,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2058",
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
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581308310,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2073",
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
int gup_huge_pmd(pmd_t orig, pmd_t * pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510672,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2480",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510672,
      "name": "gup_huge_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
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
int gup_huge_pmd(pmd_t orig, pmd_t * pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581550800,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2258",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550800,
      "name": "gup_huge_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
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
int gup_huge_pmd(pmd_t orig, pmd_t * pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581573904,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2324",
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
      "addr": 18446744071581573904,
      "name": "gup_huge_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
int gup_huge_pmd(pmd_t orig, pmd_t * pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581838496,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2419",
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
      "addr": 18446744071581838496,
      "name": "gup_huge_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
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
int gup_huge_pmd(pmd_t orig, pmd_t * pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582230608,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2554",
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
      "addr": 18446744071582230608,
      "name": "gup_huge_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 729
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
int gup_huge_pmd(pmd_t orig, pmd_t * pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582720864,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2606",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582720864,
      "name": "gup_huge_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
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
int gup_huge_pmd(pmd_t orig, pmd_t * pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582937264,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2846",
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
      "addr": 18446744071582937264,
      "name": "gup_huge_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
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
int gup_huge_pmd(pmd_t orig, pmd_t * pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583112496,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2864",
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
      "addr": 18446744071583112496,
      "name": "gup_huge_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
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
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492716596,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2073",
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
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286058424,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2073",
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
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581277158,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2073",
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
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581223274,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2073",
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
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581268358,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2073",
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
  "name": "gup_huge_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581332240,
      "name": "gup_huge_pmd",
      "external": false,
      "loc": "mm/gup.c:2073",
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
int gup_huge_pmd(pmd_t pmd, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int gup_huge_pmd(pmd_t orig, pmd_t * pmdp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
