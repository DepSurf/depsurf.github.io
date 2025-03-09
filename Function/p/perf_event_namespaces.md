# Function: <code>perf_event_namespaces</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580601348,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:6710",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/nsproxy.c:SyS_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567648,
      "name": "perf_event_namespaces.part.101",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071580601776,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580682068,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:6702",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/nsproxy.c:SyS_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649504,
      "name": "perf_event_namespaces.part.104",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071580682496,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580814196,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7076",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580778896,
      "name": "perf_event_namespaces.part.120",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071580814592,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580880852,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7085",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843616,
      "name": "perf_event_namespaces.part.120",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071580881248,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580977109,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7167",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580939440,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071580977520,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581031237,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7283",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992800,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071581031648,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581212268,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7735",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153872,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071581212464,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581255084,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7917",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194272,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071581255280,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581272924,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:8028",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581213328,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071581273264,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581514012,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:8152",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581453216,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071581514352,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581860227,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:8057",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799392,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071581860592,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582287267,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:8339",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582223344,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071582287680,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582488419,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:8367",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582423520,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071582488656,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582657139,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:8448",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582591168,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071582657376,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492383284,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7283",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__arm64_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492351152,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446603336492383608,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226270412,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7283",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__se_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226229148,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 3226270760,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285641672,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7283",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__se_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285589744,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 13835058055285642176,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272495604,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7283",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__se_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272462032,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446743936272495788,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581000085,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7283",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961600,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071581000496,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580946245,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7283",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907728,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071580946656,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580991285,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7283",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952848,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071580991696,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_namespaces(struct task_struct * task)
```

```json
{
  "name": "perf_event_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581052325,
      "name": "perf_event_namespaces",
      "external": true,
      "loc": "kernel/events/core.c:7283",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_fork"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/events/core.c:perf_event_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581017312,
      "name": "perf_event_namespaces.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071581052736,
      "name": "perf_event_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void perf_event_namespaces(struct task_struct * task)
```
</details>
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
