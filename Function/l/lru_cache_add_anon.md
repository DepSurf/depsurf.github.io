# Function: <code>lru_cache_add_anon</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/swap_state.c:__read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540576,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:405",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628672,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:406",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580695872,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580729584,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:417",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mcopy_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729584,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580815584,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:417",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580815584,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952928,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:418",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952928,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029088,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:412",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029088,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093136,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:413",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093136,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581149856,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:414",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149856,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492525976,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:414",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492525976,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226393480,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:414",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226393480,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285820176,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:414",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285820176,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272579860,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:414",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272579860,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118704,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:414",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118704,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065728,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:414",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065728,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581109904,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:414",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109904,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void lru_cache_add_anon(struct page * page)
```

```json
{
  "name": "lru_cache_add_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172304,
      "name": "lru_cache_add_anon",
      "external": true,
      "loc": "mm/swap.c:414",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172304,
      "name": "lru_cache_add_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void lru_cache_add_anon(struct page * page)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void lru_cache_add_anon(struct page * page)
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
