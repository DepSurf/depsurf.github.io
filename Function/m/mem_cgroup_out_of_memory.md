# Function: <code>mem_cgroup_out_of_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936304,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1335",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936304,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581083344,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1198",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581083344,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581138528,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1236",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581138528,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581185904,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1228",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581185904,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581315056,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1242",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581315056,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581461440,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1199",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461440,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581545456,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1380",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545456,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581663152,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1572",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581663152,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581735456,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1588",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735456,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581951024,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1553",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951024,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582006336,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1736",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582006336,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031296,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1559",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031296,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1611",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582327376,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071592224662,
      "name": "mem_cgroup_out_of_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1628",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582823408,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071594003824,
      "name": "mem_cgroup_out_of_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1688",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375408,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
    },
    {
      "addr": 18446744071596048674,
      "name": "mem_cgroup_out_of_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1722",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583594880,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
    },
    {
      "addr": 18446744071596571148,
      "name": "mem_cgroup_out_of_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1794",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790784,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
    },
    {
      "addr": 18446744071597475616,
      "name": "mem_cgroup_out_of_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493184424,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1588",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493184424,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226820448,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1588",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226820448,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286686752,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1588",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286686752,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272968844,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1588",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272968844,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581704192,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1588",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581704192,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581643408,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1588",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643408,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695504,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1588",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695504,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
bool mem_cgroup_out_of_memory(struct mem_cgroup * memcg, gfp_t gfp_mask, int order)
```

```json
{
  "name": "mem_cgroup_out_of_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581763328,
      "name": "mem_cgroup_out_of_memory",
      "external": false,
      "loc": "mm/memcontrol.c:1588",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581763328,
      "name": "mem_cgroup_out_of_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
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
