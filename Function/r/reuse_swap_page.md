# Function: <code>reuse_swap_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int reuse_swap_page(struct page * page)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764528,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:931",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:handle_mm_fault",
        "mm/huge_memory.c:khugepaged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764528,
      "name": "reuse_swap_page",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool reuse_swap_page(struct page * page, int * total_mapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580887072,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:930",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887072,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool reuse_swap_page(struct page * page, int * total_mapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955168,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:936",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/khugepaged.c:khugepaged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955168,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
bool reuse_swap_page(struct page * page, int * total_mapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581001280,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1345",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581001280,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113216,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1550",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:khugepaged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113216,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581249088,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1550",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249088,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332592,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1544",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332592,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 805
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581442352,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1653",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442352,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581506576,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1653",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506576,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715152,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1690",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715152,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581763072,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1708",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581763072,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790128,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1707",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790128,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074192,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1676",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074192,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492927944,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1653",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492927944,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226715848,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1653",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226715848,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286336704,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1653",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286336704,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272847586,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1653",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272847586,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475312,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1653",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475312,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416720,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1653",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416720,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581466624,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1653",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581466624,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
```

```json
{
  "name": "reuse_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581531376,
      "name": "reuse_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1653",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581531376,
      "name": "reuse_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 868
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * total_mapcount</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * total_map_swapcount</code>
</li>
<li>
<b>Param removed. </b>
<code>int * total_mapcount</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool reuse_swap_page(struct page * page, int * total_map_swapcount)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
