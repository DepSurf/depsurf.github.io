# Function: <code>try_to_free_mem_cgroup_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580570128,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:2900",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_resize_limit",
        "mm/memcontrol.c:mem_cgroup_resize_memsw_limit",
        "mm/memcontrol.c:mem_cgroup_handle_over_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580570128,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580662992,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3017",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662992,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580730256,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3026",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580730256,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766064,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3093",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766064,
      "name": "try_to_free_mem_cgroup_pages",
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580853408,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3117",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580853408,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990560,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3126",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990560,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581067552,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3303",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581067552,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581130720,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3263",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130720,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188464,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3349",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188464,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581378400,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3323",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378400,
      "name": "try_to_free_mem_cgroup_pages",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422080,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3327",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422080,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581443344,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3525",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581443344,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581697376,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3682",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697376,
      "name": "try_to_free_mem_cgroup_pages",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582072640,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3825",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582072640,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 565
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, unsigned int reclaim_options)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582547936,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:6761",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582547936,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, unsigned int reclaim_options)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582753472,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:7124",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753472,
      "name": "try_to_free_mem_cgroup_pages",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, unsigned int reclaim_options)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582921696,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:6491",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:reclaim_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582921696,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492569472,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3349",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492569472,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226432608,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3349",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226432608,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285878160,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3349",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285878160,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272612308,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3349",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272612308,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157312,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3349",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157312,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581104176,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3349",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104176,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581148512,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3349",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581148512,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup * memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap)
```

```json
{
  "name": "try_to_free_mem_cgroup_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581211120,
      "name": "try_to_free_mem_cgroup_pages",
      "external": true,
      "loc": "mm/vmscan.c:3349",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581211120,
      "name": "try_to_free_mem_cgroup_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int reclaim_options</code>
</li>
<li>
<b>Param removed. </b>
<code>bool may_swap</code>
</li>
</ul>
</details>
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
