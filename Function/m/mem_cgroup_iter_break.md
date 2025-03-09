# Function: <code>mem_cgroup_iter_break</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580922416,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:995",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_zone",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922416,
      "name": "mem_cgroup_iter_break.part.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071580937056,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581088456,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:879",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068720,
      "name": "mem_cgroup_iter_break.part.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071581084496,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581163453,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:881",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143744,
      "name": "mem_cgroup_iter_break.part.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071581158976,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581211195,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:851",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190896,
      "name": "mem_cgroup_iter_break.part.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071581206720,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581341579,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:865",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319040,
      "name": "mem_cgroup_iter_break.part.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071581337056,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581489069,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:836",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464800,
      "name": "mem_cgroup_iter_break.part.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071581484976,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581574839,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1025",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581549696,
      "name": "mem_cgroup_iter_break.part.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071581570752,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581686094,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1142",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581666128,
      "name": "mem_cgroup_iter_break.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071581682192,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581758974,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1153",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738416,
      "name": "mem_cgroup_iter_break.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071581754592,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581969934,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1118",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581970112,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582018906,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1243",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023536,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055081,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1070",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ],
      "caller_func": [
        "mm/vmscan.c:prealloc_shrinker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582050016,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582362934,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1125",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ],
      "caller_func": [
        "mm/vmscan.c:prealloc_shrinker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356736,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582860339,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1105",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ],
      "caller_func": [
        "mm/vmscan.c:prealloc_shrinker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848144,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583407651,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1185",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_seq_stop",
        "mm/vmscan.c:lru_gen_seq_stop",
        "mm/vmscan.c:__prealloc_shrinker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583394016,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583627996,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1210",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_seq_stop",
        "mm/vmscan.c:lru_gen_seq_stop",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:__prealloc_shrinker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583613296,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583822604,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1261",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_seq_stop",
        "mm/vmscan.c:lru_gen_seq_stop",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/shrinker.c:shrinker_alloc",
        "mm/zswap.c:zswap_pool_destroy",
        "mm/zswap.c:shrink_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583808192,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493212680,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1153",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493191800,
      "name": "mem_cgroup_iter_break.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336493208096,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226843336,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1153",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226823656,
      "name": "mem_cgroup_iter_break.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 3226838820,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286723656,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1153",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286691760,
      "name": "mem_cgroup_iter_break.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 13835058055286716448,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272989310,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1153",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272971856,
      "name": "mem_cgroup_iter_break.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446743936272985444,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581727710,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1153",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707152,
      "name": "mem_cgroup_iter_break.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071581723328,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581666494,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1153",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646144,
      "name": "mem_cgroup_iter_break.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071581662128,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581719022,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1153",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698464,
      "name": "mem_cgroup_iter_break.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071581714640,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup * root, struct mem_cgroup * prev)
```

```json
{
  "name": "mem_cgroup_iter_break",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581786926,
      "name": "mem_cgroup_iter_break",
      "external": true,
      "loc": "mm/memcontrol.c:1153",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581766336,
      "name": "mem_cgroup_iter_break.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071581782192,
      "name": "mem_cgroup_iter_break",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
