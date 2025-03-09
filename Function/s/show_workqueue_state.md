# Function: <code>show_workqueue_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579486848,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4277",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486848,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1152
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499632,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4375",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499632,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1277
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519808,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4405",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519808,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1277
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507872,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4425",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507872,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1299
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579534624,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4452",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534624,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1319
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4530",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566840,
      "name": "show_workqueue_state.cold.49",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
    },
    {
      "addr": 18446744071579561840,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4553",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604024,
      "name": "show_workqueue_state.cold.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
    },
    {
      "addr": 18446744071579599072,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4698",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627819,
      "name": "show_workqueue_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 983
    },
    {
      "addr": 18446744071579622448,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4732",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653516,
      "name": "show_workqueue_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    },
    {
      "addr": 18446744071579648384,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4755",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685175,
      "name": "show_workqueue_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 18446744071579680256,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4768",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591280536,
      "name": "show_workqueue_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 18446744071579660080,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4775",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591223485,
      "name": "show_workqueue_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 18446744071579666128,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4814",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592104726,
      "name": "show_workqueue_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071579742832,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490819488,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4732",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490819488,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1428
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224852904,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4732",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224852904,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1392
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283653008,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4732",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283653008,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1608
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271493990,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4732",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271493990,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1090
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4732",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629820,
      "name": "show_workqueue_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    },
    {
      "addr": 18446744071579624688,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4732",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558172,
      "name": "show_workqueue_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    },
    {
      "addr": 18446744071579553056,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4732",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627100,
      "name": "show_workqueue_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    },
    {
      "addr": 18446744071579621968,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void show_workqueue_state()
```

```json
{
  "name": "show_workqueue_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_workqueue_state",
      "external": true,
      "loc": "kernel/workqueue.c:4732",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/tty/sysrq.c:sysrq_handle_showstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660743,
      "name": "show_workqueue_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    },
    {
      "addr": 18446744071579655632,
      "name": "show_workqueue_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void show_workqueue_state()
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
