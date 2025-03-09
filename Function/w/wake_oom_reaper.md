# Function: <code>wake_oom_reaper</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580569232,
      "name": "wake_oom_reaper",
      "external": true,
      "loc": "mm/oom_kill.c:630",
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
      "addr": 18446744071580569232,
      "name": "wake_oom_reaper",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580634912,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:607",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634912,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580664400,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:608",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664400,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580753559,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:638",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749424,
      "name": "wake_oom_reaper.part.21",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580888215,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:640",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887280,
      "name": "wake_oom_reaper.part.20",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580960624,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:648",
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
      "addr": 18446744071580960624,
      "name": "wake_oom_reaper",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581055840,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:658",
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
      "addr": 18446744071581055840,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581111536,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:658",
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
      "addr": 18446744071581111536,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581297579,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:660",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294912,
      "name": "wake_oom_reaper.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071581295152,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581341627,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:662",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339072,
      "name": "wake_oom_reaper.part.0",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581358352,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:661",
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
      "addr": 18446744071581358352,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581606208,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:662",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071581606208,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void wake_oom_reaper(struct timer_list * timer)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581965296,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:661",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965296,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void wake_oom_reaper(struct timer_list * timer)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582399872,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:662",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582399872,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
void wake_oom_reaper(struct timer_list * timer)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582605904,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:662",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582605904,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
void wake_oom_reaper(struct timer_list * timer)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582777360,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:659",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582777360,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492478336,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:658",
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
      "addr": 18446603336492478336,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226351220,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:658",
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
      "addr": 3226351220,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285761040,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:658",
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
      "addr": 13835058055285761040,
      "name": "wake_oom_reaper",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272547400,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:658",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272544078,
      "name": "wake_oom_reaper.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581080384,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:658",
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
      "addr": 18446744071581080384,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581027568,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:658",
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
      "addr": 18446744071581027568,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581071584,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:658",
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
      "addr": 18446744071581071584,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```

```json
{
  "name": "wake_oom_reaper",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581131824,
      "name": "wake_oom_reaper",
      "external": false,
      "loc": "mm/oom_kill.c:658",
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
      "addr": 18446744071581131824,
      "name": "wake_oom_reaper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void wake_oom_reaper(struct task_struct * tsk)
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct timer_list * timer</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void wake_oom_reaper(struct task_struct * tsk)
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
