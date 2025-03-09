# Function: <code>release_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579378736,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:169",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378736,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1115
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391072,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:168",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391072,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1142
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411408,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:177",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411408,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1149
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399200,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:184",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399200,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1059
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579427248,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:184",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427248,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1059
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579445670,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:184",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit"
      ],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579442288,
      "name": "release_task.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071579447424,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579479090,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:185",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit"
      ],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475808,
      "name": "release_task.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1098
    },
    {
      "addr": 18446744071579480880,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493760,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:186",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493760,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1108
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519744,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:191",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519744,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1136
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551136,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:181",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:exit_notify",
        "kernel/exit.c:find_child_reaper",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551136,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532384,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:182",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:exit_notify",
        "kernel/exit.c:find_child_reaper",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532384,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536192,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:182",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:exit_notify",
        "kernel/exit.c:forget_original_parent",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536192,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579608608,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:182",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:exit_notify",
        "kernel/exit.c:forget_original_parent",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608608,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701680,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:186",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:forget_original_parent",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701680,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827184,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:238",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:forget_original_parent",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827184,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876272,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:239",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:forget_original_parent",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876272,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914416,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:242",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:exit_notify",
        "kernel/exit.c:forget_original_parent",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914416,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490658128,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:191",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490658128,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1312
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224733532,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:191",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224733532,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1384
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283481712,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:191",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283481712,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1424
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271402884,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:191",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271402884,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493408,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:191",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493408,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1136
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579422256,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:191",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422256,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1161
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493328,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:191",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493328,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1136
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
void release_task(struct task_struct * p)
```

```json
{
  "name": "release_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525856,
      "name": "release_task",
      "external": true,
      "loc": "kernel/exit.c:191",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525856,
      "name": "release_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1148
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
