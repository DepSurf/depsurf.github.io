# Function: <code>task_will_free_mem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580486132,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "include/linux/oom.h:105",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580936425,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "include/linux/oom.h:105",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580570288,
      "name": "task_will_free_mem",
      "external": true,
      "loc": "mm/oom_kill.c:763",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580570288,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635040,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:760",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635040,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580664944,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:765",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664944,
      "name": "task_will_free_mem",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749936,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:789",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749936,
      "name": "task_will_free_mem",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580885664,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:791",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885664,
      "name": "task_will_free_mem",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580958992,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:799",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580958992,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054176,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:809",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054176,
      "name": "task_will_free_mem",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581109872,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:809",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109872,
      "name": "task_will_free_mem",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293056,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:811",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293056,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581337216,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:813",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337216,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356656,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:812",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356656,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581604512,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:813",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581604512,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581964672,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:870",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964672,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582399216,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:869",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582399216,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582605248,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:869",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582605248,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582776704,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:866",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582776704,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492474840,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:809",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492474840,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226351860,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:809",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226351860,
      "name": "task_will_free_mem",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285761440,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:809",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285761440,
      "name": "task_will_free_mem",
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272543746,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:809",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272543746,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581078720,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:809",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078720,
      "name": "task_will_free_mem",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025904,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:809",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025904,
      "name": "task_will_free_mem",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069920,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:809",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069920,
      "name": "task_will_free_mem",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct * task)
```

```json
{
  "name": "task_will_free_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581131472,
      "name": "task_will_free_mem",
      "external": false,
      "loc": "mm/oom_kill.c:809",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131472,
      "name": "task_will_free_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
bool task_will_free_mem(struct task_struct * task)
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
