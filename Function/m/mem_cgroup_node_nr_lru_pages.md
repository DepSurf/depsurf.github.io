# Function: <code>mem_cgroup_node_nr_lru_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580915572,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:727",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581075638,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": true,
      "loc": "mm/memcontrol.c:625",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages"
      ],
      "caller_func": [
        "mm/workingset.c:count_shadow_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074448,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581149856,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": true,
      "loc": "mm/memcontrol.c:628",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149856,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581196976,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": true,
      "loc": "mm/memcontrol.c:598",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581196976,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326928,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": true,
      "loc": "mm/memcontrol.c:612",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326928,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475040,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": true,
      "loc": "mm/memcontrol.c:583",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475040,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581557440,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": true,
      "loc": "mm/memcontrol.c:721",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557440,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653968,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3601",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653968,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581726496,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3794",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581726496,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask, bool tree)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955600,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3677",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955600,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask, bool tree)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002176,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3937",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002176,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask, bool tree)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028160,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3724",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028160,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask, bool tree)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582329840,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3891",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329840,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask, bool tree)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582830736,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3842",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830736,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask, bool tree)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583373360,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3947",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583373360,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask, bool tree)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583591824,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3974",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583591824,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask, bool tree)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583782160,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:4171",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583782160,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493175896,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3794",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493175896,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286673440,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3794",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286673440,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695232,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3794",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695232,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581634256,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3794",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634256,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581686544,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3794",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686544,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```

```json
{
  "name": "mem_cgroup_node_nr_lru_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581753392,
      "name": "mem_cgroup_node_nr_lru_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3794",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753392,
      "name": "mem_cgroup_node_nr_lru_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool tree</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int mem_cgroup_node_nr_lru_pages(struct mem_cgroup * memcg, int nid, unsigned int lru_mask)
```
</details>
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
