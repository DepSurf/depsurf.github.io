# Function: <code>gup_pud_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gup_pud_range(pgd_t pgd, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579310176,
      "name": "gup_pud_range",
      "external": false,
      "loc": "arch/x86/mm/gup.c:226",
      "file": "arch/x86/mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/gup.c:__get_user_pages_fast",
        "arch/x86/mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310176,
      "name": "gup_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
int gup_pud_range(pgd_t pgd, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579310960,
      "name": "gup_pud_range",
      "external": false,
      "loc": "arch/x86/mm/gup.c:273",
      "file": "arch/x86/mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/gup.c:get_user_pages_fast",
        "arch/x86/mm/gup.c:__get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310960,
      "name": "gup_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int gup_pud_range(pgd_t pgd, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326176,
      "name": "gup_pud_range",
      "external": false,
      "loc": "arch/x86/mm/gup.c:277",
      "file": "arch/x86/mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/gup.c:get_user_pages_fast",
        "arch/x86/mm/gup.c:__get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326176,
      "name": "gup_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580878993,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:1568",
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
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580963776,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:1657",
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
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581100287,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:1680",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581178288,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:1706",
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
      "addr": 18446744071581178288,
      "name": "gup_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2839
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
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248480,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2220",
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
      "addr": 18446744071581248480,
      "name": "gup_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2884
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
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581307088,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2236",
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
      "addr": 18446744071581307088,
      "name": "gup_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2884
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
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581511840,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2620",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581511840,
      "name": "gup_pud_range.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581551968,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2398",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551968,
      "name": "gup_pud_range.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581574913,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2464",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581839554,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2559",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582231664,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2707",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582722570,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2755",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582938353,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:3014",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583113590,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:3032",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int gup_pud_range(pgd_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492716000,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2236",
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
      "addr": 18446603336492716000,
      "name": "gup_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1824
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
int gup_pud_range(pgd_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286056704,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2236",
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
      "addr": 13835058055286056704,
      "name": "gup_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3524
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
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275936,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2236",
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
      "addr": 18446744071581275936,
      "name": "gup_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2884
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
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222416,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2236",
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
      "addr": 18446744071581222416,
      "name": "gup_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2598
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
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267136,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2236",
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
      "addr": 18446744071581267136,
      "name": "gup_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2884
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
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "gup_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581330992,
      "name": "gup_pud_range",
      "external": false,
      "loc": "mm/gup.c:2236",
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
      "addr": 18446744071581330992,
      "name": "gup_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2918
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int gup_pud_range(pgd_t pgd, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, int write, struct page * * pages, int * nr)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t p4d</code> ➡️ <code>pgd_t p4d</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t p4d</code> ➡️ <code>pgd_t p4d</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
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
