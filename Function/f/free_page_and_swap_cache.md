# Function: <code>free_page_and_swap_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756352,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:248",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:khugepaged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756352,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878496,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:252",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878496,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580946544,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:254",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946544,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580991152,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:272",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991152,
      "name": "free_page_and_swap_cache",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581095088,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:303",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:tlb_remove_table",
        "mm/memory.c:tlb_remove_table_rcu",
        "mm/khugepaged.c:khugepaged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095088,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581235792,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:300",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:tlb_remove_table",
        "mm/memory.c:tlb_remove_table_rcu",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235792,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319200,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:276",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319200,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581430240,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:277",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581430240,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581494464,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:277",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581494464,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581700672,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:276",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu",
        "mm/khugepaged.c:__collapse_huge_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581700672,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581748176,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:336",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581748176,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581775968,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:306",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775968,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059008,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:301",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059008,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582496656,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:306",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582496656,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011072,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:295",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu",
        "mm/huge_memory.c:__split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011072,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583219408,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:300",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu",
        "mm/huge_memory.c:__split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583219408,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583454768,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:300",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu",
        "mm/huge_memory.c:__split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583454768,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492914176,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:277",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492914176,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226705416,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:277",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226705416,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286320256,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:277",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286320256,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272836890,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:277",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272836890,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463312,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:277",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463312,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581405488,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:277",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581405488,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581454512,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:277",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454512,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void free_page_and_swap_cache(struct page * page)
```

```json
{
  "name": "free_page_and_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518960,
      "name": "free_page_and_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:277",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518960,
      "name": "free_page_and_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
