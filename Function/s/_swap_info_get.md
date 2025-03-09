# Function: <code>_swap_info_get</code>

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
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993456,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1031",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993456,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099184,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1066",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099184,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1066",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581239872,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071581263583,
      "name": "_swap_info_get.cold.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1096",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323296,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071581346751,
      "name": "_swap_info_get.cold.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1133",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434496,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071581457003,
      "name": "_swap_info_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1133",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498736,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071581521163,
      "name": "_swap_info_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1169",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:page_trans_huge_map_swapcount",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581704496,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071581728703,
      "name": "_swap_info_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1185",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:page_trans_huge_map_swapcount",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752224,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071591331552,
      "name": "_swap_info_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1184",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:page_trans_huge_map_swapcount",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779632,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071591274171,
      "name": "_swap_info_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1153",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:page_trans_huge_map_swapcount",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063088,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071592209194,
      "name": "_swap_info_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1128",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:try_to_free_swap",
        "mm/swapfile.c:try_to_free_swap",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582501760,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071593987260,
      "name": "_swap_info_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583016272,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1132",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:folio_free_swap",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016272,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583224976,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1132",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:folio_free_swap",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583224976,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583460352,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1132",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:folio_free_swap",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583460352,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492919712,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1133",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492919712,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226709788,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1133",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226709788,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286327040,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1133",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286327040,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272840528,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1133",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272840528,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1133",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467472,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071581489899,
      "name": "_swap_info_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1133",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409728,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071581432155,
      "name": "_swap_info_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1133",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458784,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071581481211,
      "name": "_swap_info_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
```

```json
{
  "name": "_swap_info_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_swap_info_get",
      "external": false,
      "loc": "mm/swapfile.c:1133",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:split_swap_cluster",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:swap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581523216,
      "name": "_swap_info_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071581545963,
      "name": "_swap_info_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct swap_info_struct * _swap_info_get(swp_entry_t entry)
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
