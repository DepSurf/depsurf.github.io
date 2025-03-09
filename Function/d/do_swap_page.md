# Function: <code>do_swap_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580677350,
      "name": "do_swap_page",
      "external": false,
      "loc": "mm/memory.c:2446",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int do_swap_page(struct fault_env * fe, pte_t orig_pte)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580785232,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2516",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580785232,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1911
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
int do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849552,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2534",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849552,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1892
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
int do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580894976,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2740",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580894976,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1785
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
int do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992720,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2861",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992720,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2602
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
int do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581127072,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2922",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581127072,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2326
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581206320,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2659",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206320,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2481
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581280736,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2727",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280736,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2535
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581339456,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2752",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339456,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2538
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581537200,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:3100",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581537200,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2039
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580576,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:3263",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580576,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1881
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581601728,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:3354",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581601728,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1903
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581867888,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:3480",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867888,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1930
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582268400,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:3711",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582268400,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2148
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582760048,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:3690",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760048,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2351
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582975616,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:3715",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582975616,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2260
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583170496,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:3796",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583170496,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2566
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492745480,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2752",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492745480,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2268
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226577628,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2752",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226577628,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2052
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286101584,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2752",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286101584,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3196
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272730264,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2752",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272730264,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1678
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308304,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2752",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308304,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2538
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252112,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2752",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252112,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2455
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581299504,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2752",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581299504,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2538
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
vm_fault_t do_swap_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363488,
      "name": "do_swap_page",
      "external": true,
      "loc": "mm/memory.c:2752",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363488,
      "name": "do_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2531
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int do_swap_page(struct fault_env * fe, pte_t orig_pte)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault * vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fault_env * fe</code>
</li>
<li>
<b>Param removed. </b>
<code>pte_t orig_pte</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
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
