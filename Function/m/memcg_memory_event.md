# Function: <code>memcg_memory_event</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580892343,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:729",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580988363,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:729",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492737,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:729",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580961097,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:769",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581065395,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:769",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581578606,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:769",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581057216,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:749",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128518,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:749",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689683,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:749",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657072,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581112914,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581186344,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581763107,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729280,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581296805,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:764",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581370865,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:764",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581982474,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:764",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946896,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581340731,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1035",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581414498,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1035",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582032812,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1035",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993584,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581359223,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1076",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435778,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1076",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582059589,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1076",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020160,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581607076,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1068",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689052,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1068",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582367497,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1068",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high"
      ],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322352,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581967372,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1101",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582062974,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1101",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582865410,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1101",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high"
      ],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815728,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582403452,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1101",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582535593,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1101",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583412893,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1101",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high"
      ],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361312,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582609468,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1117",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739209,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1117",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583633165,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1117",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high"
      ],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583581152,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582780848,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1125",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582906825,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1125",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583828090,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:1125",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:reclaim_high"
      ],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583775072,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492480556,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492567360,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493194552,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493189296,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226354808,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3226429356,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3226848304,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226813764,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285765680,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285875520,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286730640,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286677088,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272546604,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272610138,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272993286,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272962782,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581081762,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581155192,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581731843,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698016,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581028946,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581102056,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581670523,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581637040,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581072962,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146392,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581723155,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689328,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```

```json
{
  "name": "memcg_memory_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581134631,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208952,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581791363,
      "name": "memcg_memory_event",
      "external": false,
      "loc": "include/linux/memcontrol.h:786",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756864,
      "name": "memcg_memory_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void memcg_memory_event(struct mem_cgroup * memcg, enum memcg_memory_event event)
```
</details>
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
