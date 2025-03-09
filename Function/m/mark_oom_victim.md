# Function: <code>mark_oom_victim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580486176,
      "name": "mark_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:418",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486176,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580569360,
      "name": "mark_oom_victim",
      "external": true,
      "loc": "mm/oom_kill.c:668",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569360,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580634576,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:652",
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
      "addr": 18446744071580634576,
      "name": "mark_oom_victim",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580664000,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:654",
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
      "addr": 18446744071580664000,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749040,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:676",
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
      "addr": 18446744071580749040,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884880,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:678",
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
      "addr": 18446744071580884880,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580958192,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:686",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580958192,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:696",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581053488,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071581061101,
      "name": "mark_oom_victim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581109488,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:696",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109488,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293376,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:698",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293376,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581337552,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:700",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337552,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581355888,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:699",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581355888,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:700",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581603728,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071592190167,
      "name": "mark_oom_victim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:757",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581963408,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071593965600,
      "name": "mark_oom_victim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:758",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582396944,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071596024862,
      "name": "mark_oom_victim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:758",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602816,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071596547065,
      "name": "mark_oom_victim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:755",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582774272,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071597450782,
      "name": "mark_oom_victim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492478744,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:696",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492478744,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226351488,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:696",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226351488,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285760336,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:696",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285760336,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272543514,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:696",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272543514,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581078336,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:696",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078336,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025520,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:696",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025520,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069536,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:696",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069536,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void mark_oom_victim(struct task_struct * tsk)
```

```json
{
  "name": "mark_oom_victim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581131056,
      "name": "mark_oom_victim",
      "external": false,
      "loc": "mm/oom_kill.c:696",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131056,
      "name": "mark_oom_victim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
