# Function: <code>snapshot_refaults</code>

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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580745328,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:2788",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745328,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580832544,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:2812",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580832544,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580966864,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:2820",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966864,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581043104,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:2987",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581043104,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581109488,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:2952",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109488,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166480,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:3038",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166480,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581375325,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:2991",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581419085,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:2993",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581440320,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:3191",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581693968,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:3352",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
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
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582066308,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:3495",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
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
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582538144,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:6427",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
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
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582747776,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:6790",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
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
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582915712,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:6157",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492540896,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:3038",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492540896,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226410292,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:3038",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226410292,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285846080,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:3038",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285846080,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272593780,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:3038",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272593780,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581135328,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:3038",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135328,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082272,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:3038",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082272,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581126528,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:3038",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126528,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
```

```json
{
  "name": "snapshot_refaults",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189056,
      "name": "snapshot_refaults",
      "external": false,
      "loc": "mm/vmscan.c:3038",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189056,
      "name": "snapshot_refaults",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void snapshot_refaults(struct mem_cgroup * root_memcg, pg_data_t * pgdat)
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
