# Function: <code>try_to_freeze_tasks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687088,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:27",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_processes",
        "kernel/power/process.c:freeze_kernel_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687088,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706240,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:27",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706240,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579733808,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:27",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733808,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579729712,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:30",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579729712,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762720,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762720,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797232,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
    },
    {
      "addr": 18446744071579798474,
      "name": "try_to_freeze_tasks.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843840,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
    },
    {
      "addr": 18446744071579845051,
      "name": "try_to_freeze_tasks.cold.6",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877856,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071579878897,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579928064,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071579929105,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972096,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071579973139,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959888,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071591291206,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962512,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071591234239,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092272,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071592122317,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:28",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229488,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    },
    {
      "addr": 18446744071593891688,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:28",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421472,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
    },
    {
      "addr": 18446744071595983737,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:28",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490832,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1089
    },
    {
      "addr": 18446744071596502153,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:28",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580550720,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1089
    },
    {
      "addr": 18446744071597399839,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491137464,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491137464,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225134540,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225134540,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1016
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284029856,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284029856,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271702686,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271702686,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899712,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071579900753,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835136,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071579836177,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888336,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071579889377,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
int try_to_freeze_tasks(bool user_only)
```

```json
{
  "name": "try_to_freeze_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_to_freeze_tasks",
      "external": false,
      "loc": "kernel/power/process.c:31",
      "file": "kernel/power/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:freeze_kernel_threads",
        "kernel/power/process.c:freeze_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934096,
      "name": "try_to_freeze_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
    },
    {
      "addr": 18446744071579935201,
      "name": "try_to_freeze_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
