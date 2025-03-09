# Function: <code>set_task_reclaim_state</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581106736,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:241",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106736,
      "name": "set_task_reclaim_state",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163728,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:174",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163728,
      "name": "set_task_reclaim_state",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581349728,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:179",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581349728,
      "name": "set_task_reclaim_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393136,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:172",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393136,
      "name": "set_task_reclaim_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412848,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:175",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412848,
      "name": "set_task_reclaim_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581690971,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:179",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
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
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582067550,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:181",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
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
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582539692,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:195",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:lru_gen_seq_write",
        "mm/vmscan.c:lru_gen_seq_write"
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
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582749305,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:508",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:lru_gen_seq_write",
        "mm/vmscan.c:lru_gen_seq_write"
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
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582917246,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:247",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:lru_gen_seq_write",
        "mm/vmscan.c:lru_gen_seq_write"
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
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492539544,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:174",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492539544,
      "name": "set_task_reclaim_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226407700,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:174",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226407700,
      "name": "set_task_reclaim_state",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285841552,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:174",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285841552,
      "name": "set_task_reclaim_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272591086,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:174",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272591086,
      "name": "set_task_reclaim_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581132576,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:174",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132576,
      "name": "set_task_reclaim_state",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581079520,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:174",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581079520,
      "name": "set_task_reclaim_state",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123776,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:174",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123776,
      "name": "set_task_reclaim_state",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
```

```json
{
  "name": "set_task_reclaim_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581186224,
      "name": "set_task_reclaim_state",
      "external": false,
      "loc": "mm/vmscan.c:174",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:shrink_all_memory",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581186224,
      "name": "set_task_reclaim_state",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void set_task_reclaim_state(struct task_struct * task, struct reclaim_state * rs)
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
