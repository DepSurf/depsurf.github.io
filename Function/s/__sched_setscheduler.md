# Function: <code>__sched_setscheduler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538992,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:3784",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_sched_setscheduler",
        "kernel/sched/core.c:SyS_sched_setattr",
        "kernel/sched/core.c:normalize_rt_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538992,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2545
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550064,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4037",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:SyS_sched_setattr",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550064,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2876
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574864,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4074",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:SyS_sched_setattr",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574864,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2790
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558752,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:3972",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:SyS_sched_setattr",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558752,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2291
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588128,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4016",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:SyS_sched_setattr",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588128,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579620048,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4143",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620048,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2082
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657360,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4128",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657360,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2066
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579682224,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4554",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682224,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3136
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579721952,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4756",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721952,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2807
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579764656,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4989",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764656,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2963
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579753568,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:5762",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753568,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2584
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579760336,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:6062",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760336,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2973
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846624,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:7225",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:sched_set_normal",
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846624,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3158
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579963744,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:7380",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:sched_set_normal",
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963744,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3344
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580123424,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:7522",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:sched_set_normal",
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123424,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3344
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185248,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:7623",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:sched_set_normal",
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185248,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3580
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580232400,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:7684",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:sched_set_normal",
        "kernel/sched/core.c:sched_set_fifo_low",
        "kernel/sched/core.c:sched_set_fifo",
        "kernel/sched/core.c:sched_set_stop_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232400,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3580
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490904264,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4756",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__arm64_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490904264,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2296
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224917048,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4756",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224917048,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3804
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283743008,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4756",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283743008,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4252
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271545388,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4756",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271545388,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1838
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698400,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4756",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698400,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3278
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624976,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4756",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624976,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3856
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691232,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4756",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691232,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2445
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
int __sched_setscheduler(struct task_struct * p, const struct sched_attr * attr, bool user, bool pi)
```

```json
{
  "name": "__sched_setscheduler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579728320,
      "name": "__sched_setscheduler",
      "external": false,
      "loc": "kernel/sched/core.c:4756",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:sched_setattr_nocheck",
        "kernel/sched/core.c:_sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579728320,
      "name": "__sched_setscheduler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3785
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
