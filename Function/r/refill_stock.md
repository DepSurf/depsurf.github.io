# Function: <code>refill_stock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580925919,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:1935",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581073328,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:1797",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581148748,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:1768",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581194017,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:1779",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322432,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:1797",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322432,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581470000,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:1749",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470000,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581555120,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2027",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555120,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581669856,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2228",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581669856,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742032,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2244",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742032,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581962352,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2121",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962352,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582007840,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2343",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:obj_cgroup_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582007840,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036720,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2152",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036720,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582342608,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2251",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342608,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582833040,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2253",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582833040,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583376720,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2313",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376720,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583596640,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2323",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583596640,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583792336,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2395",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583792336,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493194152,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2244",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493194152,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226827072,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2244",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226827072,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286697056,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2244",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286697056,
      "name": "refill_stock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272975142,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2244",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272975142,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581710768,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2244",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710768,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581649696,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2244",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649696,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581702080,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2244",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702080,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "refill_stock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581769264,
      "name": "refill_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2244",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769264,
      "name": "refill_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void refill_stock(struct mem_cgroup * memcg, unsigned int nr_pages)
```
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
