# Function: <code>__inc_zone_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580604992,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:280",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/swap_state.c:__add_to_swap_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604992,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707952,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:335",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707952,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773776,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:335",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773776,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580810224,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:335",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810224,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580899840,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:410",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580899840,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035648,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:410",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035648,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113232,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:410",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113232,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581177888,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:411",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177888,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236000,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:411",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236000,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422608,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:411",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422608,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581465792,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:418",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465792,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581486592,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:424",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486592,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581740272,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:456",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740272,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582121744,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:485",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582121744,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582595712,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:476",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582595712,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582807296,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:477",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807296,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582978448,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:476",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978448,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492630256,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:411",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492630256,
      "name": "__inc_zone_page_state",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226476676,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:411",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226476676,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285947616,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:411",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285947616,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272650614,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:411",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272650614,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581204848,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:411",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581204848,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581151600,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:411",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581151600,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581196048,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:411",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581196048,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "__inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581259328,
      "name": "__inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:411",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259328,
      "name": "__inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
