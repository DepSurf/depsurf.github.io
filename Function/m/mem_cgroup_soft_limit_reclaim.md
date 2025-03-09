# Function: <code>mem_cgroup_soft_limit_reclaim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(struct zone * zone, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580941360,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:2634",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941360,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581088144,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:2567",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071581088144,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163136,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:2540",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071581163136,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 838
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210880,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:2548",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071581210880,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581341264,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:2575",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071581341264,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488784,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:2503",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071581488784,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581574544,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:2777",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071581574544,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581685808,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3012",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071581685808,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 794
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758688,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3221",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071581758688,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 794
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978432,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3104",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978432,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028704,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3409",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028704,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054784,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3245",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071582054784,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 957
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3413",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071592225673,
      "name": "mem_cgroup_soft_limit_reclaim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582362624,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1002
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582860000,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3418",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582860000,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 911
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407312,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3518",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407312,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 911
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583627616,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3529",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583627616,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 851
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583822224,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3721",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583822224,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 851
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493212416,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3221",
      "file": "mm/memcontrol.c",
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
      "addr": 18446603336493212416,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226843060,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3221",
      "file": "mm/memcontrol.c",
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
      "addr": 3226843060,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 944
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286723296,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3221",
      "file": "mm/memcontrol.c",
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
      "addr": 13835058055286723296,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1352
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272989074,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3221",
      "file": "mm/memcontrol.c",
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
      "addr": 18446743936272989074,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581727424,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3221",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071581727424,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 794
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581666208,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3221",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071581666208,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 782
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718736,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3221",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071581718736,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 794
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t * pgdat, int order, gfp_t gfp_mask, long unsigned int * total_scanned)
```

```json
{
  "name": "mem_cgroup_soft_limit_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786640,
      "name": "mem_cgroup_soft_limit_reclaim",
      "external": true,
      "loc": "mm/memcontrol.c:3221",
      "file": "mm/memcontrol.c",
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
      "addr": 18446744071581786640,
      "name": "mem_cgroup_soft_limit_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 822
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>pg_data_t * pgdat</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zone * zone</code>
</li>
</ul>
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
