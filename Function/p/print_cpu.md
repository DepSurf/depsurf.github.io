# Function: <code>print_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657696,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:267",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sched_debug_show",
        "kernel/sched/debug.c:sysrq_sched_debug_show"
      ]
    },
    {
      "addr": 18446744071579865008,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:143",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657696,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3490
    },
    {
      "addr": 18446744071579865008,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673904,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:577",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071579894320,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:143",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673904,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3552
    },
    {
      "addr": 18446744071579894320,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698528,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:583",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071579906000,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:143",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698528,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3540
    },
    {
      "addr": 18446744071579906000,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579694544,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:597",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071579914160,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:137",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694544,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3335
    },
    {
      "addr": 18446744071579914160,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579725600,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:647",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071579959568,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:137",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725600,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3426
    },
    {
      "addr": 18446744071579959568,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:628",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580007200,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:135",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757040,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2166
    },
    {
      "addr": 18446744071579768865,
      "name": "print_cpu.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1462
    },
    {
      "addr": 18446744071580007200,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:627",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580054224,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:130",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579799920,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2166
    },
    {
      "addr": 18446744071579811697,
      "name": "print_cpu.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1462
    },
    {
      "addr": 18446744071580054224,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:614",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580097808,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:130",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828896,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1264
    },
    {
      "addr": 18446744071579840432,
      "name": "print_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071580097808,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:614",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580146784,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:130",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877600,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1264
    },
    {
      "addr": 18446744071579888726,
      "name": "print_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071580146784,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:612",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580209168,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:130",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920448,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
    },
    {
      "addr": 18446744071579931553,
      "name": "print_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    },
    {
      "addr": 18446744071580209168,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:666",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580193136,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:115",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579913872,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1251
    },
    {
      "addr": 18446744071591286661,
      "name": "print_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    },
    {
      "addr": 18446744071580193136,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 849
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:691",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580198176,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:115",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923152,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1199
    },
    {
      "addr": 18446744071591229690,
      "name": "print_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071580198176,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:707",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580344864,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:115",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046192,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1232
    },
    {
      "addr": 18446744071592116521,
      "name": "print_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071580344864,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:715",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sysrq_sched_debug_show",
        "kernel/sched/build_utility.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580558560,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:115",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158032,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
    },
    {
      "addr": 18446744071593883131,
      "name": "print_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
    },
    {
      "addr": 18446744071580558560,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580332944,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:716",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sysrq_sched_debug_show",
        "kernel/sched/build_utility.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580817968,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:115",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580332944,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2064
    },
    {
      "addr": 18446744071580817968,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580400240,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:762",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sysrq_sched_debug_show",
        "kernel/sched/build_utility.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580901264,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:115",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580400240,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2064
    },
    {
      "addr": 18446744071580901264,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580456784,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:763",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sysrq_sched_debug_show",
        "kernel/sched/build_utility.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580991792,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:115",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580456784,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2064
    },
    {
      "addr": 18446744071580991792,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491078488,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:614",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446603336491367696,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:130",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491078488,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1676
    },
    {
      "addr": 18446603336491367696,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225082664,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:614",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 3225365328,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:130",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225082664,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1700
    },
    {
      "addr": 3225365328,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1540
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283961808,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:614",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 13835058055284303200,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:130",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283961808,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2236
    },
    {
      "addr": 13835058055284303200,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271667550,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:614",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446743936271857442,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:130",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271667550,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1700
    },
    {
      "addr": 18446743936271857442,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1270
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:614",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580115984,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:130",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849744,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1264
    },
    {
      "addr": 18446744071579860854,
      "name": "print_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071580115984,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:614",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580061280,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:130",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784656,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1264
    },
    {
      "addr": 18446744071579795782,
      "name": "print_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071580061280,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:614",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580107056,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:130",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837968,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1264
    },
    {
      "addr": 18446744071579849094,
      "name": "print_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071580107056,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
void print_cpu(struct seq_file * m, int cpu)
```

```json
{
  "name": "print_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/sched/debug.c:614",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/sched/debug.c:sched_debug_show"
      ]
    },
    {
      "addr": 18446744071580158800,
      "name": "print_cpu",
      "external": false,
      "loc": "kernel/time/timer_list.c:130",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883008,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1274
    },
    {
      "addr": 18446744071579894150,
      "name": "print_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071580158800,
      "name": "print_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1211
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
