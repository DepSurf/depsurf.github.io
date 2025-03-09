# Function: <code>lookup_swap_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * lookup_swap_cache(swp_entry_t entry)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756576,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:275",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756576,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct page * lookup_swap_cache(swp_entry_t entry)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878816,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:282",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878816,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct page * lookup_swap_cache(swp_entry_t entry)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580946896,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:282",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946896,
      "name": "lookup_swap_cache",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct page * lookup_swap_cache(swp_entry_t entry)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580991520,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:300",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991520,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581095504,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:331",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_readahead_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095504,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236208,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:333",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236208,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319616,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:309",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319616,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581430672,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:310",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581430672,
      "name": "lookup_swap_cache",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581494896,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:310",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581494896,
      "name": "lookup_swap_cache",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581701104,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:309",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581701104,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581748608,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:369",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581748608,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581776400,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:339",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581776400,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:334",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592208946,
      "name": "lookup_swap_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582059232,
      "name": "lookup_swap_cache",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:339",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593987001,
      "name": "lookup_swap_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582496912,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
    }
  ]
}
```
</details>
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
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492914776,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:310",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492914776,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226705984,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:310",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226705984,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286321072,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:310",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286321072,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272837282,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:310",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272837282,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463744,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:310",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463744,
      "name": "lookup_swap_cache",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581405920,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:310",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581405920,
      "name": "lookup_swap_cache",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581454944,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:310",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454944,
      "name": "lookup_swap_cache",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "lookup_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581519392,
      "name": "lookup_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:310",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519392,
      "name": "lookup_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct page * lookup_swap_cache(swp_entry_t entry, struct vm_area_struct * vma, long unsigned int addr)
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
