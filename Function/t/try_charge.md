# Function: <code>try_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924144,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2025",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924144,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1885
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071792,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:1905",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071792,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1781
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581147168,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:1867",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581147168,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1820
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581192512,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:1878",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192512,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1809
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322560,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:1905",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322560,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1682
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581472576,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:1892",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581472576,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1632
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566720,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2170",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566720,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1882
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678176,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2375",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678176,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2014
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581750112,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2538",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581750112,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2042
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581970384,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2447",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581970384,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1678
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019152,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2709",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019152,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1601
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582045392,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2507",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:obj_cgroup_charge_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582045392,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1859
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
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582366319,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2760",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:charge_memcg"
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
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582864205,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2751",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
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
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583411693,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2821",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
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
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583631965,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2831",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
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
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583826893,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2924",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:mem_cgroup_hugetlb_try_charge",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493204072,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2538",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493204072,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1680
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226834604,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2538",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226834604,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2452
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286709840,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2538",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286709840,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2732
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272981986,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2538",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272981986,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1876
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718848,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2538",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718848,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2042
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657728,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2538",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657728,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2006
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581710160,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2538",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710160,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2042
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
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777664,
      "name": "try_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2538",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777664,
      "name": "try_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2071
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int try_charge(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
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
