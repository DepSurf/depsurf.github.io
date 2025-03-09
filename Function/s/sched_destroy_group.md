# Function: <code>sched_destroy_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579524310,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:7748",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_css_free"
      ],
      "caller_func": [
        "kernel/sched/auto_group.c:autogroup_move_group",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:sched_autogroup_exit",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567376,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578688,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:7778",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:sched_autogroup_exit",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578688,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579604784,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:7931",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:sched_autogroup_exit",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604784,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583248,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6145",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583248,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612608,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6213",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612608,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642480,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6333",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642480,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579680112,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6314",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680112,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713040,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6789",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713040,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755312,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6992",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755312,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579789568,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:7226",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789568,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579781120,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:8191",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781120,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579789248,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:8560",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789248,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884832,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:9788",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884832,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002160,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:10111",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_exit",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002160,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580164160,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:10291",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_exit",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164160,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212496,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:10435",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_exit",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212496,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580261152,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:10399",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_exit",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580261152,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490933800,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6992",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490933800,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224952188,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6992",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224952188,
      "name": "sched_destroy_group",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283789376,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6992",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283789376,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271567852,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6992",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271567852,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579731232,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6992",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731232,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660080,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6992",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660080,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716816,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6992",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716816,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sched_destroy_group(struct task_group * tg)
```

```json
{
  "name": "sched_destroy_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762944,
      "name": "sched_destroy_group",
      "external": true,
      "loc": "kernel/sched/core.c:6992",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762944,
      "name": "sched_destroy_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
