# Function: <code>__next_mem_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __next_mem_range(u64 * idx, int nid, ulong flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587355846,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:884",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:memblock_find_dma_reserve",
        "arch/x86/kernel/e820.c:memblock_find_dma_reserve",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587355846,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void __next_mem_range(u64 * idx, int nid, ulong flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587856642,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:874",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:memblock_find_dma_reserve",
        "arch/x86/kernel/e820.c:memblock_find_dma_reserve",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587856642,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
void __next_mem_range(u64 * idx, int nid, ulong flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588071332,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:874",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:memblock_find_dma_reserve",
        "arch/x86/kernel/e820.c:memblock_find_dma_reserve",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588071332,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
void __next_mem_range(u64 * idx, int nid, ulong flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588297820,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:870",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588297820,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
void __next_mem_range(u64 * idx, int nid, ulong flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588863079,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:870",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588863079,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
void __next_mem_range(u64 * idx, int nid, ulong flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589242124,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:878",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589242124,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589484411,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:991",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589484411,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589945013,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1014",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589945013,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590172556,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1014",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590172556,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591190927,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1022",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/page_alloc.c:init_unavailable_mem",
        "mm/page_alloc.c:init_unavailable_mem",
        "mm/memblock.c:free_low_memory_core_early",
        "mm/memblock.c:free_low_memory_core_early",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:do_one_pass",
        "mm/memtest.c:do_one_pass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591190927,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730064,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:983",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/memblock.c:free_low_memory_core_early",
        "mm/memblock.c:free_low_memory_core_early",
        "mm/memblock.c:free_low_memory_core_early",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:do_one_pass",
        "mm/memtest.c:do_one_pass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730064,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581752512,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:984",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:do_one_pass",
        "mm/memtest.c:do_one_pass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752512,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1019",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:do_one_pass",
        "mm/memtest.c:do_one_pass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592207779,
      "name": "__next_mem_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582033344,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1024",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:do_one_pass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593985414,
      "name": "__next_mem_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071582462128,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1042",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596037890,
      "name": "__next_mem_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071582976048,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1055",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/memblock.c:free_low_memory_core_early",
        "mm/memblock.c:free_low_memory_core_early",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596560115,
      "name": "__next_mem_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071583187904,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1113",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597464522,
      "name": "__next_mem_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071583371744,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492890360,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1014",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492890360,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226687416,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1014",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226687416,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286288928,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1014",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286288928,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270891922,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1014",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270891922,
      "name": "__next_mem_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589774844,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1014",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589774844,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589497667,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1014",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589497667,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590218252,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1014",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590218252,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void __next_mem_range(u64 * idx, int nid, enum memblock_flags flags, struct memblock_type * type_a, struct memblock_type * type_b, phys_addr_t * out_start, phys_addr_t * out_end, int * out_nid)
```

```json
{
  "name": "__next_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590268610,
      "name": "__next_mem_range",
      "external": true,
      "loc": "mm/memblock.c:1014",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memblock.c:memblock_find_in_range_node",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590268610,
      "name": "__next_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>ulong flags</code> ➡️ <code>enum memblock_flags flags</code>
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
