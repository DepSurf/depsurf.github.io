# Function: <code>proc_sched_show_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void proc_sched_show_task(struct task_struct * p, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664432,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:547",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664432,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5625
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
void proc_sched_show_task(struct task_struct * p, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579682336,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:858",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682336,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5765
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
void proc_sched_show_task(struct task_struct * p, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706944,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:861",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706944,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5757
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
void proc_sched_show_task(struct task_struct * p, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579703184,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:875",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703184,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5827
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734736,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:925",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734736,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 6012
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:877",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771661,
      "name": "proc_sched_show_task.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2303
    },
    {
      "addr": 18446744071579763376,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3841
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:876",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814493,
      "name": "proc_sched_show_task.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2274
    },
    {
      "addr": 18446744071579806256,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3805
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:856",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842442,
      "name": "proc_sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2387
    },
    {
      "addr": 18446744071579834416,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3828
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:856",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890706,
      "name": "proc_sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2387
    },
    {
      "addr": 18446744071579882736,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3828
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:862",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933476,
      "name": "proc_sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2266
    },
    {
      "addr": 18446744071579925648,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3627
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:916",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591288584,
      "name": "proc_sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2266
    },
    {
      "addr": 18446744071579919520,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3627
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:930",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591231655,
      "name": "proc_sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2275
    },
    {
      "addr": 18446744071579927776,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3633
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:946",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592118548,
      "name": "proc_sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2275
    },
    {
      "addr": 18446744071580051024,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3633
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:945",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593887884,
      "name": "proc_sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2556
    },
    {
      "addr": 18446744071580183952,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3946
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580370896,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:946",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580370896,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7264
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580439520,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:992",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580439520,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7289
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580498752,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:989",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580498752,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7236
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491085208,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:856",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491085208,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5048
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225088944,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:856",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225088944,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5128
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283971312,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:856",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283971312,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 6848
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271673708,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:856",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271673708,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4490
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:856",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579862819,
      "name": "proc_sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2387
    },
    {
      "addr": 18446744071579854864,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3828
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:856",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797762,
      "name": "proc_sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2387
    },
    {
      "addr": 18446744071579789792,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3828
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:856",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851074,
      "name": "proc_sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2387
    },
    {
      "addr": 18446744071579843104,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3828
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
void proc_sched_show_task(struct task_struct * p, struct pid_namespace * ns, struct seq_file * m)
```

```json
{
  "name": "proc_sched_show_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_sched_show_task",
      "external": true,
      "loc": "kernel/sched/debug.c:856",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:sched_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896115,
      "name": "proc_sched_show_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2438
    },
    {
      "addr": 18446744071579888144,
      "name": "proc_sched_show_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3851
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pid_namespace * ns</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, m</code> ➡️ <code>p, ns, m</code>
</li>
</ul>
</details>
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
