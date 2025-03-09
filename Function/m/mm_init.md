# Function: <code>mm_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594941924,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:482",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579359824,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:593",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_alloc",
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359824,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595105714,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:464",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366976,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:606",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366976,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595351547,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:467",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385072,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:755",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579385072,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596269308,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:494",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372576,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:800",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372576,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602585283,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:496",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399568,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:813",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399568,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602753378,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:513",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413168,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:920",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413168,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604547395,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:513",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579445936,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:975",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445936,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604641484,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:549",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462272,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:992",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462272,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604653745,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:549",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488960,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1008",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488960,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609005184,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:806",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579517216,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1022",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517216,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612069093,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:820",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579499808,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1016",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499808,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 745
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614207238,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:821",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503152,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1022",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503152,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615125600,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:836",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579573920,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1041",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573920,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616887455,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:829",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579666464,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1114",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666464,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627477625,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:834",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786144,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1125",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786144,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 899
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
struct mm_struct * mm_init(struct mm_struct * mm, struct task_struct * p, struct user_namespace * user_ns)
```

```json
{
  "name": "mm_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579833072,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1257",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579833072,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1190
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
struct mm_struct * mm_init(struct mm_struct * mm, struct task_struct * p, struct user_namespace * user_ns)
```

```json
{
  "name": "mm_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870912,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1256",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870912,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1083
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510803656,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:549",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490621840,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1008",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490621840,
      "name": "mm_init",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243249244,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:549",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 3224701536,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1008",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224701536,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302365120,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:549",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283438256,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1008",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283438256,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270601092,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:549",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271379394,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1008",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271379394,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604580017,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:549",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462624,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1008",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462624,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604571729,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:549",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391584,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1008",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391584,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604657841,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:549",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462544,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1008",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462544,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void mm_init()
```

```json
{
  "name": "mm_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604657841,
      "name": "mm_init",
      "external": false,
      "loc": "init/main.c:549",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494960,
      "name": "mm_init",
      "external": false,
      "loc": "kernel/fork.c:1008",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494960,
      "name": "mm_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param added. </b>
<code>struct task_struct * p</code>
</li>
<li>
<b>Param added. </b>
<code>struct user_namespace * user_ns</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct mm_struct *</code>
</li>
</ul>
</details>
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
