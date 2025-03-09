# Function: <code>trace_initcall_level</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578855886,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable"
      ]
    },
    {
      "addr": 18446744071602924175,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603052129,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578855886,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578855909,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable"
      ]
    },
    {
      "addr": 18446744071604722111,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578855909,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856209,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable"
      ]
    },
    {
      "addr": 18446744071604822906,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856209,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856209,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable"
      ]
    },
    {
      "addr": 18446744071604857255,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856209,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578860558,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:do_initcalls"
      ]
    },
    {
      "addr": 18446744071609187855,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860558,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591237613,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:do_initcalls"
      ]
    },
    {
      "addr": 18446744071612254222,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591237613,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591180285,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:do_initcalls"
      ]
    },
    {
      "addr": 18446744071614395757,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591180285,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592036454,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:do_initcalls"
      ]
    },
    {
      "addr": 18446744071615330043,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592036454,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593802184,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:do_initcalls"
      ]
    },
    {
      "addr": 18446744071617113588,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593802184,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627479459,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable",
        "init/main.c:do_initcalls",
        "init/main.c:do_initcalls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627779969,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619222979,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable",
        "init/main.c:do_initcalls",
        "init/main.c:do_initcalls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619542849,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621512691,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable",
        "init/main.c:do_initcalls",
        "init/main.c:do_initcalls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621841745,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490176916,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable"
      ]
    },
    {
      "addr": 18446603336510890564,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490176916,
      "name": "trace_initcall_level",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224385860,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable"
      ]
    },
    {
      "addr": 3243378912,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224385860,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282230560,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable"
      ]
    },
    {
      "addr": 13835058055302524796,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282230560,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271336862,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable"
      ]
    },
    {
      "addr": 18446743936270630462,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271336862,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856209,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable"
      ]
    },
    {
      "addr": 18446744071604762271,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856209,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578849252,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable"
      ]
    },
    {
      "addr": 18446744071604730143,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578849252,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856209,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable"
      ]
    },
    {
      "addr": 18446744071604839899,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856209,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_initcall_level(const char * level)
```

```json
{
  "name": "trace_initcall_level",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856257,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:kernel_init_freeable"
      ]
    },
    {
      "addr": 18446744071604861325,
      "name": "trace_initcall_level",
      "external": false,
      "loc": "include/trace/events/initcall.h:10",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856257,
      "name": "trace_initcall_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void trace_initcall_level(const char * level)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void trace_initcall_level(const char * level)
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
