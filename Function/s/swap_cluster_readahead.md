# Function: <code>swap_cluster_readahead</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237120,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:566",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237120,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581320544,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:528",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581320544,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431632,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:539",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431632,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581495872,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:539",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581495872,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581702752,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:557",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702752,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 781
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581750480,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:649",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581750480,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581778304,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:618",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581778304,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:613",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592209065,
      "name": "swap_cluster_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071582061440,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 769
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:623",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593987132,
      "name": "swap_cluster_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071582499872,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:607",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596039123,
      "name": "swap_cluster_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071583013856,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:622",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596561254,
      "name": "swap_cluster_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071583222592,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
struct folio * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct mempolicy * mpol, long unsigned int ilx)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:634",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597466866,
      "name": "swap_cluster_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071583457952,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492916096,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:539",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492916096,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226707028,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:539",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226707028,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286322768,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:539",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286322768,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 976
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272838210,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:539",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272838210,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464720,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:498",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464720,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 599
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581406896,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:539",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406896,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455920,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:539",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455920,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swap_cluster_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581520352,
      "name": "swap_cluster_readahead",
      "external": true,
      "loc": "mm/swap_state.c:539",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581520352,
      "name": "swap_cluster_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct page * swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mempolicy * mpol</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int ilx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_fault * vmf</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct page *</code> ➡️ <code>struct folio *</code>
</li>
</ul>
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
