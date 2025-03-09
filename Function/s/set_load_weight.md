# Function: <code>set_load_weight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579519891,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:812",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__setscheduler_params",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:sched_init"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595258430,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:730",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595503319,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:737",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596423002,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:736",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578992,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:738",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578992,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607936,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:716",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607936,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645056,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:705",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645056,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669856,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:747",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669856,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706928,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:747",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706928,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579765283,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:749",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790421,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579754186,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:838",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591281771,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579762102,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:848",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224836,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579848522,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:1202",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592106527,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579964985,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:1272",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:sched_fork"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593874232,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627768819,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:1260",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:sched_fork"
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
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619529923,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:1282",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:sched_fork"
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
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621828772,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:1327",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:sched_fork"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510885392,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:747",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_fork"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490890720,
      "name": "set_load_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243372312,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:747",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_fork"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224906912,
      "name": "set_load_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302518500,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:747",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_fork"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283730592,
      "name": "set_load_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270626086,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:747",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_fork"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271540286,
      "name": "set_load_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683248,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:747",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683248,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611568,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:747",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611568,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579680464,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:747",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680464,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void set_load_weight(struct task_struct * p, bool update_load)
```

```json
{
  "name": "set_load_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579714784,
      "name": "set_load_weight",
      "external": false,
      "loc": "kernel/sched/core.c:747",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714784,
      "name": "set_load_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void set_load_weight(struct task_struct * p, bool update_load)
```
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void set_load_weight(struct task_struct * p, bool update_load)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void set_load_weight(struct task_struct * p, bool update_load)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void set_load_weight(struct task_struct * p, bool update_load)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void set_load_weight(struct task_struct * p, bool update_load)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void set_load_weight(struct task_struct * p, bool update_load)
```
</details>
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
