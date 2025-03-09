# Function: <code>__gup_device_huge</code>

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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580871920,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:1356",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580871920,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963312,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:1445",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963312,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098320,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:1450",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098320,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581178048,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:1475",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581178048,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247968,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:1899",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247968,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581306544,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:1913",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306544,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581509728,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:2313",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509728,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581549840,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:2091",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581549840,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572960,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:2157",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572960,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837520,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:2250",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837520,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582229488,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:2383",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229488,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582719616,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:2429",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582719616,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582936096,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:2664",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582936096,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583111344,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:2682",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583111344,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492716828,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:1913",
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
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286058556,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:1913",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275392,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:1913",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275392,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581221872,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:1913",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581221872,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266592,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:1913",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266592,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```

```json
{
  "name": "__gup_device_huge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581330448,
      "name": "__gup_device_huge",
      "external": false,
      "loc": "mm/gup.c:1913",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330448,
      "name": "__gup_device_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>pfn, addr, end, pages, nr</code> ➡️ <code>pfn, addr, end, flags, pages, nr</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page * * pages, int * nr)
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
