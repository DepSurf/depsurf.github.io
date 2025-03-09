# Function: <code>gup_huge_pud</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gup_huge_pud(pud_t pud, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309536,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "arch/x86/mm/gup.c:193",
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
      "addr": 18446744071579309536,
      "name": "gup_huge_pud",
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
int gup_huge_pud(pud_t pud, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579310688,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "arch/x86/mm/gup.c:246",
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
      "addr": 18446744071579310688,
      "name": "gup_huge_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int gup_huge_pud(pud_t pud, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579325920,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "arch/x86/mm/gup.c:250",
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
      "addr": 18446744071579325920,
      "name": "gup_huge_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580880861,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:1451",
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
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580965938,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:1540",
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
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581102283,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:1563",
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
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581180353,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:1588",
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
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581250448,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2099",
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
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581309056,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2115",
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
int gup_huge_pud(pud_t orig, pud_t * pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581509968,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2514",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509968,
      "name": "gup_huge_pud",
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
int gup_huge_pud(pud_t orig, pud_t * pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581550096,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2292",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550096,
      "name": "gup_huge_pud",
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
int gup_huge_pud(pud_t orig, pud_t * pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581573216,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2358",
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
      "addr": 18446744071581573216,
      "name": "gup_huge_pud",
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
int gup_huge_pud(pud_t orig, pud_t * pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837808,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2453",
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
      "addr": 18446744071581837808,
      "name": "gup_huge_pud",
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
int gup_huge_pud(pud_t orig, pud_t * pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582229872,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2594",
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
      "addr": 18446744071582229872,
      "name": "gup_huge_pud",
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
int gup_huge_pud(pud_t orig, pud_t * pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582720064,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2646",
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
      "addr": 18446744071582720064,
      "name": "gup_huge_pud",
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
int gup_huge_pud(pud_t orig, pud_t * pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582936544,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2890",
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
      "addr": 18446744071582936544,
      "name": "gup_huge_pud",
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
int gup_huge_pud(pud_t orig, pud_t * pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583111776,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2908",
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
      "addr": 18446744071583111776,
      "name": "gup_huge_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
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
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492717200,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2115",
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
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286058048,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2115",
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
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581277904,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2115",
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
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581224148,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2115",
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
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581269104,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2115",
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
  "name": "gup_huge_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581333002,
      "name": "gup_huge_pud",
      "external": false,
      "loc": "mm/gup.c:2115",
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
int gup_huge_pud(pud_t pud, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int gup_huge_pud(pud_t orig, pud_t * pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
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
