# Function: <code>mem_cgroup_uncharge_swap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943520,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:5674",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swap_entry_free",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943520,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void mem_cgroup_uncharge_swap(swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091376,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:5941",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swap_entry_free",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091376,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void mem_cgroup_uncharge_swap(swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166592,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:5941",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swap_entry_free",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166592,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581214400,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:6006",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214400,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345024,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:6112",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345024,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581492848,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:6187",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581492848,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581578720,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:6518",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578720,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581689888,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:6810",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689888,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581763312,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7140",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581763312,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581982656,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:6997",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581982656,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582032976,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7251",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032976,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059760,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7120",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059760,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582072584,
      "name": "mem_cgroup_uncharge_swap",
      "external": false,
      "loc": "include/linux/swap.h:748",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582367904,
      "name": "mem_cgroup_uncharge_swap",
      "external": false,
      "loc": "include/linux/swap.h:748",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap"
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
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582512595,
      "name": "mem_cgroup_uncharge_swap",
      "external": false,
      "loc": "include/linux/swap.h:663",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582865891,
      "name": "mem_cgroup_uncharge_swap",
      "external": false,
      "loc": "include/linux/swap.h:663",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap"
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
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583031571,
      "name": "mem_cgroup_uncharge_swap",
      "external": false,
      "loc": "include/linux/swap.h:673",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583413291,
      "name": "mem_cgroup_uncharge_swap",
      "external": false,
      "loc": "include/linux/swap.h:673",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap"
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
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583240435,
      "name": "mem_cgroup_uncharge_swap",
      "external": false,
      "loc": "include/linux/swap.h:664",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583633563,
      "name": "mem_cgroup_uncharge_swap",
      "external": false,
      "loc": "include/linux/swap.h:664",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap"
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
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583474963,
      "name": "mem_cgroup_uncharge_swap",
      "external": false,
      "loc": "include/linux/swap.h:655",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583828491,
      "name": "mem_cgroup_uncharge_swap",
      "external": false,
      "loc": "include/linux/swap.h:655",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap"
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493217208,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7140",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493217208,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226848492,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7140",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226848492,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286730896,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7140",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286730896,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272993432,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7140",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272993432,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581732048,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7140",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581732048,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581670720,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7140",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581670720,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581723360,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7140",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723360,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_uncharge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791568,
      "name": "mem_cgroup_uncharge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7140",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791568,
      "name": "mem_cgroup_uncharge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nr_pages</code>
</li>
</ul>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages)
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
