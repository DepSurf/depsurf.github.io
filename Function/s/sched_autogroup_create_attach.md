# Function: <code>sched_autogroup_create_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650784,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/auto_group.c:153",
      "file": "kernel/sched/auto_group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650784,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666336,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/auto_group.c:153",
      "file": "kernel/sched/auto_group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666336,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579690896,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/auto_group.c:173",
      "file": "kernel/sched/auto_group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690896,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687744,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:173",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687744,
      "name": "sched_autogroup_create_attach",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718592,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:173",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718592,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752695,
      "name": "sched_autogroup_create_attach.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579751344,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795559,
      "name": "sched_autogroup_create_attach.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579794176,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824103,
      "name": "sched_autogroup_create_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579822704,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872407,
      "name": "sched_autogroup_create_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579870832,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914727,
      "name": "sched_autogroup_create_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579912784,
      "name": "sched_autogroup_create_attach",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591284415,
      "name": "sched_autogroup_create_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579906256,
      "name": "sched_autogroup_create_attach",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591227435,
      "name": "sched_autogroup_create_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579915280,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592114167,
      "name": "sched_autogroup_create_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580037248,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:192",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593885465,
      "name": "sched_autogroup_create_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580175616,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580356848,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:193",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356848,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580424432,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:193",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424432,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580484000,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:193",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484000,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491069568,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491069568,
      "name": "sched_autogroup_create_attach",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225073964,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225073964,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283950592,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283950592,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271659908,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271659908,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579844551,
      "name": "sched_autogroup_create_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579843152,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579779495,
      "name": "sched_autogroup_create_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579777920,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579832775,
      "name": "sched_autogroup_create_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579831200,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void sched_autogroup_create_attach(struct task_struct * p)
```

```json
{
  "name": "sched_autogroup_create_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_autogroup_create_attach",
      "external": true,
      "loc": "kernel/sched/autogroup.c:170",
      "file": "kernel/sched/autogroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877799,
      "name": "sched_autogroup_create_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579876400,
      "name": "sched_autogroup_create_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
