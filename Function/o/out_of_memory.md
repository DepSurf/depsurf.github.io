# Function: <code>out_of_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580487648,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:673",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580487648,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580571632,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:989",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571632,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1026
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580637952,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:984",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637952,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580670032,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:994",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670032,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580755088,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1019",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755088,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1254
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1021",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893114,
      "name": "out_of_memory.cold.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071580890064,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1196
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580963908,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1074",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966740,
      "name": "out_of_memory.cold.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071580963792,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1138
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581060784,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1042",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058000,
      "name": "out_of_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
    },
    {
      "addr": 18446744071581061627,
      "name": "out_of_memory.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581060784,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581116560,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1043",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113760,
      "name": "out_of_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
    },
    {
      "addr": 18446744071581117400,
      "name": "out_of_memory.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581116560,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581300384,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1045",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581297856,
      "name": "out_of_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071581301142,
      "name": "out_of_memory.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581300384,
      "name": "out_of_memory",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581344384,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1049",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581341792,
      "name": "out_of_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071591324937,
      "name": "out_of_memory.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581344384,
      "name": "out_of_memory",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581363472,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1048",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361136,
      "name": "out_of_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    },
    {
      "addr": 18446744071591266978,
      "name": "out_of_memory.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581363472,
      "name": "out_of_memory",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1049",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592191080,
      "name": "out_of_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071581611280,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 729
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1107",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_may_oom",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593966478,
      "name": "out_of_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071581971504,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1106",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:lru_gen_age_node",
        "mm/page_alloc.c:__alloc_pages_may_oom",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596024904,
      "name": "out_of_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582405808,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1106",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:lru_gen_age_node",
        "mm/page_alloc.c:__alloc_pages_may_oom",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596547107,
      "name": "out_of_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582611824,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 847
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1104",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:lru_gen_age_node",
        "mm/page_alloc.c:__alloc_pages_may_oom",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597450824,
      "name": "out_of_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582783392,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492481752,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1043",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492481752,
      "name": "out_of_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1044
    },
    {
      "addr": 18446603336492485112,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226358140,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1043",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226358140,
      "name": "out_of_memory",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285767024,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1043",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285767024,
      "name": "out_of_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1548
    },
    {
      "addr": 13835058055285771360,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272549518,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1043",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272549518,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581085408,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1043",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082608,
      "name": "out_of_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
    },
    {
      "addr": 18446744071581086248,
      "name": "out_of_memory.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581085408,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581032592,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1043",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029792,
      "name": "out_of_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
    },
    {
      "addr": 18446744071581033432,
      "name": "out_of_memory.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581032592,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581076608,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1043",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581073808,
      "name": "out_of_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
    },
    {
      "addr": 18446744071581077448,
      "name": "out_of_memory.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581076608,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
bool out_of_memory(struct oom_control * oc)
```

```json
{
  "name": "out_of_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581138464,
      "name": "out_of_memory",
      "external": true,
      "loc": "mm/oom_kill.c:1043",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/tty/sysrq.c:moom_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135536,
      "name": "out_of_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 981
    },
    {
      "addr": 18446744071581139325,
      "name": "out_of_memory.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581138464,
      "name": "out_of_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
