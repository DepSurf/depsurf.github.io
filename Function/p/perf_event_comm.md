# Function: <code>perf_event_comm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580434064,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:5905",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580434064,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507008,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:6422",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507008,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571088,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:6520",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571088,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580601376,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:6617",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601376,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580682096,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:6605",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682096,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:6979",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819490,
      "name": "perf_event_comm.cold.131",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580814224,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:6988",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886162,
      "name": "perf_event_comm.cold.131",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580880880,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7070",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983621,
      "name": "perf_event_comm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580977136,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7186",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037631,
      "name": "perf_event_comm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581031264,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581212336,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7638",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581212336,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581255152,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7820",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581255152,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7931",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591265396,
      "name": "perf_event_comm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581272992,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:8055",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188254,
      "name": "perf_event_comm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581514080,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7960",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593963318,
      "name": "perf_event_comm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581860304,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582287360,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:8242",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582287360,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582488512,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:8270",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582488512,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582657232,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:8351",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582657232,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492383320,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7186",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492383320,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226270444,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7186",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226270444,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285641744,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7186",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285641744,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272495634,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7186",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272495634,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7186",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006479,
      "name": "perf_event_comm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581000112,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7186",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952607,
      "name": "perf_event_comm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580946272,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7186",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997679,
      "name": "perf_event_comm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580991312,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void perf_event_comm(struct task_struct * task, bool exec)
```

```json
{
  "name": "perf_event_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_comm",
      "external": true,
      "loc": "kernel/events/core.c:7186",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__set_task_comm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058767,
      "name": "perf_event_comm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581052352,
      "name": "perf_event_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
